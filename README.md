# JS-Exercicio

<h1>Exercícios: Módulo 01</h1>

<b>1o exercício</b>

Crie uma função que dado o objeto a seguir:
</br>
```
var endereco = {
rua: "Rua dos pinheiros", numero: 1293,
bairro: "Centro", cidade: "São Paulo",
uf: "SP"
};
```

Retorne o seguinte conteúdo:
</br>
<code>
O usuário mora em São Paulo / SP, no bairro Centro, na rua "Rua dos Pinheiros" com no 1293.
</code>


<b>2o exercício</b>

Crie uma função que dado um intervalo (entre x e y) exiba todos número pares:

<code>
function pares(x, y) {
  // código aqui
}

pares(32, 321);
</code>

<b>3o exercício</b>

Escreva uma função que verifique se o vetor de habilidades passado possui a habilidade "Javascript" e retorna um booleano true/false caso exista ou não.

<code>
function temHabilidade(skills) {
  // código aqui
}
var skills = ["Javascript", "ReactJS", "React Native"]; temHabilidade(skills); // true ou false
</code>


Dica: para verificar se um vetor contém um valor, utilize o método indexOf.



<b>4o exercício</b>

Escreva uma função que dado um total de anos de estudo retorna o quão experiente o usuário é:

<code>
function experiencia(anos) {
  // código aqui
}
var anosEstudo = 7; experiencia(anosEstudo);
// De 0-1 ano: Iniciante
// De 1-3 anos: Intermediário // De 3-6 anos: Avançado
// De 7 acima: Jedi Master
</code>


<b>5o exercício</b>

Dado o seguinte vetor de objetos:
<code>
var usuarios = [ {
nome: "Diego",
habilidades: ["Javascript", "ReactJS", "Redux"] },
{
nome: "Gabriel",
habilidades: ["VueJS", "Ruby on Rails", "Elixir"]
} ];
</code>

Escreva uma função que produza o seguinte resultado:

<code>
O Diego possui as habilidades: Javascript, ReactJS, Redux
O Gabriel possui as habilidades: VueJS, Ruby on Rails, Elixir
</code>

Dica: Para percorrer um vetor você deve utilizar a sintaxe for...of e para unir valores de um array com um separador utilize o join.







<h1> Exercises: Module 01 </h1>

<b> 1st exercise </b>

Create a function that gives the following object:
<code>
var address = {
street: "Rua dos pinheiros", number: 1293,
neighborhood: "Centro", city: "São Paulo",
uf: "SP"
};
</code>

Return to the following content:
<code>
The user lives in São Paulo / SP, in the Centro neighborhood, on Rua "Rua dos Pinheiros" with no 1293.
</code>


<b> 2nd exercise </b>

Create a function that, given an interval (between x and y), displays all even numbers:

<code>
function pairs (x, y) {
  // code here
}

pairs (32, 321);
</code>


<b> 3rd exercise </b>

Write a function that checks if the skill vector passed has the "Javascript" skill and returns a true / false boolean whether it exists or not.

<code>
function temHabilidade (skills) {
  // code here
}
var skills = ["Javascript", "ReactJS", "React Native"]; skills (skills); // true or false
</code>


Tip: to check if a vector contains a value, use the indexOf method.


<b> 4th exercise </b>

Write a function that, given a total of years of study, returns how experienced the user is:

<code>
function experience (years) {
  // code here
}
var anosEstudo = 7; experience (yearsStudy);
// From 0-1 year: Beginner
// From 1-3 years old: Intermediate // From 3-6 years old: Advanced
// From 7 up: Jedi Master
</code>


<b> 5th exercise </b>

Given the following vector of objects:
<code>
var users = [{
name: "Diego",
skills: ["Javascript", "ReactJS", "Redux"]},
{
name: "Gabriel",
skills: ["VueJS", "Ruby on Rails", "Elixir"]
}];
</code>

Write a function that produces the following result:

<code>
Diego has the skills: Javascript, ReactJS, Redux
Gabriel has the skills: VueJS, Ruby on Rails, Elixir
</code>

Tip: To traverse a vector you must use the for ... of syntax and to join values ​​of an array with a separator use join.

