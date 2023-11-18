<script>
    export let url
    export let title = null
</script>

<main>
    <!-- svelte-ignore a11y-missing-attribute -->
    <iframe class="video" title={title} src={url} frameborder=0 allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen ></iframe>
</main>

<style>
    .video {
        margin: 10px;
        box-shadow:#959da533 0 8px 24px;
        border-radius: 10px;
        width: 600px;
        height: 337.5px;
    }
</style>
