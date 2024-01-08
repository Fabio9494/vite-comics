<script>
export default {
    name: 'AppHeader',
    data() {
        return {
            links: [
                {
                    label: 'CHARACTERS',
                    url: '#',
                    current: false
                },
                {
                    label: 'COMICS',
                    url: '#',
                    current: true
                },
                {
                    label: 'MOVIES',
                    url: '#',
                    current: false
                },
                {
                    label: 'TV',
                    url: '#',
                    current: false
                },
                {
                    label: 'GAMES',
                    url: '#',
                    current: false
                },
                {
                    label: 'COLLECTIBLES',
                    url: '#',
                    current: false
                },
                {
                    label: 'VIDEOS',
                    url: '#',
                    current: false
                },
                {
                    label: 'FANS',
                    url: '#',
                    current: false
                },
                {
                    label: 'NEWS',
                    url: '#',
                    current: false
                }
            ]
        }
    }
}
</script>

<template lang="">
    <header>
        <div class="container">
        <img src="../assets/img/dc-logo.png" alt="">
        
            <ul>
                <li v-for="(link,index) in links">
                    <a :class="link.current ? 'active' : ''" :href="link.url"> 
                        {{link.label}}
                    </a>
                </li>
            </ul>
        </div>
    </header>
</template>

<style lang="scss" scoped>
header {
    display: flex;
    justify-content: center;
    padding: 30px 0px;
    width: 100vw;

    .container {
        display: flex;
        width: 80%;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    img {
        width: 80px;
    }

    ul {
        list-style: none;
        display: flex;
    }

    li a {
        margin: 5px;
        color: black;

        &.active {
            color: rgb(0, 55, 255);
            text-decoration: underline;
        }

    }
}
</style>