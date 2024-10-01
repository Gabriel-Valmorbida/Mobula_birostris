# Mobula_birostris

<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>replit</title>
  <link href="style.css" rel="stylesheet" type="text/css" />
</head>
<h2>Formulário Pogger's</h2>
<body>
  <form>
<div>
  <label for="nome">Nome:</label>
  <input type="text" id="nome" name="usuario_nome" />
</div>
  <div>
    <label for="idade">Idade:</label>
    <input type="number" id="idade" name="usuario_idade" 
      min="1" max="100"/>
  </div>
  <div>
    <label for="cidade">Cidade:</label>
    <input type="text" id="cidade" name="usuario_cidade"/>
  </div>
  <label for="cpf">CPF:</label>
  <input type="text" id="cpf" name="usuario_cpf"/>
  </div>              
  
  <div class="button">
    <button type="submit">Enviar dados</button>
  </div>
  </form>
  <script src="script.js"></script>
</body>

</html>
