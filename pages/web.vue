<template>
    <div class="essays menu-page flex flew-row">
        <div class="w-33 nav-half-cont">
            <div class="w-100 pv2 pb3 borderbox">
                <div class="sidestar-cont">
                    <img class="sidestar-image" src="/img/red-jordanfurr.png" alt="JF in a STAR" quality="80" format="webp">
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
                <h2>web</h2>
                <p>Jordan indpendently designs and builds websites at his practice <a class="bt" href="https://badtaste.dev/" target="_">bad taste</a>. Since 2019, he has worked with a diverse range of clients, drawing on expertise gained from earning a Bachelor of Computer Science (2017–2021).</p>
                <a class="getintouch" href="mailto:jordan@jordanfurr.com">Get in touch</a>
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