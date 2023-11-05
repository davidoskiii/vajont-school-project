<script>
    import { scrollTo, scrollRef, scrollTop } from 'svelte-scrolling'
</script>

<main>
    <div class="timeline">
        <!-- svelte-ignore a11y-missing-attribute -->
        <a use:scrollTo={'introduzione'} class="dot year-1990">1990</a>
        <!-- svelte-ignore a11y-missing-attribute -->
        <a use:scrollTo={'introduzione'} class="dot year-2000">2000</a>
        <!-- svelte-ignore a11y-missing-attribute -->
        <a use:scrollTo={'introduzione'} class="dot year-2010">2010</a>
        <!-- svelte-ignore a11y-missing-attribute -->
        <a use:scrollTo={'introduzione'} class="dot year-2020">2020</a>
        <!-- svelte-ignore a11y-missing-attribute -->
        <a use:scrollTo={'introduzione'} class="dot year-2030">2030</a>
    </div>
</main>

<style>

</style>
