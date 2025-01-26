<template>
    <div class="essays menu-page flex flew-row">
        <div class="w-33 nav-half-cont">
            <div class="w-100 pv2 pb3 borderbox">
                <div class="sidestar-cont">
                    <img class="sidestar-image" src="/img/green-jordanfurr.png" alt="JF in a STAR">
                </div>
                <div class="sidebarnav pr6 borderbox flex flex-col text-center">
                    <div>
                        <nuxt-link to="/essays" class="sidebarword essays-nav" exact-active-class="active">
                            <p>essays</p>
                        </nuxt-link>
                    </div>
                    <div>
                        <nuxt-link to="/web" class="sidebarword web-nav" exact-active-class="active">
                            <p>web dev</p>
                        </nuxt-link>
                    </div>
                    <div>
                        <nuxt-link to="/projects" class="sidebarword projects-nav" exact-active-class="active">
                            <p>projects</p>
                        </nuxt-link>
                    </div>
                    <div>
                        <nuxt-link to="/database" class="sidebarword database-nav" exact-active-class="active">
                            <p>database</p>
                        </nuxt-link>
                    </div>
                    <div>
                        <nuxt-link to="/news" class="sidebarword news-nav" exact-active-class="active">
                            <p>news</p>
                        </nuxt-link>
                    </div>
                </div>
            </div>
        </div>
        <div class="w-66 pl5 pr3 borderbox cont-half-cont">
            <div class="description">
                <h2>projects</h2>
                <p>Jordan has launched and collaborated on a variety of projects.</p>
                <p class="subtitle">FEATURED</p>
                <div class="j-list">
                    <nuxt-link to="/iti" class="word-link"><p>Invitation to Interact</p></nuxt-link>
                    <nuxt-link to="https://starlaces.org/" class="word-link"><p>STAR Laces</p></nuxt-link>
                    <p>Samewave 7</p>
                    <p>Green Butterfly</p>
                </div>

            </div>
        </div>
        <div class="about-btn">
            <nuxt-link to="/about" class="word-link">
                <p>about</p>
            </nuxt-link>
        </div>
        <div class="jordan-btn">
            <nuxt-link to="/" class="word-link">
                <h1>Jordan Furr</h1>
            </nuxt-link>
        </div>
    </div>
</template>