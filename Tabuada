<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora tabuada</title>
</head>
<body>
    <form action="" method="post">
        <label>Digite um valor para calcular a tabuada</label><br>
        <input type="number" name="txtNumero" id="txtNumero"><br>
        <input type="submit" value="Calcular">

    </form>

    <?php
        #Cria variável a partir da entrada do usuário
        $num = $_POST['txtNumero'];

        #Cria um loop que vai ser finalizado quando o valor de 'i' for igual a 10
        for($i = 1; $i <= 10; $i++){
            #Calcula os valores e guarda na variável total
            $total = $num * $i;
            #Imprime os valores na tela para o usuário
            echo "$num x $i = $total<br>";
                
            }

    ?>

</body>
</html>
