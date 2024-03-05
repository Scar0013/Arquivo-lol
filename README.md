Todos os perssonagens do lol + Exercicios 


Por mais que possamos criar objetos, as vezes, nossos objetos são tão grandes, que precisamos manipular um tipo de arquivo especial, chamados de arquivos .JSON.

Exemplos
https://developer.riotgames.com/docs/lol
https://github.com/ngryman/lol-champions/blob/master/champions.json

```js

var dadosPersonagens; 

fetch('arquivo.json') 
	.then(response => response.json()) 
	.then(data => { dadosPersonagens = data; console.log(dadosPersonagens); })
	.catch(error => console.log('Erro ao ler o arquivo JSON:', error));


dadosPersonagens[0].name; //






```

Exercicio:
1) Faça um loop que imprima, ID, name, e icon de cada personagem listado dentro do JSON (um por linha, exemplo: 

24, NOME CHAMPION, URL IMAGEM
25, NOME CHAMPION, URL IMAGEM
26, NOME CHAMPION, URL IMAGEM
)
