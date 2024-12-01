<template>
    <div class="essays menu-page flex flew-row">
        <div class="w-33 nav-half-cont">
            <div class="w-100 pv2 pb3 borderbox">
                <div class="sidestar-cont">
                    <img class="sidestar-image" src="/img/blue-jordanfurr.png" alt="JF in a STAR">
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
                <h2>news</h2>
                <div class="flex flex-col news-dash">
                    <div v-for="(news, index) in newsArray" :key="index" class="news-row"
                        :class="{ 'last-row': index === newsArray.length - 1 }">
                        <p class="news-item" @click="toggleHover(index)" :class="{ 'hovered': hoverIndex === index }"
                            @mouseleave="handleMouseLeaveWeb(index)">
                            {{ hoverIndex === index ? news[1] : news[0] }}
                        </p>
                    </div>
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

<script>
export default {
    data() {
        return {
            hoverIndex: -1,
            isOpen: new Array(6).fill(false),
            newsArray: [
                ["Dec 1, 2024", "Jordan is switching from Nuxt to Next.js / React."],
                ["Nov 30, 2024", "Jordan went to the movies by himself for the first time."],
                ["Nov 25, 2024", "Jordan completed this news tool!"],
                ["Nov 24, 2024", "Jordan is rewatching the series, Pose."],
                ["Nov 23, 2024", "Jordan completed his star animation."],
                ["Nov 10, 2024", "Jordan is now based in Paris, France."]
            ]
        };
    },
    methods: {
        toggleHover(index) {
            this.hoverIndex = this.hoverIndex === index ? -1 : index;
        },
        handleMouseLeaveWeb(index) {
            this.hoverIndex = - 1;
        }
    }
};
</script>