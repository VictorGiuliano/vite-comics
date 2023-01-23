<script>
export default {
    name: 'AppMain',
    props: {
        comics: Array
    }
}
</script>
<template>
    <main>
        <div class=" bkg-b container">
            <div class="label stick">
                <h1>CURRENT SERIES</h1>
            </div>
            <div class="card-container">
                <div v-for="comic in comics" :key="comic.thumb" class="comics-card">
                    <img :src="comic.thumb" :alt="comic.series">
                    <h4>{{ comic.series }}</h4>
                </div>
            </div>
            <button class="btn btn-more">
                <h1>LOAD MORE</h1>
            </button>
        </div>
        <section class="bonus">
            <div class=" bkg-bl"></div>
        </section>
    </main>

</template>
<style lang="scss">
@use '../assets/scss/partials/variables' as *;

main {
    background-color: black;
}

.bkg-b {
    min-height: 100px;
    display: flex;
    flex-direction: column;
    align-items: center;
    position: relative;
}

.bonus {
    background-color: $blu;
    min-height: 120px;
}

h4 {
    color: $white;
    font-size: 10px;
    padding: 15px 0;
}


.label,
.btn {
    width: 10%;
    background: $blu;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 10px 15px;

    h1 {
        color: $white;
        font-size: 40%;
    }
}

.stick {
    position: absolute;
    left: 0;
    top: -15px;
}

.btn-more {
    cursor: pointer;
}

.card-container {
    display: flex;
    flex-wrap: wrap;
    margin-top: 2rem;

    .comics-card {
        flex-basis: calc(100% / 6);
        padding: 15px;

        img {
            display: block;

            max-height: 100%;
            max-width: 100%;
        }
    }
}
</style>