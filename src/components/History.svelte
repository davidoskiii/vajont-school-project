<script>
    import { scrollTo, scrollRef, scrollTop } from 'svelte-scrolling'
    import HorizzontalTimeline from "./Timelines/HorizzontalTimeline.svelte";
    import Carousel from 'svelte-carousel'
</script>

<main>
    <div class="history">
        <div class="text-div">
            <h2>Storia</h2>
            <div class="history-paragraph-start start-history m-5">
                <div class="m-5">
                    <h1>Viaggio nel Passato: La valle del disastro</h1>
                    <p>Entra nel cuore di una delle pagine più oscure della storia italiana. Scopri la narrazione completa del disastro del Vajont, una tragedia che ha sconvolto il mondo nel 1963. Attraverso una sequenza cronologica dettagliata e testimonianze dirette, questa sezione rivelerà gli eventi che hanno portato a una catastrofe senza precedenti, gettando luce sui protagonisti, le decisioni cruciali e le conseguenze durature che hanno segnato questa epocale tragedia.</p>
                </div>
                <div class="carousel-container m-5">
                    <Carousel swiping={false} autoplay autoplayDuration={2000}>
                        <img class="image-carousel" src="https://media-assets.wired.it/photos/6523ca3b7ff82f5e7241bda0/16:9/w_1920,c_limit/158986304" alt="elicottero disastro">
                        <img class="image-carousel" src="https://www.raicultura.it/dl/img/2019/10/04/1570203895060_h_00101051.jpg" alt="elicottero disastro">
                        <img class="image-carousel" src="https://www.raicultura.it/dl/img/2019/10/04/1570203895060_h_00101050.jpg" alt="elicottero disastro">
                    </Carousel>
                </div>
            </div>
            <HorizzontalTimeline/>
            <div class="history-paragraph-image">
                <div class="sibling-image m-5">
                    <img class="image-carousel rounded-image" src="https://media-assets.wired.it/photos/6523ca3b7ff82f5e7241bda0/16:9/w_1920,c_limit/158986304" alt="elicottero disastro">
                </div>
                <div class="m-5">
                    <h1>Viaggio nel Passato: La valle del disastro</h1>
                    <p>Entra nel cuore di una delle pagine più oscure della storia italiana. Scopri la narrazione completa del disastro del Vajont, una tragedia che ha sconvolto il mondo nel 1963. Attraverso una sequenza cronologica dettagliata e testimonianze dirette, questa sezione rivelerà gli eventi che hanno portato a una catastrofe senza precedenti, gettando luce sui protagonisti, le decisioni cruciali e le conseguenze durature che hanno segnato questa epocale tragedia.</p>
                </div>
                <section use:scrollRef={'1990'}></section>
            </div>
            <div class="history-paragraph">
                <h1>La Tragedia del Vajont: Quando la Montagna Tremò</h1>
                <p>Nella storia del Vajont, uno dei disastri più devastanti della storia italiana, la natura si è scontrata con l'ingegno umano in una tragedia inimmaginabile. Questo racconto esplora gli eventi che hanno portato al crollo della montagna del Vajont nel 1963, provocando una delle peggiori catastrofi della storia moderna. Dalle cause alla devastazione e alle conseguenze, questa storia è un ricordo doloroso delle vite perdute e delle lezioni apprese dall'errore umano.</p>
            </div>
            <div class="history-paragraph">
                <h1>La Tragedia del Vajont: Quando la Montagna Tremò</h1>
                <p>Nella storia del Vajont, uno dei disastri più devastanti della storia italiana, la natura si è scontrata con l'ingegno umano in una tragedia inimmaginabile. Questo racconto esplora gli eventi che hanno portato al crollo della montagna del Vajont nel 1963, provocando una delle peggiori catastrofi della storia moderna. Dalle cause alla devastazione e alle conseguenze, questa storia è un ricordo doloroso delle vite perdute e delle lezioni apprese dall'errore umano.</p>
            </div>
            <div class="history-paragraph centered-flex">
                <div class="m-5">
                    <h1>La Tragedia del Vajont: Quando la Montagna Tremò</h1>
                    <p>Nella storia del Vajont, uno dei disastri più devastanti della storia italiana, la natura si è scontrata con l'ingegno umano in una tragedia inimmaginabile. Questo racconto esplora gli eventi che hanno portato al crollo della montagna del Vajont nel 1963, provocando una delle peggiori catastrofi della storia moderna. Dalle cause alla devastazione e alle conseguenze, questa storia è un ricordo doloroso delle vite perdute e delle lezioni apprese dall'errore umano.</p>
                </div>
                <div class="carousel-container m-5">
                    <Carousel swiping={false} autoplay autoplayDuration={2000}>
                        <img class="image-carousel" src="https://media-assets.wired.it/photos/6523ca3b7ff82f5e7241bda0/16:9/w_1920,c_limit/158986304" alt="elicottero disastro">
                        <img class="image-carousel" src="https://www.raicultura.it/dl/img/2019/10/04/1570203895060_h_00101051.jpg" alt="elicottero disastro">
                        <img class="image-carousel" src="https://www.raicultura.it/dl/img/2019/10/04/1570203895060_h_00101050.jpg" alt="elicottero disastro">
                    </Carousel>
                </div>
            </div>
        </div>
        <!-- <div class="vertical-timeline">
            <VerticalTimeline/>
        </div> -->
    </div>
</main>

<style>

</style>