<template>
    <nav class="navbar navbar-expand-lg navbar-light">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Tesoro Azteca</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Inicio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Características</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Blog</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Historia</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Galería</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Descargas</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<style scoped>
.navbar-light {
    background-color: #333333 !important; /* Negro no muy oscuro */
}

.navbar-brand {
    font-size: 1.75rem;
    color: #DAA520; /* Oro */
    font-family: 'Cinzel', serif;
}

.navbar-brand:hover {
    color: #00A86B; /* Jade */
}

.navbar-nav .nav-link {
    color: #FFFFFF; /* Blanco */
    font-size: 1.25rem;
    margin-left: 1rem;
    margin-right: 1rem;
    font-family: 'Raleway', sans-serif;
}

.navbar-nav .nav-link:hover {
    color: #DAA520; /* Oro */
}

.navbar-toggler {
    border-color: #00A86B; /* Jade */
}

.navbar-toggler-icon {
    background-image: url("data:image/svg+xml;charset=UTF8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(0, 168, 107, 0.7)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
}
</style>
