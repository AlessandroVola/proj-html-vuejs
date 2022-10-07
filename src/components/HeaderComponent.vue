<template>
    <div class="container">
        <img src="" alt="">
        <nav>
            <ul class="d-flex justify-content-around">
                <li>HOME</li>
                <li>PAGES</li>
                <li>PROGRAM</li>
                <li>TICKETS</li>
                <li>SPEAKERS</li>
                <li>PAPERS</li>
                <li>BLOG</li>
                <li>SHORTCODES</li>
                <li>I</li>
                <li>use-font-awesome</li>
            </ul>
        </nav>
    </div>
</template>


<script>

export default {
    name: 'HeaderComponent'

}



</script>


<style lang="scss" scoped>
.container {
    min-height: 100px;
}

li {
    list-style-type: none;
    color: grey;
}
</style>