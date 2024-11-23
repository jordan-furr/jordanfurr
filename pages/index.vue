<template>
    <div class="h-100">
        <div class="h-100 home-cont">
            <div class="h-100 star-cont flex flex-col">
                <div class="flex flex-row space-between h-50 align-center first-row-star">
                    <div class="star-word-cont">
                        <div class="star-word essays">
                            <nuxt-link to="/essays" class="word-link" exact-active-class="active">
                                <p>essays</p>
                            </nuxt-link>
                        </div>
                    </div>
                    <div class="star-word-cont">
                        <div class="star-word web">
                            <nuxt-link to="/web" class="word-link" exact-active-class="active">
                                <p>web dev</p>
                            </nuxt-link>
                        </div>
                    </div>
                </div>
                <div class="flex flex-row space-between h-25 align-center second-row-star">
                    <div class="star-word-cont">
                        <div class="star-word projects">
                            <nuxt-link to="/projects" class="word-link" exact-active-class="active">
                                <p>projects</p>
                            </nuxt-link>
                        </div>
                    </div>
                    <div class="star-word-cont">
                        <div class="star-word news">
                            <nuxt-link to="/news" class="word-link" exact-active-class="active">
                                <p>news</p>
                            </nuxt-link>
                        </div>
                    </div>

                </div>
                <div class="flex margin-a h-20 align-center database-word-cont">
                    <div class="star-word">
                        <nuxt-link to="/database" class="word-link" exact-active-class="active">
                            <p>database</p>
                        </nuxt-link>
                    </div>
                </div>
            </div>
        </div>
        <div class="about-btn">
            <nuxt-link to="/about" class="word-link" exact-active-class="active">
                <p>about</p>
            </nuxt-link>
        </div>
    </div>
</template>