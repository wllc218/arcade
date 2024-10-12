# Prática

Faça o código seguindo o que se pede:

- Para todas as variáveis e funções, seja explícito sobre os tipos de dados que eles recebem e retornam.

- crie uma variável `nome` do tipo `string` e atribua a ela o valor `"João"`;
- let nome: string = "João";

- crie uma variável `idade` do tipo `number` e atribua a ela o valor `18`;
- let idade: number = 18;
  
- crie uma constante `limite` do tipo `number` e atribua a ela o valor `18`;
- const limite: number = 18;
  
- crie uma variável `maiorDeIdade` do tipo `boolean` e atribua a ela o valor `false`;
- let mariorDeIdade: boolean = false;
  
- faça um `if` que verifica se `idade` é maior ou igual a `limite` e mude o valor de `maiorDeIdade` para `true` se for maior ou igual;
- if (idade >= limite) maiorDeIdade = true

- crie um vetor de frutas do tipo `string` e adicione a ele as frutas `"maçã"`, `"banana"` e `"laranja"`;
- let frutas: string[] = ["maçã", "banana", "laranja"]

- crie um `for` que imprime cada fruta do vetor de frutas utilizando `console.log`;
- for (let i of frutas.keys()) { console.log(frutas[i]) } 

- faça um vetor de nomes do tipo `number` ou `null` e adicione a ele os valores `1`, `2`, `null`, `4`, `0`, `null`;
- let nomes: (number | null)[] = [1, 2, null, 4, 0, null];

- faça um `for` que imprime cada nome do vetor de nomes utilizando `console.log` apenas se o valor não for `null`;
- for (let i of nomes.keys()) { console.log(); }
  
- crie uma função que recebe uma idade e retorna `criança` se a idade for menor que `12`, `adolescente` se a idade for menor que `18` e `adulto` se a idade for maior ou igual a `18`;
- let testIdade = (idade => idade <= 12  ? "criança" : idade > 12 && idade < 18 ? "jovem" : "adulto");

- chame a função para alguns valores de idade e imprima os resultados utilizando `console.log`;
- console.log(testIdade(12)) // Criança
- console.log(testIdade(15)) // Jovem
- console.log(testIdade(18)) // Adulto
