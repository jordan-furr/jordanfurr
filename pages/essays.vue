<template>
    <div class="essays menu-page flex flew-row">
        <div class="w-33 nav-half-cont">
            <div class="w-100 pv2 pb3 borderbox">
                <div class="sidestar-cont">
                    <img class="sidestar-image" src="/img/navy-jordanfurr.png" alt="JF in a STAR">
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
                <h2>essays</h2>
                <p>Jordan writes memoir-theory, blending personal narrative with modern social theory and history.
                    Introduced to the genre while minoring in American Culture at the University of Michigan, Jordan’s
                    work reflects a sharp, reflective voice.</p>
                <p><em>Texting on a Horse</em>, a debut essay collection set to be completed in
                    2025, reflects on growing up as a Mormon girl in Provo, UT; training horses using Buck Brannaman's
                    method, moving to France mid-highschool; transitioning socially and medically in college despite
                    resistance; and six years on Testosterone, considering temporary frames of Transness.
                </p>
                <!--
                <h4>2024</h4>
                <p>...</p>
                <h4>2019</h4>
                <p>...</p>
                <h4>2018</h4>
                <p>...</p>
                <h4>2017</h4>
                <p>...</p>
                -->
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