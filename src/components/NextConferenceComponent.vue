<template>
    <div>
        <div class="container text-center text-white">
            <div>
                <h3>CONFERENCE ON</h3>
            </div>
            <div>
                <h2>SOCIAL NETWORKS</h2>
            </div>
            <div class="d-flex justify-content-around">
                <div>23 - 26 MAY 2019</div>
                <div>/</div>
                <div>SANS FRANCISCO</div>
                <div>/</div>
                <div>8 SPEAKERS</div>
            </div>
            <div>
                <button>REGISTER ONLINE</button>
            </div>
        </div>
    </div>
</template>


<script>
export default {
    name: 'NextConferenceComponent'

}




</script>


<style lang="scss" scoped>
.container {
    min-height: 350px;
    background-color: grey;

    div {
        padding: 10px;
    }


}

button {
    border: none;
    background-color: #f72b0c;
    padding: 10px;
    color: white;
}
</style>