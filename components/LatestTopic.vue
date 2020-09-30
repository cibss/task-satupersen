<template>
    <div>
        <b-media right-align vertical-align="center"  v-for="x in 3" :key="x" class="mb-3">
            <template v-slot:aside>
                <b-img blank blank-color="#ccc" width="152" alt="placeholder"></b-img>
            </template>
            <h6 class="mt-0 mb-1">
                <b>How a Fluid Framework service works</b>
            </h6>
            <span class="mb-5">Fluid Framework allows you to build distributed, collaborative apps with 
                lightning fast speed and buttery smooth performance. And it does…
            </span> 
            <br><br>
            <span>Kurt Berglund</span> <br>
            <span>Sep 18 · 5 min read</span>
        </b-media>
    </div>
</template>

<style scoped>

</style>