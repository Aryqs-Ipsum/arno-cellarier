<template>
    <div>
        <div class="border-bottom">
            <div class="container">
                <h1>Oops !</h1>
                <p>Ce site est en construction, revenez plus tard pour découvrir mon travail.</p>
                <figure>
                    <video width="300" height="300" loop autoplay muted>
                        <source src="https://i.imgur.com/R0HCpEo.mp4" type="video/mp4" />
                        Votre navigateur n'arrive pas à afficher la vidéo du dinosaure :/
                    </video>
                </figure>
            </div>
        </div>
    </div>
</template>

<style>
.border-bottom {
    box-sizing: border-box;
    border-bottom: 8px solid #109C58;
    height: 100vh;
}

.container {
    padding: 16px;
    max-width: 800px;
    margin: 0 auto;
}

.container figure {
    margin-top: 100px;
}

.container h1 {
    font-size: 2.5rem;
    margin-bottom: 0;
}

.container p {
    font-size: 1.2rem;
}
</style>