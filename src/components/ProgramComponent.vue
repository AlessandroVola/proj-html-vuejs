<template>
    <div class="border">
        <div class="container p-5">
            <div class="d-flex justify-content-between align-items-center m-5">
                <h3>PROGRAM</h3>
                <p class="text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit. <br> Quas,
                    dignissimos
                    sunt perferendis ratione
                    illo velit iste, laudantium.</p>
                <p class="text-danger">View Full Program</p>
            </div>
            <div class="row m-5 text-white">
                <div class="col-2 actual">
                    <p>DAY 1</p>
                    <p>23 may 2016</p>
                </div>
                <div class="col-2">
                    <p>DAY 2</p>
                    <p>23 may 2040</p>
                </div>
                <div class="col-2">
                    <p>DAY 3</p>
                    <p>24 may 2030</p>
                </div>
                <div class="col-2">
                    <p>DAY 4</p>
                    <p>25 may 2030</p>
                </div>
                <div class="col-2">
                    <p>DAY 5</p>
                    <p>26 may 2030</p>
                </div>
                <div class="col-2">
                    <p></p>
                    <p></p>
                </div>
            </div>
            <div class="row m-5">
                <div class="col-4">
                    <p>09:00</p>
                    <p>ROOM A</p>
                    <p class="text-danger">LAURENCE FRANCIS</p>
                </div>
                <div class="col-8">
                    <h5>WELCOMING AND INTRODUCTION</h5>
                    <p class="text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum corporis
                        odit ullam nesciunt.
                    </p>
                    <img src="" alt="">
                </div>
            </div>
        </div>
    </div>




</template>


<script>
export default {
    name: 'ProgramComponent',
}



</script>


<style lang="scss" scoped>
.col-2 {
    background-color: red;
    border-right: 1px solid black;


    p {
        margin: 5px 0 0 3px;
        padding: 3px;
    }
}

.actual {
    background-color: #bf351f;
}
</style>