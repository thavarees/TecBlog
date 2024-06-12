<!DOCTYPE html>
<html>
<head>
    <title>TecBlog - O seu Blog de tecnologia</title>
    <meta charset="utf-8">
    <link rel="stylesheet" type="text/css" href="css/estilo.css">
</head>
<body>

<div id="area-cabecalho">

    <div id="area-logo">
        <h1>Tec<span class="branco">Blog</span></h1>
    </div>

    <div id="area-menu">
        <a href="index.html">Home</a>
        <a href="jogos.html">Jogos</a>
        <a href="celulares.html">Celulares</a>
        <a href="informatica.html">Informática</a>
        <a href="eletronicos.html">Eletrônicos</a>
    </div>
</div>

<div id="area-principal">

    <!-- Abertura da área de postagens -->
    <div id="area-postagens">
        
        <div class="postagem">
            <h2>Título da postagem 1</h2>
            <span class="data-postagem">postado em 20 de Março de 2022</span>
            <img width="620px" src="imagens/imagem1.jpg">
            <p>
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
            </p>
            <a href="">Leia mais</a>
        </div><!--// fechamento da postagem-->

        <div class="postagem">
            <h2>Título da postagem 2</h2>
            <span class="data-postagem">postado em 10 de Março de 2022</span>
            <img width="620px" src="imagens/imagem2.jpg">
            <p>
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
            </p>
            <a href="">Leia mais</a>
        </div><!--// fechamento da postagem-->

    </div><!--// fechamento da área de postagens -->

    <div id="area-lateral">

        <div class="conteudo-lateral">
            <h3>Postagens recentes</h3>
            <div>
                <p class="texto-lateral">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
                <a href="">Leia mais</a>
            </div>

            <hr>

            <div>
                <p class="texto-lateral">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
                <a href="">Leia mais</a>
            </div>

        </div>

        <div class="conteudo-lateral">
            <h3>Categorias</h3>
        
            <a href="">Jogos</a><br>
            <a href="">Celulares</a><br>
            <a href="">Informática</a><br>
            <a href="">Eletrônicos</a><br>

        </div>

    </div>

</div>

<div id="rodape">
    Todos os direitos reservados
</div>

</body>
</html>


/*Formatações CSS*/

/*Limpando as formatações padões*/
* {
	margin:0;
	padding: 0
}
body{
	font-size: 1em;
	font-display: "Trebuchet", Helvetica, sans-serif;
	background: #e6e6e6;
}

/*Layout*/

#area-cabecalho{
	background: #f7b600;
	padding: 15px;
	text-align: center;
}

#area-logo, #area-menu{
	padding: 10px;
}

#area-principal{
	width: 920px;
	margin: 0 auto;
	padding: 15px;
}

#area-postagens{
	width: 660px;
	float: left;
}

#area-lateral{
	width: 240px;
	float: right;
}

.postagem{
	padding: 20px;
	margin-bottom: 20px;
	background: white;
}

.conteudo-lateral{
	background: white;
	padding: 10px;
	margin-bottom: 20px;
}

#rodape{
	clear: both;
	text-align: center;
	padding: 15px;
	background: #ccc;
}

/*Formatação do menu*/

a{
	text-decoration: none;
}

a:link, a:visited{
	color: #f7b600;

}

a:hover{
	text-decoration: underline;
}

#area-cabecalho a:link, #area-cabecalho a:visited{
	color: #fff;
	padding: 8px 12px;

}

#area-cabecalho a:hover{
	color: #f7b600;
	background: #fff;
	text-decoration: none;
}

/*Formatação Geral*/

h1{
	color: #4e4e4e;
	font-size: 2.5em;
}

h2{
	color: #f7b600;
}

h3{
	color: #565656;
	background: #ccc;
	padding: 5px;
}

.branco{
	color: white;
}

.data-postagem{
	font-size: 0.8em;
	border-bottom: 1px solid #f4f4f4;
	padding-bottom: 10px;
	margin-bottom: 10px;
	display: block;
}

.texto-lateral{
	font-size: 0.8em;
	padding: 5px;
}
