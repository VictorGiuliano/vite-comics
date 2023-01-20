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
                    <h1>DC COMICS</h1>
                    <ul class="other">
                        <li><a class="different">Characters</a></li>
                        <li><a class="different">Comics</a></li>
                        <li><a class="different">Movies</a></li>
                        <li><a class="different">Tv</a></li>
                        <li><a class="different">Games</a></li>
                        <li><a class="different">Videos</a></li>
                        <li><a class="different">News</a></li>
                    </ul>
                    <h1>SHOP</h1>
                    <ul class="other">
                        <li><a class="different">Shop Dc</a></li>
                        <li><a class="different">Shop Dc Collectibles</a></li>
                    </ul>
                </div>
                <div class="list">
                    <h1>DC</h1>
                    <ul class="other">
                        <li><a class="different">Characters</a></li>
                        <li><a class="different">Comics</a></li>
                        <li><a class="different">Movies</a></li>
                        <li><a class="different">Tv</a></li>
                        <li><a class="different">Characters</a></li>
                        <li><a class="different">Comics</a></li>
                        <li><a class="different">Movies</a></li>
                        <li><a class="different">Tv</a></li>
                        <li><a class="different">Characters</a></li>
                        <li><a class="different">Comics</a></li>
                        <li><a class="different">Movies</a></li>
                        <li><a class="different">Tv</a></li>
                    </ul>
                </div>
                <div class="list">
                    <h1>Sites</h1>
                    <ul class="other">
                        <li><a class="different">Characters</a></li>
                        <li><a class="different">Comics</a></li>
                        <li><a class="different">Movies</a></li>
                        <li><a class="different">Tv</a></li>
                        <li><a class="different">Characters</a></li>
                        <li><a class="different">Comics</a></li>
                        <li><a class="different">Movies</a></li>
                        <li><a class="different">Tv</a></li>
                        <li><a class="different">Characters</a></li>
                        <li><a class="different">Comics</a></li>
                        <li><a class="different">Movies</a></li>
                        <li><a class="different">Tv</a></li>
                    </ul>
                </div>
            </div>

            <div class="banner">
                <img src="../assets/img/dc-logo-bg.png">
            </div>
        </div>



    </footer>

</template>
<style>
footer {
    background-image: url('../assets/img/footer-bg.jpg');
    min-height: 600px;
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

.row {
    display: flex;
    flex-basis: 70%;
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
    flex-basis: 30%;
}
</style>
