# Preparação para o Teste

## Tópicos

- Interação Pessoa Computador
- User research
- Ideation
- Prototyping
- Evaluation
- Help and Documentation

## 1 - Interação Pessoa Computador

Campo multidisciplinar que estuda o design da tecnologia e a interação do sistema com humanos através da interface.

### 1.1 - User Centered Design (UCD)

Processo iterativo que foca nas necessidades dos utilizadores em cada fase. Investigam através de formulários ou entrevistas para conhecer o contexto, interesses e opiniões em relação às necessidades. 

#### 1.1.1 - User Interface (UI)

Parte visível do sistema que deve ser estimulante (sons, vídeo, cores). Permite ao utilizador interagir com o sistema e realizar tarefas, dando feedback. Objectiva e foca nas ferramentas, aspectos visuais e tarefas.

#### 1.1.1 - User Experience (UX)

A experiência do utilizador no sistema, todo o contexto e emoções. Não há designers de UX mas sim designs para UX. Subjectiva e foca nas interações e sensações.

### 1.2 - Design Process

#### 1.2.1 - Waterfall Model

Assume que tudo já é completamente conhecido e especificado e testa a funcionalidade só depois da implementação. Não é uma boa escolha para desenhar produtos que dependem da subjectividade dos utilizadores.  

#### 1.2.2 - Iteractive Design Process

Compõem-se em curtas iterações e tem três fases principais de desenvolvimento:

1. Idealizar e desenhar;
2. Criar um protótipo;
3. Testar e avaliar junto dos utilizadores finais, *stakeholders*;

## 2 - User research

### 2.1 - People involved

#### 2.1.1 - Users

Utilizadores do produto final e ditarão o seu sucesso. Deve ser o centro do processo de criação, usando o UCD.

#### 2.1.2 - Stakeholders

Define as motivações iniciais, os objectivos e requisitos primários. Podem estar errados, pois não são os utilizadores finais.

#### 2.1.3 - Designers

Procuram os utilizadores para saberem as suas motivações e necessidades. Têm em consideração também os requisitos dos stakeholders.

### 2.2 - Métodos de pesquisa

- `Atitudinais` (o que as pessoas fazem no produto) e `Comportamentais` (o que dizem sobre o produto);
- `Formais` (lista estruturada de tarefas, adequada para sistemas existentes) e `Informais` (exploratória, para criar novos designs);
- `Quantitativos` e `Qualitativos`;
- `Implícitos` (pela observação, medidas de reação e de conclusão de tarefas) e `Explícitos` (questionários, inquéritos, relatos);

### 2.3 - Personas

Caracterização clara do utilizador, que tem como objectivo ajudar a tomar decisões no campo dos requisitos. Foca-se nos objectivos e não nas tarefas. São definidos por:
- Motivações/Objectivos
- Necessidades
- Frustrações

Cenários de atividade complementam as Personas. São como uma história, onde a aplicação a desenvolver poderia ser útil. Não deve ter detalhes de implementação da User Interface.

## 3 - Ideation

### 3.1 - Conceptual Model

O que os utilizadores podem fazer no sistema, objectos, atributos e relações entre eles. Não é uma user interface, nem diagrama do sistema, nem especifica as interações possíveis nem o **mental model** do utilizador.

### 3.2 - Functional Requirements

Definem um conjunto de funcionalidades do sistema para ilustrar a sua funcionalidade e cobrir os requisitos. Devem responder ao que fazer e não como fazer, não mencionando a interface.

### 3.3 - Usability Requirements

Avaliam a usabilidade ao nível da eficácia (erros), eficiência (cliques) e satisfação (parte qualitativa subjectiva) dos utilizadores.

### 3.4 - Ideation

A ideação é o output do processo criativo e inovador, não o ponto de partida. Tem de haver um equilíbrio entre a quantidade e qualidade, usando o modelo *Agile*. <br>
Um exemplo de modelo é o `Crazy8`, em que cada membro tem 8 ideias em 8 minutos e apresenta ao resto da equipa as melhores em 3 minutos.

## 4 - Prototyping

Representação concreta mas parcial do sistema para coletar feedback dos utilizadores. Testam-se ideias, reduz-se o tempo de produção com ideias más, foca-se na UI e nas funcionalidades. Há protótipos de dois tipos:

- `Horizontais`: foco alargado mas superficial em todas as tarefas;
- `Verticais`: foco restrito mas profundo em determinadas tarefas;

### 4.1 - Técnicas

#### 4.1.1 - Experimentais

- `Storyboard`, conjunto de desenhos que contam uma história onde a aplcação é útil;
- `Bodystroming`, através de role plays o utilizador experimenta fisicamente a situação;
- `Wizard of Oz`, as funcionalidades são simuladas por humanos, serve para reconhecimento de gestos ou língua de sistemas complexos;

#### 4.1.2 - Low-Fidelity

Focam-se mais na funcionalidade e na possível resposta do sistema:

- `Papel`, baixo custo, fáceis e rápidos, mas não são escaláveis;
- `Mockup`, de maior custo e mais demorados. Podem ser *lo-fi* (como os wireframes) ou *hi-fi* (como os hi-res widgets);

#### 4.1.3 - High-Fidelity

Além da funcionalidade, já se focam também na aparência:

- `Interactive mockups`, através de hiperlinks que levam a outras páginas, interações não programáveis; 
- `Functional mockups`, implementa partes lógicas do sistema, normalmente é um protótipo vertical e hi-fi;

## 5 - Evaluation

De acordo com a visão 5W1H (Why, What, Where, When, Who, How). Pode ser uma avaliação `formativa`, durante o processo do design para apontar para a fase seguinte do protótipo ou `sumativa`, no final para medir o sucesso através de testes quantitativos. A avaliação pode conter os utilizadores (field studies, ubsability testing) ou não (analytical evaluation).

### 5.1 - Avaliação com Utilizadores

- `Field Studies`, testar em ambiente natural para entender o comportamento dos utilizadores. Identificam oportunidades e requisitos;
- `Usability Testing`, medição da performence dos utilizadores nas tarefas. No final existe um questionário ou entrevistas para as partes não quantificáveis;

### 5.2 - Avaliação sem Utilizadores

- `Heuristic Evaluation`, método analítico que é bom para avaliar protótipos inicias, é rápido e barato. 
- `Predictive Evaluation`, mais barata mas limitada a sistemas como tarefas previsíveis. Por exemplo o KML, que mede o tempo de resposta de cada tecla no teclado;

### 5.3 - Eurísticas de Nielsen

1. Visibilidade do status do sistema (barra de progresso);
2. Mensagems com uma linguagem natural (sistema-realidade);
3. User control and freedom, alertas para operações de maior risco, para poderem ser revertidas;
4. Consistência, botões e cores do mesmo lado;
5. Errors prevention, dando os limites de escolha e mensagens de confirmação;
6. Recognition rather recall, não apelar à memória dos utilizadores;
7. Flexibility and efficiency of use, usando atalhos para utilizadores experientes;
8. Aesthetic and minimalist design
9. Help users recognize, diagnose, and recover from errors, obtendo mensagens de erros claras;
10. Help and documentation, o sistema deve ser simples de modo a não ser necessário um manual;

## 5.4 - Testing

Os testes podem ser **between-subjects/inter-groups** quando cada grupo testa o seu sistema ou **within-subjects/intra-group** quando todos testam todos os sistemas.<br> 
As variáveis testadas podem ser independentes (como o layout, cores, características dos participantes) e dependentes (quantidade de erros, cliques). <br>
Os dados testados podem ser quantitativos, qualitativos, objectivos e subjectivos, muitas vezes usa-se a SUS (*System Usability Scale*) para casos subjectivos e qualitativos da aplicação. Podem ser coletados de forma direta ou indireta. 

## 5.5 - Ética

Durante o teste devemos ter em consideração o tempo, conforto, informação, privacidade e controlo. Existem três princípios fundamentais da ética: respeito, caridade/fazer o bem (fazer a pesquisa com objectivo de melhorar) e justiça (garantir o equilóbrio entre os participantes). 