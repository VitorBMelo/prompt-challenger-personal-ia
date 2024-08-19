<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

Criando um Plano de Treino Personalizado para Endomorfos: Foco em Funcional e Peso Livre
Entendendo o Perfil:

    Endomorfo: Tende a ganhar peso com facilidade, especialmente na região abdominal.
    Treino ABC: Divisão dos grupos musculares em três dias para otimizar a recuperação e promover o crescimento muscular.
    Funcional e Peso Livre: Prioriza movimentos compostos e naturais, utilizando o peso do corpo e halteres para um treino mais completo e eficaz.

##Objetivo:

    Queimar gordura: Priorizar exercícios que elevem a frequência cardíaca e aumentem o gasto calórico.
    Tonificar os músculos: Desenvolver força e definição muscular, focando nos grandes grupos musculares.
    Melhorar a resistência: Aumentar a capacidade de realizar exercícios por um período mais longo.

##Exemplo de Plano de Treino ABC:

    Dia A: Peito, Tríceps e Abdômen
        Aquecimento: 5 minutos de cardio leve (pular corda, bicicleta) + 5 minutos de mobilidade articular.
        Peito: Supino com halteres, flexões, crucifixo inclinado.
        Tríceps: Extensão de tríceps com halteres, mergulhos, tríceps pulley.
        Abdômen: Plank, bicicleta, elevação de pernas.
    Dia B: Costas, Bíceps e Abdômen
        Aquecimento: 5 minutos de cardio leve + 5 minutos de mobilidade articular.
        Costas: Remada curvada, puxada frontal, terra.
        Bíceps: Rosca direta com halteres, rosca martelo, rosca concentrada.
        Abdômen: Russian twist, leg raise, scissor.
    Dia C: Perna e Abdômen
        Aquecimento: 5 minutos de cardio leve + 5 minutos de mobilidade articular.
        Perna: Agachamento livre, afundo, lunges, calf raise.
        Abdômen: Plank lateral, bicicleta invertida, abdominal com rotação.

##Observações:

    Repetições e séries: Para queimar gordura e tonificar os músculos, realize entre 12 e 15 repetições por série e 3 a 4 séries por exercício.
    Descanso: Descanse entre 45 segundos e 1 minuto entre as séries.
    Intensidade: Aumente gradualmente a carga dos exercícios para continuar desafiando seus músculos e promovendo o crescimento.
    Nutrição: Combine o treino com uma alimentação equilibrada e rica em proteínas para auxiliar na construção muscular e na perda de gordura.
    Cardio: Inclua atividades cardiovasculares como corrida, natação ou ciclismo em dias alternados aos treinos de força para aumentar o gasto calórico.

##Dicas Adicionais:

    Varie os exercícios: Alterne os exercícios a cada 4-6 semanas para evitar a adaptação muscular e continuar estimulando o crescimento.
    Contratar um profissional: Consulte um educador físico para um acompanhamento personalizado e evitar lesões.
    Ouvir o corpo: Respeite seus limites e ajuste o treino conforme necessário.
    Lembre-se: Este é apenas um exemplo de plano de treino. A personalização é fundamental para alcançar seus objetivos. Adapte este plano às suas necessidades e preferências, sempre buscando orientação profissional.
