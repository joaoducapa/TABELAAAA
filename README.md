<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form action="processar.php" method="post">
        <label for="nome">nome:</label>
        <input type="text" id="nome" name="nome" placeholder="digite seu nome completo" required> <br>

        <label for="email">E-mail:</label>
        <input type="email" id="email" name="email" placeholder="Digite seu e-mail" required> <br>

        <label for="telefone">telefone:</label>
        <input type="tel" id="telefone" name="telefone" placeholder="Digite seu telefone" required> <br>

        <label for="rua">Rua:</label>
        <input type="text" id="rua" name="rua" placeholder="Digite o nome da rua" required> <br>

        <label for="cidade">Cidade:</label>
        <input type="text" id="cidade" name="cidade" placeholder="Digite o nome da cidade" required> <br>

        <label for="estado">Estado:</label>
        <input type="text" id="estado" name="estado" placeholder="Digite o nome do estado" required> <br>

        <label for="cep">CEP:</label>
        <input type="text" id="cep" name="cep" placeholder="Digite o cep" required> <br>

        <label for="dataNascimento">DataNascimento:</label>
        <input type="date" id="dataNascimento" name="dataNascimento" placeholder="dataNascimento" required> <br>

        <button>type="submit">Enviar</button>
        
     </form>
    


        
</body>
</html>
