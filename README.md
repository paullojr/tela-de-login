<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>tela de longin</title>
    <style>
        body{
            font-family: Arial, Helvetica, sans-serif;
            background-image: linear-gradient(45deg, green,yellow)
        }
        div{background-color: rgba(0, 0, 0, 0.8);
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%,-50%);
            padding: 80px;
            border-radius: 15px;
            color: beige;
            }
            input{
                padding: 15px;
                border:none ;
                outline: none;
                font-size: 15px;

                            }
                            button{
                                background-color: blue;
                                border: none;
                                padding: 15px;
                                width: 100%;
                                border-radius: 10px;
                                color:aliceblue;
                                font-size: 15px;
                            }
                        button:hover{
                            background-color: rgba(0, 255, 255, 0.541);
                            
                        }
    </style>
</head>
<body>
    <div>
        <h1> <!---login e senha -->
            login
        </h1>
        <input type="text" placeholder="nome" ><br><br> <!---nome do longin-->
        <input type="password" placeholder="senha"><!---senha --><br><br>
        <button>enviar</button>
    </div>
</body>
</html>
