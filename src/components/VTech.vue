<script setup>
const tech = [
    {
        img: {
            src: "/php.png",
            alt: "PHP"
        },
        name: "PHP"
    },
    {
        img: {
            src: "/laravel.png",
            alt: "Laravel"
        },
        name: "Laravel"
    },
    {
        img: {
            src: "/js.png",
            alt: "JavaScript"
        },
        name: "JavaScript"
    },
    {
        img: {
            src: "/nuxt.png",
            alt: "Nuxt.js"
        },
        name: "Nuxt.js"
    },
    {
        img: {
            src: "/mySQL.png",
            alt: "MySQL"
        },
        name: "MySQL"
    },
    {
        img: {
            src: "/postgreSQL.png",
            alt: "PostgreSQL"
        },
        name: "PostgreSQL"
    },
    {
        img: {
            src: "/rest_api.png",
            alt: "RESTful API"
        },
        name: "RESTful API"
    },
    {
        img: {
            src: "/gitlab.png",
            alt: "GitLab"
        },
        name: "GitLab"
    }
]
</script>

<template>
    <section class="tech">
        <div class="container">
            <h2>
                Технологии
            </h2>
            <div class="row">
                <div class="col-6 col-md-4 col-lg-3"
                    v-for="(item, index) in tech"
                    :key="index"
                >
                    <div class="tech__card">
                        <div class="tech__card-img-wrap">
                            <img :src="item.img.src" :alt="item.img.alt">
                        </div>
                        <div class="tech__card-name">{{ item.name }}</div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>

</style>