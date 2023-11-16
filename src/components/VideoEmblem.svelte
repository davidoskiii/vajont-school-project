<script>
    export let url
</script>

<main>
    <!-- svelte-ignore a11y-missing-attribute -->
    <iframe class="video" src={url} frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</main>

<style>
    .video {
        border-radius: 10px;
        width: 600px;
        height: 337.5px;
    }
</style>
