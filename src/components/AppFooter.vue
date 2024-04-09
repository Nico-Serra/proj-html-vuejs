<script>
export default {
    name: 'AppFooter',
    data() {
        return {

        }
    }
}
</script>

<template>
    <footer>
        <div class="footer_top">
            <div class="container">
                <div class="row">
                    <div class="col-3">
                        <img src="/img/avada-food-logo-mob.png" alt="">
                        <div class="social">
                            <a href=""><i class="fa-brands fa-facebook-f"></i></a>
                            <a href=""><i class="fa-brands fa-instagram"></i></a>
                            <a href=""><i class="fa-brands fa-x-twitter"></i></a>
                            <a href=""><i class="fa-brands fa-youtube"></i></a>
                        </div>
                    </div>
                    <div class="col-3">
                        <div class="menu_footer">
                            <ul>
                                <li>Home</li>
                                <li>Recipies</li>
                                <li>Places</li>
                                <li>Blog</li>
                                <li>About</li>
                                <li>Contact</li>
                            </ul>
                        </div>
                    </div>
                    <div class="col-3">
                        <div class="contact">
                            <h4>
                                Contact
                            </h4>
                            <div class="info">
                                <i class="fa-solid fa-location-dot"></i>
                                <p> 516 New York Ave, Brooklyn, Kings, New York 11203</p>
                            </div>
                            <div class="info">
                                <i class="fa-solid fa-phone"></i>
                                <p> +6181-919-1661</p>
                            </div>
                            <div class="info">
                                <i class="fa-solid fa-envelope"></i>
                                <p> info@your-domain.com</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-3">
                        <div class="download_app">
                            <h4>
                                Get our App
                            </h4>
                            <img src="/img/download-android.png" alt="">
                            <img src="/img/download-app-store.png" alt="">
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="footer_bottom">
            <p>&copy;Copyright 2012-2024|Powered By Nicola Serra </p>
        </div>
    </footer>

</template>

<style>
footer {

    .footer_top {
        width: 70%;
        margin: auto;
        padding: 2rem 0;

        .col-3:first-child {
            text-align: center;
            padding: 1rem 0;
         
        }

        .col-3{
            height: 100%;
        }

        .social {
            padding: 2rem 0;
            display: flex;
            justify-content: center;
            gap: 1rem;

            a {
                text-decoration: none;
                color: var(--food-dark);
            }
        }

        .menu_footer {
            
            

            ul {
                list-style: none;

                li {
                    font-weight: 600;
                    padding: 0.5rem 0;
                }
            }
        }

        .contact {
            padding: 0 1rem;


            h4 {
                color: var(--food-primary);
                text-transform: uppercase;
            }


            .info {
                display: flex;
                align-items: first baseline;
                gap: 0.5rem;
                color: gray;
            }
        }

        .download_app{
            padding: 0 1rem ;

            h4 {
                color: var(--food-primary);
                text-transform: uppercase;
            }
        }
    }

    .footer_bottom{
        text-align: center;
        background-color: var(--food-light);
        padding: 1rem;
    }
}
</style>