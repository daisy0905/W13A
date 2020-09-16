<template>
    <div class="page-body">
        <div></div>
        <h3>Main title</h3>
        <h3>Content</h3>
        <h3>Sub-content</h3>
        <div></div>
    </div>
</template>

<script>
export default {
    name: "page-body"
}
</script>

<style scoped>
    .page-body {
        display: grid;
        justify-items: center;
        align-items: center;
        grid-template-columns: 1fr 1fr 3fr 2fr 1fr;
    }

</style>