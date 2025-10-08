# Funções Java Script
Dentro deste repositório iremos discutir um pouco sobre funções dentro de java script com exemplos e montar um pequeno tutorial para poder definir e criar
funçoes. E iremos explorar os três principais formatos de funções sendo **Declaration**, **Expression** e **Arrow**

## O que são funções ?
Funções são nada mais que uma maneira do programador crie "blocos reutilizaveis" para fazer uma determinada tarefa, e também para melhorar a vida do programador
com código mais légivel, organizado e que evite muitas repetições e segue um exemplo de uma função em Js.

``` 
function tutorial() {
   console.log('Você hoje ira ver um pequeno tutorial de funçoes em Js');
}
```

Este é um pequeno exemplo de uma função em java script

## Criação de uma função 
Para criar uma função primeiro você precisar utilizar a plavara-chave ***function***(dependendo do formato que for usar) com isso já temos o inicio  de nossa função 
após isso devemos dar um ***nome*** isso seria dar um nome pra função para que possa ser cahamada depois e assim como em variaveis 
só pode ser usadas nela digitos, letras e alguns caracteres especias depois colocamos ***()*** colocamos esses parênteses para os 
parametros da função esses os valores das funções ou as variáveis locais e por ultimo colocamos ***{}*** essas chaves serão o corpo da função 
e dentro dela iremos colocar o código que queremos que seja repitível como foi mostradono exemplo anterior.

#### Exemplo:
```
function saudacao(nome){
   console.log('Bom dia,', nome ,'!');
}
//aqui temos uma função com o nome de saudacao com um parametro com nome e dentro do bloco temos um console log
saudacao("Pedro");
//e agora chamamos a função e mudamos o parametro de nome para "Pedro"
```

## Os três tipos de formatos de funções
### Function Declaration
Essa é a forma tradicional de se definir uma função e o formato que foi utilizado nos exemplos anteriores.

#### Exemplo:
```
function subtracao(a,b){
   return a - b;
}

console.log(subtracao(7,3))
```
Essas são funções com prioridade de carregamento, isso quer dizer que essas são funções onde o interpretador ira dar prioridade de "leitura" para
este formato de função.

### Function Expression
Este é um formato onde a função é atríbuida a uma variavel

#### Exemplo:
```
const soma = function(a,b){
    return a + b
}
// Em vez de colocar o parametro no nome da função aqui neste formato o atribuimos a função
console.log(Soma(10,7))
//E para chamar a função colocamos o nome da variavel e os parametros.
```
##### Vantagens:



### Arrow Function 
Este é um formato que utiliza uma sintaxe mais curta, ela é ideal para funções rápidas e callbacks

#### Exemplo:
```
const divi = (a,b) => a/b
//Diferente dos outros formatos essa tem uma sintexe bem diferente onde o parametro é atribuido a variavel e utlizando uma arrow para montar o corpo da função e ela não utiliza do "function"
divi()
//E como no formato "expression" chamamos o nome da varíavel
```
## Conclusão
Com esse pequeno tutorial de funções você deve ter entendido como se deve criar uma função em java script, para poder melhorar o seu código e os diferentes
tipos de formatos que uma função pode ter cada uma com uma vantagem e desvantagem que o programador decide qual será ideal para ele. 

