<script>
    import Title from "$lib/title.svelte"
    import "../styles/global.css"
</script>




<header>
    <Title title="Ninja Gaming Guides" />
</header>




<main>
    <slot />
</main>




<footer>
    <p>Copyright 2022 Ninja Gaming Guide</p>
</footer>





<style>
    header {
        display: flex;
        justify-content: center;
    }
    main {
        max-width: 960px;
        margin: 20px auto;
    }
</style>