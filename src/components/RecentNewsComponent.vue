<template>
    <div>
        <div class="container p-5">
            <div class="d-flex justify-content-between p-3">
                <h4>RECENT NEWS</h4>
                <p class="text-danger font-italic">Read all news</p>
            </div>
            <div class="row">
                <div class="col-4 p-5" v-for="piece in news" :key="piece">
                    <img src="" alt="">
                    <p>{{piece.date}} / {{piece.comment}}</p>
                    <h4>{{piece.title}}</h4>
                    <p>{{piece.content}}</p>
                    <p class="text-danger">Read More</p>
                </div>
            </div>
        </div>
    </div>





</template>


<script>
export default {
    name: 'RecentNewsComponent',
    data: function () {
        return {
            news: [
                {
                    img: "src/assets/speaker-6.jpg",
                    date: "03 dec 2013",
                    comment: "0 comments",
                    title: "SEDIAL EIUSMOD TEMPOR",
                    content: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Harum voluptas fugiat, eligendi accusantium tempore cumque exercitationem"
                },
                {
                    img: "src/assets/speaker-6.jpg",
                    date: "03 dec 2013",
                    comment: "0 comments",
                    title: "SEDIAL EIUSMOD TEMPOR",
                    content: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Harum voluptas fugiat, eligendi accusantium tempore cumque exercitationem"
                },
                {
                    img: "src/assets/speaker-6.jpg",
                    date: "03 dec 2013",
                    comment: "0 comments",
                    title: "SEDIAL EIUSMOD TEMPOR",
                    content: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Harum voluptas fugiat, eligendi accusantium tempore cumque exercitationem"
                },

            ]


        }
    }
}



</script>


<style lang="scss" scoped>
.container {
    min-height: 400px;
}
</style>