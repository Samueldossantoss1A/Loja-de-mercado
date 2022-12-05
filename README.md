Index.html

<!DOCTYPE html>
<html lang="pt-br">
	<head>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width">
		<title>Barbearia Alura</title>

		<link rel="stylesheet" href="reset.css">
		<link rel="stylesheet" href="style.css">
		<link href="https://fonts.googleapis.com/css?family=Montserrat&display=swap" rel="stylesheet">
	</head>

	<body>
		<header>
			<div class="caixa">
				<h1><img src="logo.png"></h1>

				<nav>
					<ul>
						<li><a href="index.html">Home</a></li>
						<li><a href="produtos.html">Produtos</a></li>
						<li><a href="contato.html">Contato</a></li>
					</ul>
				</nav>
			</div>
		</header>

		<img class="banner" src="banner.jpg">

		<main>
			<section class="principal">
				<h2 class="titulo-principal">Sobre a Barbearia Alura</h2>

				<h2 class="titulo-centralizado">Sobre o Mercado Deller</h2>
                <p>Localizado no centro da cidade, Traz para os clientes produtos para o dia a dia com descontos e com o menor preço da cidade,tudo que você precisar você encontra aqui, no <strong>Mercado Deller</strong>.</p>
                <p id="missao"><em>Nossa missão é: <strong>"Dar tudo oque o cliente precisa com um preço mais barato"</strong>.</em></p>
                <p>Oferecemos nesse site um jeito de você fazer sua compra sem precisar sair de casa e com um preço bem mais barato.</p>
			</section>

			<section class="mapa">
				<h3 class="titulo-principal">Nosso estabelecimento</h3>
				<p>Nosso estabelecimento está localizado no coração da cidade.</p>

			</section>

			<section class="beneficios">
				<h3 class="titulo-principal">Benefícios</h3>

				<div class="conteudo-beneficios">
					<ul class="lista-beneficios">
						<li class="itens">Atendimento aos Clientes</li>
						<li class="itens">Espaço diferenciado</li>
						<li class="itens">Localização</li>
						<li class="itens">Profissionais Qualificados</li>
						<li class="itens">Pontualidade</li>
						<li class="itens">Limpeza</li>
					</ul><img src="beneficios.jpg" class="imagem-beneficios">
				</div>
			</section>
		</main>

		<footer>
			<img src="bg.jpg">
			<p class="copyright">&copy; Copyright Mercado Deller - 2022</p>
		</footer>
	</body>
</html>

----------------style.css--------------------------


   #banner {
	width:100%;
}

.principal{
	background: #b3ddff;
	padding: 20px;
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
	color: #ff0000;
}

.itens {
	font-style: italic
}

.beneficios {
	background: #b3ddff;
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
