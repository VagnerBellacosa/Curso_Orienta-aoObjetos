# Curso Orientacao Objetos

Primeiros passos em Orientação a Objetos comparaçao com logica estrutural e evoluçao

## O que é um paradigma de programação?

Um paradigma pode ser entendido como a forma com a qual se decide resolver determinado problema por meio da programação de computadores. Nesse sentido, temos alguns paradigmas possíveis que eventualmente podem ser usados mais de um (caso a linguagem escolhida ofereça suporte).

Como exemplos, podemos citar os dois primeiros (que deram origem aos demais), que são o *tipo imperativo* e o *declarativo*. Existem também o tipo **estruturado** e o **paradigma orientado a objetos**, que serão abordados mais adiante.

### O que é o paradigma de POO?

O paradigma da **POO(Programação Orientada a Objetos)** é um modelo de análise, projeto e programação baseado na aproximação entre o mundo real e o mundo virtual, através da criação e interação entre objetos, atributos, códigos, métodos, entre outros.

A primeira linguagem de programação com paradigma de orientação a objetos foi criada em 1970, por **Alan Kay**. Ele era matemático, biólogo e, ao longo de sua vida repleta de invenções, criou vários programas de aprendizado voltados para crianças.

Segundo Kay, *“o computador ideal deveria funcionar como um organismo vivo, isso é, cada célula se relaciona com outras a fim de alcançar um objetivo, mas cada uma funciona de forma autônoma. As células poderiam também reagrupar-se para resolver outro problema, ou desempenhar outras funções”*.

De fato, o matemático tinha em seu pensamento uma mistura de raciocínio lógico com biológico, o que vinha de suas duas formações originais. Em determinado momento de sua vida, Alan Kay passou a trabalhar na gigante **Xerox**, mais precisamente no departamento de estudos.

Durante suas atividades, ele idealizou a criação de um aparelho chamado **Dynabook**. Era uma espécie de tablet com teclado físico (isso em plena década de 70). Para que o Dynabook se tornasse realidade, era necessário o desenvolvimento de uma linguagem de programação por meio da qual pudesse ser construído o sistema do aparelho.

Foi então que surgiu a primeira linguagem de programação orientada a objetos: o *Smalltalk*. A linguagem de POO de Alan Kay foi a primeira a contar com os conceitos de **classes, objetos, atributos e métodos**.

### Como funciona a POO?

A programação orientada a objetos tem o propósito principal de aproximar o mundo lógico da programação e o mundo em que vivemos. À vista disso, ela parte do princípio de que tudo é objeto — isso mesmo, tudo o que existe são os objetos.

No entanto, eles necessitam ser criados (tal qual no mundo real). Para isso, eles precisam de uma espécie de fôrma, de um invólucro, algo que possa lhes dar ao menos seu aspecto inicial: um ponto de partida!

Imagine alguma unidade fabril realizando a fabricação de determinado produto. Esse item (objeto) pode ser qualquer coisa: um carro, uma televisão ou mesmo ovos de Páscoa. Em todos os casos, no início dessa produção, haverá o uso de uma fôrma para dar o aspecto inicial dos objetos finais.

Todas essas fôrmas são equivalentes ao conceito de classes em POO. Após terminado esse processo é que os produtos passam por personalizações: os carros ganham cores e acessórios, as televisões recebem diferentes programações internas e os ovos de Páscoa serão de embalagens e recheios diversos.

Esse quadro completa nosso comparativo de POO: todas essas características individuais dos objetos são os seus atributos, que pertencem somente a eles. Já suas funcionalidades (caso tenham alguma) são os seus métodos. Por exemplo, acelerar e frear são funcionalidades de um carro.

São essas quatro características — objetos, classes, atributos e métodos — que definem o paradigma de programação orientada a objetos. Lembre-se de que algumas particularidades podem (e são) compartilhadas entre diferentes objetos, conferindo grande versatilidade a esse tipo de paradigma.

### Quais as diferenças da POO para a Programação Estruturada?

Existe uma grande diferença da POO em relação ao paradigma estruturado quanto ao acesso aos dados. Na POO, eles não são mais generalistas, tais quais as variáveis globais que estão visíveis e utilizáveis por todos a qualquer momento.

Sua estruturação de dados é menor, já que é feita por meio dos objetos. Assim, eles ficam acessíveis somente aos seus métodos, em vez de ser acessíveis por todas as funções, como ocorre no paradigma estruturado.

A partir disso, o acesso se dará de modo orientado. Lembrando que essa estrutura é maleável, pois pode haver troca de dados entre os diferentes objetos. Isso confere dinamicidade ao código fonte desenvolvido, além de melhor alocação de memória.

### Quais são os 4 pilares básicos da POO?

A forma com se relacionam as quatro características recém-definidas vai constituir o conceito de POO. Para uma linguagem de programação ser considerada orientada a objetos, deve haver quatro comportamentos característicos. São eles o *encapsulamento*, a *herança*, o *polimorfismo* e a *abstração*.

1. Encapsulamento

O encapsulamento é a capacidade que determinado método ou atributo de um objeto tem de se manter invisível. Ou seja, ele continua funcional, mas sem mostrar como. É aquele famoso pensamento de saber o que faz, mas não saber como se faz.

Isso tem sua razão. Para o programa, pouco interessa como determinado método é construído. O que de fato importa é que ele faça aquilo que promete, pois assim poderá ser utilizado com eficiência.

Isso garante uma camada extra de proteção para a aplicação, pois os detalhes de implementação não são revelados. Se essa é a intenção da pessoa que faz a programação, ela é garantida por meio da declaração de que aquele método é privado e não público.

2. Herança

Como o próprio nome diz, trata-se de uma relação de receber algo pré-existente. No caso da POO, a herança é um evento que ocorre entre classes. A doadora é chamada de classe-mãe. Já a classe que herda é chamada de filha.

Quando ocorre uma herança, a classe-filha herda as características da classe-mãe. Isso é bastante útil para um reaproveitamento de código, pois não seria necessário refazer algo que já existe. Parte-se de um ponto e se desenvolvem novos métodos.

3. Polimorfismo

Já o polimorfismo é uma característica inerente aos métodos dos objetos. Significa dizer que um mesmo método pode ser utilizado em diferentes objetos, de diferentes classes.

Podemos imaginar esse tipo de evento ocorrendo num sistema bancário: o extrato (método) mostra a movimentação da conta de clientes de determinada categoria (objeto). 

No entanto, pode-se usar essa funcionalidade para clientes no geral. Além disso, ele pode ser utilizado no sistema de outros bancos (classes) também!

4. Abstração

Também chamada de interface ou template. Muitos simplificam sua explicação como sendo uma espécie de mistura de encapsulamento e polimorfismo. A ideia principal é representar um objeto de forma abstrata, que seja obrigatoriamente herdado por outras classes.

Assim, é possível criar uma classe abstrata com atributos e métodos, mas sua implementação deve ser feita nas classes herdadas. Na programação, é chamada de superclasse, sendo que um objeto não pode ser criado diretamente dela.

#### Quais as vantagens de usar a POO?

O paradigma de orientação a objetos traz seis vantagens intrínsecas a toda linguagem que faz seu uso. Devido à busca pela representação do mundo real na programação de computadores por meio de objetos e classes, esses benefícios sempre são alcançados.

A seguir, são apresentadas as características de um software desenvolvido com POO. Parte-se da definição aplicável a um sistema e sua respectiva explanação.

- Confiável

A geração de código baseado no conceito de objetos e classes fornece uma grande independência ao programa. Assim, qualquer intervenção que seja necessária não afetará outros pontos do sistema. Isso confere robustez e confiabilidade.

- Oportuno

A criação paralela de código torna todo o processo bastante ágil. Ganha-se em tempo e eficiência, tornando um software com paradigma POO oportuno. Várias equipes podem trabalhar no mesmo projeto de forma independente.

- Ajustável

Essa característica diz respeito ao processo de manutenção do código-fonte. Ao atualizar uma parte pequena, o conceito de herança garante que, automaticamente, todas as partes que utilizarem tal método sejam beneficiadas.

Essa característica torna especial o paradigma de POO, pois é muito comum que equipes de desenvolvimento de softwares sejam escaladas para trabalhar com softwares já existentes. Dessa forma, torna-se mais fácil executar o trabalho de manutenção.

- Extensível

O uso do princípio da reutilização do software adiciona funcionalidades ao sistema já existente. Não é preciso “reinventar a roda”, reescrevendo o código. Isso confere maior capacidade de estender um sistema já existente.

- Reutilizável

Um mesmo objeto pode ser utilizado em aplicações diferentes, desde que sejam compatíveis. Se tivéssemos um objeto “aluno”, por exemplo, ele poderia ser utilizado em sistemas de empresas diferentes, desde que elas contassem com alunas e alunos na sua estrutura.

Assim, tanto uma escola de música como uma academia poderiam fazer uso do objeto “aluno” em um possível software para uso próprio, pois ambas as empresas têm essas pessoas como seu público.

- Natural
O conceito de POO que traz para a programação o mundo concreto, tal qual vemos no dia-a-dia, faz com que se ganhe naturalidade. O ponto de vista humano se torna mais próximo do virtual. Assim, pensa-se no problema geral, em vez de concentrar o foco em pormenores.

### Que linguagens de programação utilizam POO?

A grande maioria das linguagens modernas são orientadas a objetos. POO é um paradigma que revolucionou a escrita de código moderno. Algumas linguagens fazem uso obrigatório dela, enquanto para outras é facultativo.

O exemplo mais emblemático de linguagem puramente POO, certamente, é o Java. É largamente utilizado em vários dispositivos por todo o planeta e ganhou mais força ainda ao ser a linguagem escolhida pelo Google para o desenvolvimento de aplicativos para o sistema Android.

Podemos citar outras tantas linguagens com paradigma POO: Delphi, PHP (orientada a classes) e Python — que ganhou força nos últimos anos, sendo bastante difundida para soluções de data science.

Dentre todos os paradigmas de linguagem de programação existentes, a POO se destacou com características únicas e vantagens notáveis. Desde sua criação, já se mostrou um conceito inovador e revolucionário. Com o impulso dado a partir da década de 90, mais linguagens vêm surgindo baseadas nesse paradigma. Vale a pena concentrar estudos sobre o tema pela sua grande relevância atual.

