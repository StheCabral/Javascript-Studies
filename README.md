# Javascript-Studies
 Algunas anotações e exercícios em JavaScript

# Funções
São ações executadas assim que são chamadas ou em decorrência de algum evento
```
function nameOfFunction(parameters) {
  action
  return result
}
let result = name()

```
Uma variável pode receber uma função:
```
let v = function(x) {
 return x*2
}
v(2)
```
### Arrow Functions
Forma resumida de escrever funções, economiza digitação. Não precisa do nome "function" pois está subentendido. 
```
(a, b) => {
return a+b
}
```
São anônimas, se quiser dar nomes precisa atribuir a uma variável
```
const sum = (a, b) => {
return a+b
}
```
No casod de funções com apenas uma ação podemos resumir da seguinte forma já que tudo depois da fat arrow é entendido como retorno
```
const sum = (a, b) => a+b
```
exemplo:
`document.addEventListener('click', () => {console.log('clicked')}`
Além das modificações de sintaxe, as arrow functions alteram completamente a forma como o This é usado dentro da função
### This em Function x This em Arrow Functions
Funçẽs padrão tem um .this que pode ser modificado usando o `.bind()` mas as Arrow Functions não tem diz e quando chamado ele vai buscar no this do node (mesmo que você use o `.bind()`



