<template>
    <div>
        <div class="navbar-wrapper">
            <div class="logo-container">
                <img src="../assets/img/dc-logo.png" alt="main logo DC">
            </div>
            <div class="navbar-container">
                <ul class="my-navbar">
                    <li class="navbar-items">items</li>
                    <li class="navbar-items">items</li>
                    <li class="navbar-items">items</li>
                    <li class="navbar-items">items</li>
                    <li class="navbar-items">items</li>
                    <li class="navbar-items">items</li>
                    <li class="navbar-items">items</li>
                    
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name : 'HeaderIndex',
}
</script>

<style scoped lang="scss">
.navbar-wrapper{
    width: 80%;
    height: 15vh;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
}

.logo-container{
    width: 20%;
    height: 100%;
    display: flex;
    justify-content: center;
        img{
            vertical-align: middle;
            height: 60%;
            align-self: center;
        }
}

.navbar-container{
    width: 55%;
    height: 100%;
}

.my-navbar{
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    height: 100%;
    margin: 0 0 0 0;
    padding: 0;
    li {
        list-style: none;
    }
}
</style>