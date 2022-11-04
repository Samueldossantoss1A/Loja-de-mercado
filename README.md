Index.html

<!DOCTYPE html>
<html lang="pt-br">
	<head>
		<meta charset="UTF-8">
		<title>Mercado Deller</title>
		<link rel="stylesheet" href="style.css">
	</head>

	<body>
		<header>
			<h1 class="titulo-principal">Mercado Deller</h1>
		</header>
		<img id="banner" src="banner.jpg">
		<div class="principal">
			<h2 class="titulo-centralizado">Sobre o Mercado Deller</h2>
            <p>Localizado no centro da cidade, Traz para os clientes produtos para o dia a dia com descontos e com o menor preço da cidade,tudo que você precisar você encontra aqui, no <strong>Mercado Deller</strong>.</p>
            <p id="missao"><em>Nossa missão é: <strong>"Dar tudo oque o cliente precisa com um preço mais barato"</strong>.</em></p>
            <p>Oferecemos nesse site um jeito de você fazer sua compra sem precisar sair de casa e com um preço bem mais barato.</p>
		</div>

		<div class="beneficios">
			<h3 class="titulo-centralizado">Benefícios</h3>

			<ul>
				<li class="itens">Atendimento aos Clientes</li>
				<li class="itens">Espaço diferenciado</li>
				<li class="itens">Localização</li>
				<li class="itens">Profissionais Qualificados</li>
			</ul>

			<img src="beneficios.jpg" class="imagembeneficios">
		</div>
	</body>
</html>

----------------style.css--------------------------


    body {
	
    }
    
    #banner {
        width:100%;
    }
    
    .principal{
        background: #CCCCCC;
        padding: 30px;
    }
    
    .titulo-principal {
        padding-left: 20px;
    }
    
    .titulo-centralizado {
        text-align: center
    }
    
    p {
        text-align: center;
    }
    
    #missao {
        font-size: 20px
    }
    
    em strong {
        color: #FF0000;
    }
    
    .itens {
        font-style: italic
    }
    
    .beneficios {
        background: #FFFFFF;
        padding: 20px;
    }
    
    ul {
        display: inline-block;
        vertical-align: top;
        width: 20%;
        margin-right: 15%;
    }
    
    .imagembeneficios {
        width: 50%;
    }
