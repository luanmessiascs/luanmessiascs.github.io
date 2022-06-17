<template>
    <nav class="navbar navbar-dark bg-dark">
        <div class="container-fluid">
            <router-link class="navbar-brand" to="/">
                Começo <span class="bi bi-pc-display-horizontal"></span>
            </router-link>
            <span class="navbar-text">
                Solução Inovadora, tanto no front, quanto no back.
            </span>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
            data-bs-target="#menu" aria-controls="menu" aria-expanded="false"
            aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
        </div>
        <div id="menu" class="collapse navbar-collapse">
            <div class="container d-flex justify-content-center">
                <ul class="nav">
                    <li class="nav-item">
                        <router-link class="nav-link link-light" to="/my-projects">
                            Meus Projetos <span class="bi bi-desktop"></span>
                        </router-link>
                    </li>
                    <li class="nav-item">
                        <router-link class="nav-link link-light" to="/about-me">
                            Sobre Mim <span class="bi bi-person-circle"></span>
                        </router-link>
                    </li>
                    <li class="nav-item">
                        <router-link class="nav-link link-light" to="/project-codes">
                            Código dos Aplicativos <span class="bi bi-git"></span>
                        </router-link>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>