# Tags Semânticas

* **`<header>`**: Define o cabeçalho de uma seção ou página.
* **`<footer>`**: Define o rodapé de uma seção ou página.
* **`<section>`**: Define uma seção no documento.
* **`<article>`**: Define um conteúdo independente e auto-contido.
* **`<aside>`**: Define conteúdo lateral ou complementar.
* **`<nav>`**: Define links de navegação.
* **`<main>`**: Define o conteúdo principal do documento.

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
    <header>
        <h1>Meu Site</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">Sobre</a></li>
            <li><a href="#services">Serviços</a></li>
            <li><a href="#contact">Contato</a></li>
        </ul>
    </nav>
    <main>
        <section id="home">
            <h2>Bem-vindo ao Meu Site</h2>
            <p>Conteúdo principal da página inicial.</p>
        </section>
        <article>
            <h2>Google Chrome</h2>
            <p>Google Chrome is a web browser developed by Google, released in 2008. Chrome is the world's most popular
                web browser today!</p>
        </article>
        <aside>
            <h4>Epcot Center</h4>
            <p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international
                pavilions, award-winning fireworks and seasonal special events.</p>
        </aside>
        <section id="about">
            <h2>Sobre Nós</h2>
            <p>Informações sobre a empresa.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Meu Site. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
~~~

