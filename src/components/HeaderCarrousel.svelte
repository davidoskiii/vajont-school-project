<script lang="ts">
    import { scrollTo, scrollRef, scrollTop } from 'svelte-scrolling'
    import Navbar from "./Navbar.svelte";
    import Header from "./Header.svelte";

    import { onMount } from 'svelte';

    let backgroundIndex = 1;

    onMount(() => {
    const backgroundDiv = document.querySelector('.background-1');

    const interval = setInterval(() => {
        // Remove previous background class
        backgroundDiv.classList.remove(`background-${backgroundIndex}`);

        // Increment the index or reset to 1 if it's the last class
        backgroundIndex = (backgroundIndex % 3) + 1;

        // Add the new background class
        backgroundDiv.classList.add(`background-${backgroundIndex}`);
    }, 4000);

    // Clear the interval when the component is destroyed
    return () => clearInterval(interval);
    });
</script>

<main>
    <section use:scrollRef={'introduzione'}></section>
    <!-- I have other classes as background-2 and background-3 -->
        <div class="background-1">
            <Navbar/>
            <div class="content">
                <Header/>
            </div>
        </div>
</main>

<style>

</style>



