<template>
    <div class="div-size mb-5 pa-5">
        <h6><b>FEATURED WRITER</b></h6>
        <b-row>
            <b-col>
                <b-media vertical-align="center" class="mb-3">
                    <template v-slot:aside>
                        <b-img blank blank-color="#ccc" width="60" alt="placeholder"></b-img><br>
    
                    </template>
                    <h6 class="mt-0 mb-1">
                        <b>Eze Onukwube</b>
                    </h6>
                    <span class="mb-0">Eze is a writer, software engineer and life enthusiast. Follow me on Twitter: @EzeOnukwube</span>
                </b-media>
            </b-col>
            <b-col>
                <b-media vertical-align="center"  v-for="x in 3" :key="x" class="mb-3">
                    <template v-slot:aside>
                        <b-img blank blank-color="#ccc" width="60" alt="placeholder"></b-img>
                    </template>
                    <h6 class="mt-0 mb-1">
                        <b>Idea to Start Your Day: The Wonders of Vertical Integration</b>
                    </h6>
                    <span class="mb-0">5 min read</span>
                </b-media>
            </b-col>
        </b-row>
    </div>
</template>

<style scoped>
    .div-size{
        width: 100%;
        size: 800px;
        background-color: rgb(242, 242, 242);
    }
</style>