<script>
export default {
    name: 'Subscribe&PicsMain',
    data() {
        return {

        }
    }
}
</script>

<template>
    <div class="subscribe">
        <div class="ebook">
            <h2>Subscribe <span>&</span> Receive A Free eBook</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet sit necessitatibus facere rerum,
                aliquam exercitationem iure dicta veniam repudiandae sunt.</p>

            <div class="email">
                <input type="text" placeholder="Insert your email ...* ">
                <button>subscribe</button>
            </div>

            <div class="small">Lorem ipsum dolor sit amet consectetur.</div>
        </div>
    </div>
    <!-- /.subscribe -->

    <div class="pics">
        <div class="container">
            <div class="row">
                <div class="col-3"><img src="/img/Yogurt-Nan.jpg" alt=""></div>
                <div class="col-3"><img src="/img/Mixed-fruits.jpg" alt=""></div>
                <div class="col-3"> <img src="/img/r-rachel-park-366508-unsplash-min.jpg" alt=""></div>
                <div class="col-3"><img src="/img/r-michelle-tsang-500721-unsplash-min.jpg" alt=""></div>
            </div>
        </div>
    </div>
    <!-- /.pics -->

</template>

<style>
.subscribe {
    margin-top: 2rem;
    height: 500px;
    background-color: var(--food-lighter);
    background-image: url(/img/subscribe-sec-bg.png);
    background-size: cover;
    display: flex;
    align-items: center;
    justify-content: center;

    .ebook {
        width: 50%;
        margin: auto;
        text-align: center;

        h2 {
            font-family: "PT Serif", serif;

            span {
                color: var(--food-primary);
            }
        }

        .email {
            display: flex;
            justify-content: center;
            gap: 1rem;
            padding: 2rem 0;

            input {
                flex-grow: 1;
                border: 1px solid lightgray;
                padding: 0.8rem;
                outline: none;
                border-radius: 5px;
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
</style>