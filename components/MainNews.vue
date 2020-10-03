<template>
    <div class="wrapper">
        <div id="left">
            <HighlightNews />
            <LatestTopic/>
            <FeaturedWriter class="mt-5"/>
            <LatestTopic/>
        </div>
        <div id="right">
            <TopicInfo class="mt-4"/>
            <RelatedTopic class="mt-5"/>
            <PopularTopic class="mt-5"/>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    .wrapper {
        display: flex;
        align-content: center;
        justify-content: space-evenly;
    }

    #left{
        width: 55%;
    }

    #right{
        width: 25%;
    }


    @media only screen and (max-width: 1024px) {
        #left{
            width: 90%;
        }

        #right{
            display: none;
        }
    }

</style>