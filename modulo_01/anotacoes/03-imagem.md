## IMAGENS
* direito de imagens 
* sempre procurar por imagens de domínio público
    * em uma pesquisa no google --> ferramentas --> direito de uso --> marcada para reutilização  
### Formato de imagens - JPEG e PNG
* JPEG (Joint Photographics Experts Group)
    * JPG em formato JPEG --> arquivos pequenos e eque ocupam pouco espaço em disco
* PNG (Portable Network Graphics) 
    * substituir o GIF
    * é compacto mas não tanto quanto o JPEG
    * capacidade de configurar o opacidade de cada pixel, transparência
### em html 
* utilizar a tag img 
    * < img src="logo-html.png" alt="Logo HTML5">
### Redimensionar imagem
* utilizar o gimp --> imagem --> redimensionar imagem --> escolher o tamanho --> arquivo --> exportar como 

### emoji 
* pode simplesmente copiar e colar o emoji dentro do codigo html ou adiconar o codigo de cada emoji disponivel em emojipedia e escreve-los juntos a '&#x' 
    * exemplo: &#x1F4D5;
### FAVICON - ícone de favoritos
* são os pequenos ícones que aparecem ao lado do site na parte superior do navegador
* deve ser adicionado na < head> do código com a tag < link> de favicon 
    * < link rel="shortcut icon" href="imagens/favicon.ico" type="image/x-icon">
* formatos aceitos
    * .ico ou .png ou .svg

### Imagem Flexível
* imagem que se adapta ao tamanho da tela
* agora além da tag < img>tem temos que usar no inicio a tag < picutre> e a tag <source>
    * Dentro de < source> temos 3 atributos 
        * type que indica o media type da image
        * srcset que configura o nome da imagem que será carregada quando o tamanho for atingindo 
        * media indica o tamanho máximo a ser considerado para carregar a imagem indicada em srcset
        
### Vídeos
   
* Utilizar a tag < video> se o vídeo estiver hospedado no própio servidor.
    * Alguns atributos da tag < video>
        * width = indica a largura que o vídeo ocupará na tela
        * poster = capa do vídeo, enquanto o vídeo não é reproduzido
        * controls = configura se os controles do vídeo vão aparecer na parte inferior, para ativar os controles adicionar controls na tag video
        * autoplay = diz para o navegador tocar o vídeo assim que a página for carregada
