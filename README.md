<!-- # landing-page-template

<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="styles.css">
    <title>4FOOD</title>
</head>

<body>
    <header>
        <div class="procurar-lupa-login">
            <form action="/" method="GET" class="form">
                <input type="search" placeholder="Procurar" class="busca-de-produtos" name="busca-de-produtos">
                <button type="submit">
                    <img class="icone" src="img/search-icon.png">
                </button>
            </form>
            <a target="_blank" href="" class="login">Login</a>
        </div>
    </header>


    <main class="principal">

        <section class="principal-conteudo">
            <div class="botoes"> <a href="#"><button class="botao-mercado">teste</button></a>
                <a href="#"><button class="botao-comida-pronta">teste</button></a>
            </div>
            <img class="principal-logo" src="img/4food.png" alt="logotipo-chapeu-formatura">


            <div class="principal-conteudo-texto">

                <h1 class="principal-titulo">Sempre os melhores preços</h1>
            </div>

        </section>

        <!-- <section class="secundario">
            <h3 class="secundario-titulo">texto não tao pequeno</h3>
            <p class="secundario-paragrafo">paragrafo1</p>
            <p class="secundario-paragrafo">paragrafo1</p>
            <p class="secundario-paragrafo">paragrafo1</p>
        </section> -->

    </main>

    <footer class="rodape">
        <h2>4Food</h2></b>
        <p> © Copyright 2021 - 4Food -
            Todos os direitos reservados 4Food com Agência de Restaurantes Online S.A.
        </p><img class="imagem-footer" src="img/Instagram-Icon.png" alt="rodapé">
        <title>4FOOD</title>
    </footer>

<!-- </body>

</html> --> -->


.rodape {
    position:static;
    width: 100%;
    bottom: 0;
    text-align: center;
    border: 1px solid black;
    display: flex;
    justify-content: space-evenly;
    background-color: beige;
}
*img { 
    width: 40px;
    height: 40px;
} 

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
}

.principal{
    background-color: #ffffff;
    border-top: 0.5px solid hsla(0, 0%, 0%, 0.425);
    margin-bottom: 48px;
}

.principal-conteudo{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-around;
    margin-top: 30px;
    margin-left: 30px;
    margin-right: 30px;
}

.principal-conteudo-texto{
    display: flex;
    flex-direction: column;
    gap: 24px;
}

.principal-titulo{
    font-weight: 400;
    font-size: 64px;
    color: hsla(199, 100%, 14%, 0.425);
}

.principal-subtitulo{
    font-weight: 400;
    font-size: 24px;
    color: hsla(200, 100%, 9%, 0.425);
}

.botao-mercado{
	background:linear-gradient(to bottom, #baebff 5%, #c4f5ff 100%);
	border-radius:8px;
	color:#000000;
    font-size:20px;
	font-weight:bold;
	padding:13px 32px;
    height: 55;
    width: 81800;
}

.botao-comida-pronta{
    background:linear-gradient(to bottom, #baebff 5%, #c4f5ff 100%);
	border-radius:8px;
	color:#000000;
    font-size:20px;
	font-weight:bold;
	padding:13px 32px;
    height: 55;
    width: 81800;
}

.principal-4food-logo{
    width: 25%; 
    border-radius: 50%;
    margin-top: 25px;
}

.botoes{
 display:grid;
 align-items:center;
}


.secundario{
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 24px;
    margin-top: 48px;
    border-top: 0.5px solid hsla(199, 58%, 50%, 0.425);
    padding-top: 48px;
}

.secundario-titulo{
    
    font-weight: 400;
    font-size: 64px;
    color: hsla(199, 100%, 14%, 0.425);
}

.secundario-paragrafo{
    
    font-weight: 400;
    font-size: 24px;
    color: hsla(200, 100%, 9%, 0.425);
    border-radius: none;
}

.procurar-lupa-login {
    display: flex;
    padding: 16px;
    justify-content: flex-end;
    gap: 16px;
    align-items: center;
}

.busca-de-produtos {
    font-size: 16px;
}

.icone {
    width: 16px;
}
.login {
    font-size: 18px;

}

.imagem-footer{
width: 50px;
}
