# CORES
* pode ser selecionada pelo:
    * nome da color 
    * pelo codigo hexadecimal 
    *pelo codigo rgb (mistura das cores: red, green, blue) 
    * por padrão HSL (matriz, saturação, ou luminância)
* codigo hexadecimal abre um leque maior de possibilidades
    * é formado por 6 valores (numero e/ou letras)
* exemplo: laranja, #FA6800, rgb(250,104,0)

### adobe color 
* para ajudar na escolha da paleta de cores --> disco de cores
* encontrar uma cor a partir de uma imagem --> extrair tema

### paletton.com
* parecido com o adobe
* permite simular como as cores ficariam dentro de um site --> preview

### colorZilla
* extensão do google que permite descobrir o código de cada cor em qualquer site
* chrome web store --> colorzilla --> usar no chrome

## Degrade
* dentro de < head> adicionar a tag < style> e body{ backgroud-imagem: linear-gradient(direção, cor inicial, cor final)} 
    * pode ter mais de duas cores, é preciso apenas colocar todas as cores dentro do parênteses
    * também pode-se definir a proporção de cada cor, basta adicionar a porcentagem logo após a cor
* configurações globais dentro da css *