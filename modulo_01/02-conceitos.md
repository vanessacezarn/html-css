## HTML - Hypertext Markup Language
* focada em conteúdo( textos, imagens, videos)
* linguagem fundamental para estruturar o conteúdo de páginas da web
* baseada em marcações chamadas **tags**
  * tem que ter abertura de tag, conteúdo e fechamento de tag 
		* exemplo: <h1> TITULO DO SITE </h1> 
		* atalho no vscode para colocar um parágrafo já digitado dentro de uma tag --> selecionar o texto --> ctrl+shift+P --> Wrap --> Emment: Wrap with abbreviation--> digitar a tag que deseja --> enter
* estrutura básica do html

```html
<!DOCTYPE html>
<html lang="pt-br">
	<head> "cabeça"
		< meta charset="UTF-8">
		<meta name= "viewport"
		content="width=decive-width,
		initial-sacle=1.0">
		<title>Document</title>
	</head>
	<body> "corpo"
		<h1>Olá Mundo</h1>
	</body>
</ html>
```
* <head> = cabeça da página --> onde ocorre configurações iniciais como formato, estilo, ícone de favoritos, ...
	* < meta charset="UTF-8"> --> fornece suporte para caracteres acentuados
	* <meta name= "viewport" content="width=decive-width, initial-sacle=1.0"> -->indica que o conteúdo aparecerá em em todo espaço disponível da tela com uma escala 1:1
	* <title> --> titulo da página, que aparece como identificação da aba do navegador
* <body> = corpo da página --> o que vai aparecer na tela --> conteúdo do site

* Hierarquia de títulos (headings)
	* possuem 6 níveis de hierarquia --> tags de h1 até h6

* Semântica
	* negrito --> <strong>
	* italico --> <em>
	* texto marcado --> <mark>
	* cuidado algumas tags podem se tornar obsoletas

## CSS - Cascading Style Sheets
* foco em design ( cores, tamanho, posicionamento)
* linguagem de estilo fundamental para a web
* usada para controlar a aparência e o layout de páginas escritas em HTML
* estilo em css: seletor, declaração (propriedade : valor)
		* exemplo:
``` css
 h1{
    font-family; Arial;
    font-size: 20pt;
    color:blue;
     }
```
## JavaScript 
* linguagem de programação utilizada principalmente em desenvolvimento web
* interatividade --> menu, animações, validações

## Front-end
* client-side 
* parte do sistema em que o usuário interage diretamente
  * layout, botões, menus
* em geral utiliza HTML, CSS, JavaScript
## Back-end
* server-side
* responsável pela lógica, processamento de dados e regras de negócio
	* cadastro, login, validações
* utiliza em geral: java, python,  c#, MySQL
## Full stack
* desenvolvedor que abrange tanto front-end quanto back-end
* ou seja, desenvolve tanto a interface do usuário tanto a lógica e o servidor
