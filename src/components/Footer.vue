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
            <div class="social-wrapper">
                <button> SIGN-UP NOW!</button>
                <div class="social-items">
                    <h2>FOLLOW US</h2>
                </div>
            </div>
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
    ul{
        margin: 1.5rem;
        font-weight: bold;
        li{
            list-style-type: none;
            
        }
    }
}

.footer{
    background-image: url(../assets/img/footer-bg.jpg);
    width: 100%;
    height: 45vh;
}

.footer-wrapper{
    display: flex;
    justify-content: space-between;
    overflow-y: hidden;
    width: 65%;
    height: 100%;
    margin: 0 auto;
}

.socials{
    background-color: #303030;
    height: 10vh;
}

.social-wrapper{
    width: 65%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem;
    button{
        padding: 0.7rem;
        background-color: #303030;
        color: white;
        border: 1px solid #0282f9
    }
}
</style>