# Tags de Tabela

* **`<table>`**: Define uma tabela.
* **`<tr>`**: Define uma linha na tabela.
* **`<td>`**: Define uma célula de dados na tabela.
* **`<th>`**: Define uma célula de cabeçalho na tabela.
* **`<thead>`**: Agrupa o cabeçalho da tabela.
* **`<tbody>`**: Agrupa o corpo da tabela.
* **`<tfoot>`**: Agrupa o rodapé da tabela.
* **`<caption>`**: Define uma legenda para a tabela.

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
        <style>
            body{
                background-color: #8AA399;
                display: flex;
                justify-content: center;
                align-items: center;
                height: 100vh;
                margin: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .table-container{
                width: auto;
                background-color: #8FA6CB;
                padding: 20px;
                border-radius: 8px;
                box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            }
            table{
                width: 100%;
                border-collapse: collapse;
                background-color: #DBF4A7;
            }
            th, td{
                padding: 10px;
                border: 1px solid black;
                text-align: center;
            }
            thead{
                background-color: #7D84B2;
            }
            tfoot{
                background-color: #D5F9DE;
                font-weight: bold;
            }
            @media (max-width:600px){
                body{
                    padding: 10px;
                }
                .table-container{
                    width: 100%;
                    padding: 10px;
                }
            }
        </style>
    </head>
    <body>
        <div class="table-container">
            <table>
                <thead>
                <tr>
                    <th>Semana</th>
                    <th>Janeiro</th>
                    <th>Fevereio</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>1 Semana</td>
                    <td>200</td>
                    <td>100</td>
                </tr>
                <tr>
                    <td>2 Semana</td>
                    <td>300</td>
                    <td>500</td>
                </tr>
                <tr>
                    <td>3 Semana</td>
                    <td>600</td>
                    <td>500</td>
                </tr>
                <tr>
                    <td>4 Semana</td>
                    <td>100</td>
                    <td>100</td>
                </tr>
            </tbody>
            <tfoot>
                <tr>
                    <td>Total</td>
                    <td>1200</td>
                    <td>1200</td>
                </tr>
            </tfoot>
            </table>
        </div>
    </body>
</html>
~~~

