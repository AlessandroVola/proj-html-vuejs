<template>
    <div class="container">
        <div class="d-flex justify-content-between p-5">
            <h3>SPEAKERS</h3>
            <div class="d-flex">
                <p>previous</p>
                <p>next</p>
            </div>
        </div>
        <div class="speakers d-flex justify-content-center">
            <div class="m-5 text-center" v-for="speaker in speakers" :key="speaker">
                <img src="src/assets/speaker-6.jpg" alt="">
                <h5>{{speaker.name}}</h5>
                <p class="text-secondary">{{speaker.role}}</p>
            </div>
        </div>
    </div>




</template>


<script>
export default {
    name: 'SpeakersComponent',
    data: function () {
        return {
            speakers: [
                {
                    img: "src/assets/speaker-6.jpg",
                    name: "PATRICK SPENCER",
                    role: "S&P Analyzer"
                },
                {
                    img: "src/assets/speaker-6.jpg",
                    name: "JANET JONES",
                    role: "Newyork Post's GM"
                },
                {
                    img: "src/assets/speaker-6.jpg",
                    name: "MICHAEL DOVER",
                    role: "Starbuck's CEO"
                },
                {
                    img: "src/assets/speaker-6.jpg",
                    name: "ANGELINA HOLY",
                    role: "Maxii's Manager"
                },
            ]


        }
    }
}



</script>


<style lang="scss" scoped>
.container {
    min-height: 300px;
}
</style>