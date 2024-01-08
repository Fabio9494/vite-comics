<script>
export default {
    name: 'AppFooter',
    data() {
        return {

        }
    }
}
</script>

<template lang="">
    <footer>
    <div>
    <ul>
        <li><h2>DC COMICS</h2></li>
        <li>CHARACTERS</li>
        <li>COMICS</li>
        <li>MOVIES</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>COLLECTIBLES</li>
        <li>VIDEOS</li>
        <li>FANS</li>
        <li>NEWS</li>
        <li><h2>SHOP</h2></li>
        <li>Shop DC</li>
        <li>Shop DC Collectibles</li>
    </ul>
    <ul>
        <li><h2>DC</h2></li>
        <li>Terms Of Use</li>
        <li>Privacy policy</li>
        <li>Ad Choices</li>
        <li>Advertising</li>
        <li>Jobs</li>
        <li>Subscriptions</li>
        <li>Talent</li>
        <li>CPSC Certificates</li>
        <li>Ratings</li>
        <li>Shop Help</li>
        <li>Contact Us</li>
    </ul>
    <ul>
        <li><h2>SITES</h2></li>
        <li>DC</li>
        <li>Mad Magazine</li>
        <li>DC Kids</li>
        <li>DC Universe</li>
        <li>DC Power Visa</li>
    </ul>
    </div>
    <div >
        <img class="logo" src="../assets/img/dc-logo-bg.png" alt=""> 
    </div>
    </footer>

</template>

<style lang="scss" scoped>
footer {
    background-image: url(../assets/img/footer-bg.jpg);
    display: flex;
    justify-content: space-between;
    color: grey;
    font-size: 10px;
    padding: 20px 120px;

    ul {
        list-style: none;
        text-align: left;
    }

    .logo {
        width: 50%;
    }

    div {
        display: flex;
        justify-content: end;
    }
}
</style>