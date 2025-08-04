# Porta-da-transpar-ncia-
A <!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>App Modelo</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <h1>Bem-vindo ao App Modelo!</h1>
  <button id="btn">Clique aqui</button>

  <script src="main.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  text-align: center;
  padding: 2rem;
  background: #f0f0f0;
}

h1 {
  color: #333;
}

button {
  padding: 10px 20px;
  font-size: 1rem;
  cursor: pointer;
}

document.getElementById('btn').addEventListener('click', () => {
  alert('Você clicou no botão!');
});
