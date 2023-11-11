<script>
    import { scrollTo, scrollRef, scrollTop } from 'svelte-scrolling'
</script>

<main>
    <div class="centered-flex">
        <div class="timeline">
            <!-- svelte-ignore a11y-missing-attribute -->
            <a use:scrollTo={{ref: '1955', offset: -250}} class="dot">1955</a>
            <!-- svelte-ignore a11y-missing-attribute -->
            <a use:scrollTo={{ref: '1957', offset: -250}} class="dot">1957</a>
            <!-- svelte-ignore a11y-missing-attribute -->
            <a use:scrollTo={{ref: '1959', offset: -250}} class="dot">1959</a>
            <!-- svelte-ignore a11y-missing-attribute -->
            <a use:scrollTo={{ref: '1963', offset: -250}} class="dot">1963</a>
            <!-- svelte-ignore a11y-missing-attribute -->
            <a use:scrollTo={{ref: '2023', offset: -250}} class="dot">2023</a>
        </div>
    </div>
</main>

<style>

</style>
