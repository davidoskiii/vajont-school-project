<script>
    import { scrollTo, scrollRef, scrollTop } from 'svelte-scrolling'
</script>

<main>
    <div class="header">
        <div class="card">
            <h1>Ciaoo</h1>
        </div>
    </div>
</main>
<section use:scrollRef={'introduzione'}></section>
<section use:scrollRef={'about'}></section>

<style>

</style>
