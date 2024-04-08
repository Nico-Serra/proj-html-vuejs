<script>
export default {
    name: 'AppMain',
    data() {
        return {

        }
    }
}
</script>

<template>
    <main>
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
        <div class="journal">
            <div class="top_text">
                <div class="left-line"></div>
                <div>Foodie Journal</div>
                <div class="right-line"></div>

            </div>
            <div class="container">
                <div class="row">
                    <div class="col-4">
                        <div class="top_image">
                            <img src="/img/single-post-img3.jpg" alt="">
                        </div>
                        <div class="food_description">
                            <p>
                                Food Corner: Top Japanese Restaurants for Sushi
                            </p>
                            <div class="date_admin">
                                By Admin | March 25,2019
                            </div>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="top_image">
                            <img src="/img/fi-roundup.jpg" alt="">
                        </div>
                        <div class="food_description">
                            <p>
                                Roundup: My new favourite Recipes For Healty Living
                            </p>
                            <div class="date_admin">
                                By Admin | March 25,2019
                            </div>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="top_image">
                            <img src="/img/fi-toasts.jpg" alt="">
                        </div>
                        <div class="food_description">
                            <p>
                                Why These Toast with Tea aree Ny New Favorite
                            </p>
                            <div class="date_admin">
                                By Admin | March 25,2019
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- /.journal -->
        <div class="recipes">

        </div>
        <!-- /.recipes -->
        <div class="collection">

        </div>
        <!-- /.collection -->

        <div class="farm">

        </div>
        <!-- /.farm -->

        <div class="subscribe">

        </div>
        <!-- /.subscribe -->

        <div class="pics">

        </div>
        <!-- /.pics -->
    </main>

</template>

<style>
main {
    background-color: var(--food-light);
    

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

    .journal {
        margin-top: -2rem;
        padding: 1rem;
        width: 70%;
        margin: auto;
        background-color: var(--food-lighter);

        .top_text {
            display: flex;

            .left-line,
            .right-line {
                flex-grow: 1;
                border-top: 0.5px dotted var(--food-light);
                height: 1px;
            }

            div {
                text-transform: uppercase;
                padding: 0 1rem;
            }


        }

        .food_description{
            p{
                font-weight: 500;
            }

            .date_admin{
                font-size: 10px;
                color: var(--food-dark);
            }
        }
    }

    .row {
        padding: 1rem;
        display: flex;
        align-items: center;
        justify-content: space-between;
        gap: 1rem;
        font-family: "PT Serif", serif;

        .col-4 {
            width: ((100%/12)*4);

            img {
                max-width: 100%;
            }
        }
    }

}
</style>