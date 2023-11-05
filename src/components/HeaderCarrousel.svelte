<script>
    import { scrollTo, scrollRef, scrollTop } from 'svelte-scrolling'
    import Navbar from "./Navbar.svelte";
    import Header from "./Header.svelte";
    import Carousel from 'svelte-carousel'
</script>

<main>
    <section use:scrollRef={'introduzione'}></section>
    <Carousel swiping={false} arrows={false} autoplay autoplayDuration={5000} autoplayProgressVisible>
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
</main>

<style>

</style>



