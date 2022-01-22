<script>
    export let title = "Ninja Gaming"
</script>




<div class="title">
    <img src="/controller.svg" class="title-image" alt="site logo">
    <h1 class="title-h1">{title}</h1>
</div>


<style>
    .title {
        display: flex;
    }
    .title-image {
        display: inline-block;
        filter: invert(80%) sepia(18%) saturate(386%) hue-rotate(195deg) brightness(100%) contrast(90%);
    }
    .title-h1 {
        margin-left: 10px;
    }
</style>