<script>
export default {
    name: 'AppHeader',
    data() {
        return {
            links: [
                {
                    text: 'Characters',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Comics',
                    url: '#',
                    current: true,
                },
                {
                    text: 'Movies',
                    url: '#',
                    current: false,
                },
                {
                    text: 'TV',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Games',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Collectibles',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Videos',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Fans',
                    url: '#',
                    current: false,
                },
                {
                    text: 'News',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Shop',
                    url: '#',
                    current: false,
                },
            ]

        }

    }
}
</script>

<template>
    <header>
        <div class="container">
            <nav class="navbar">
                <div class="navbar-logo"><i class="fa-brands fa-discord"></i>
                    <img src="../assets/img/dc-logo.png">
                </div>
                <div class="navbar-menu">
                    <ul>
                        <li v-for="link in links" :key="link.text" :class="{ 'current': link.current }"><a
                                :href="link.url">{{ link.text }}</a></li>
                    </ul>
                </div>
            </nav>
        </div>
    </header>
</template>
    
<style>
.navbar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    background-color: white;
    width: 100%;
}

.navbar-logo {
    text-align: left;
    padding: 20px;
}

.navbar-menu {
    text-align: right;
}
</style>