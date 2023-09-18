# Operadores e Estruturas em C#

## 🚀 Operadores

#### Operadores Aritméticos

- [X] `+` (adição): Soma dois valores.
- [X] `-` (subtração): Subtrai um valor de outro.
- [X] `*` (multiplicação): Multiplica dois valores.
- [X] `/` (divisão): Divide um valor pelo outro.
- [X] `%` (módulo): Retorna o resto da divisão de um valor pelo outro.

#### Operadores de Atribuição

- [X] `=` (atribuição): Atribui um valor a uma variável.
- [X] `+=` (atribuição de adição): Adiciona um valor a uma variável.
- [X] `-=` (atribuição de subtração): Subtrai um valor de uma variável.
- [X] `*=` (atribuição de multiplicação): Multiplica uma variável por um valor.
- [X] `/=` (atribuição de divisão): Divide uma variável por um valor.

#### Operadores de Comparação

- [X] `==` (igual): Verifica se dois valores são iguais.
- [X] `!=` (diferente): Verifica se dois valores são diferentes.
- [X] `<` (menor que): Verifica se um valor é menor que outro.
- [X] `>` (maior que): Verifica se um valor é maior que outro.
- [X] `<=` (menor ou igual a): Verifica se um valor é menor ou igual a outro.
- [X] `>=` (maior ou igual a): Verifica se um valor é maior ou igual a outro.

#### Operadores Lógicos

- [X] `&&` (E lógico): Retorna verdadeiro se ambas as condições forem verdadeiras.
- [X] `||` (OU lógico): Retorna verdadeiro se pelo menos uma das condições for verdadeira.
- [X] `!` (Negação lógica): Inverte o valor lógico de uma expressão.

#### Operadores Bit a Bit

- [X] `&` (E bit a bit): Realiza uma operação AND bit a bit entre dois valores.
- [X] `|` (OU bit a bit): Realiza uma operação OR bit a bit entre dois valores.
- [X] `^` (OU exclusivo bit a bit): Realiza uma operação XOR bit a bit entre dois valores.
- [X] `~` (Negação bit a bit): Inverte todos os bits de um valor.

#### Operadores de Deslocamento de Bits

- [X] `<<` (Deslocamento à esquerda): Desloca os bits de um valor para a esquerda.
- [X] `>>` (Deslocamento à direita): Desloca os bits de um valor para a direita.



## 👨🏻‍💻 Como executar o Teste

[Via Terminal] - Digitar o Comando :  robot -d ./logs .\tests


## 👨🏻‍💻 Estruturas de Controle


##### Estruturas Condicionais

- [X] `if` (se): Executa um bloco de código se a condição for verdadeira.

 Exemplo:

```csharp


  intidade=18;

  if (idade>=18)

  {

      Console.WriteLine("Você é maior de idade.");

  }
```


- [X] `else` (senão): Executa um bloco de código alternativo se a condição do if for falsa.

 Exemplo:

```csharp
 intidade=15;

if (idade>=18)

{

    Console.WriteLine("Você é maior de idade.");

}

else

{

    Console.WriteLine("Você é menor de idade.");

}
```



- [X] `elseif` (senãose): Executa um bloco de código alternativo se a condição do if for falsa.

 Exemplo:

```csharp
intnota=75;

if (nota>=90)

{

    Console.WriteLine("Nota A");

}

elseif (nota>=80)

{

    Console.WriteLine("Nota B");

}

elseif (nota>=70)

{

    Console.WriteLine("Nota C");

}

else

{

    Console.WriteLine("Nota F");

}
```


- [X]  `switch` (escolha): Avalia uma expressão e executa um bloco de código correspondente com base em valores.

 Exemplo:

```csharp
int opcao = 2;

switch (opcao)

{

    case 1:

        Console.WriteLine("Opção 1 selecionada.");

        break;

    case 2:

        Console.WriteLine("Opção 2 selecionada.");

        break;

    case 3:

        Console.WriteLine("Opção 3 selecionada.");

        break;

    default:

        Console.WriteLine("Opção inválida.");

        break;

}
```
