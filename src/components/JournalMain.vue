<script>
export default {
    name: 'JournalMain.vue',
    data() {
        return {

        }
    }
}
</script>

<template>
    <div class="journal">
        <div class="p-1">
            <div class="top_text">
                <div class="left-line"></div>
                <div>Foodie Journal</div>
                <div class="right-line"></div>

            </div>
            <div class="container">
                <div class="row">
                    <div class="col-4">
                        <div class="top_image">
                            <div class="image_card">
                                <img src="/img/single-post-img3.jpg" alt="">
                                <div class="food_description_hover">
                                    <div class="circle">
                                        <i class="fa-solid fa-link"></i>
                                    </div>
                                    <p>
                                        Food Corner: Top Japanese Restaurants for Sushi
                                    </p>
                                </div>
                            </div>
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
                            <div class="image_card">
                                <img src="/img/fi-roundup.jpg" alt="">
                                <div class="food_description_hover">
                                    <div class="circle">
                                        <i class="fa-solid fa-link"></i>
                                    </div>
                                    <p>
                                        Roundup: My new favourite Recipes For Healty Living
                                    </p>
                                </div>
                            </div>
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
                            <div class="image_card">
                                <img src="/img/fi-toasts.jpg" alt="">
                                <div class="food_description_hover">
                                    <div class="circle">
                                        <i class="fa-solid fa-link"></i>
                                    </div>
                                    <p>
                                        Why These Toast with Tea aree Ny New Favorite
                                    </p>
                                </div>
                            </div>
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
    </div>
    <!-- /.journal -->

</template>

<style>
.journal {
    margin-top: -2rem;
    width: 70%;
    margin: auto;
    background-color: var(--food-lighter);

    .p-1 {
        padding: 1rem;

        .top_image {
            padding: 1rem;
            position: relative;

            img {
                display: block;
            }


        }

        .top_text {
            display: flex;
            align-items: center;

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




        .food_description {
            font-family: "PT Serif", serif;

            padding: 0 1rem;

            p {
                font-weight: 500;
            }

            .date_admin {
                font-size: 10px;
                color: var(--food-dark);
            }
        }
    }

    .top_image:hover {
        .food_description_hover {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        img {
            opacity: 0.2;
        }
    }
}
</style>