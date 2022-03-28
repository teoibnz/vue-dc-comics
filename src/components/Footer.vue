<template>
    <div class="footer">
        <div class="footer-wrapper">
            <div class="list-wrapper">
                <div>
                    <ul>DC COMICS
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                    </ul>
                    <ul>SHOP
                        <li></li>
                        <li></li>
                    </ul>
                </div>
                <div>
                    <ul>DC
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                    </ul>
                </div>
                <div>
                    <ul> SITES
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                        <li></li>
                    </ul>
                </div>
            </div>
        
            <div>
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
        <div class="socials">

        </div>
    </div>
</template>

<script>
export default {
    name : 'FooterIndex'
}
</script>

<style scoped lang="scss">
.list-wrapper{
    
    display: flex;
    color: white;
    padding: 1rem;
    
    img{
        height: 100%;
        
    }
}

.footer{
    background-image: url(../assets/img/footer-bg.jpg);
    width: 100%;
    height: 50vh;
}

.footer-wrapper{
    display: flex;
    justify-content: space-between;
    overflow-y: hidden;
    width: 80%;
    height: 100%;
    margin: 0 auto;
}
</style>