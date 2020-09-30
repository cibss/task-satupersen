<template>
    <div>
        <h6>POPULAR IN  SOFTWARE ENGINEERING</h6>
        <b-media right-align vertical-align="center"  v-for="x in 5" :key="x" class="mb-3">
            <template v-slot:aside>
                <b-img blank blank-color="#ccc" width="55" alt="placeholder"></b-img>
            </template>
            <h6 class="mt-0 mb-1">
                <b>22 YouTube Channels To Level Up Your Programming Skills</b>
            </h6>
            <span class="mb-0">19 min read</span>
        </b-media>
    </div>    
</template>

<style scoped>

</style>