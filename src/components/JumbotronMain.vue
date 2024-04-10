<script>
export default {
    name: 'JumbotronMain',
    data() {
        return {

        }
    }
}
</script>

<template>
    <div class="jumbotron">

        <div class="post">
            <div class="today">
                today's Pick
            </div>
            <div class="text_post">
                <p>
                    Food Corner: Top Japanese Restaurants for Sushi
                </p>
                <div class="date">
                    March 25,2019
                </div>
            </div>
        </div>
    </div>
    <!-- /.jumbotron -->

</template>

<style>
     .jumbotron {
        height: 500px;
        background-image: url(/img/single-post-img3.jpg);
        background-size: cover;
        display: flex;
        align-items: center;
        justify-content: center;
        margin-bottom: -3rem;

        .post {
            width: 50%;
            margin: auto;


            .today {
                width: 20%;
                margin: auto;
                font-size: 12px;
                text-transform: uppercase;
                font-weight: 500;
                background-color: var(--food-primary);
                color: white;
                padding: 0.5rem 0.8rem;
                border-radius: 5px;
                text-align: center;
                position: relative;


            }

            .text_post {
                font-family: "PT Serif", serif;
                margin-top: -1.25rem;
                padding: 1rem 2rem;
                text-align: center;
                background-color: var(--food-lighter);
                border-radius: 10px;
                font-weight: 500;
            }


            p {
                font-size: 32px;
            }
        }
    }
</style>