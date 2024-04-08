<script>
export default {
    name: 'AppHeader',
    data() {
        return {

        }
    }
}
</script>

<template>
    <header>
        <div class="top_header">
            <div class="left_header">
                <div class="download">
                    Download App
                    <span>iOS</span>
                </div>
                <div>
                    Advertise with us
                </div>
            </div>
            <div class="right_header">
                <i class="fa-brands fa-facebook-f"></i>
                <i class="fa-brands fa-instagram"></i>
                <i class="fa-brands fa-x-twitter"></i>
                <i class="fa-brands fa-youtube"></i>
            </div>
        </div>
        <!-- top_header -->
        <div class="logo">
            <img src="/img/avada-food-logo.png" alt="">
        </div>
        <!-- logo -->
        <div class="menu">
            <ul>
                <li>Home</li>
                <li>Recipies</li>
                <li>Places</li>
                <li>Blog</li>
                <li>About</li>
                <li>Contact</li>
                <li><i class="fa-solid fa-magnifying-glass"></i></li>
            </ul>
        </div>
        <!-- menu -->
    </header>
    <!-- Header -->
</template>

<style>
.top_header {
    width: 70%;
    margin: auto;
    color: var(--food-dark);
    display: flex;
    justify-content: space-between;
    gap: 5rem;
    padding-top: 1rem;
    font-size: 12px;

    .left_header {
        display: flex;
        gap: 1rem;
    }

    .right_header {
        display: flex;
        gap: 1rem;
    }

    span {
        background-color: var(--food-primary);
        color: var(--food-lighter);
        font-size: 8px;
        padding: 0.2rem 0.3rem;
        border: 0.5px solid;
        border-radius: 5px;
    }
}

.logo {
    text-align: center;
    padding: 1rem 0;
}

.menu {
    ul {
        width: 50%;
        margin: auto;
        list-style: none;
        display: flex;
        gap: 2rem;
        justify-content: center;
        font-weight: 500;

        li {
            padding-bottom: 1rem;
        }

        li:first-child {
            color: var(--food-primary);
            border-bottom: 2px solid var(--food-primary);
        }
    }
}
</style>