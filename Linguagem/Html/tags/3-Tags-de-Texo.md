# Tags de Texto

* **`<p>`**: Define um parágrafo.
* **`<br>`**: Insere uma quebra de linha.
* **`<hr>`**: Insere uma linha na horizontal.
* **`<strong>`**: Destaca texto em negrito.
* **`<em>`**: Destaca texto em negrito.
* **`<small>`**: Define texto pequeno.
* **`<blockquote>`**: Define uma citação em bloco.
* **`<code>`**: Define um trecho de código.
* **`<pre>`**: Define texto pré-formatado.

~~~html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Exemplo de Código JavaScript</title>
    <meta name="description" content="Exemplo de uso da tag code para exibir código JavaScript">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }

        pre {
            background-color: #f4f4f4;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        code {
            font-family: "Courier New", Courier, monospace;
            color: #d63384;
        }
    </style>
</head>
<body>
    <p>Um parágrafo.</p>
    <hr>
    <p>
        <small>Lorem ipsum</small> dolor sit amet. Et <strong>voluptatem</strong> quod est dolores magnam ut laboriosam
        eveniet quo provident<br> eaque est vero facere. Et laborum incidunt vel dolor beatae non sint ducimus id
        expedita modi est galisum<br> natus aut reiciendis iure sed deleniti minima. Qui temporibus voluptatem sed
        <em>voluptatem</em> iure est explicabo<br> magnam non nisi eaque et velit praesentium nam magni praesentium aut
        ipsum dolorem.
    </p>
    <blockquote>laboriosam</blockquote>
    <p>
        <small>Lorem ipsum</small> dolor sit amet. Et <strong>voluptatem</strong> quod est dolores magnam ut laboriosam
        eveniet quo provident<br> eaque est vero facere. Et laborum incidunt vel dolor beatae non sint ducimus id
        expedita modi est galisum<br> natus aut reiciendis iure sed deleniti minima. Qui temporibus voluptatem sed
        <em>voluptatem</em> iure est explicabo<br> magnam non nisi eaque et velit praesentium nam magni praesentium aut
        ipsum dolorem.
    </p>
    <h1>Exemplo de Código JavaScript</h1>
    <p>Aqui está um exemplo de como usar a tag <code>&lt;code&gt;</code> para exibir código JavaScript em uma página
        HTML:</p>
    <pre><code>
function saudacao(nome) {
    return `Olá, ${nome}!`;
}
const nome = "Mundo";
console.log(saudacao(nome));
    </code></pre>
    <p>Você também pode usar a tag <code>&lt;code&gt;</code> inline para pequenos trechos de código, como neste exemplo: <code>const nome = "Mundo";</code></p>
    <script>
        console.log("Teste do console.log");
    </script>
</body>
</html>
~~~
