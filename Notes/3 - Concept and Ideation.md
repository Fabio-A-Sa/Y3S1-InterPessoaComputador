# Concept and Ideation

## Conceptual Model

Modelo que descreve o que os utilizadores podem fazer no sistema. Expressa objectos, atributos e ações que podem ser efetuadas e o mapping entre elas, de modo a arranjar as ideias antes de passar ao protótipo/mockup. O conceptual model não é:

- Uma user interface;
- Não é um diagrama do sistema;
- Não representa ações, nem especifica as interações possíveis;

O modelo conceptual apresenta objectos com atributos, ações e relações entre esses mesmos objectos. Um exemplo segundo os slides:

**Objects (attributes):**
- Photo (date, caption);
- photo set (title);
- event (local, date);
- person (name);
- archive (name, shared);
- user (name)

**Actions:**
- Insert, remove, select photo;
- create, edit, remove caption;
- create, edit, remove event;
- create, edit, remove, share archive

**Relations:**
- Archive has photos,
- photo set has photos,
- event has photos,
- user access shared archive,
- photo has persons,
- person can be in several photos

## Requirements and tasks management

### Functional requirements

Baseados nas personas e nos seus cenários/contexto/atividade. Exemplo: "A aplicação deve ser capaz de: loggin in, manage photos (insert photo, characterize), search for content...".

### Task selection

É uma lista de tarefas específicas que ilustram a utilização do sistema, mostrar os requisitos e servir de base para a avaliação e evolução do modelo. Devem ser reais, representativas, não mencionar a interface mas sim as sua funcionalidade ("o utilizador pode criar um album" e não "o utilizador clica num botão para criar um album"), deve ter termos específicos e de complexidade mista.

### Usability requirements

Avaliam a usabilidade, em termos de eficácia, eficiência e satisfação dos utilizadores. 

## Ideation

A ideia é o output do processo criativo, não o ponto de partida. Tem de haver um equilíbrio entre quantidade e qualidade. O modelo Agile, com curtos sprints, é melhor do que o Waterfall pois permite refinar ideias sem comprometer toda a idealização anterior do produto.

### Crazy 8

Método de design sprints. Cada membro do grupo apresenta 8 ideias em 8 minutos, com o objectivo de criar variedade de soluções. Cada membro tem ainda 3 minutos para partilhar as melhores opções e discutir com o grupo.