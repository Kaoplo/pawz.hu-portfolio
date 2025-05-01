<script lang="ts">
    import IntroHeader from "$lib/layouts/introHeader.svelte";
    import Socials from "$lib/layouts/Socials.svelte";
</script>

<svelte:head>
    <title>pawz.hu</title>
    <meta name="description" content="pawz.hu website created by Kaoplo." />
</svelte:head>

<section class="home">
    <div class="wrapper">
        <IntroHeader/> 
        <Socials/>
    </div>
</section>

<style lang="scss" global>
    :global(html), :global(body) {
        background-image: url(river.gif);
        background-size:cover;
        background-repeat: no-repeat;
        margin: 0;
        padding: 0;
        height: 100%;
        image-rendering: pixelated;
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
        background-color: rgb(48, 48, 48);
        padding: 1rem;
    }
    @media (orientation: portrait) {
        .wrapper {
            width: 100%;
        }
    }
</style>
