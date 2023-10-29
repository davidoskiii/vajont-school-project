<script>
    import Navbar from "./components/Navbar.svelte";
    import Header from "./components/Header.svelte";
    import Footer from "./components/Footer.svelte";
    import Carousel from 'svelte-carousel'
    import Toast from "./components/Toast.svelte";
    import {showToast} from "./components/Toast.svelte"
</script>

<main>
    <Carousel swiping={true} arrows={false} autoplay autoplayDuration={5000} autoplayProgressVisible>
        <div class="background-1">
            <Navbar/>
            <div class="content">
                <Header/>
            </div>
        </div>
        <div class="background-2">
            <Navbar/>
            <div class="content">
                <Header/>
            </div>
        </div>
        <div class="background-3">
            <Navbar/>
            <div class="content">
                <Header/>
            </div>
        </div>
    </Carousel>
    <button class="btn" on:click={() => showToast("Ciao", 4000)}>Mosta notifica</button>
    <button class="btn" on:click={() => showToast("", 4000)}>Mosta notifica</button>
    <Toast/>
    <Footer/>
</main>

<style>
    :global(body) { /* this will apply to <body> */ margin: 0; padding: 0; }
</style>
