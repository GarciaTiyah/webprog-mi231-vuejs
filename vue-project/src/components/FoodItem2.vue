<template>
    <div>
        <h2>{{ name }}</h2>
        <p>{{ message }}</p>
    </div>
</template>

<script>
export default {
    data() {
        return {
            name: 'Grapes',
            message: 'I like Grapes'
        }
    }
};
</script>

<style>
  #app > div {
        border: dashed black 1px;
        display: inline-block;
        margin: 10px;
        padding: 10px;
        background-color: lightyellow;
    }
</style>                                