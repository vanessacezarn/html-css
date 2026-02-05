* box model = conceito em que a grande maioria dos elementos HTML de um site são como caixas
* uma caixa pode estar dentro de outra caixa --> aninhamento
## uma caixa é formada por :
* conteúdo: texto, imagem, ...
    * box-size = tamanho do caixa --> width = largura; height = altura
* borda = em volta do conteúdo
    * possui espessura (border-width), cor(border-color), formato(border-style)
* padding (preenchimento)= entre a borda e o conteúdo (da borda para dentro)
    * top = acima, right = direita, bottom = abaixo, left = esquerda
* margin = da borda para fora 
    * top = acima, right = direita, bottom = abaixo, left = esquerda
    * para centralizar uma caixa = margin: auto;
* outline(contorno)= entre a margem e a borda
    * é um traçado visual que se pode criar fora da borda
    * possui espessura, formato, cor

## shorthands
* para border ou  outline devem seguir a ordem : width(largura), style(estilo), color(cor)
* para padding ou margin devem seguir a ordem: top(superior), right(direita), bottom(inferior), left(esqueda) 

## Tipos de caixas
* block-level
    * um elemento desse tipo sempre vai iniciar em uma nova linha e vai ocupar a largura total do elemento onde está contido, se não estiver em outra caixa vai ocupar 100% da largura do < body>
    * o elemento mais conhecido é o < div> (elemento de bloco) e suas variações como < main>, < section>,...
* inline-level
    * começa no ponto exato onde foi definida
    * sua largura ocupa apenas o tamanho relativo ao seu conteúdo
    * exemplos : < span> < a>, < q>, < abbr>,< br>,...

## Grouping Tags e Semantic Tags
* Header 
    * áreas relativas a cabeçalhos
    * geralmente inclui títulos e subtítulos
    * pode conter menus de navegações
* Nav
    * define a área que possui os links de navegação pela estrutura de páginas que vão compor o website --> menu
    * pode estar dentro de um < header>
* Main
    * agrupador usado para delimitar o conteúdo principal do site
    * geralmente concentra as seções, artigos e conteúdos periféricos
* Section
    * cria seções para a página
    * pode conter o conteúdo diretamente no seu corpo ou dividir os conteúdos em artigos com conteúdos específicos
* Article
    * elemento que contém um conteúdo que pode ser lido de forma independente e dizem respeito a um mesmo assunto
    * pode ser utilizado para delimitar um post de blog ou fórum, notícia,...
* Aside
    * delimita um conteúdo periférico e complementar ao conteúdo principal de um artigo ou seção
    * geralmente um < aside> está posicionado ao lado de um determinado texto ou no meio.
* Footer
    * cria um rodapé para o site inteiro, seção ou artigo
    * possui as informações sobre a autoria do conteúdo, links adicionais, mapa do site, documentos relacionados

## Sombra nas caixas
* propiedade box-shadow possui 4 valores
    * deslocamento horizontal(h-offset) = quanto a sombra vai andar para o lado direito ( valores negativos causam deslocamento para esquerda)
    * deslocamento vetical(v-offset) = quanto a sombra vai para baixo, valores negativos causam deslocamento para cima
    * embaçamento(blur) = quanto a sombra vai se espalhar pelo fundo
    * cor (collor) = cor da sombra
## Bordas decoradas
* vértices arredondados = border-radius:
    * border-radius: 10px --> arredonda todas as bordas de forma simétrica
    * border-radius: 10px 20px 30px 40px --> arredonda uma borda de cada forma
    * border-radius: 10px 30px --> arrendonda vétices intercalados, partindo do canto superior esquerdo