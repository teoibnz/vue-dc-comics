<template>
    <div class="bonus">
        <div class="container">
            <div class="card-wrapper" v-for="(element, index) in imagesNav" :key="index">
                <img :src="element.url" alt="">
                <h4> {{element.text}} </h4>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name : 'BonusIndex',
    data : function (){
        return {
            imagesNav : [
                {
                    text : 'DIGITAL COMICS',
                    url : 'buy-comics-digital-comics.png',
                },
                {
                    text : 'DC MERCHANDISE',
                    url : 'buy-comics-merchandise.png',
                },
                {
                    text : 'SUBSCRIPTION',
                    url : 'buy-comics-subscriptions.png',
                },
                {
                    text : 'DC MERCHANDISE',
                    url : 'buy-comics-shop-locator.png',
                },
                {
                    text : 'DC POWER VISA',
                    url : 'buy-dc-power-visa.svg',
                },
            ]
        }
    }
}
</script>

<style scoped lang="scss">
.bonus{
    height: 15vh;
    background-color: #0282f9;
}

.container{
    width: 65%;
    margin: 0 auto;
    display: flex;
    justify-content: space-around;
}

.card-wrapper{
    margin: 1rem;
    padding: 1rem;
    color: white;
}
</style>