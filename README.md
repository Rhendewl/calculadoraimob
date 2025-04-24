<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Calculadora de Funil Imobiliário</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f7f7f7;
      padding: 20px;
      max-width: 600px;
      margin: auto;
    }
    h1 {
      color: #333;
      text-align: center;
    }
    label {
      font-weight: bold;
      display: block;
      margin-top: 15px;
    }
    input {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    button {
      background-color: #2e86de;
      color: white;
      padding: 10px 15px;
      margin-top: 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      width: 100%;
      font-size: 16px;
    }
    button:hover {
      background-color: #1b4f72;
    }
    .resultado {
      background: white;
      padding: 15px;
      margin-top: 20px;
      border-radius: 5px;
      box-shadow: 0px 0px 8px rgba(0,0,0,0.1);
    }
  </style>
</head>
<body>
  <h1>Calculadora de Funil Imobiliário</h1>
  <label for="metaVendas">Meta de vendas:</label>
  <input type="number" id="metaVendas" placeholder="Ex: 5" />

  <label for="taxaFechamento">Taxa de fechamento (%):</label>
  <input type="number
