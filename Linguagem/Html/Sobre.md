# Sobre o Html. 

**Html** (HyperText Markup Language) é a linguagem padrão para a criação de páginas web e aplicações web. 
 
Desde sua criação por Tim Berners-Lee no final dos anos 1980, o HTML tem evoluído constantemente, formando a base da web moderna. HTML permite a estruturação de conteúdo na web de uma maneira que seja compreensível tanto para navegadores quanto para usuários.

#### Estrutura Básica

Um documento HTML é composto por elementos aninhados, que são delimitados por tags. A estrutura básica de um documento HTML inclui:

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Título da Página</title>
</head>
<body>
    <h1>Olá, mundo!</h1>
    <p>Este é um parágrafo de exemplo.</p>
</body>
</html>
~~~

* **`<!DOCTYPE html>`:** Declaração do tipo de documento, indicando que o documento é HTML5.
* **`<Html>`:** Elemento raiz que envolve todo o conteúdo do documento.
* **`<head>`:** Contém metadados sobre o documento, como título, codificação de caracteres e links para estilos e scripts.
* **`<title>`:** Define o título da página, exibido na aba do navegador.
* **`<body>`:** Contém o conteúdo visível da página, como textos, imagens, links e outros elementos.

#### Elementos Comuns

HTML inclui uma variedade de elementos que permitem a construção de páginas ricas e interativas:

* **Elementos de Cabeçalho:** `<h1>, <h2>, <h3>, <h4>, <h5>, <h6> - usados para títulos e subtítulos.`
* **Parágrafos:** `<p>` - define um parágrafo de texto.
* **Links:** `<a>` - cria um hyperlink para outra página ou recurso.
* **Listas:** `<ul>, <ol>, <li>` - definem listas não ordenadas, ordenadas e itens de lista.
* **Imagens:** `<img>` - incorpora uma imagem na página.
* **Tabelas:** `<table>, <tr>, <td>, <th>` - usados para criar tabelas de dados.
* **Formulários:** `<form>, <input>, <textarea>, <button>` permitem a coleta de dados do usuário.

#### Atributos

Elementos HTML podem ter atributos que fornecem informações adicionais sobre o elemento. Alguns atributos comuns incluem:

* **id:** Identificador único do elemento.
* **class:** Classificação do elemento, permitindo a aplicação de estilos CSS.
* **src:** Fonte de um recurso externo, como uma imagem.
* **href:** Destino de um link.
* **alt:** Texto alternativo para imagens.

#### Semântica

HTML5 introduziu novos elementos semânticos que melhoram a legibilidade e a estrutura do código, como `<header>, <nav>, <article>, <section>, <aside> e <footer>.` Esses elementos ajudam a descrever a função do conteúdo dentro de uma página, tornando-a mais acessível e fácil de entender para motores de busca e leitores de tela.

#### Multimídia e APIs

HTML5 também trouxe suporte nativo para áudio e vídeo `<audio>, <video>`, além de APIs poderosas para desenvolvimento de aplicações web avançadas:

* **Canvas:** Permite o desenho de gráficos e imagens dinâmicas.
* **Geolocation:** Obtém a localização geográfica do usuário.
* **Web Storage:** Fornece métodos para armazenar dados no lado do cliente (localStorage e sessionStorage).
* **Web Workers:** Permite a execução de scripts em segundo plano, melhorando o desempenho.

#### Vantagens do HTML

* **Estrutura e Semântica:** Permite a criação de documentos bem estruturados e semanticamente significativos.
* **Compatibilidade:** Suportado por todos os navegadores modernos.
* **Facilidade de Uso:** Simples de aprender e usar, com uma ampla gama de tutoriais e recursos disponíveis.
* **Integração:** Funciona bem com CSS para estilos e JavaScript para interatividade.

##### HTML é a base da web, e seu conhecimento é essencial para qualquer desenvolvedor web. Compreender HTML permite criar páginas web acessíveis, bem estruturadas e prontas para serem estilizadas com CSS e dinamizadas com JavaScript.
