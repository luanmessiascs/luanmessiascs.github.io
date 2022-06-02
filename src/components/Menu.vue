<template>
    <div id="container-content">
        <h1>Meu Perfil</h1>
        <nav id="menu">
            <ul>
                <li><router-link to="/">Página Inicial</router-link></li>
                <li><router-link to="/about">Sobre Mim</router-link></li>
                <li><a href="#">Projetos</a></li>
                <ul>
                    <li><a href="#">Collections</a></li>
                    <li><a href="#">Receitasnet</a></li>
                </ul>
            </ul>
        </nav>
    </div>
</template>
<style scoped>
    /* fontes personalizadas que serão incluídas */

    /* @charset "UTF-8";
    @font-face {
        font-family: "WorkSans";
        src: url("./fonts/WorkSans-Bold.ttf");
    }

    @font-face {
        font-family: "Exo2";
        src: url("./fonts/Exo2-ExtraBoldItalic.ttf");
    } */

    div#container-content {
        position: absolute;
        top: 0px;
        left: 0px;
        width: 200px;
        height: 99.3%;
        background: #01262e;
        box-shadow: 1px 3px 3px black;
        border-right: 3px solid #0cc753;
        border-bottom: 4px solid #0cc753;
    }

    div#container-content h1 {
        position: relative;
        text-align: center;
        color: #00fff2;
        font-size: 20pt;
        margin-top: 5px;
        padding-bottom: 5px;
        border-bottom: 2px solid #00eeff;
        font-family: 'Exo2', Arial;
        font-size: 16pt;
    }

    div#container-content nav#menu {
        position: relative;
        display: block;
        margin-left: auto;
        margin-right: auto;
        width: 96%;
        border: 1px solid #0ccec4;
    }

    div#container-content nav#menu ul {
        position: relative;
        list-style: none;
    }

    div#container-content nav#menu ul li {
        position: relative;
        margin: 10px auto 2px auto;
    }

    div#container-content nav#menu ul li a {
        font-family: 'WorkSans';
        text-decoration: none;
        font-size: 14pt;
        color: #00eeff;
    }

    div#container-content nav#menu ul ul li a{
        font-family: 'Times New Roman', Times, serif;
    }
</style>