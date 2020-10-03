<template>
    <div>
        <b-media right-align vertical-align="center"  v-for="x in 3" :key="x" class="mb-3">
            <template v-slot:aside>
                <a href="https://medium.com/full-stack-architecture/better-software-through-well-defined-configuration-context-a6364d164605">
                    <b-img class="news-img" src="https://miro.medium.com/max/304/1*64fnk5crY9Il-j3fFbr2vQ.jpeg"></b-img>
                </a>
            </template>
            <h6 class="mt-0 mb-1">
                <b>
                    <a href="https://medium.com/full-stack-architecture/better-software-through-well-defined-configuration-context-a6364d164605">
                        Better Software Through Well-Defined Configuration Context
                    </a>    
                </b>
            </h6>
            <p class="mb-1">
                <a href="https://medium.com/full-stack-architecture/better-software-through-well-defined-configuration-context-a6364d164605">
                    Fluid Framework allows you to build distributed, collaborative apps with 
                    lightning fast speed and buttery smooth performance. And it does…
                </a>    
            </p> 
            
            <div class="mt-2">
                <p class="mb-0">
                    <a href="https://medium.com/@erichosick">Eric Hosick</a>
                    in 
                    <a href="https://medium.com/full-stack-architecture">Full-Stack Architecture</a>
                </p>
                <b-img v-b-tooltip.hover title="Bookmark story" src="~/assets/bookmark.png" style="float: right;"></b-img>
                <p>Oct 2 · 3 min read</p>        
            </div>
            
        </b-media>
    </div>
</template>

<style scoped>
    p{
        font-size: 14px;
    }

    a{
        color: inherit;
        text-decoration: none;
    }

    .news-img{
        object-fit: cover;
        width: 152px;
        height: 135px;
    }
</style>