# FORMULARIO-LOGIN-INTERDISCIPLINAR
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></SURPREENDA-SE></title>

    <style>

        *{
            box-sizing: border-box;
        }

        body{
            width: 100%;
            height: 100%;
        }

        form{
            width: 300px;
            margin: 200px auto;
            text-align: center;
        }

        input{
            display: block;
            margin: 10px auto;
            width: 250px;
            height: 30px;
        }

    </style>

</head>
<body>


    <form>

        <h3>Login</h3>
        <input type="text" placeholder="Login" id="login">
        <input type="password" placeholder="Senha" id="senha">
        <input type="submit" onclick="logar(); return false">
        <input type="reset" value="cancelar" class=" cancela-login-senha" formnovalidate>

    </form>


    <script>


        function logar(){

            var login = document.getElementById('login').value;
            var senha = document.getElementById('senha').value;

            if(login == "cristiano" && senha == "cristiano"){
                alert('Sucesso');
                location.href = "BOAS VINDAS CRISTIANO VITOR.php";
            }else{
                alert('Usuario ou senha incorretos');
            }

        }

    </script>

</body>
</html>
