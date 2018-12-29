<template>
    <section class="recipes">
        <hea-der />
        <rec-ipe 
            thumbnail="https://www.inspiredtaste.net/wp-content/uploads/2011/12/Pan-Roasted-Chicken-Bread-Recipe-3-1200.jpg"
            title="Chicken"
            previewtext="This thread has been automatically locked since there has not been any recent activity after it was closed. Please open a new issue for related bugs."
        />
        <rec-ipe 
            thumbnail="https://www.inspiredtaste.net/wp-content/uploads/2011/12/Pan-Roasted-Chicken-Bread-Recipe-3-1200.jpg"
            title="Chicken"
            previewtext="This thread has been automatically locked since there has not been any recent activity after it was closed. Please open a new issue for related bugs."
        />
        <rec-ipe 
            thumbnail="https://www.inspiredtaste.net/wp-content/uploads/2011/12/Pan-Roasted-Chicken-Bread-Recipe-3-1200.jpg"
            title="Chicken"
            previewtext="This thread has been automatically locked since there has not been any recent activity after it was closed. Please open a new issue for related bugs."
        />
        <!-- <article class="recipe">
            <div class="thumbnail" style="background-image: url('https://www.inspiredtaste.net/wp-content/uploads/2011/12/Pan-Roasted-Chicken-Bread-Recipe-3-1200.jpg');"></div>
            <h1>Food Title</h1>
            <p>Description Here</p>
        </article>
        <article class="recipe">
            <div class="thumbnail" style="background-image: url('https://www.inspiredtaste.net/wp-content/uploads/2011/12/Pan-Roasted-Chicken-Bread-Recipe-3-1200.jpg');"></div>
            <h1>Food Title</h1>
            <p>Description Here</p>
        </article> -->

        <svg>
            <use xlink:href="#cny"></use>
        </svg>
        <svg v-html="require('~/assets/img/cny.svg')"></svg>
    </section>
</template>
<script>
import HeaDer from '~/components/head/header.vue';
import RecIpe from '~/components/recipe/recipes.vue';
import cny from '~/assets/img/cny.svg'
export default {
    components: {
        HeaDer,
        RecIpe
    },
    created () {
        require('~/assets/img/cny.svg')
    }
}

</script>

<style scoped>
.recipes{
    display: flex;
    flex-flow: row wrap;
    justify-content: center;
    align-items: center;
    margin-top: 60px;
}
.recipe{
    box-sizing: border-box;
    width: 300px;
    box-shadow: 0px 2px 4px #ccc;
    border: 1px solid #aaa;
    margin: 10px;
    padding: 6px;
}
.thumbnail{
    height: 200px;
    background-position: center;
    background-size: cover;
}
</style>
