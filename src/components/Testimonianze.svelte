<script>
    import { scrollTo, scrollRef, scrollTop } from 'svelte-scrolling'
    import VideoEmblem from "./VideoEmblem.svelte";
</script>

<main>
    <div class="testimonianze mb-70">
        <div class="text-div">
            <section use:scrollRef={'testimonianze'}>
                <h2>Testimonianze</h2>
            </section>
            <div class="history-paragraph-image">
                <div class="m-5" style="width: 1500px;">
                    <p>In questa sezione sono riportati i resoconti diretti dei sopravvissuti al tragico evento della frana della diga del Vajont. Le testimonianze offrono un'istantanea toccante e dettagliata degli avvenimenti che hanno segnato la vita di coloro che hanno vissuto la catastrofe in prima persona. Attraverso le parole degli intervistati, emerge la drammaticità dell'esperienza e la devastazione che ha colpito la comunità circostante. I racconti forniscono una prospettiva umana e emotiva, sottolineando la forza e la resilienza delle persone coinvolte di fronte a una tragedia di tale portata. Le testimonianze costituiscono un importante documento storico, offrendo una visione personale e autentica di uno degli eventi più dolorosi della storia recente.</p>
                </div>
            </div>
            <div class="videos">
                <VideoEmblem url="https://drive.google.com/file/d/1AaVAD8FPHEsw4F2Q7t2AMiYG4dPeeQio/preview"/>
                <!-- https://drive.google.com/file/d/1KYqok0Fyn9lVziGbsz-d40ex0jhP5JxY/preview -->
                <VideoEmblem url="https://www.youtube.com/embed/JdiQ0sxlj8s" title="La storia di Gino, sopravvissuto alla tragedia del Vajont"/>
                <VideoEmblem url="https://drive.google.com/file/d/10Re30IkUdWetD6sNAh1Kgjibg8uCSEeF/preview"/>
            </div>
        </div>
    </div>
</main>

<style>
    .videos {
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .testimonianze {
        display:flex;
        align-content:center;
        justify-content:center;
        text-align:center;
        padding:0 160px
    }
</style>
