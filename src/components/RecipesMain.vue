<script>
export default {
    name: 'RecipesMain',
    data() {
        return {

        }
    }
}
</script>

<template>
    <div class="recipes">
        <div class="text">
            <h4>
                Popoular Recipes
            </h4>

            <p>
                Lorem ipsum dolor, sit amet consectetur adipisicing elit. At, voluptate optio animi totam reiciendis
                aliquid eius suscipit ratione alias debitis.
            </p>
        </div>

        <div class="container">
            <div class="row">
                <div class="col-6 left_col">
                    <div class="card">
                        <div class="top_image">
                            <div class="image_card">
                                <img src="/img/Yogurt-Nan.jpg" alt="">
                                <div class="food_description_hover">
                                    <div class="circle">
                                        <i class="fa-solid fa-link"></i>
                                    </div>
                                    <p>
                                        Lunch Favourite with Salad, Naan And Beans
                                    </p>
                                </div>
                            </div>
                        </div>
                        <div class="image_description">
                            <h4>
                                Lunch Favourite with Salad, Naan And Beans
                            </h4>
                            <p>
                                Bakery,Featured,Healty,Latest Recipes,Staff Picks
                            </p>

                            <hr>

                            <p>
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut perspiciatis maiores
                                eaque.
                                Facilis facere et rerum. Eum beatae cum facere modi recusandae ad nostrum et
                                quisquam
                                aut, numquam repellendus obcaecati omnis expedita soluta dolore culpa ullam esse
                                totam
                                quae accusantium. Animi illo earum minus repellendus expedita tempora inventore, non
                                soluta.
                            </p>

                            <button>
                                Learn More
                            </button>
                        </div>
                    </div>
                </div>
                <div class="col-6 right_col">
                    <div class="col-6">
                        <div class="small_card">
                            <div class="image_card">
                                <img src="/img/Mixed-fruits.jpg" alt="">
                                <div class="food_description_hover">
                                    <div class="circle">
                                        <i class="fa-solid fa-link"></i>
                                    </div>
                                    <p>
                                        Fruit Platter with Banana, Mango, Berries and Orange
                                    </p>
                                </div>
                            </div>

                        </div>
                    </div>
                    <div class="col-6">
                        <div class="small_card">

                            <div class="image_card">
                                <img src="/img/r-rachel-park-366508-unsplash-min.jpg" alt="">
                                <div class="food_description_hover">
                                    <div class="circle">
                                        <i class="fa-solid fa-link"></i>
                                    </div>
                                    <p>
                                        English Breakfast
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-6">
                        <div class="small_card">
                            <div class="image_card">
                                <img src="/img/r-michelle-tsang-500721-unsplash-min.jpg" alt="">

                                <div class="food_description_hover">
                                    <div class="circle">
                                        <i class="fa-solid fa-link"></i>
                                    </div>
                                    <p>
                                        Dessert
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-6">
                        <div class="small_card">
                            <div class="image_card">
                                <img src="/img/quick-summer-drink-460x295.jpg" alt="">
                                <div class="food_description_hover">
                                    <div class="circle">
                                        <i class="fa-solid fa-link"></i>
                                    </div>
                                    <p>
                                        Summer-drink
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-6">
                        <div class="small_card">
                            <div class="image_card">
                                <img src="/img/r-maarten-van-den-heuvel-400626-unsplash-min-460x295.jpg" alt="">

                                <div class="food_description_hover">
                                    <div class="circle">
                                        <i class="fa-solid fa-link"></i>
                                    </div>
                                    <p>
                                        Tomato, Avocado & ...
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-6">
                        <div class="small_card">
                            <div class="image_card">
                                <img src="/img/perfect-cosmopolitan-460x295.jpg" alt="">


                                <div class="food_description_hover">
                                    <div class="circle">
                                        <i class="fa-solid fa-link"></i>
                                    </div>
                                    <p>
                                        Perfect-Cosmopolitan
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-6">
                        <div class="small_card">
                            <div class="image_card">
                                <img src="/img/fi2x-6-460x295.jpg" alt="">
                                <div class="food_description_hover">
                                    <div class="circle">
                                        <i class="fa-solid fa-link"></i>
                                    </div>
                                    <p>
                                        Fruits
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-6">
                        <div class="small_card">
                            <div class="image_card">
                                <img src="/img/r-brooke-lark-96398-unsplash-min-460x295.jpg" alt="">

                                <div class="food_description_hover">
                                    <div class="circle">
                                        <i class="fa-solid fa-link"></i>
                                    </div>
                                    <p>
                                        Jam Tart & Tea
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- /.recipes -->

</template>

<style>
.recipes {
    padding-top: 2.5rem;
    width: 70%;
    margin: auto;

    .text {
        text-align: center;
        width: 50%;
        margin: auto;
        padding-bottom: 1.5rem;

        h4 {
            font-weight: 500;
            text-transform: uppercase;
        }
    }

    .left_col {

        font-family: "PT Serif", serif;



        .card {
            padding: 1rem;

            .image_card:hover {
                .food_description_hover {
                    display: flex;
                    flex-direction: column;
                    align-items: center;
                }

                img {
                    opacity: 0.2;
                }
            }

            .image_description {
                padding: 1rem 2rem;
                background-color: var(--food-lighter);

                hr {
                    border-top: 1px dotted var(--food-light);

                }

                p {
                    font-size: 14px;
                }

                button {
                    background-color: var(--food-primary);
                    border: none;
                    color: var(--food-lighter);
                    text-transform: uppercase;
                    padding: 0.8rem;
                }
            }
        }
    }

    .right_col {
        padding: 0;
        display: flex;
        flex-wrap: wrap;



        .small_card {

            padding: 1rem;
        }

        .small_card:hover {
            .food_description_hover {
                display: flex;
                flex-direction: column;
                align-items: center;

                p {
                    font-size: 10px;
                }
            }

            img {
                opacity: 0.2;
            }
        }





    }
}
</style>