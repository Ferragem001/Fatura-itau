# Fatura-itau
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fatura Itaú HiperCard</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: 20px auto;
            background-color: #fff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .header {
            text-align: center;
            padding-bottom: 20px;
            border-bottom: 2px solid #eee;
        }
        .header img {
            width: 150px;
        }
        .header h1 {
            color: #ff6200;
            margin-top: 10px;
        }
        .section {
            margin: 20px 0;
        }
        .section h2 {
            color: #0033a0;
            border-bottom: 2px solid #ff6200;
            padding-bottom: 10px;
        }
        .summary, .details, .payment-options, .additional-info {
            padding: 10px;
            border: 1px solid #eee;
            border-radius: 5px;
            background-color: #fafafa;
        }
        .summary p, .payment-options p, .additional-info p {
            margin: 10px 0;
        }
        .details table {
            width: 100%;
            border-collapse: collapse;
        }
        .details table, .details th, .details td {
            border: 1px solid #eee;
            padding: 10px;
            text-align: left;
        }
        .footer {
            text-align: center;
            margin-top: 20px;
            padding-top: 20px;
            border-top: 2px solid #eee;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <img src="logo-itau.png" alt="Itaú HiperCard">
            <h1>Fatura do Cartão HiperCard</h1>
            <p>Nome do Titular: João da Silva</p>
            <p>Número do Cartão: **** **** **** 1234</p>
            <p>Data de Emissão: 15/07/2024</p>
            <p>Data de Vencimento: 05/08/2024</p>
        </div>
        
        <div class="section summary">
            <h2>Resumo da Fatura</h2>
            <p>Limite de Crédito: R$ 5.000,00</p>
            <p>Limite Disponível: R$ 2.500,00</p>
            <p>Total da Fatura Anterior: R$ 1.200,00</p>
            <p>Pagamento Recebido: R$ 1.200,00</p>
            <p>Compras e Saques: R$ 2.000,00</p>
            <p>Juros/Encargos: R$ 50,00</p>
            <p>Total a Pagar: R$ 2.050,00</p>
            <p>Pagamento Mínimo: R$ 205,00</p>
        </div>
        
        <div class="section details">
            <h2>Detalhamento das Transações</h2>
            <table>
                <thead>
                    <tr>
                        <th>Data</th>
                        <th>Descrição</th>
                        <th>Valor</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>01/07/2024</td>
                        <td>Compra Supermercado</td>
                        <td>R$ 300,00</td>
                    </tr>
                    <tr>
                        <td>02/07/2024</td>
                        <td>Compra Restaurante</td>
                        <td>R$ 150,00</td>
                    </tr>
                    <tr>
                        <td>05/07/2024</td>
                        <td>Pagamento Internet</td>
                        <td>R$ 100,00</td>
                    </tr>
                    <tr>
                        <td>10/07/2024</td>
                        <td>Saque Caixa Eletrônico</td>
                        <td>R$ 500,00</td>
                    </tr>
                    <tr>
                        <td>12/07/2024</td>
                        <td>Compra Loja de Roupas</td>
                        <td>R$ 950,00</td>
                    </tr>
                </tbody>
            </table>
        </div>
        
        <div class="section payment-options">
            <h2>Opções de Pagamento</h2>
            <p><strong>Código de Barras:</strong> 12345.67890 12345.678901 23456.789012 3 45678.901234</p>
            <p><strong>PIX:</strong> Chave aleatória para pagamento por PIX.</p>
            <p><strong>Débito Automático:</strong> Opção para habilitar o débito automático na conta Itaú.</p>
