<template>
    <div>
        <div class="container p-5">
            <div class="row">
                <div class="col-6">
                    <h3>PRESENTATION</h3>
                    <img src="" alt="">
                </div>
                <div class="col-6">
                    <h3>TWITTER FEED</h3>
                    <div class="mt-4" v-for="tweet in tweets" :key="tweet">
                        <!-- to add twitterLogo -->
                        <p>{{tweet.text}} <span class="text-danger">{{tweet.link}}</span> </p>
                        <div>{{tweet.day}}</div>
                    </div>
                </div>
            </div>
        </div>
    </div>




</template>


<script>
export default {
    name: 'TwitterComponent',
    data: function () {
        return {
            tweets: [
                {
                    text: "Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quibusdam quia assumenda neque aspernatur fugiat autem perferendis hic repellendus libero saepe.",
                    link: "https//t.co/jFrns8",
                    day: "3 days ago"
                },
                {
                    text: "Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quibusdam quia assumenda neque aspernatur fugiat autem perferendis hic repellendus libero saepe.",
                    link: "https//t.co/jFrns8",
                    day: "3 days ago"
                },
                {
                    text: "Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quibusdam quia assumenda neque aspernatur fugiat autem perferendis hic repellendus libero saepe.",
                    link: "https//t.co/jFrns8",
                    day: "3 days ago"
                },

            ]
        }
    }
}



</script>


<style lang="scss" scoped>

</style>