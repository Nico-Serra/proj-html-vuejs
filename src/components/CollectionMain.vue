<script>
export default {
    name: 'CollectionMain',
    data() {
        return {

        }
    }
}
</script>

<template>

    <div class="collection">
        <div class="text">
            <h4>
                Culinary Collection
            </h4>

            <p>
                Lorem ipsum dolor, sit amet consectetur adipisicing elit. At, voluptate optio animi totam reiciendis
                aliquid eius suscipit ratione alias debitis.
            </p>
        </div>

        <div class="container">
            <div class="row">
                <div class="col-3">
                    <div class="card">
                        <div class="card_info">
                            <img src="/img/drinks-recipes.png" alt="">
                            <div class="text_card">Drinks</div>
                        </div>
                    </div>

                </div>
                <div class="col-3">
                    <div class="card">
                        <div class="card_info">
                            <img src="/img/soups-recipes.png" alt="">
                            <div class="text_card">soups</div>
                        </div>
                    </div>

                </div>
                <div class="col-3">
                    <div class="card">
                        <div class="card_info">
                            <img src="/img/baking-recipes.png" alt="">
                            <div class="text_card">Baking</div>
                        </div>
                    </div>

                </div>
                <div class="col-3">
                    <div class="card">
                        <div class="card_info">
                            <img src="/img/dinner-recipes.png" alt="">
                            <div class="text_card">dinner</div>
                        </div>
                    </div>

                </div>
                <div class="col-3">
                    <div class="card">
                        <div class="card_info">
                            <img src="/img/healthy-recipes.png" alt="">
                            <div class="text_card">healthy</div>
                        </div>
                    </div>

                </div>
                <div class="col-3">
                    <div class="card">
                        <div class="card_info">
                            <img src="/img/staff-picks.png" alt="">
                            <div class="text_card">staff-picks</div>
                        </div>
                    </div>

                </div>
                <div class="col-3">
                    <div class="card">
                        <div class="card_info">
                            <img src="/img/premium-recipes.png" alt="">
                            <div class="text_card">appetisers</div>
                        </div>
                    </div>

                </div>
                <div class="col-3">
                    <div class="card">
                        <div class="card_info">
                            <img src="/img/quick-easy-recipes.png" alt="">
                            <div class="text_card">quick & easy</div>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </div>
    <!-- /.collection -->
</template>

<style>
.collection {
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

    .col-3 {

        .card {
            padding: 1rem;

            .card_info {
                background-color: var(--food-lighter);
                text-align: center;

                img {
                    width: 50%;
                }


                .text_card {
                    text-transform: uppercase;
                    padding: 0.5rem
                }
            }
        }

        .card:hover {
            .text_card {
                background-color: var(--food-primary);
                color: var(--food-lighter);
            }
        }
    }
}
</style>