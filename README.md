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

/*Limpando as formatações padões*/
* {
	margem:0;
	preenchimento: 0
}
corpo{
	tamanho da fonte: 1em;
	exibição de fonte: "Trebuchet", Helvética, sem serifa;
	plano de fundo: #e6e6e6;
}

/*Layout*/

#área-cabecalho{
	plano de fundo: #f7b600;
	preenchimento: 15px;
	alinhamento de texto: centro;
}

#area-logotipo, #area-menu{
	preenchimento: 10px;
}

#área-principal{
	largura: 920px;
	margem: 0 automático;
	preenchimento: 15px;
}

#area-postagens{
	largura: 660px;
	flutuar: esquerda;
}

#área-lateral{
	largura: 240px;
	flutuar: certo;
}

.postagem{
	preenchimento: 20px;
	margem inferior: 20px;
	fundo: branco;
}

.conteudo-lateral{
	fundo: branco;
	preenchimento: 10px;
	margem inferior: 20px;
}

#rodape{
	limpar ambos;
	alinhamento de texto: centro;
	preenchimento: 15px;
	plano de fundo: #ccc;
}

/*Formatação do menu*/

a{
	decoração de texto: nenhuma;
}

a:link, a:visitado{
	cor: #f7b600;

}

a:passar o mouse{
	decoração de texto: sublinhado;
}

#area-cabecalho a:link, #area-cabecalho a:visitou{
	cor: #fff;
	preenchimento: 8px 12px;

}

#area-cabecalho a:hover{
	cor: #f7b600;
	plano de fundo: #fff;
	decoração de texto: nenhuma;
}

/*Formação Geral*/

h1{
	cor: #4e4e4e;
	tamanho da fonte: 2,5em;
}

h2{
	cor: #f7b600;
}

h3{
	cor: #565656;
	plano de fundo: #ccc;
	preenchimento: 5px;
}

.branco{
	cor branca;
}

.data-postagem{
	tamanho da fonte: 0,8em;
	borda inferior: 1px sólido #f4f4f4;
	preenchimento inferior: 10px;
	margem inferior: 10px;
	exibição: bloco;
}

.texto-lateral{
	tamanho da fonte: 0,8em;
	preenchimento: 5px;
}
