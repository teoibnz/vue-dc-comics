<template>
    <div class="footer">
        <div class="footer-wrapper">
            <div class="list-wrapper">
                <div>
                    <ul>DC COMICS
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>
                    <ul>SHOP
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
                </div>
                <div>
                    <ul>DC
                        <li>Terms Of Use</li>
                        <li> Privacy policy (New)</li>
                        <li>Ad Choise</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li> Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>
                    </ul>
                </div>
                <div>
                    <ul> SITES
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
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
        padding-bottom: 0.5rem;
        li{
            list-style-type: none;
            color: grey;
            margin-top: 0.3rem;
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
    padding-top: 2rem;
    button{
        padding: 0.7rem;
        background-color: #303030;
        color: white;
        border: 1px solid #0282f9
    }
}
</style>