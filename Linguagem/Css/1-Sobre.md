# Css.
___

**CSS** (Cascading Style Sheets) é uma linguagem utilizada para descrever a apresentação de um documento HTML ou XML. CSS define como os elementos HTML devem ser exibidos, proporcionando uma separação entre o conteúdo e a apresentação. Com CSS, você pode controlar o layout, cores, fontes e outros aspectos visuais de uma página web.

#### Estrutura Básica

Um arquivo CSS consiste em uma série de regras que especificam como os elementos HTML devem ser estilizados. Cada regra CSS possui um seletor e um bloco de declarações:

~~~css
seletor {
    propriedade: valor;
    propriedade: valor;
}
~~~
#### Exemplos
~~~css
/* Seleciona todos os elementos <p> e define a cor do texto para azul e a fonte para Arial */
p {
    color: blue;
    font-family: Arial, sans-serif;
}

/* Seleciona o elemento com id "header" e define um fundo cinza */
#header {
    background-color: #f4f4f4;
}

/* Seleciona todos os elementos com a classe "container" e define a largura para 100% */
.container {
    width: 100%;
}
~~~

#### Seletores

CSS oferece uma variedade de seletores para aplicar estilos aos elementos:

* **Seletores de Elemento:** Selecionam todos os elementos de um tipo específico (div, p, h1, etc.).
* **Seletores de Classe:** Selecionam elementos que possuem uma determinada classe (.classe).
* **Seletores de ID:** Selecionam um elemento com um ID específico (#id).
* **Seletores de Atributo:** Selecionam elementos com um atributo específico ([atributo="valor"]).
* **Seletores de Pseudo-classe:** Selecionam elementos em um estado específico (:hover, :active, :nth-child, etc.).
* **Seletores de Pseudo-elemento:** Selecionam partes específicas de elementos (::before, ::after, ::first-line, etc.).

#### Cascata e Herança.

CSS segue um modelo de cascata e herança, onde as regras são aplicadas em uma ordem específica:

* **Especificidade:** Regras com seletores mais específicos têm maior prioridade.
* **Origem das Regras:** Estilos inline têm a maior prioridade, seguidos por estilos em folhas de estilo internas e externas.
* **Importância:** A palavra-chave `!important` pode ser usada para dar prioridade máxima a uma regra.

#### Modelo de Caixa

O modelo de caixa é um conceito fundamental em CSS que descreve como os elementos são exibidos e dimensionados na página:

* **Margem:** Espaço externo ao redor do elemento.
* **Borda:** Linha ao redor do elemento.
* **Padding:** Espaço interno entre o conteúdo do elemento e a borda.
* **Conteúdo:** O próprio conteúdo do elemento.

~~~css
.elemento {
    margin: 10px;
    border: 1px solid #000;
    padding: 20px;
    width: 100px;
    height: 50px;
}
~~~
#### Layouts

CSS oferece várias técnicas para criar layouts responsivos e flexíveis:

* **Flexbox:** Layout unidimensional para alinhar e distribuir espaço entre itens em um contêiner.
* **Grid:** Layout bidimensional para criar layouts complexos com linhas e colunas.
* **Positioning:** Controle da posição dos elementos com static, relative, absolute, fixed e sticky.
* **Media Queries:** Aplicação de estilos com base em características da tela, como largura, altura e resolução.

##### Exemplo de Flexbox

~~~css
.container {
    display: flex;
    justify-content: center; /* Alinha os itens horizontalmente ao centro */
    align-items: center; /* Alinha os itens verticalmente ao centro */
    height: 100vh; /* Altura total da viewport */
}

.item {
    width: 100px;
    height: 100px;
    background-color: lightcoral;
    margin: 10px;
}
~~~

#### Exemplo de Grid

~~~css
.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr); /* Três colunas de largura igual */
    gap: 10px; /* Espaço entre os itens */
}

.item {
    background-color: lightblue;
    padding: 20px;
    text-align: center;
}
~~~

#### Ferramentas e Pré-processadores

CSS pode ser ampliado com ferramentas e pré-processadores que facilitam a escrita e a manutenção dos estilos:

* **Sass:** Pré-processador que adiciona funcionalidades como variáveis, aninhamento e mixins.
* **Less:** Pré-processador que oferece recursos semelhantes ao Sass.
* **PostCSS:** Ferramenta que permite o uso de plugins para transformar CSS com várias funcionalidades.

##### CSS é uma linguagem poderosa que permite criar designs atraentes e responsivos para a web.