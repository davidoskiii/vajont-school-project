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
                <li><a use:scrollTo={{ref: 'storia', offset: -55, duration: 2000}}>Storia</a></li>
                <!-- svelte-ignore a11y-missing-attribute -->
                <li><a use:scrollTo={{ref: 'causa', offset: -55, duration: 2000}}>Causa</a></li>
                <li><a href="/contact">Contattami</a></li>
            </ul>
            <div>
                <a href="https://it.wikipedia.org/wiki/Diga_del_Vajont">
                    <input class="btn-empty" type="button" value="Wikipedia" />
                </a>
                <a href="https://github.com/davidoskiii/vajont-school-project">
                    <input class="btn" type="button" value="Source Code" />
                </a>
            </div>
        </nav>
    </div>
</main>

<style>

</style>
