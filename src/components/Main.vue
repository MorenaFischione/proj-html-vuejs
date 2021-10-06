<template>
    <section class="jambotron">
        <div class="container-fluid my_container">
            <div class="row">
                <div class="col-10 p-3">
                    <h3>Certified fitness professional</h3>
                    <h1>Take control of your health</h1>
                    <i class="fas fa-angle-up"></i><i class="fas fa-angle-up"></i><i class="fas fa-angle-up"></i>
                </div>
                <div class="col-2">

                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name : "Main",

}
</script>

<style lang="scss">
@import "../style/variables.scss";

.jambotron {
    background-image: url(../assets/images/slider82x-scaled.jpg);
    height: 900px;

    .my_container {
        width: 80%;

        .fas {
            font-size: 1.2rem;
        }
    }

    
        
}

</style>