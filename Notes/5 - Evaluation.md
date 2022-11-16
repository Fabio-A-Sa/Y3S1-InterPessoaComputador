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

Métodos baseados em modelos teóricos para medir a performence, os produtos e o design sem envolver diretamente os utilizadores. É mais barata do que o **user testing**. Por exemplo o sistema KLM (Keystroke Level Model), que mede o tempo de conclusão de tarefas com base no tempo de resposta a cada tecla e ao número de teclas pressionadas. 

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

- 1. Variáveis dependentes: O seu valor depende do sistema a ser testado. Medidas a partir do tempo, quantidade de erros, SUS (System Usability Scale).

- 2. Variáveis independentes: Não dependem das variáveis a medir. São características da solução implementada, como o layout, cores, e características dos participantes, como idade.

### Tipos de dados

- 1. `Quantitativos`: Dados que dão para quantificar, que são específicos e que dão para medir. Repostas fechadas. Quantos erros? Qual preferes, A ou B? Quanto tempo demoraste? Completaste a tarefa? Sim ou Não?

- 2. `Qualitativos`: Perguntas de resposta aberta. O que mais gostou na experiência? O que achaste da foto de capa?

- 3. `Objectivos`: Não dependem das predisposições dos utilizadores, como o tempo, erros, frequência cardíaca.

- 4. `Subjectivos`: Tem relação com a percepção do utilizador, como por exemplo as suas preferências, SUS.

### Como colectar os dados?

Pode ser de **forma direta**, observando os utilizadores a realizar as tarefas ou em pessoa e vídeo, ou de **forma indireta**, como diários e logs interativos automáticos. É sempre favorável realizar testes piloto de acordo com o progresso da aplicação. Os utilizadores concentram-se na recompensa, embora possam ser influenciados só pela observação ou pelo efeito da novidade.

## Ética

Durante um teste, devemos ter em consideração o tempo, conforto, informação, privacidade e controlo.

- Os participantes devem ser voluntários;
- O teste deve vir acompanhado com informação;
- Os participantes podem sair a qualquer momento, sem pressão;
- O sistema deve ser avaliado, não os utilizadores;
- Privacidade quanto aos dados pessoais;

### Populações vulneráveis

- Crianças;
- Pessoas com deficiência;
- Minorias étnicas, religiosas;

### Princípios da ética

#### 1. Respeito pelas pessoas

- As pessoas têm autonomia e escolha;
- Não devem ser exploradas, não devem ser usadas como meio;
- Proteger os mais vulneráveis, com o consentimento informado;

#### 2. Fazer o bem

- Fazer as pesquisas com o objectivo de melhorar (o sistema, a população);
- Considerar os riscos e benificios em todas as considerações dos testes;

#### 3. Justiça

- Garantir o equilíbrio entre os participantes;
- Distribuir os riscos e benefícios entre os participantes;
- Recrutamentos dos participantes de forma imparcial;

## Análise Qualitativa

Aplica-se com dados não numéricos, como atitudes, comportamentos, experiências, motivações, que descrevem eventos, reações e opiniões. Exemplos:

- Word Clouds;
- Análise temática, onde as respostas dão origem a códigos/labels e estes dão origem a temas;
- Diagramas de afinidade;

## Análise Quantitativa

Permite fazer uma análise estatística, descritiva, inferência estatística de forma mais automática. A estatística permite:

- Indentificar possíveis falhas;
- Detectar padrões;
- Gerar e testar hipóteses;
- Garantir as conclusões correctas;

### Tipos de medidas:

- Medidas `nominais`: cores, marcas, nome;
- Medidas `ordinais`: [pequeno, médio, grande] [feliz, neutro, infeliz];
- Medidas `contínuas`: idade, altura, peso, tempo, número de erros;

Normalmente cálculo da média, moda, mediana, desvio padrão.

## Inferência Estatística

### Teste de hipótese

- Escolha de uma amostra representativa da população;
- Formular uma hipótese nula (exemplo: não há uma relação entre as variáveis A e B);
- Efetuar os testes, recolha da informação;
- Aplicar o tratamento estatístico;

### T-Student

Usado para variáveis contínuas e compara dois valores médios. Assume que a amostra tem uma distribuição normal para mais do que 30 elementos.

### Intervalos de Confiança

Com base numa amostra, calcula-se o intervalo de confiança para os valores medidos e atribui-se à população num todo. 

### Qui-Quadrado

Usado para variáveis nominais (como preferências, cores, marcas) e serve para comparar a frequência esperada dessa seleção. 

### Correlação de Pearson

Usada para determinar se duas variáveis estão relacionadas. Resulta em valores que variam entre -1 e 1:
- zona `negativa`: as variáveis estão inversamente relacionadas;
- zona `nula`: as variáveis não têm qualquer relação;
- zona `positiva`: as variáveis estão diretamente relacionadas;

### Cálculo em excel

Duas colunas com as amostras, cálculo da média, test e obtem o valor de T, ir à tabela e tirar conclusões sobre H0 e H1. 