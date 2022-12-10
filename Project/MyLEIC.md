# MyLEIC

## 1. Motivação

A `MyLEIC` é uma aplicação web que apresenta uma solução para um problema real dos alunos do LEIC: organiza numa só plataforma as várias ferramentas e dependências utilizadas para elaborar os projetos de Unidades Curriculares:

- **Moodle e Sigarra**, para formação de grupos;
- **Slack e Discord**, para comunicação via mensagem e chamada com docentes e membros do projeto;
- **GitHub/GitLab**, como repositório remoto onde o código fica hospedado e com todas as funcionalidades do Git;
- **IDE/Text Editor**, para programar em várias linguagens, fazer debug e compilar os sistemas;
- **Google Docs**, para elaboração e apresentação de trabalhos/relatórios;

Com a nossa proposta, os alunos serão capazes de ter mais foco no projecto com acesso a todas as ferramentas mas sem preocupações com o ambiente de desenvolvimento.

### 1.1 Porquê web application?

Por questões de comodidade e acessibilidade dos utilizadores. É do conhecimento geral que nem todos os computadores têm uma arquitetura ou características que suportem determinados compiladores, processamento ou programas. Num exemplo mais prático, os computadores da biblioteca da FEUP estão pouco preparados para acomodar uma vasta lista de dependências de software. <br> 
Com a `MyLEIC` todo o ambiente necessário ficará à distância de um clique e de um simples login com a conta da faculdade.

## 2. Questionário

O questionário, disponível [aqui](https://docs.google.com/forms/d/1iKJoHXNnsMDaZH4x4fmuw-VroRcyJrpFOu9RPHErHTw/edit), teve como público alvo os alunos atuais do LEIC. Através de questões simples, averiguamos os seguintes aspectos:

### 2.1 Caraterização dos inquiridos

Foi importante perceber a faixa etária consultada e as suas competências na área da informática, para que a aplicação seja útil a todos os níveis de conhecimento. Os dados recolhidos revelaram que a maioria dos inquiridos têm conhecimento intermédio nos domínios da programação e versionamento de código. 

> Faixa etária <br>
> Ano curricular atual <br>
> Experiência em programação (nenhuma, iniciante, intermédia, avançada) <br>
> Experiência em ferramentas de controlo de versão como o Git (nenhuma, iniciante, intermédia, avançada)<br>

### 2.2 Apresentação do problema e proposta de uma solução

Os dados revelam que todos os inquiridos usam mais do que quatro plataformas para realizar cada um dos projectos propostos ao longo do curso. Desses, 95% gostariam de ter acesso a uma única plataforma que reunisse todas as ferramentas referidas anteriormente. A maioria sentir-se-ia mais focada no trabalho a desenvolver, impactando positivamente no rendimento e aproveitamento do tempo.

> Qual ou quais plataformas usa frequentemente para elaborar projectos do curso? <br>
> Quão importante seria existir uma plataforma centralizada que reunisse todas as plataformas anteriores? <br>
> Em que medida a utilização dessa plataforma melhoraria a sua qualidade de estudo (concentração, organização, rendimento...) <br>

### 2.3 Requisitos funcionais

Há uma grande preocupação em que a aplicação tenha um design familiar aos olhos dos utilizadores. Para isso questionamos qual é o IDE/Text Editor de eleição para programar. Neste requisito o VSCode foi, de longe, o mais escolhido.

Além disso, notou-se uma preocupação crescente para melhorar a colaboração entre alunos do mesmo grupo e até entre grupos da mesma Unidade Curricular. 
Possibilidade de reuniões com Live Chat, chamadas de voz e programação colaborativa foram os requisitos mais desejados.

> Qual IDE/Text Editor usa mais frequentemente? <br>
> Funcionalidades do IDE (várias linguagens, acesso direto a ferramentas do git, histórico de modificações de ficheiros, debugger, dark mode); <br>
> Em que medida a incorporação de um sistema de colaboração entre alunos e entre grupos seria favorável ao aprendizado (dúvidas, organização, distribuição de tarefas, agendar reuniões diárias...)? <br>

## 3. Repostas

### 3.1. Who are the users?
Just age is not enough…

### 3.2. What tasks do they perform?
Currently.

### 3.3. What tasks are desirable?
Be creative!

### 3.4. How are tasks learned?
Not how users learn how to use new devices.
Is there any previous knowledge required?

### 3.5. Where are tasks performed?
Characterize the environment.

### 3.6. What is the relationship between user and information?
Identify sensitive and/or shared information.
Do users feel comfortable in sharing such information?
How do they access the information?

### 3.7. What other instruments does the user have?
Identify other instruments used in such tasks.

### 3.8. How do users communicate?
If they do at all... If so, how?

### 3.9. How often tasks are performed?
Identify which tasks are more frequent.

### 3.10. Are there time restrictions?
How long are users willing to spend to perform a task?

### 3.11. What happens if something goes wrong?
Not only what can go wrong, but also how users deal with
that.

## 4. Personas

### 4.1 Persona 1

A Maria Cândida é uma aluna do LEIC que embora tenha todos os recursos disponíveis, como computador pessoal e sítio calmo para estudar, sente-se perdida no meio de tanta informação. Tem várias cadeiras em que o projecto é desenvolvido no GitHub, outras no GitLab, projectos onde a comunicação com os docentes é efetuada no Slack, outras no Moodle. Tenta marcar reuniões frequentes com os colegas de trabalho usando Whatsapp, Discord ou Email mas acaba por esquecer de algumas.

### 4.2 Persona 2

O Tó Pereira é um aluno do LEIC que por não ter computador com capacidade de suportar algumas aplicações precisa de usar um dos disponíveis na Biblioteca da FEUP. Mas todos têm o sistema operativo Windows e devido à quantidade de software diferente a instalar torna o estudo que poderia ser produtivo num autêntico desastre. Isto para não falar nas reuniões diárias que tem de entrar para ajudar o seu grupo.

### 4.3 Persona 3

#TODO, se quisermos