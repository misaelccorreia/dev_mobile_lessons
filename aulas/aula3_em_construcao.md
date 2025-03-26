#  Introdução à Programação Orientada a Objetos

## Boas-vindas e Contexto

- O professor dá as boas-vindas aos alunos para mais uma aula do curso de programação orientada a objetos com Java e PHP, destacando que a aula será rica em conteúdo.

## Definição de Objeto

- O professor questiona os alunos sobre o que é um objeto, incentivando-os a identificar objetos ao seu redor, como celulares e computadores.
- Exemplos de objetos são apresentados: celular, carro, mouse e joystick. O professor provoca reflexão sobre outros elementos que podem ser considerados objetos.

## Características dos Objetos

- A definição clássica de objeto é discutida: "uma coisa material ou abstrata percebida pelos sentidos", incluindo características, comportamentos e estados.
- O controle remoto é usado como exemplo prático para ilustrar características (como botões), comportamentos (ligar/desligar) e estados (ligado/desligado).

## Exemplos Adicionais

- Um compromisso agendado também é considerado um objeto, com suas próprias características (data/hora), comportamentos (marcar/desmarcar) e estados (confirmado/suspenso).
- A caneta é apresentada como um exemplo simples de objeto, sendo material ou imaterial, percebida pelos sentidos.

# Curiosidades sobre Canetas

## Engenharia por Trás da Caneta

- O professor compartilha curiosidades sobre canetas: o buraco na tampa foi projetado para segurança infantil, evitando engasgamento em caso de ingestão acidental.

## Conclusão da Aula

# A Estrutura de Objetos na Programação Orientada a Objetos

## Conceito de Objeto e Classe

- O conceito de caneta é utilizado como exemplo para discutir objetos em programação, destacando que uma caneta é um objeto específico, mas existem muitos outros tipos de objetos.
- Todos os objetos, como as canetas, seguem um modelo ou formato pré-definido que é planejado pelas empresas durante sua criação.
- A caneta representa um objeto enquanto o molde usado para criá-la é considerado uma classe; a classe serve para classificar os objetos.

## Atributos, Métodos e Estado

- Para entender um objeto, três perguntas devem ser respondidas: "O que eu tenho?", "O que eu faço?" e "Qual é o meu estado?".
- Exemplos de atributos da caneta incluem cor, tamanho da ponta e quantidade de carga. Já os métodos referem-se às ações que a caneta pode realizar, como escrever ou rabiscar.
- Os conceitos fundamentais são: atributos (características), métodos (comportamentos) e estado (condição atual do objeto). Cada objeto deve ter esses três elementos.

## Importância da Classificação

- Todo objeto deriva de uma classe; a palavra "classe" refere-se ao molde utilizado para gerar o objeto. Isso ajuda na organização e categorização dos diferentes tipos de objetos.

## Interrupção sobre Apoio ao Curso

- O apresentador interrompe a aula para falar sobre o apoio ao curso em vídeo, incentivando colaborações financeiras dos alunos para melhorar a qualidade das aulas.
- É mencionado que as aulas têm cores diferentes: vermelho para teóricas, azul para PHP e verde para Java. Essa identidade visual visa facilitar a navegação no curso.

# Introdução à Programação Orientada a Objetos

## Definição de Classe e Objeto

- O instrutor menciona que, para criar um objeto, é necessário primeiro definir uma classe. Ele compara isso ao processo de fabricação de uma caneta, onde um molde é criado antes da produção.
- A classe é definida como um planejamento ou classificação do objeto. O exemplo dado é a criação da classe "caneta", que será estruturada em forma de algoritmo.

## Atributos da Classe

- Os atributos são as características do objeto. No caso da caneta, os atributos incluem modelo (tipo caractere), cor (também tipo caractere), e carga (número inteiro).
- Outro atributo importante mencionado é se a caneta está tampada ou não, que seria um valor lógico (verdadeiro ou falso).

## Métodos da Classe

- Após definir os atributos, o instrutor fala sobre os métodos do objeto. O primeiro método apresentado é "rabiscar", que representa uma ação que a caneta pode realizar.
- O segundo método mencionado é "tampar". Ambos os métodos podem receber parâmetros, mas inicialmente não foram definidos com parâmetros para simplificar o entendimento.

## Lógica dos Métodos

- Para o método "rabiscar", o código deve verificar se a caneta está tampada antes de permitir que ela escreva. Se estiver tampada, uma mensagem de erro será exibida.
- Além disso, também deve ser verificado se há carga suficiente na caneta para escrever; caso contrário, não será possível rabiscar.

## Interação com o Usuário e Criação do Objeto

- O instrutor enfatiza que o programador ensina ao computador sobre o objeto através do código da classe. A interação entre métodos e atributos permite manipular as propriedades do objeto.
- Ao final, ele explica que idealizar uma classe é semelhante ao processo de criação de protótipos em engenharia; primeiro se planeja antes de criar objetos concretos.

## Conclusão sobre Classes e Objetos

#  Compreendendo Objetos e Classes em Programação

## Atributos e Estado de um Objeto

- O exemplo da caneta Bic cristal ilustra como os atributos (como cor, tipo de ponta e carga) definem o estado do objeto. O estado é percebido pelos sentidos, mas algumas características não são visíveis.
- O estado de um objeto é sempre definido em um momento específico, podendo mudar ao longo do tempo. É importante entender que a classificação do estado depende desse momento.

## Instanciação de Classes

- Todo objeto deve ter atributos e métodos definidos por uma classe. Para criar um objeto a partir de uma classe, utilizamos o termo "instanciar".
- Ao instanciar uma classe, geramos um novo objeto. Por exemplo, ao criar `c1` como uma nova caneta, estamos criando uma instância da classe caneta.

## Atributos dos Objetos

- Os atributos podem ser definidos após a instanciação. Por exemplo, podemos definir a cor da caneta com `c1.cor = azul`.
- Métodos também são utilizados para interagir com os objetos; por exemplo, `c1.rabiscar()` indica que rabiscar é um método associado à caneta.

## Múltiplas Instâncias

- É possível ter múltiplas instâncias da mesma classe sem que elas compartilhem estados ou atributos. Por exemplo, `c2` pode ser outra caneta com características diferentes.
- Cada instância pode ter seus próprios atributos; assim, `c2.cor = vermelho` não afeta o atributo da primeira caneta (`c1`).

## Definições Oficiais em Orientação a Objetos

- Uma classe define os atributos e métodos comuns que serão compartilhados por objetos criados a partir dela. Todos os objetos têm características semelhantes mas valores diferentes.
- Um objeto é considerado uma instância de uma classe; portanto, mesmo que existam classes definidas sem objetos criados (como no caso do controle remoto), isso não impede sua definição teórica.

## Exemplificação com Formas

# Conceitos de Programação Orientada a Objetos

## Atributos e Estados dos Objetos

- Os bolinhos mencionados representam objetos que compartilham atributos comuns, mas possuem estados diferentes, como sabor e cobertura.
- O conceito de "classe" é introduzido através da analogia com pessoas, onde todos têm atributos semelhantes (como altura e cor dos olhos), mas estados distintos.

## Abstração na Programação

- A abstração é um conceito fundamental em programação orientada a objetos, permitindo ignorar detalhes irrelevantes para focar nos atributos importantes de um objeto.
- Exemplos práticos são dados sobre quais atributos são relevantes em diferentes contextos, como peso em uma escola versus características físicas em um cadastro de modelo.

## Importância da Abstração

- Embora muitos considerem a abstração o primeiro pilar da programação orientada a objetos, o apresentador opta por trabalhar com três pilares principais.
- A abstração é destacada como essencial para simplificar a complexidade dos seres humanos ao selecionar apenas os atributos relevantes para cada situação.

## Atividade Prática Proposta

- O instrutor propõe uma atividade onde os alunos devem identificar dois objetos concretos no ambiente ao seu redor e classificá-los conforme suas características e métodos.
- Exemplifica como classificar uma cadeira considerando suas propriedades físicas e estado atual.

## Classificação de Objetos Abstratos

- Após classificar objetos concretos, os alunos devem identificar dois objetos abstratos do cotidiano e descrever seus atributos e comportamentos.
- Um exemplo dado é o ato de preparar uma aula, que possui características mensuráveis mesmo sendo um conceito abstrato.


