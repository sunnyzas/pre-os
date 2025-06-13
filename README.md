<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lista de Preços do Restaurante</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 20px;
            background-color: #e0f2f7; /* Um azul claro suave */
            color: #333;
        }
        h1 {
            color: #00796b; /* Um verde-água mais escuro */
            text-align: center;
            margin-bottom: 30px;
            font-size: 2.5em;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
        }
        table {
            width: 85%;
            margin: 20px auto;
            border-collapse: collapse;
            box-shadow: 0 4px 15px rgba(0,0,0,0.15); /* Sombra mais pronunciada */
            background-color: #ffffff;
            border-radius: 8px; /* Cantos arredondados */
            overflow: hidden; /* Garante que os cantos arredondados funcionem com a borda */
        }
        th, td {
            padding: 15px 20px;
            text-align: left;
            border-bottom: 1px solid #e0e0e0;
        }
        th {
            background-color: #009688; /* Verde-água */
            color: white;
            text-transform: uppercase;
            font-weight: bold;
            letter-spacing: 0.05em;
        }
        tr:nth-child(even) {
            background-color: #f2fafa; /* Linhas pares um pouco mais claras */
        }
        tr:hover {
            background-color: #c8e6c9; /* Um verde claro ao passar o mouse */
            cursor: pointer;
        }
        .price {
            text-align: right;
            font-weight: bold;
            color: #e91e63; /* Um rosa vibrante para o preço */
            font-size: 1.1em;
        }
        .category-heading {
            background-color: #b2dfdb; /* Cor de fundo para cabeçalhos de categoria */
            color: #004d40; /* Cor do texto para cabeçalhos de categoria */
            font-weight: bold;
            text-align: center;
            font-size: 1.3em;
        }
    </style>
</head>
<body>

    <h1>Cardápio e Lista de Preços</h1>

    <table>
        <thead>
            <tr>
                <th colspan="2">Item</th>
                <th>Preço</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td colspan="3" class="category-heading">Opções de Refeição</td>
            </tr>
            <tr>
                <td>Buffet Livre</td>
                <td>Refeição completa à vontade</td>
                <td class="price">R$ 16,00</td>
            </tr>
            <tr>
                <td>Almoço por Quilo</td>
                <td>Refeição pesada por quilo</td>
                <td class="price">R$ 37,00</td>
            </tr>
            <tr>
                <td colspan="3" class="category-heading">Refrigerantes</td>
            </tr>
            <tr>
                <td>Refrigerante 350ml</td>
                <td>Lata (diversas marcas)</td>
                <td class="price">R$ 6,00</td>
            </tr>
            <tr>
                <td>Refrigerante 220ml</td>
                <td>Mini lata (diversas marcas)</td>
                <td class="price">R$ 4,00</td>
            </tr>
            <tr>
                <td>Coca-Cola KS</td>
                <td>Garrafa de vidro retornável</td>
                <td class="price">R$ 6,00</td>
            </tr>
            <tr>
                <td>Coca-Cola 1 Litro</td>
                <td>Garrafa grande</td>
                <td class="price">R$ 10,00</td>
            </tr>
            <tr>
                <td>Coca-Cola 2 Litros</td>
                <td>Garrafa familiar</td>
                <td class="price">R$ 12,00</td>
            </tr>
            <tr>
                <td>Refrigerante 600ml</td>
                <td>Garrafa individual</td>
                <td class="price">R$ 8,00</td>
            </tr>
            <tr>
                <td>Tubaína</td>
                <td>Garrafa 600ml</td>
                <td class="price">R$ 8,00</td>
            </tr>
            <tr>
                <td colspan="3" class="category-heading">Outras Bebidas</td>
            </tr>
            <tr>
                <td>Chá / Suco (copo)</td>
                <td>Copo 300ml (sabores variados)</td>
                <td class="price">R$ 6,00</td>
            </tr>
            <tr>
                <td>Água Mineral</td>
                <td>Garrafa 500ml</td>
                <td class="price">R$ 4,00</td>
            </tr>
            <tr>
                <td>Energéticos</td>
                <td>Lata (diversas marcas)</td>
                <td class="price">R$ 12,00</td>
            </tr>
            <tr>
                <td>Sucos Naturais</td>
                <td>Copo 300ml (frutas da estação)</td>
                <td class="price">R$ 5,00</td>
            </tr>
            <tr>
                <td>Chá Litrinho</td>
                <td>Garrafa pequena de chá</td>
                <td class="price">R$ 7,00</td>
            </tr>
        </tbody>
    </table>

</body>
</html>
