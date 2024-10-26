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

**Proposta obtida através do ChatGPT**

Com base nas variáveis e nas regras que você forneceu, aqui está um treino adaptado para o perfil de um aluno mesomorfo, sedentário, 
de 35 anos, com dores na coluna, disponibilidade de 5 dias para treino, e foco em exercícios funcionais, cardio e HIIT. Esse treino 
também considera as restrições alimentares devido à gastrite e alergias específicas.

### Plano de Treino

**Objetivo:** Fortalecer a musculatura, aliviar dores na coluna, melhorar a resistência cardiovascular e mobilidade, além de promover 
a perda de gordura.

**Estrutura do Treino:** ABCDE, com ênfase em exercícios de fortalecimento e mobilidade.

---

### **Dia 1 - Treino Funcional: Core e Mobilidade**

- **Aquecimento (5-10 min)**: Caminhada leve e alongamentos dinâmicos.
- **Circuito de Core e Mobilidade** (3x cada exercício):
  - Ponte glútea (15 repetições)
  - Prancha com apoio de antebraço (20-30 segundos)
  - Abdominais com elevação de pernas (12 repetições)
  - Exercício de mobilidade para coluna lombar (5 repetições para cada lado)
- **Alongamento (5 min)**: Alongamento focado em coluna e flexores do quadril.

> **Objetivo**: Melhorar a estabilidade da coluna e fortalecer o core para aliviar a pressão nas costas.

---

### **Dia 2 - Cardio de Baixa Intensidade**

- **Caminhada Inclinada ou Bicicleta Ergométrica** (30 min)
  - Intensidade: Moderada, para evitar sobrecarga na coluna.
  - Manter ritmo constante e sem sobrecarregar a postura.
- **Alongamento (5 min)**: Especialmente para lombar e membros inferiores.

> **Objetivo**: Estimular o sistema cardiovascular de forma leve e segura para o aluno sedentário.

---

### **Dia 3 - Treino Funcional: Membros Inferiores**

- **Aquecimento (5-10 min)**: Caminhada e alongamentos.
- **Exercícios Funcionais** (3x cada exercício):
  - Agachamento com peso corporal (15 repetições)
  - Avanço (12 repetições por perna)
  - Elevação de calcanhar (15 repetições)
  - Exercício de mobilidade de quadril (10 repetições)
- **Alongamento (5 min)**: Alongamento de membros inferiores.

> **Objetivo**: Desenvolver força nas pernas, o que ajuda a estabilizar a coluna e reduzir dores nas costas.

---

### **Dia 4 - HIIT de Baixa Intensidade para Iniciantes**

- **Circuito HIIT (4 rodadas)**:
  - Jumping Jacks (30 segundos)
  - Agachamento com apoio (15 repetições)
  - Elevação de joelhos (30 segundos)
  - Deslocamento lateral (30 segundos)
  - Descanso entre exercícios: 30 segundos
- **Alongamento (5 min)**: Mobilidade de quadril e ombros.

> **Objetivo**: Promover queima calórica e melhorar a capacidade cardiorrespiratória com intensidade controlada para evitar
> impacto excessivo na coluna.

---

### **Dia 5 - Treino Funcional: Membros Superiores e Core**

- **Aquecimento (5-10 min)**: Movimentos leves de ombro e rotação de tronco.
- **Circuito Funcional para Membros Superiores** (3x cada exercício):
  - Remada com elástico (15 repetições)
  - Flexão com apoio no joelho (12 repetições)
  - Prancha com extensão alternada de braço (20-30 segundos)
  - Alongamento ativo de coluna torácica (10 repetições)
- **Alongamento (5 min)**: Alongamento para ombros e braços.

> **Objetivo**: Fortalecer os membros superiores e estabilizar o core para suporte da coluna.

---

### **Considerações Nutricionais**

- **Gastrite**: Priorizar alimentos cozidos e de fácil digestão, evitando legumes crus em excesso.
- **Alergias**: Eliminar qualquer produto que contenha amendoim, castanhas e frutos do mar.
- **Sugestão**: Pequenas refeições leves e frequentes ajudam a reduzir o desconforto da gastrite, e fontes de proteína como
- frango, ovos e iogurtes são boas opções que respeitam as restrições.

Esse plano de treino é pensado para evoluir gradualmente, respeitando o estado sedentário e as condições de saúde do aluno. 
Com o tempo e a orientação certa, é possível progredir com segurança para aumentar a intensidade dos exercícios.
