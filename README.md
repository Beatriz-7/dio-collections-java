# dio-collections-java
Exercícios referente ao bootcamp Dio/GFT Java - Collections

# Collection

- é um objeto que agrupa múltiplos elementos(variáveis primitivas ou objetos) dentro de uma única unidade.

- serve para armazenar e processar conjuntos de dados de forma eficiente.

- antes do Java 2 (JDK 1.2), a implementação de coleções na linguagem Java incluía poucas classes e não tinha a organização de um framework.

## Composição
 
Interfaces: É um contrato que quando assumido por uma classe deve ser implementado.

Implementações ou Classes: são as materializações, a codificação das interfaces.

Algoritmos: É uma sequência lógica, finita e definida de instruções que devem ser seguidas para resolver um problema.

## java.util.List

- Elementos duplicados e garante ordem de inserção

## java.util.Set

- Não permite elementos duplicados
- Não possui índice

## java.util.Map

- Elementos únicos (key) para cada valor (value)

### Classe Anônima

A classe anônima em Java é uma classe não recebeu um nome e é tanto declarado e instanciado em uma única instrução. Você deve considerar o uso de uma classe anônima 
sempre que você precisa para criar uma classe que será instanciado apenas uma vez.

### Functional Interface

Qualquer interface com um SAM (Single Abstract Method) é uma interface funcional e sua implementação pode ser tratada como expressões lambda. 

- Comparator
- Consumer
- Function
- Predicate

### Lambda

Uma função lambda é uma função sem declaração, isto é, não é necessário colocar um nome, um tipo de retorno e o modificador de acesso. A ideia é que o método seja 
declarado no mesmo lugar em que será usado. As funções lambda em Java tem a sintaxe definida como (argumento) -> (corpo).

### Reference Method

Method Reference é um novo recurso do Java 8 que permite fazer referência a um método ou construtor de uma classe (de forma funcional) e assim indicar que ele deve ser
utilizado num ponto específico do código, deixando-o mais simples e legível. Para utilizá-lo, basta informar uma classe ou referência seguida do símbolo “::” e o nome
do método sem os parênteses no final.

### Streams API

A Streams API traz uma nova opção para a manipulação de coleções em Java seguindo os princípios da programação funcional. Combinada com as expressões lambda, ela 
proporciona uma forma diferente de lidar com conjuntos de elementos, oferecendo ao desenvolvedor uma maneira simples e concisa de escrever código que resulta em 
facilidade de manutenção e paralelização sem efeitos indesejados em tempo de execução.

Source - Pipeline - Terminal
