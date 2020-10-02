<template>
    <div>
        <b-media right-align vertical-align="center"  v-for="x in 3" :key="x" class="mb-3">
            <template v-slot:aside>
                <b-img src="https://miro.medium.com/max/304/1*64fnk5crY9Il-j3fFbr2vQ.jpeg" style="width: 152px"></b-img>
            </template>
            <h6 class="mt-0 mb-1">
                <b>How a Fluid Framework service works</b>
            </h6>
            <p class="mb-1">Fluid Framework allows you to build distributed, collaborative apps with 
                lightning fast speed and buttery smooth performance. And it does…
            </p> 
            
            <div class="mt-2">
                <p class="mb-0">Kurt Berglund</p>
                <p>Sep 18 · 5 min read</p>
            </div>
        </b-media>
    </div>
</template>

<style scoped>
    p{
        font-size: 14px;
    }
</style>