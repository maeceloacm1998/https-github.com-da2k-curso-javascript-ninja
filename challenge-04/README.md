# Desafio da semana #4

```js
/*
Declare uma variável chamada `isTruthy`, e atribua a ela uma função que recebe
um único parâmetro como argumento. Essa função deve retornar `true` se o
equivalente booleano para o valor passado no argumento for `true`, ou `false`
para o contrário.
*/
var isTruthy = function (x){ x == true ? true : false }

// Invoque a função criada acima, passando todos os tipos de valores `falsy`.
isTruthy('', 0 , -0 );

/*
Invoque a função criada acima passando como parâmetro 10 valores `truthy`.
*/
isThuthy(1,2,3,4,5,6,7,8,9,10);

/*
Declare uma variável chamada `carro`, atribuindo à ela um objeto com as
seguintes propriedades (os valores devem ser do tipo mostrado abaixo):
- `marca` - String
- `modelo` - String
- `placa` - String
- `ano` - Number
- `cor` - String
- `quantasPortas` - Number
- `assentos` - Number - cinco por padrão
- `quantidadePessoas` - Number - zero por padrão
*/
var carro = {
marca: Pegeout,
modelo: Xtreme,
placa: 123qwe,
ano: 2020,
quantasPortas:4,
assentos: 5,
quantidadePessoas: 0
}
/*
Crie um método chamado `mudarCor` que mude a cor do carro conforme a cor
passado por parâmetro.
*/
function mudaCor (cor){
carro.cor = cor;
}

/*
Crie um método chamado `obterCor`, que retorne a cor do carro.
*/
function obterCor (){
return carro.cor;
}

/*
Crie um método chamado `obterModelo` que retorne o modelo do carro.
*/
function obterModelo (){
return carro.modelo;
}

/*
Crie um método chamado `obterMarca` que retorne a marca do carro.
*/
function obterMarca (){
return carro.marca;
}

/*
Crie um método chamado `obterMarcaModelo`, que retorne:
"Esse carro é um [MARCA] [MODELO]"
Para retornar os valores de marca e modelo, utilize os métodos criados.
*/
function obterMarcaModelo (){
return 'Esse carro é um' + carro.marca + carro.modelo;
}

/*
Crie um método que irá adicionar pessoas no carro. Esse método terá as
seguintes características:
- Ele deverá receber por parâmetro o número de pessoas entrarão no carro. Esse
número não precisa encher o carro, você poderá acrescentar as pessoas aos
poucos.
- O método deve retornar a frase: "Já temos [X] pessoas no carro!"
- Se o carro já estiver cheio, com todos os assentos já preenchidos, o método
deve retornar a frase: "O carro já está lotado!"
- Se ainda houverem lugares no carro, mas a quantidade de pessoas passadas por
parâmetro for ultrapassar o limite de assentos do carro, então você deve
mostrar quantos assentos ainda podem ser ocupados, com a frase:
"Só cabem mais [QUANTIDADE_DE_PESSOAS_QUE_CABEM] pessoas!"
- Se couber somente mais uma pessoa, mostrar a palavra "pessoa" no retorno
citado acima, no lugar de "pessoas".
*/
carro.addPessoasCar = function( pessoas ) {
carro.vagasCar = 5 - carro.quantidadePessoas;
if(carro.vagasCar == 0){
return ' O carro está lotado .';
}
else if(pessoas > carro.vagasCar){
return ' só cabem mais '+ carro.vagasCar+' pessoas.2';
}
else if(pessoas > carro.vagasCar && carro.vagasCar == 1){
return ' só cabe mais '+ carro.vagasCar+' pessoa.1';
}
else {
carro.quantidadePessoas += pessoas;
return ' Já temos '+carro.quantidadePessoas +' pessoas no carro ';
pessoas = 0;
}
}

/*
Agora vamos verificar algumas informações do carro. Para as respostas abaixo,
utilize sempre o formato de invocação do método (ou chamada da propriedade),
adicionando comentários _inline_ ao lado com o valor retornado, se o método
retornar algum valor.

Qual a cor atual do carro?
*/
obterCor (); 

// Mude a cor do carro para vermelho.
mudarCor (vermelho);

// E agora, qual a cor do carro?
Vermelho.

// Mude a cor do carro para verde musgo.
mudarCor (musgo);

// E agora, qual a cor do carro?
Musgo

// Qual a marca e modelo do carro?
Xtreme

// Adicione 2 pessoas no carro.
addPessoasCar (2);

// Adicione mais 4 pessoas no carro.
addPessoasCar(4);

// Faça o carro encher.
ja encheu uai

// Tire 4 pessoas do carro.
carro.quantidadePessoas -= 4;

// Adicione 10 pessoas no carro.
addPessoasCar(10);

// Quantas pessoas temos no carro?
12.
```
