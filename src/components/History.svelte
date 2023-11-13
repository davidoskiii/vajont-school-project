<script>
    import { scrollTo, scrollRef, scrollTop } from 'svelte-scrolling'
    import HorizzontalTimeline from "./Timelines/HorizzontalTimeline.svelte";
    import Carousel from 'svelte-carousel'
    import VideoEmblem from './VideoEmblem.svelte';
</script>

<main>
    <div class="history">
        <div class="text-div">
            <section use:scrollRef={'storia'}>
                <h2>Storia</h2>
                <div class="history-paragraph-start start-history m-5">
                    <div class="m-5">
                        <h1>Viaggio nel Passato: La valle prima della diga</h1>
                        <p>Prima della costruzione della diga, la Valle del Vajont era un crocevia di storie millenarie. In questa sezione, esploreremo Longarone prima del 1955, vivendo la vita di una comunità ignara del destino imminente. Attraverso gli anni che precedettero la costruzione della diga, assaporiamo le speranze e sfide di una popolazione che vedeva nel progresso simboleggiato dalla diga un futuro radioso. Saremo testimoni degli eventi che plasmarono il destino della Valle del Vajont, una narrazione che sfiora grandezza e inquietudine, offrendo lezioni per il presente e il futuro.</p>
                    </div>
                    <div class="carousel-container m-5">
                        <Carousel swiping={false} autoplay autoplayDuration={2000}>
                            <img class="image-carousel" src="https://www.rainews.it/cropgd/686x453/dl/img/2023/9/30/1696079578108_VistadellagoladelVajontprimadellacostruzionedelladiga_nel__WIKIPEDIA.jpg" alt="longarone">
                            <img class="image-carousel" src="https://www.rainews.it/cropgd/641x453/dl/img/2023/9/30/1696081167334_Longarone_prima_della_tragediaANSABD.JPG" alt="">
                            <img class="image-carousel" src="https://www.raicultura.it/dl/img/2019/10/04/1570203895060_h_00101051.jpg" alt="elicottero disastro">
                            <img class="image-carousel" src="https://www.raicultura.it/dl/img/2019/10/04/1570203895060_h_00101050.jpg" alt="elicottero disastro">
                        </Carousel>
                    </div>
                </div>
                <HorizzontalTimeline/>
            </section>
            <section use:scrollRef={'1955'}>
                <div class="history-paragraph-image">
                    <div class="sibling-image m-5">
                        <img class="image-carousel rounded-image" src="https://media-assets.wired.it/photos/6523ca3b7ff82f5e7241bda0/16:9/w_1920,c_limit/158986304" alt="elicottero disastro">
                    </div>
                    <div class="m-5">
                        <h1>1955: Le Radici di Longarone </h1>
                        <p>Longarone, incantevole borgo ai piedi delle montagne, già prima del 1955 respirava la sua storia intrisa di tradizioni e comunità unite. La vita ruotava intorno alle colture, alle serate in piazza, e ai legami familiari. Tuttavia, l'arrivo degli anni '50 portò l'ombra imponente della Diga del Vajont, preludio a una trasformazione che avrebbe ridefinito per sempre il destino di questo idilliaco paesino.</p>
                    </div>
                </div>
            </section>
            <section use:scrollRef={'1957'}>
                <div class="history-paragraph-image">
                    <div class="m-5">
                        <h1>1957: La costruzione della diga</h1>
                        <p>Il 1957 vede il via alla costruzione della Diga del Vajont, trasformando Longarone in un cantiere frenetico. Mentre la struttura cresce, l'entusiasmo per il progresso si intreccia con crescenti preoccupazioni sulla sicurezza. La comunità assiste con orgoglio alla nascita di un'imponente opera idroelettrica, ma dietro la facciata emergono tensioni e scelte tecniche che avranno conseguenze drammatiche negli anni a venire.</p>
                    </div>
                    <div class="sibling-image m-5">
                        <VideoEmblem/>
                    </div>
                </div>
            </section>
            <section use:scrollRef={'1959'}>
                <div class="history-paragraph-image">
                    <div class="sibling-image m-5">
                        <img class="image-carousel rounded-image" src="https://media-assets.wired.it/photos/6523ca3b7ff82f5e7241bda0/16:9/w_1920,c_limit/158986304" alt="elicottero disastro">
                    </div>
                    <div class="m-5">
                        <h1>1959: Crescita e Sfide</h1>
                        <p>Il 1959 segna un periodo di crescita accelerata per Longarone, alimentato dalla costruzione della Diga del Vajont. L'espansione economica porta nuove opportunità, ma anche sfide cruciali. La comunità affronta il dilemma tra progresso e preservazione delle radici culturali, mentre emergono preoccupazioni sulla sicurezza e sostenibilità ambientale. Questo capitolo della storia del Vajont evidenzia le tensioni dinamiche tra modernizzazione e la salvaguardia di una identità comunitaria in evoluzione.</p>
                    </div>
                </div>
            </section>
            <section use:scrollRef={'1963'}>
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
            </section>
            <section use:scrollRef={'2023'}>
                <div class="history-paragraph-image">
                    <div class="sibling-image m-5">
                        <img class="image-carousel rounded-image" src="https://media-assets.wired.it/photos/6523ca3b7ff82f5e7241bda0/16:9/w_1920,c_limit/158986304" alt="elicottero disastro">
                    </div>
                    <div class="m-5">
                        <h1>Viaggio nel Passato: La valle del disastro</h1>
                        <p>Entra nel cuore di una delle pagine più oscure della storia italiana. Scopri la narrazione completa del disastro del Vajont, una tragedia che ha sconvolto il mondo nel 1963. Attraverso una sequenza cronologica dettagliata e testimonianze dirette, questa sezione rivelerà gli eventi che hanno portato a una catastrofe senza precedenti, gettando luce sui protagonisti, le decisioni cruciali e le conseguenze durature che hanno segnato questa epocale tragedia.</p>
                    </div>
                </div>
            </section>
        </div>
        <!-- <div class="vertical-timeline">
            <VerticalTimeline/>
        </div> -->
    </div>
</main>

<style>

</style>
