<template>
    <article class="recipe">
        <div class="thumbnail" :style="{backgroundImage: 'url(' + thumbnail + ')'}"></div>
        <h1>{{ title }}</h1>
        <p>{{ previewtext }}</p>
    </article>
</template>
<script>
export default {
   props:['thumbnail', 'title', 'previewtext']
}
</script>
<style scoped>
.recipe{
    box-sizing: border-box;
    width: 300px;
    box-shadow: 0px 2px 4px #ccc;
    border: 1px solid #aaa;
    margin: 60px 10px 10px;
    padding: 6px;
}
.thumbnail{
    height: 200px;
    background-position: center;
    background-size: cover;
}
</style>
