8. Tags de Formulário
Usadas para criar formulários interativos.

* **`<form>`**: Define um formulário.
* **`<input>`**: Define um campo de entrada.
* **`<textarea>`**: Define uma área de texto.
* **`<button>`**: Define um botão.
* **`<select>`**: Define um menu suspenso.
* **`<option>`**: Define uma opção em um menu suspenso.
* **`<label>`**: Define um rótulo para um elemento de formulário.
* **`<fieldset>`**: Agrupa elementos de um formulário.
* **`<legend>`**: Define uma legenda para um `<fieldset>`.

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
    <form action="" method="get">
        <fieldset>
            <legend>Formulário</legend>
            <label for="fname">Primeiro nome:</label>
            <input type="text" id="fname" name="fname"><br>
            <label for="lname">Útimo nome:</label>
            <input type="text" id="lname" name="lname"><br>
            <input type="submit" value="Enviar">
        </fieldset>
    </form>
    <fieldset>
        <legend>Aleatório</legend>
        <label for="Meu textarea">TextArea:</label>
        <textarea id="Meu textarea" rows="2" cols="8"></textarea>
        <button id="Meu textarea" name="Meu textarea">Enviar</button>
        <select name="cars" id="cars">
            <option value="volvo">Volvo</option>
            <option value="saab">Saab</option>
            <option value="mercedes">Mercedes</option>
            <option value="audi">Audi</option>
        </select>
    </fieldset>
</body>
</html>
~~~
