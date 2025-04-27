<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu site dos anos 90</title>
    <style>
    body, html{
        margin: 0;
        padding: 0;
        height: 100vh;
        background: url(https://www.google.com/url?sa=i&url=https%3A%2F%2Fblog.stripme.com.br%2Fde-repente-30-anos-depois-10-coisas-dos-anos-90-que-estao-de-volta%2F&psig=AOvVaw0bjfapW9CYjpH6hPZwb9l9&ust=1745844776209000&source=images&cd=vfe&opi=89978449&ved=0CBMQjRxqFwoTCKijwuSg-IwDFQAAAAAdAAAAABAR)repeat;
        display: flex;
        justify-content: center;
        align-items: center;
        font-family: 'Comic sans MS', cursive, sans-serif;
        color: yellow;
    }  

     .container{
        width: 800px;
        height: 600px;
        background-color: #00008b;
        border: 10px ridge yellow;
        padding: 20px;
        box-sizing: border-box;
        overflow: auto;
        text-align: center;
    }

    h1{
        font-size: 48px;
        text-shadow: 2px 2px #ff00ff;
        animation: piscaTitulo 1s infinite alternate;
    }

    @keyframes piscaTitulo{
        from {opacity: 1; }
        to {opacity: 0.5; }
    }

    p{
        font-size: 20px;
        margin-top: 20px;
    }

    .botao{
        display: inline-block;
        margin-top: 30px;
        padding: 10px 20px;
        font-size: 24px;
        color: white;
        background-color: red;
        border: 3px dashed yellow;
        text-decoration: none;
        animation: piscaBotao 0.8s infinite alternate;
        cursor: pointer;
    }

    @keyframes piscaBotao{
        from {background-color: red; } 
        to {background-color: orange; }
    }

    .rodape{
        margin-top: 40px;
        font-size: 16px;
        color: #00ffff;
    }
    </style>
    <script>
   function clicarBotao(){
   alert("Veio matar a saudade dos velhos tempos no lugar certo!"); 
   }     
    </script>
</head>
<body>
   <div class="container">
    <h1>Bem-Vindo Ao Meu Site!</h1>
    <p>Este é o local ideal para o site anos 90! Cheio de cores vibrantes, animações piscantes e muito amor pela internet raiz!</p>

    <button class="botao" onclick="clicarBotao()">Clique aqui!</button>

    <div class="rodape">
      <p>&copy;1999 Meusite90s.com | Todos os direitos reservados</p>  
    </div>
   </div>
</body>
</html>
