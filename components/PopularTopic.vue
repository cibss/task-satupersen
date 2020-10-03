<template>
    <div>
        <p> <b>POPULAR IN  SOFTWARE ENGINEERING</b> </p>
        <hr class="divider">

        <b-media right-align vertical-align="center"  v-for="x in 5" :key="x" class="mb-3">
            <template v-slot:aside>
                <b-img class="news-img" src="https://miro.medium.com/max/110/1*Xx2YxTWIGNI3ExVLq1meoA.png"></b-img>
            </template>
            <p class="mt-0 mb-1">
                <a href="https://blog.codegiant.io/programming-skills-d77d4abdf255">
                    <b>22 YouTube Channels To Level Up Your Programming Skills</b>
                </a>
            </p>
            <p class="mb-0">19 min read</p>
        </b-media>
    </div>    
</template>

<style scoped>
    .divider{
        width: 100%;
        border-top: 1px solid #8c8b8b;
    }

    p, a{
        font-size: 14px;
    }

    a{
        color: inherit;
        text-decoration: none;
    }

    .news-img{
        object-fit: cover;
        width: 55px;
        height: 55px;
    }
</style>