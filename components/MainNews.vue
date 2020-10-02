<template>
    <b-container style="display: flex;" class="container">
        <div class="left">
            <b-img fluid src="~/assets/main-news.JPG" class="mt-5"> </b-img>
            <h3>Demystifying Palantir: The Most Controversial Company to Go Public in 2020</h3>
            <p>The software and consulting business is doubling down on its work with government agencies</p>

            <div class="author-wrap mt-3">
                <div>
                    <b-avatar flex class="avatar" src="https://miro.medium.com/fit/c/80/80/1*aQM0PDcKq_I833QjiifY0A.jpeg"></b-avatar>
                </div>
                <div class="ml-3">
                    <p>
                        Owen Williams in <a href="https://debugger.medium.com/">Debugger</a> <br>
                    </p>
                    <p>Oct 2 · 4 min read</p>
                </div>
            </div>

            <p class="mt-4"><b>LATEST</b></p>
            <hr class="divider mt-2">

            <LatestTopic/>
            <FeaturedWriter class="mt-5"/>
            <LatestTopic/>
        </div>

        <div class="right">
            <TopicInfo class="mt-5"/>
            <RelatedTopic class="mt-5"/>
            <PopularTopic class="mt-5"/>
        </div>
    </b-container>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    h3{
        font-weight: bold;
    }

    p{
        font-size: 14px;
        margin: 0;
    }

    .left{
        float: left;
        width: 69%;
        margin-right: 11%;
        justify-content: center;
    }

    .right{
        float: left;
        width: 29%;
    }

    a{
        color: inherit;
        text-decoration: none;
    }

    .author-wrap {
        width: 100%;
        display: flex;
        align-items: center
    }

    .avatar {
        display: block
    }

    .divider{
        width: 100%;
        border-top: 1px solid #8c8b8b;
    }
    

    @media only screen and (max-width: 1024px) {
        .right{
            /* visibility: hidden; */
            display: none;
        }
    }
</style>