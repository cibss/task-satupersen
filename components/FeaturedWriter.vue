<template>
    <div class="div-size mb-5">
        <h6 class="pt-4 pl-4"><b>FEATURED WRITER</b></h6>
        <b-row class="ml-3 mr-3 mb-3">
            <b-col class="col-12 col-sm-6 col-md-6">
                <div class="author-wrap mt-3">
                    <div>
                        <div class="circle-crop mr-4">
                            <a href="https://medium.com/@ezeonukwube">
                                <b-img flex class="avatar" src="https://miro.medium.com/fit/c/256/256/2*K598oHD4pZGoawMcyiOvFw.jpeg"></b-img>
                            </a>
                        </div>
                        <b-button class="mt-3 ml-4" variant="outline-secondary" size="sm">Follow</b-button>
                    </div>
                    <div>
                        <h6 class="mb-2"> 
                            <a href="https://medium.com/@ezeonukwube">
                                <b>Eze Onukwube</b> 
                            </a>
                        </h6>
                        <p>Eze is a writer, software engineer and life enthusiast. Follow me on Twitter: @EzeOnukwube</p>
                    </div>
                </div>
            </b-col>

            <b-col class="col-12 col-sm-6 col-md-6">
                <b-media vertical-align="center"  v-for="x in 3" :key="x" class="mb-3">
                    <template v-slot:aside>
                        <a href="https://medium.com/cogwheel-of-the-mind/idea-to-start-your-day-the-golden-circle-of-desire-61ca11522228">
                            <b-img class="news-img" src="https://miro.medium.com/max/120/1*Rl2dZNw2ea057XV4SymDVw.jpeg"></b-img>
                        </a>
                    </template>
                    <p class="mt-0 mb-1">
                        <a href="https://medium.com/cogwheel-of-the-mind/idea-to-start-your-day-the-golden-circle-of-desire-61ca11522228">
                            <b>Idea to Start Your Day: The Wonders of Vertical Integration</b>
                        </a>
                    </p>
                    <p class="mb-0">5 min read</p>
                </b-media>
            </b-col>
        </b-row>
    
    </div>
</template>

<style scoped>
    .div-size{
        width: 100%;
        background-color: rgb(242, 242, 242);
    }

    .author-wrap {
        width: 100%;
        display: flex;
        align-items: center
    }

    .avatar {
        display: block;
        margin: 0 auto;
        margin-left: 0%; 
        height: 100%;
        width: auto;
    }

    .circle-crop{
        width: 128;
        height: 128px;
        position: relative;
        overflow: hidden;
        border-radius: 50%;
    }

    p{
        font-size: 14px;
    }

    .news-img{
        object-fit: cover;
        width: 60px;
        height: 60px;
    }

    a{
        color: inherit;
        text-decoration: none;
    }
</style>