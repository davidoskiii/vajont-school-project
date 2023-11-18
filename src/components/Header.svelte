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
    <!-- I have other classes as background-2 and background-3 -->
        <div class="background-1">
            <Navbar/>
            <div class="content">
                <div class="header">
                    <!-- <Card title="Title" text="Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolore nostrum nesciunt qui recusandae accusamus maxime. Ipsum iure odit placeat in quae, laboriosam ea incidunt at, quidem saepe commodi, tempora omnis."/> -->
                    <h1>Benvenuti nel Mondo del Vajont</h1>
                    <p>Benvenuti nel nostro sito dedicato alla storia della Diga del Vajont, un monumento ingegneristico immerso in una narrazione tragica e affascinante. Esploreremo le radici della comunità di Longarone precedenti alla costruzione della diga nel 1955, attraverso le tappe cruciali del 1957 e del 1959, sino alla drammatica vicenda del disastro del 1963. Infine, esamineremo la Diga e la Valle del Vajont oggi, testimoni silenziosi di una storia che ha lasciato un'impronta indelebile nella memoria collettiva.</p>
                </div>
            </div>
        </div>
</main>

<style>

</style>



