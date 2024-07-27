# Tags de Cabeçalho

- **`<h1>` a `<h6>`**: Cabeçalhos, do maior (`<h1>`) ao menor (`<h6>`).
- **`<meta>`**: Define metadados sobre o documento, como charset e viewport.
- **`<link>`**: Usado para vincular recursos externos, como folhas de estilo.
- **`<style>`**: Contém CSS para estilizar o documento.
- **`<base>`**: Define a URl base para todos os links relativos no documento.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Exemplo de Uso da Tag Base</title>
    <base href="https://www.exemplo.com/" target="_blank" />
  <style>
    body{
        color: red;
    }
  </style>
  </head>
  <body>
    <h1>TEXTO</h1>
    <h2>TEXTO</h2>
    <h3>TEXTO</h3>
    <h4>TEXTO</h4>
    <h4>TEXTO</h5>
    <h6>TEXTO</h6>
    <a href="pagina.html">Ir para a Página</a>
    <img src="imagens/foto.jpg" alt="Foto Exemplo" />
</body>
</html>
```
