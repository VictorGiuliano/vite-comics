<script>
export default {
    name: 'AppMain',
}
</script>
<template>
    <main>
        <div class=" bkg-b container">
            <h1> --> Content goes here &lt;-- </h1>
        </div>
        <section class="bonus">
            <div class=" bkg-bl"></div>
        </section>
        <section class="list">


        </section>




    </main>

</template>
<style>
main {
    background-color: black;
}

.bkg-b {
    height: 100px;
    display: flex;
    align-items: center;
}

.bonus {
    background-color: dodgerblue;
    min-height: 120px;
}

h1 {
    color: white;
    font-size: 25px;
}
</style>