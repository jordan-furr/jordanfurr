<template>
    <div class="essays menu-page flex flew-row">
        <div class="w-33 nav-half-cont">
            <div class="w-100 pv2 pb3 borderbox">
                <div class="h-20">
                    <img class="w-100" src="/img/green-jordanfurr.png" alt="">
                </div>
                <div class="flex flex-col space-between h-75">
                </div>
            </div>
        </div>
        <div class="w-66 ph6 borderbox cont-half-cont">
            <div class="description">
                <h2>web</h2>
                <p>Jordan Furr designs and builds bespoke websites for diverse portfolio of clients.</p>
                <p>bad taste</p>
                <h4>featured</h4>
                <p>...</p>
                <h4>get in touch</h4>
                <p>jordan@jordanfurr.com</p>
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