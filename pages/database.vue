<template>
    <div class="essays menu-page flex flew-row">
        <div class="w-33 nav-half-cont">
            <div class="w-100 pv2 pb3 borderbox">
                <div class="h-20">
                    <img class="w-100" src="/img/yellow-jordanfurr.png" alt="">
                </div>
                <div class="flex flex-col space-between h-75">
                </div>
            </div>
        </div>
        <div class="w-66 ph6 borderbox cont-half-cont">
            <div class="description">
                <h2>database</h2>
                <p>Welcome to things I like!</p>
            </div>
        </div>
        <div class="about-btn">
            <nuxt-link to="/about" class="word-link" exact-active-class="active">
                <p>about</p>
            </nuxt-link>
        </div>
        <div class="jordan-btn">
            <nuxt-link to="/" class="word-link" exact-active-class="active">
                <h1>Jordan Furr</h1>
            </nuxt-link>
        </div>
    </div>
</template>