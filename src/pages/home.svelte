<script>
    import Footer from "../components/Footer.svelte";
    import Toast from "../components/Toast.svelte";
    import HeaderCarrousel from "../components/HeaderCarrousel.svelte";
    import History from "../components/History.svelte";
    import {showToast} from "../components/Toast.svelte"
    import Causa from "../components/Causa.svelte";
</script>

<main>
    <HeaderCarrousel/>
    <History/>
    <Causa/>
    <button class="btn" on:click={() => showToast("Ciao", 4000)}>Mosta notifica</button>
    <button class="btn" on:click={() => showToast("", 4000)}>Mosta notifica</button>
    <Toast/>
    <Footer/>
</main>

<style>

</style>
