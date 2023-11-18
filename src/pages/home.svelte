<script>
    import Footer from "../components/Footer.svelte";
    import Toast from "../components/Toast.svelte";
    import HeaderCarrousel from "../components/Header.svelte";
    import History from "../components/History.svelte";
    import {showToast} from "../components/Toast.svelte"
    import Causa from "../components/Causa.svelte";
    import Testimonianze from "../components/Testimonianze.svelte";
</script>

<main>
    <HeaderCarrousel/>
    <History/>
    <Causa/>
    <Testimonianze/>
    <!-- <button class="btn" on:click={() => showToast("Text here", 4000)}>Mosta notifica</button> -->
    <!-- <Toast/> -->
    <Footer/>
</main>

<style>

</style>
