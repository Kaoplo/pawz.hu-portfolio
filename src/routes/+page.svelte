<script lang="ts">
    import IntroHeader from "$lib/layouts/introHeader.svelte";
</script>

<svelte:head>
    <title>pawz.hu</title>
    <meta name="description" content="pawz.hu website created by Kaoplo." />
</svelte:head>

<section class="home">
    <div class="wrapper">
        <IntroHeader/> 
    </div>
</section>

<style lang="scss" global>
    :global(html), :global(body) {
        background-color: rgb(48, 48, 48);
        margin: 0;
        padding: 0;
        height: 100%;
    } 
    .home {
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .wrapper {
        height: 100%;
        width: 60%;
        border: 5px solid white;
    }
</style>
