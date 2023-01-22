<script>
export default {
    name: 'AppFooter',
}
</script>
<template>
    <footer>
        <div class="head-footer container">
            <div class="row">
                <div class="list">
                    <h1 class="title">DC COMICS</h1>
                    <ul class="other">
                        <li><a class="different">Characters</a></li>
                        <li><a class="different">Comics</a></li>
                        <li><a class="different">Movies</a></li>
                        <li><a class="different">Tv</a></li>
                        <li><a class="different">Games</a></li>
                        <li><a class="different">Videos</a></li>
                        <li><a class="different">News</a></li>
                    </ul>
                    <h1 class="title">SHOP</h1>
                    <ul class="other">
                        <li><a class="different">Shop Dc</a></li>
                        <li><a class="different">Shop Dc Collectibles</a></li>
                    </ul>
                </div>
                <div class="list">
                    <h1 class="title">DC</h1>
                    <ul class="other">
                        <li><a class="different">Therm of Use</a></li>
                        <li><a class="different">Privacy policy (NEW)</a></li>
                        <li><a class="different">Ad Choices</a></li>
                        <li><a class="different">Advertising</a></li>
                        <li><a class="different">Jobs</a></li>
                        <li><a class="different">Subscriprions</a></li>
                        <li><a class="different">Talent Workshops</a></li>
                        <li><a class="different">CPSC Certificates</a></li>
                        <li><a class="different">Ratings</a></li>
                        <li><a class="different">Shop Help</a></li>
                        <li><a class="different">Contact Us</a></li>
                    </ul>
                </div>
                <div class="list">
                    <h1 class="title">Sites</h1>
                    <ul class="other">
                        <li><a class="different">DC</a></li>
                        <li><a class="different">Mad Magazine</a></li>
                        <li><a class="different">DC Kids</a></li>
                        <li><a class="different">DC Universe</a></li>
                        <li><a class="different">DC Power Vista</a></li>
                    </ul>
                </div>
            </div>

            <div class="banner">
                <img src="../assets/img/dc-logo-bg.png">
            </div>
        </div>
        <section class="footer-social">
            <div class="f-footer container">
                <div class="socials">
                    <button>SIGN-UP NOW!</button>
                </div>
                <div class="socials">
                    <a>FOLLOW US</a>
                    <img src="../assets/img/footer-facebook.png">
                    <img src="../assets/img/footer-twitter.png">
                    <img src="../assets/img/footer-youtube.png">
                    <img src="../assets/img/footer-pinterest.png">
                    <img src="../assets/img/footer-periscope.png">
                </div>
            </diV>
        </section>



    </footer>

</template>
<style>
footer {
    background-image: url('../assets/img/footer-bg.jpg');

    background-repeat: no-repeat;
}

.head-footer {
    display: flex;
}

.list {
    display: flex;
    flex-direction: column;
    flex-shrink: 1;
    flex-basis: calc(100% /3);
}

.title {
    font-size: 20px;
    padding: 1.4rem 0;
}

.row {
    display: flex;
    flex-basis: 60%;
}

.other {
    list-style-type: none;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    margin: 20px, 40px;
}

.different {
    color: grey;
    padding: 0;
    cursor: pointer;
}

.different:hover,
.differente:active {
    color: blue;
    border-bottom: 0px;
}

.banner {
    flex-grow: 0;
    flex-basis: 40%;
}

.footer-social {
    background-color: rgb(31, 29, 29);
}

.f-footer {
    min-height: 100px;
    display: flex;
    justify-content: space-between;
}

.socials {
    display: flex;
    align-items: center;
}

.f-footer img {
    max-height: 50%;
    width: 50%;
    padding: 0 10px;
    cursor: pointer;
}

button {
    height: 35px;
    padding: 0 10px;
    border: 1px solid dodgerblue;
    background-color: rgb(31, 29, 29);
    color: white;
    cursor: pointer;
}
</style>
