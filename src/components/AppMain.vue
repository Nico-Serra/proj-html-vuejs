<script>
import JumbotronMain from './JumbotronMain.vue';
import JournalMain from './JournalMain.vue';
import RecipesMain from './RecipesMain.vue';
import CollectionMain from './CollectionMain.vue';
import FarmMain from './FarmMain.vue'
import SubscribePicsMain from './Subscribe&PicsMain.vue';

export default {
    name: 'AppMain',
    data() {
        return {

        }
    },
    components: {
        JumbotronMain,
        JournalMain,
        RecipesMain,
        CollectionMain,
        FarmMain ,
        SubscribePicsMain
    }
}
</script>

<template>
    <main>
        <JumbotronMain/>

        <JournalMain/>

        <RecipesMain/>

        <CollectionMain/>

        <FarmMain/>

        <SubscribePicsMain/>

       
    </main>

</template>

<style>
main {
    background-color: var(--food-light);

    

    /* hover */
    .image_card {
        background-color: var(--food-primary);
        position: relative;

        .food_description_hover {
            display: none;
            text-align: center;
            position: absolute;
            left: 50%;
            top: 50%;
            z-index: 100;
            transform: translate(-50%, -50%);
            color: var(--food-lighter);
            font-family: "PT Serif", serif;


            p {
                font-weight: 500;
            }

            .circle {
                width: 35px;
                height: 35px;
                border-radius: 50%;
                background-color: var(--food-lighter);
                display: flex;
                justify-content: center;
                align-items: center;


                i {
                    opacity: 1;
                    color: var(--food-dark);
                    font-size: 14px;
                }
            }
        }
    }
}
</style>