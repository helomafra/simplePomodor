## DOM 

- Document Object Model 
- Document se refere ao documento html 

```js
document.body 
document.head
```

- Como pegar por exemplo o elemento play no html? 
```js
document.querySelector('.play')
//ou 
document.querySelector('#timer')
```

- Event-driven (direcionada a eventos)
  - Por exeplo um clique, uma rolagem

- Programação imperativa 
  - Da ordens, passo a passo do que deve ser feito 

- Programação declarativa 
  -É mais direta, como o react 

- Callback
  - Quando passamos uma função como argumento de outra função e vai executar depois de certo tempo 
  - Exemplo: 
  ```js
  //quando o evento clique acontecer, execute essa função 
  play.addEventListener('click', function() {})
  ``

- setTimeout 
  - executa a função depois de certo tempo determinado, em ms
  - setTimeout(function(){}, tempo para executar função)

- Factory 
  
