<script>
    import { scrollTo, scrollRef, scrollTop } from 'svelte-scrolling'
    import HorizzontalTimeline from "./HorizzontalTimeline.svelte";
    import Carousel from 'svelte-carousel'
    import VideoEmblem from './VideoEmblem.svelte';
</script>

<main>
    <div class="history">
        <div class="text-div">
            <section use:scrollRef={'date'}>
                <h2>Date Principali</h2>
                <div class="history-paragraph-start start-history m-5">
                    <div class="m-5">
                        <h1>Introduzione</h1>
                        <p>In questa sezione, ci apprestiamo a tracciare un percorso temporale che ci condurrà attraverso gli eventi cruciali legati alla tragica vicenda del Vajont. Le principali date selezionate rappresentano punti chiave lungo questa dolorosa cronologia, offrendo una visione dettagliata del susseguirsi degli avvenimenti che hanno portato alla catastrofe della diga.</p>
                    </div>
                    <div class="carousel-container m-5">
                        <Carousel swiping={false} autoplay autoplayDuration={3500}>
                            <img class="image-carousel" src="https://www.rainews.it/cropgd/686x453/dl/img/2023/9/30/1696079578108_VistadellagoladelVajontprimadellacostruzionedelladiga_nel__WIKIPEDIA.jpg" alt="longarone">
                            <img class="image-carousel" src="http://download.kataweb.it/mediaweb/image/brand_corrierealpi/2013/09/08/1378650462808_3.jpg" alt="">
                            <img class="image-carousel" src="https://live.staticflickr.com/2670/3963950080_3d3ed9c7fb_c.jpg" alt="elicottero disastro">
                            <img class="image-carousel" src="https://enasc.it/wp-content/uploads/2021/10/R-2.jpg" alt="elicottero disastro">
                            <img class="image-carousel" src="http://www.ertoecasso.it/immagini/vajont/disastro.jpg" alt="elicottero disastro">
                        </Carousel>
                    </div>
                </div>
                <HorizzontalTimeline/>
            </section>
            <section use:scrollRef={'1955'}>
                <div class="history-paragraph-image">
                    <div class="sibling-image m-5">
                        <img class="image-carousel rounded-image" src="https://www.rainews.it/cropgd/641x453/dl/img/2023/9/30/1696081167334_Longarone_prima_della_tragediaANSABD.JPG" alt="elicottero disastro">
                    </div>
                    <div class="m-5">
                        <h1>1955: Le radici di Longarone</h1>
                        <p>La costruzione della diga iniziò nel 1957, sotto la supervisione dell’ingegner Carlo Semenza che sminui’ fin dall’inizio le paure relative a rischi geologici ed eventi franosi che potevano essere provocati da un intervento di quelle proporzioni sul versante sinistro della montagna. I rilevamenti condotti sul monte Tóc, che in friulano significa “marcio”, non avevano dato esiti incoraggianti ma, nonostante i forti dubbi circa la sicurezza della zona, si scelse di andare ugualmente avanti.</p>
                    </div>
                </div>
            </section>
            <section use:scrollRef={'1957'}>
                <div class="history-paragraph-image">
                    <div class="m-5">
                        <h1>1957: La costruzione della diga</h1>
                        <p>Il 1957 vede il via alla costruzione della Diga del Vajont, trasformando la valle in un cantiere frenetico. La vicenda della costruzione della diga interessa in prima battuta le comunità di Erto e Casso, che per prime sono coinvolte nella questione attraverso l’espropriazione di una parte consistente delle loro terre, gli abitanti dovettero lasciare le loro case e abbandonare le loro terre. In realtà il processo non fu così pacifico, ma la SADE, negli anni, forzando la mano e non incontrando nessun ostacolo dal comune e dallo stato, riuscì a fare sua quella valle.</p>
                    </div>
                    <div class="sibling-image m-5">
                        <VideoEmblem url="https://drive.google.com/file/d/1fgHm8SLvFRMaeXDK7a2SNFGTOekAigdF/preview"/>
                    </div>
                </div>
            </section>
            <section use:scrollRef={'1959'}>
                <div class="history-paragraph-image">
                    <div class="sibling-image m-5">
                        <img class="rounded-image" src="https://www.gedistatic.it/content/gnn/img/corrierealpi/2023/09/25/184451229-e711c018-33e7-40d2-86d3-1627d6f8fde2.jpg?webp" alt="elicottero disastro">
                    </div>
                    <div class="m-5">
                        <h1>1959: Le prime frane</h1>
                        <p>Il 22 Marzo 1959 una piccola frana di 3.000.000 m3 di terra cadde nel bacino della diga di Pontesei sollevando un’onda di 20 metri che uccise un operaio. Il 4 Novembre  1959 una piccola frana di solo 800.000 m3 si staccò dalla parete del Toc e finì nella diga, sollevando un’onda di 20 metri che non lasciò vittime. In quell’occasione la montagna si spaccò e sul fronte settentrionale del Toc comparve la famosa M.</p>
                    </div>
                </div>
            </section>
            <section use:scrollRef={'1963'}>
            <div class="history-paragraph centered-flex">
                <div class="m-5">
                    <h1>1963: Una Tragedia Inimmaginabile</h1>
                    <p>Il 9 ottobre 1963  crolla la montagna del Vajont.
                        Uno dei disastri più devastanti della storia italiana, la natura si è scontrata con l'ingegno umano in una tragedia inimmaginabile. Dalle cause, alla devastazione e alle conseguenze, questa storia è un ricordo doloroso delle vite perdute e delle lezioni apprese dall'errore umano.</p>
                </div>
                <div class="carousel-container m-5">
                    <Carousel swiping={false} autoplay autoplayDuration={2000}>
                        <img class="image-carousel" src="https://www.skuola.net/news_foto/2018/vajont.jpg" alt="elicottero disastro">
                        <img class="image-carousel" src="https://www.raicultura.it/dl/img/2019/10/04/1570203895060_h_00101051.jpg" alt="elicottero disastro">
                        <img class="image-carousel" src="https://www.raicultura.it/dl/img/2019/10/04/1570203895060_h_00101050.jpg" alt="elicottero disastro">
                    </Carousel>
                </div>
            </div>
            </section>
            <section use:scrollRef={'2023'}>
                <div class="history-paragraph-image">
                    <div class="sibling-image m-5">
                        <img class="image-carousel rounded-image" src="https://staticgeopop.akamaized.net/wp-content/uploads/sites/32/2023/10/iStock-1192444134.jpeg" alt="elicottero disastro">
                    </div>
                    <div class="m-5">
                        <h1>Oggi: La Diga e la Valle del Vajont nel Nuovo Millennio</h1>
                        <p>La Diga del Vajont, emblema dell'ingegneria degli anni '50, oggi si erge maestosa nella Valle come memoria vivente. Attraverso costanti lavori di manutenzione, la Diga garantisce sicurezza e continua ad affascinare visitatori con la sua imponenza. La Valle, segnata dalla tragedia del 1963, è diventata un luogo di riflessione e turismo, con sentieri panoramici che offrono viste spettacolari. Monumenti commemorativi e musei onorano la storia, trasmettendo un messaggio di resilienza e speranza nell'affrontare il passato.</p>
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
