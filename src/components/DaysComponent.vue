<template>
    <div class="bg-secondary">
        <div class="container text-center">
            <div class="time  d-flex justify-content-center">
                <div class="day " v-for="time in times" :key="time">
                    <h3>{{ time.number}}</h3>
                    <p>{{ time.type }}</p>
                </div>
            </div>
            <h4 class="m-5">SUBSCRIBE FOR UPDATES</h4>
            <div class="d-flex justify-content-center ">
                <input type="text" placeholder="Please fill your email">
                <button>SUBSCRIBE</button>
            </div>
        </div>
    </div>
</template>


<script>

export default {
    name: 'DaysComponent',
    data: function () {
        return {
            times: [{
                number: 3399,
                type: "DAYS"
            },
            {
                number: 17,
                type: "HOURS"
            },
            {
                number: 28,
                type: "MINS"
            },
            {
                number: 17,
                type: "SECS"
            }],
            items: [{}],
        }
    }

}



</script>


<style lang="scss" scoped>
.container {
    min-height: 450px;
}

.day {
    background-color: rgb(78, 77, 77, 0.5);
    margin: 40px 10px;
    color: white;
    padding: 20px;

    h3 {
        font-size: 50px;
    }
}

input {
    padding: 0 110px;
}

button {
    border: none;
    background-color: #f72b0c;
    padding: 10px;
    color: white;
    margin: 0 10px;
}
</style>