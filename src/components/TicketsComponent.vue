<template>
    <div class="background">
        <div class="container p-5">
            <h2 class="text-center text-white">TICKETS</h2>
            <div class="row mt-5">
                <div class="col-3 mx-auto text-center bg-white p-0" v-for="ticket in tickets" :key="ticket">
                    <div class="bg-secondary p-3">
                        <h5>{{ticket.type}}</h5>
                        <h5 class="text-danger">{{ticket.price}}</h5>
                    </div>
                    <div class="text-secondary">
                        <p>{{ticket.day}}</p>
                        <p>Coffe Break</p>
                        <p>Lunch(International Buffet)</p>
                        <p>Document Sheets</p>
                        <p>{{ticket.discount}}</p>
                    </div>
                    <div class="bg-danger text-white p-3">BOOK NOW</div>
                </div>
            </div>
        </div>

    </div>




</template>


<script>
export default {
    name: 'TicketsComponent',
    data: function () {
        return {
            tickets: [
                {
                    type: "One day passes",
                    price: "FREE",
                    day: "One Day Access",
                    discount: "50USD Voucher For Next Event"
                },
                {
                    type: "Four days passes",
                    price: "750.00USD",
                    day: "Four days Access",
                    discount: "100USD Voucher For Next Event"
                },
                {
                    type: "Two days pass",
                    price: "580.00 USD",
                    day: "Two Days Access",
                    discount: "70USD Voucher For Next Event"
                },
            ]
        }
    }

}



</script>


<style lang="scss" scoped>
.background {
    background-color: #9c9c9c;
}

.container {
    min-height: 400px;
}
</style>