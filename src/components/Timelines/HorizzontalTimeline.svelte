<script>
    import { scrollTo, scrollRef, scrollTop } from 'svelte-scrolling'
</script>

<main>
    <div class="centered-flex">
        <div class="timeline">
            <!-- svelte-ignore a11y-missing-attribute -->
            <a use:scrollTo={{ref: '1955', offset: -250}} class="dot year-1955">1955</a>
            <!-- svelte-ignore a11y-missing-attribute -->
            <a use:scrollTo={{ref: '1957', offset: -250}} class="dot year-1957">1957</a>
            <!-- svelte-ignore a11y-missing-attribute -->
            <a use:scrollTo={'introduzione'} class="dot year-2010">2010</a>
            <!-- svelte-ignore a11y-missing-attribute -->
            <a use:scrollTo={'introduzione'} class="dot year-2020">2020</a>
            <!-- svelte-ignore a11y-missing-attribute -->
            <a use:scrollTo={'introduzione'} class="dot year-2030">2030</a>
        </div>
    </div>
</main>

<style>

</style>
