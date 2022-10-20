# 5 - Evaluation

A avaliação pode envolver os próprios utilizadores (para uma avaliação a nível da usabilidade) ou não, para avaliar o projecto de forma mas analítica. Deve ser abordada segundo os 5W (Why, What, Where, When, Who, How). A avaliação pode ser:

### Formativa

- Durante o processo de design;
- Os resultados informam a próxima fase de design;

### Summative

- É a avaliação final para medir o sucesso da aplicação;
- Tempo, erros, performence;

## Tipos de avaliação

### Field Studies

A principal ideia é testar o projecto num ambiente natural, de forma a entender o que os utilizadores fazem normalmente e como os produtos ajudam. Ajudam a identificar oportunidades, estabelece mais requisitos, facilitam a introdução de nova tecnologia e avaliar essa mesma tecnologia

### Usability testing

Mais orientada para as métricas de performence nas tarefas típicas. Avaliam a satisfação do utilizador, o número de erros, as interações com a interface, normalmente com recurso a questionários e entrevistas. 

### Analitical evaluation

Não envolve utilizadores finais. Podem ser de dois tipos:

#### Heuristic evaluation

Trata-se de uma avalição eurística para identificar problemas de usabilidade e envolve peritos em avaliação de protótipos. São bosns para avaliar protótipos iniciais, porque são rápidos, baratos e fáceis de usar. No projecto, usaremos as **eurísticas de Nielsen**.

#### Predictive evaluation

Métodos baseados em modelos teóricos para medir a performence, os produtos e o design sem envolver diretamente os utilizadores. É mais barata do que o **user testing**.
#TODO -> KLM and 

## Nielsen Usability Heuristics

### 1 - Visibility od System status

Ter informação do que está acontecer no sistema. Todos os reports devem ser claros e objectivos. Pode acontecer mudanças no cursor, indicação do tempo restante da operação, indicadores com base em progress bars.

### 2 - Match between system and real world

A conexão entre o utilizador e o sistema é feita com linguagem natural, mais próxima possível ao ambiente habitual de quem usa. Não usar informações técnicas, pois são pouco informativas para quem é externo ao sistema. Tem de estar alinhado ao modelo conceptual.

### 3 - User control and freedom

Os utilizadores por vezes cometem erros (eliminam programas, por exemplo) e é necessário que exista uma caixa de diálogo que confirme a operação com linguagem natural, de modo a poder ser revertida.

### 4 - Consistency and standars

O sistema deve ser consistente a nível do layout, linguagem, cores, botões.

### 5 - Erros prevention

A interface deve ajudar a prevenir erros e assim evitar mensagens de controlo (tópico 3). Por exemplo, escolha de um dia no calendário.

### 6 - Recognition rather than recall

A interface deve ser suficientemente simples para que não exija um manual de instruções ou ocupe o utilizador com acessos externos ou a memorizar etapas. Cada opção deve ser facilmente reconhecida, através de labels, exemplos significativos ou por grupos.

### 7 - Flexibility and efficiency of use

Normalmente não usados por utilizadores recentes por desconhecimento de determinadas opções. Exemplos: atalhos de teclado, features mais escondidas num menu.

### 8 - Aesthetic and minimalistic design

As caixas de diálogo não devem conter informações que são relevantes ou raramente usadas. Toda a unidade extra de informação deve estar contida em zonas específicas, de modo a clarificar a constituição do sistema e não sobrecarregar o aspecto da plataforma.

### 9 - Help user with erros

Caixas de diálogo que ajudam os utilizadores a reconhecer os erros do sistema. São úteis para todos os utilizadores, desde que sejam em linguagem natural e indiquem de forma precisa o problema que está a ocorrer. 

### 10 - Help and documentation

Um sistema deve ser simples de utilizar sem ser necessário um manual, mas dúvidas podem ocorrer. A documentação disponível no sistema deve ser fácil de pequisar e baseada nas tarefas que os utilizadores podem efetuar. Descrevem em passos concretos mas curtos as etapas de realização de cada uma.

## Testing with Users

1. `Who?` Os testes devem ser efetuados com utilizadores finais, que sabem do contexto da aplicação, balanceados em género e idades. Pelo menos 10 a 20;

2. `How Many?` Pelo menos 10 a 20, com algumas iterações, para ter uma variedade significativa para tirar conclusões e descobrir problemas. Os testes podem ser:
    - **between-subjects/inter-groups** (cada grupo testa o seu sistema);
    - **within-subjects/intra-group** (todos os utilizadores testam todos os sistemas). Neste cenário, os elementos podem testar sistemas em diversas sequências: randommized, sequenced e por latin-tables.

### Variáveis a ser testadas

#### 1. Variáveis dependentes

O seu valor depende do sistema a ser testado. Medidas a partir do tempo, quantidade de erros, SUS (System Usability Scale).

#### 2. Variáveis independentes

Não dependem das variáveis a medir. São características da solução implementada, como o layout, cores, e características dos participantes, como idade.

### Tipos de dados

#### 1. Quantitativas



#### 2. Qualitativas

