<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>JoKenPô</title>
</head>
<body>
    <h1>JoKenPô em JavaScript</h1>
    <h3>Jogador:</h3>
    <img src="pedra.png" alt="pedra" height="50" width="64">    
    <img src="papel.png" alt="papel" height="50" width="64">
    <img src="tesoura.png" alt="tesoura" height="50" width="64">
    <form name = "frmJokenpo">
        <input type="radio" name="grupo" id="pedra">Pedra
        <input type="radio" name="grupo" id="papel">Papel
        <input type="radio" name="grupo" id="tesoura">Tesoura    
    <p>
        <input type="button" value=" JOGAR " onclick="jogar()">
        <input type="reset" value=" RESET " onclick="resetar()">
    </p>
</form>
<hr>
<h3>Computador:</h3>
<img src="pc.png" alt="pc" id="pc">
<hr>

<h3 id="resultado"></h3>
<script src="jokenpô.js"></script>

</body>
</html>