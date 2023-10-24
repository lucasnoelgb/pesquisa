# ALUNOS
<h3>Lucas Noel <br>
    Lucas Carvalho</h3>

# TRANSLAÇÃO

A translação em JavaScript envolve mover um elemento em uma determinada direção, como para a direita, para a esquerda, para cima ou para baixo. Você pode realizar uma translação modificando as propriedades CSS `left` (para mover horizontalmente) e `top` (para mover verticalmente) de um elemento HTML. Vou demonstrar um exemplo simples de translação em JavaScript:

Suponha que você tenha um elemento HTML com o id "elemento" que deseja transladar. Primeiro, você precisa criar um arquivo HTML com o seguinte código:

![WhatsApp Image 2023-10-10 at 11 51 07](https://github.com/lucasnoelgb/pesquisa/assets/129121307/0a72fa61-7fcc-476e-a196-1f50064facbd)

Neste exemplo, o elemento com o id "elemento" será transladado 100 pixels para a direita e 50 pixels para baixo quando o código JavaScript for executado. Você pode ajustar as coordenadas X e Y de acordo com suas necessidades para mover o elemento em diferentes direções. Certifique-se de que o arquivo "script.js" esteja vinculado corretamente ao seu arquivo HTML.

# ROTAÇÃO

Em JavaScript, a rotação é geralmente associada à manipulação de elementos HTML, como imagens ou elementos gráficos, para girá-los em torno de um ponto específico. Você pode realizar a rotação usando CSS ou transformações de matriz. Aqui está uma breve explicação de como fazer isso:

1. *Usando CSS:*
   Você pode aplicar rotação a elementos HTML usando propriedades CSS. Por exemplo, para girar uma imagem em HTML, você pode fazer o seguinte:

  
![WhatsApp Image 2023-10-17 at 08 53 55](https://github.com/lucasnoelgb/pesquisa/assets/129121307/13235f06-53c9-44c3-8932-c7901e313ba7)


   Isso aplicará uma rotação de 45 graus à imagem.

2. *Usando transformações de matriz:*
   Você também pode realizar rotação usando transformações de matriz. Aqui está um exemplo de como girar um elemento em JavaScript:


![WhatsApp Image 2023-10-17 at 08 53 55 (1)](https://github.com/lucasnoelgb/pesquisa/assets/129121307/db4e66ae-fe53-4908-a5c4-75e175767281)

   

Isso irá girar o elemento em 45 graus. Tenha em mente que você precisa definir a propriedade `style.transform` do elemento que deseja girar.

Lembre-se de que a rotação é especificada em graus (deg) no sentido anti-horário. Você pode ajustar o ângulo de rotação de acordo com suas necessidades.

# ESCALA

A escala em JavaScript é uma técnica que permite redimensionar elementos HTML, como imagens ou divs, aumentando ou diminuindo o tamanho em relação ao tamanho original. Isso é feito através de CSS ou programaticamente com JavaScript. Aqui estão as duas abordagens:

1. *Usando CSS:*
   Você pode aplicar uma escala a um elemento HTML usando CSS. Por exemplo, para aumentar o tamanho de uma imagem em HTML, você pode fazer o seguinte:

![WhatsApp Image 2023-10-17 at 08 58 02](https://github.com/lucasnoelgb/pesquisa/assets/129121307/87ff9f56-83f7-4aa8-9aff-56279d7d9ba2)


   Isso aumentará o tamanho da imagem em 1,5 vezes o tamanho original.

2. *Usando JavaScript:*
   Você também pode aplicar escalas programaticamente em JavaScript, o que é útil quando deseja controlar a escala dinamicamente. Por exemplo:

![WhatsApp Image 2023-10-17 at 08 58 02 (1)](https://github.com/lucasnoelgb/pesquisa/assets/129121307/bf5b224f-b147-4c48-a849-6d9c07514171)

   

   Isso aumentará o tamanho do elemento em duas vezes o tamanho original.

Lembre-se de que um valor de escala de 1 representa o tamanho original, valores maiores que 1 aumentam o elemento e valores menores que 1 diminuem o elemento. Você pode ajustar o valor da escala de acordo com suas necessidades. Certifique-se de definir a propriedade `style.transform` do elemento que deseja dimensionar.

# TRANSFORM

A propriedade `transform` em JavaScript permite aplicar transformações visuais, como rotação, escala, translação e muito mais, a elementos HTML. Ela é amplamente usada para criar animações e manipular a aparência de elementos na página. A propriedade `transform` é usada com CSS e pode ser aplicada a qualquer elemento HTML.

A propriedade `transform` aceita uma série de funções de transformação, que podem ser combinadas conforme necessário. Alguns exemplos dessas funções são:

![WhatsApp Image 2023-10-17 at 08 59 46](https://github.com/lucasnoelgb/pesquisa/assets/129121307/bfa2f6bf-6642-466c-9ddd-6a9d227590ca)


![WhatsApp Image 2023-10-17 at 08 59 46 (1)](https://github.com/lucasnoelgb/pesquisa/assets/129121307/833ffa55-7385-4b95-84b9-84d55344fcdf)


![WhatsApp Image 2023-10-17 at 08 59 46 (2)](https://github.com/lucasnoelgb/pesquisa/assets/129121307/62f36593-c113-4c7d-950b-d673413e1489)


![WhatsApp Image 2023-10-17 at 08 59 47](https://github.com/lucasnoelgb/pesquisa/assets/129121307/d0f5497a-e3a4-4364-9c8d-5d63a7f54b9c)


![WhatsApp Image 2023-10-17 at 08 59 47 (1)](https://github.com/lucasnoelgb/pesquisa/assets/129121307/72b8af46-dea3-410b-9597-87fb53b2ec5a)

   

Para aplicar várias transformações em um elemento, você pode combiná-las em uma única string. Por exemplo:

javascript
element.style.transform = "translate(100px, 50px) rotate(45deg) scale(2)";


Isso moverá, girará e redimensionará o elemento.

A propriedade `transform` é uma maneira poderosa de criar animações e manipular elementos na página da web de forma dinâmica, permitindo uma variedade de efeitos visuais.

# CLIPPING PATH

O Clipping Path em JavaScript permite recortar elementos de uma imagem ou de um elemento HTML para que apenas uma parte específica seja visível. Aqui está uma explicação básica de como funciona:

1. *Defina um elemento ou imagem*: Primeiro, você precisa ter um elemento HTML ou uma imagem na qual deseja aplicar o clipping path.

 ![WhatsApp Image 2023-10-17 at 09 03 36](https://github.com/lucasnoelgb/pesquisa/assets/129121307/800a0154-b796-489e-9f37-a3c6f46fe7b6)


 ![WhatsApp Image 2023-10-17 at 09 03 37](https://github.com/lucasnoelgb/pesquisa/assets/129121307/05498f46-7669-4be7-90fb-0bc9c9682e19)


![WhatsApp Image 2023-10-17 at 09 03 37 (1)](https://github.com/lucasnoelgb/pesquisa/assets/129121307/2d92603b-5e6a-48a6-b5e8-7c8271a47194)

 
![WhatsApp Image 2023-10-17 at 09 03 37 (2)](https://github.com/lucasnoelgb/pesquisa/assets/129121307/e431a045-cb0a-4b41-a983-70f29fcb4c1b)

   

Isso é uma explicação simplificada de como o Clipping Path funciona em JavaScript. Você pode personalizar o caminho de recorte de acordo com suas necessidades para criar efeitos de recorte específicos em imagens ou elementos HTML.
