# Web-site-Meu-Perfil-Investidor-
This is an investor profile testing site that, after testing, returns a summary of your user profile and some possible investiments products that are suitable for your investor profile.

*/HTML Initial Page Code/*
<html lang="pt-BR">
    <head>
        <meta charset="utf-8">
        <meta name= "author" content="Diego Rodrigues">
        <meta name="description" content="A proposta é criar um questionário simples, lúdico e dinâmico para pessoas
        em geral, que tenham o interesse em começar a investir, saberem qual o seu perfil de investidor.">

        <title>Home Meu Perfil Investidor</title>
        <link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link href="https://fonts.googleapis.com/css2?family=Architects+Daughter&family=Arvo:ital@0;1&family=Gluten:wght@300&family=Open+Sans&display=swap" rel="stylesheet">
        <link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link href="https://fonts.googleapis.com/css2?family=Fredericka+the+Great&display=swap" rel="stylesheet">
        <link href="animacao.css" rel="stylesheet">
        <link href="Layout.css" rel="stylesheet">
        <link href="tipografia.css" rel="stylesheet">

    </head>
    <body>
        <header>
            <nav>
                <div id="logo">
                    <ion-icon id="icone-home" name="home"></ion-icon>
                </div>

                <ul id="esquerda">
                    <li><a href="../Home/Home_perfil_investidor.html">HOME</a></li>
                    <li><a href="../Meu perfil/teste_perfil.html">MEU PERFIL</a></li>
                    <li><a id="cont_edu">CONTEÚDO EDUCACIONAL</a>
                        <ul>
                            <li><a href="../Meu perfil/perfil_conservador.html">Perfil Conservador</a></li>
                            <li><a href="../Meu perfil/perfil_moderado.html">Perfil Moderado</a></li>
                            <li><a href="../Meu perfil/perfil_agressivo.html">Perfil Agressivo</a></li>
                            <li><a href="../Educacional/Fundo_garantia.html">Fundo de Garantia</a></li>
                            <li><a href="../Educacional/Renda_variável_e_fixa.html">Renda Fixa e Variável</a></li>
                        </ul>
                    </li>
                    <li><a href="../Redes sociais/redes_sociais.html">REDES SOCIAIS</a></li>
                </ul>
                <ul id="direita">
                    <li><a id="inscrever" href="inscricao.html">LOGIN</a></li>
                    <ion-icon id="icone-user" name="person-circle-outline"></ion-icon>
                </ul>
            </nav>
            
            <div id="chamada">
                <h1>Meu Perfil Investidor</h1>
                <h2>Descubra os melhores investimentos para o seu perfil!</h2>
                <a href="../Meu perfil/teste_perfil.html">Ir para o teste</a>
            </div>
        </header>

        <script src="https://unpkg.com/ionicons@5.1.2/dist/ionicons.js"></script>
    </body>
</html>
