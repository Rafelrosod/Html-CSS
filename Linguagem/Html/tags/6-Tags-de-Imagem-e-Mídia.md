# Tags de Imagem e Mídia.

* **`<img>`**:: Insere uma imagem.
* **`<<audio>`**: Insere um arquivo de áudio.
* **`<video>`**: Insere um arquivo de vídeo.
* **`<source>`**: Especifica múltiplas fontes para elementos de mídia.
* **`<track>`**: Adiciona faixas de texto a elementos de mídia.

~~~html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title></title>
        <meta name="description" content="">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="">
    </head>
    <body>
        <img width="600px" height="400px" src="https://i.pinimg.com/originals/5d/ca/7c/5dca7cc260f6a37fac8dd593474c1d8e.jpg">
        <audio controls>
            <source src="itadori-vs-mahito.mp3" type="audio/mp3">
        </audio>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/Ao28h8lltXg?si=KaqNeyGbFWFRUgd9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" llowfullscreen></iframe>
    </body>
</html>
~~~