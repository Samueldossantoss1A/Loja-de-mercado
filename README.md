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

----------------produtos.html--------------------------
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title>Produtos - Mercado Deller</title>

		<link rel="stylesheet" href="reset.css">
		<link rel="stylesheet" href="produtos.css">
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

		<main>
			<ul class="produtos">
				<li>
					<h2>Frutas</h2>
					<img src="frutas.jpg">
					<p class="produto-descricao">Todos os tipos de frutas</p>
				</li>
				<li>
					<h2>Carnes</h2>
					<img src="carnes.jpg">
					<p class="produto-descricao">Carnes de todos os tipos</p>
				</li>
				<li>
					<h2>Produtos de Limpeza</h2>
					<img src="produtosdelimpeza.jpg">
					<p class="produto-descricao">Protudos de limpezas de todos os tipos</p>
				</li>
			</ul>
		</main>

		<footer>
			<img src="logo-branco.png">
			<p class="copyright">&copy; Copyright Mercado Deller - 2022</p>
		</footer>
	</body>
</html>
----------------produtos.css--------------------------
header {
	background: #BBBBBB;
	padding: 20px 0;
}

.caixa {
	position: relative;
	width: 940px;
	margin: 0 auto;
}

nav {
	position: absolute;
	top: 110px;
	right: 0;
}

nav li {
	display: inline;
	margin: 0 0 0 15px;
}

nav a {
	text-transform: uppercase;
	color: #000000;
	font-weight: bold;
	font-size: 22px;
	text-decoration: none;
}

nav a:hover {
	color: #C78C19;
	text-decoration: underline;
}

.produtos {
	width: 940px;
	margin: 0 auto;
	padding: 50px 0;
}

.produtos li {
	display: inline-block;
	text-align: center;
	width: 30%;
	vertical-align: top;
	margin: 0 1.5%;
	padding: 30px 25px;
	box-sizing: border-box;
	border: 2px solid #000000;
	border-radius: 10px;
}

.produtos li:hover {
	border-color: #C78C19;
}

.produtos li:active {
	border-color: #088C19;	
}

.produtos li:hover h2 {
	font-size: 25px;
}

.produtos h2 {
	font-size: 25px;
	font-weight: bold;
}

.produto-descricao {
	font-size: 20px;
}

footer {
	text-align: center;
	background: url("bg.jpg");
	padding: 40px 0;
}

.copyright {
	color: #FFFFFF;
	font-size: 100px;
	margin: 100px 0 0;
}
-----------------reset.css--------------------

/* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}
