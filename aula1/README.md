#Lição de casa

1. Crie uma pasta chamada aula1. Entre nela.

1. Crie um arquivo chamado "index.js". Nele, crie 3 objetos de gastos com pelo menos 5 propriedades, sendo pelo menos uma delas de cada um dos seguintes tipos: string, number e boolean.
  
  Existem 3 formas de se fazer isso, portanto monte cada objeto segundo uma das formas abaixo: um objeto com suas propriedades já nele (a) ou inserindo depois as propriedades (b e c):
  - a: 
  ```javascript
  var obj = { 
      key1: 'prop1', 
      key2: 'prop2' 
  };
  ```
  - b:
  ```javascript
  var obj = {};
  obj.key1 = 'prop1';
  obj.key2 = 'prop2';
  ```
  - outra forma (bônus!):
  ```javascript
  var obj = {};
  obj['key1'] = 'prop1';
  obj['key2'] = 'prop2';
  ```
1. Insira esses objetos dentro de um array. Vc se lembra do push?

1. Crie um arquivo index.html nesse mesmo nível com um formulário com os respectivos campo de um gasto, segundo os objetos que você criou acima. 
Se os objetos têm uma propriedade chamada "titulo", faz sentido ter um campo para receber esse valor. 
Talvez input[type=text] para esse caso? E qual tag usaríamos para a descrição, que é um texto longo?
Lembre-se: existem inputs do tipo "texto", "number"... e outros mais. Pesquise para ver qual tag e/ou tipo cabe melhor no que você precisa.
  
  _(Esses campos servirão para criarmos novos objetos no JavaScript na próxima aula.)_

1. Crie também uma tabela onde serão mostrados os objetos de gasto ─ um gasto por linha, uma coluna por propriedade. 
Na próxima aula vamos aprender a pegar esses dados do JavaScript, fique tranquilo. 
Por ora, copie as informações de pelo menos um dos gastos diretamente no HTML, para que ele apareça na tela.

1. Faça a página ficar mais interessante visualmente utilizando CSS. Crie um arquivo style.css no mesmo nível do index.html e coloque uma referência a ele no arquivo HTML.

1. Faça uma referência a index.js antes de fechar a tag ```</body>```.


