<script>
    import { scrollTo, scrollRef, scrollTop } from 'svelte-scrolling'
    import Card from "./Card.svelte";
    import Menu from "./Menu/Menu.svelte";
</script>

<main>
    <div class="header">
        <!-- <Card title="Title" text="Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolore nostrum nesciunt qui recusandae accusamus maxime. Ipsum iure odit placeat in quae, laboriosam ea incidunt at, quidem saepe commodi, tempora omnis."/> -->
        <h1>Benvenuti nel Mondo del Vajont</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint id dolor magnam sunt praesentium corrupti obcaecati ea, soluta, a minus maxime, molestias accusamus possimus numquam non quas doloribus unde fuga.</p>
    </div>
</main>
<section use:scrollRef={'about'}></section>

<style>

</style>
