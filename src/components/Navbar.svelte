<script>
    import { scrollTo, scrollRef, scrollTop } from 'svelte-scrolling'
    import Switch from './Switch.svelte';
</script>

<main>
    <div>
        <nav class="navbar">
            <h1 class="logo"><a class="logo" href="/">Diga del Vajont</a></h1>
            <ul class="links">
                <!-- svelte-ignore a11y-missing-attribute -->
                <li><a use:scrollTo={{ref: 'introduzione-storia', offset: -55}}>Storia</a></li>
                <!-- svelte-ignore a11y-missing-attribute -->
                <li><a use:scrollTo={'introduzione-causa'}>Causa</a></li>
                <li><a href="/contact">Contattami</a></li>
            </ul>
            <div>
                <button class="btn-empty">GitHub</button>
                <button class="btn">LeetCode</button>
            </div>
        </nav>
    </div>
</main>

<style>

</style>
