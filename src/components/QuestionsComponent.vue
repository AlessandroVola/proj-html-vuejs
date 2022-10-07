<template>
    <div class="container d-flex justify-content-around">
        <div class="card" v-for="question in questions" :key="question">
            <h4>{{ question.domanda }} </h4>
            <p>{{ question.testo }}</p>
            <p class="text-danger">{{ question.link }}</p>
        </div>
    </div>
</template>


<script>
export default {
    name: 'QuestionsComponent',
    data: function () {
        return {
            questions: [{
                domanda: 'WHO WE ARE',
                testo: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum, corporis eaque? Consequuntur, enim',
                link: 'Learn More'
            },
            {
                domanda: 'WHAT WE DO',
                testo: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum, corporis eaque? Consequuntur, enim',
                link: 'Learn More'
            },
            {
                domanda: 'WHY US?',
                testo: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum, corporis eaque? Consequuntur, enim',
                link: 'Learn More'
            }],
            items: [{}],
        }
    }
}



</script>


<style lang="scss" scoped>
.container {
    min-height: 200px;
}

.card {
    width: calc(100% / 3);
    padding: 50px;
    border: none;
}
</style>