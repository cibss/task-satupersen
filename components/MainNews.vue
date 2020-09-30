<template>
    <b-container style="display: flex;">
        <div class="left">
            <b-img fluid src="~/assets/main-news.JPG" class="mt-5"> </b-img>
            <h4>Demystifying Palantir: The Most Controversial Company to Go Public in 2020</h4>
            <p>The software and consulting business is doubling down on its work with government agencies</p>

            <div>
                <b-avatar flex src="https://miro.medium.com/fit/c/80/80/1*aQM0PDcKq_I833QjiifY0A.jpeg"></b-avatar>
            </div>

            <h6 class="mt-5">LATEST</h6>
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
    .left{
        float: left;
        width: 60%;
        margin-right: 11%;
        justify-content: center;
    }

    .right{
        float: left;
        width: 29%;
    }

    @media only screen and (max-width: 1024px) {
        .right{
            visibility: hidden;
        }
    }
</style>