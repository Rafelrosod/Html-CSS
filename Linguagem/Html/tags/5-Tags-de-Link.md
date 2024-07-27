# Tag de Link

* **`<a>`**: Define um hyperlink

O `target` atributo especifica onde abrir o documento vinculado.

O `target` atributo pode ter um dos seguintes valores:

* `_self` - Padrão. Abre o documento na mesma janela/guia em que foi clicado
* `_blank` - Abre o documento em uma nova janela ou aba
* `_parent`- Abre o documento no quadro pai
* `_top-` - Abre o documento no corpo inteiro da janela

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
        <p>
            Nota: Um link não precisa ser texto. Um link pode ser uma imagem ou qualquer outro elemento HTML!
        </p>
        <a href="https://www.w3schools.com/">Link text</a>
        <a href="https://www.youtube.com/watch?v=aP5avoK9Mbg&t=2s" target="_self">Link self</a>
        <a href="https://www.youtube.com/watch?v=aP5avoK9Mbg&t=2s" target="_blank">Link blank</a>
        <a href="https://www.youtube.com/watch?v=aP5avoK9Mbg&t=2s" target="_parent">Link parent</a>
        <a href="https://www.youtube.com/watch?v=aP5avoK9Mbg&t=2s" target="_top">Link top</a>
    </body>
</html>
~~~