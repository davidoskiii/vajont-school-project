<script>
    import { scrollTo, scrollRef, scrollTop } from 'svelte-scrolling'
    import Carousel from 'svelte-carousel'
    import VideoEmblem from './VideoEmblem.svelte';
    import Section from './Section.svelte';
</script>

<main>
    <Section/>
    <div class="cause">
        <div class="text-div">
            <section use:scrollRef={'causa'}>
                <h2>Causa</h2>
                <div class="history-paragraph-start start-history m-5">
                    <div class="m-5">
                        <h1>Intro causa</h1>
                        <p>In questa sezione spiegheremo le varie condizioni geologiche che causarono il disastro, e come coloro che scoprirono ciò venivano silenziati, causando l'evitabile tragedia. Daremo uno sguardo alla formazione del terreno, la paleofrana e frana che causarono questo catastrofico evento. </p>
                    </div>
                </div>
            </section>
            <section use:scrollRef={'..'}>
                <div class="history-paragraph-image">
                    <div class="m-5">
                        <h1>Scelta del Territorio</h1>
                        <p>Entra nel cuore di una delle pagine più oscure della storia italiana. Scopri la narrazione completa del disastro del Vajont, una tragedia che ha sconvolto il mondo nel 1963. Attraverso una sequenza cronologica dettagliata e testimonianze dirette, questa sezione rivelerà gli eventi che hanno portato a una catastrofe senza precedenti, gettando luce sui protagonisti, le decisioni cruciali e le conseguenze durature che hanno segnato questa epocale tragedia. he causarono il disastro, e come coloro che scoprirono ciò venivano silenziati, causando l'evitabile tragedia. Daremo uno sguardo alla formazione del terreno, della</p>
                    </div>
                    <div class="sibling-image m-5">
                        <img class="image-carousel rounded-image" src="https://media-assets.wired.it/photos/6523ca3b7ff82f5e7241bda0/16:9/w_1920,c_limit/158986304" alt="elicottero disastro">
                    </div>
                </div>
            </section>
            <section use:scrollRef={'....'}>
                <div class="history-paragraph-image">
                    <div class="sibling-image m-5">
                        <img class="image-carousel rounded-image" src="https://media-assets.wired.it/photos/6523ca3b7ff82f5e7241bda0/16:9/w_1920,c_limit/158986304" alt="elicottero disastro">
                    </div>
                    <div class="m-5">
                        <h1>Gestione Critica della situazione</h1>
                        <p>Il 1959 segna un periodo di crescita accelerata per Longarone, alimentato dalla costruzione della Diga del Vajont. L'espansione economica porta nuove opportunità, ma anche sfide cruciali. La comunità affronta il dilemma tra progresso e preservazione delle radici culturali, mentre emergono preoccupazioni sulla sicurezza e sostenibilità ambientale. Questo capitolo della storia del Vajont evidenzia le tensioni dinamiche tra modernizzazione e la salvaguardia di una identità comunitaria in evoluzione.</p>
                    </div>
                </div>
            </section>
            <section use:scrollRef={'.'}>
                <div class="history-paragraph-image">
                    <div class="m-5">
                        <h1>Paleofrana e Analisi Geologica</h1>
                        <p>Longarone, incantevole borgo ai piedi delle montagne, già prima del 1955 respirava la sua storia intrisa di tradizioni e comunità unite. La vita ruotava intorno alle colture, alle serate in piazza, e ai legami familiari. Tuttavia, l'arrivo degli anni '50 portò l'ombra imponente della Diga del Vajont, preludio a una trasformazione che avrebbe ridefinito per sempre il destino di questo idilliaco paesino.</p>
                    </div>
                    <div class="sibling-image m-5">
                        <img class="image-carousel rounded-image" src="https://staticgeopop.akamaized.net/wp-content/uploads/sites/32/2021/10/immagine-1-argilla-1.jpg?im=Resize,width=570;" alt="elicottero disastro">
                    </div>
                </div>
            </section>
            <section use:scrollRef={'...'}>
                <div class="history-paragraph-image">
                    <div class="sibling-image m-5">
                        <VideoEmblem url="https://drive.google.com/file/d/1cKUY5uFmX3n8Tys5AgAWZw7bxMi42Rc0/preview"/>
                    </div>
                    <div class="m-5">
                        <h1>Scivolamento della Roccia nella Diga</h1>
                        <p>Il 1957 vede il via alla costruzione della Diga del Vajont, trasformando Longarone in un cantiere frenetico. Mentre la struttura cresce, l'entusiasmo per il progresso si intreccia con crescenti preoccupazioni sulla sicurezza. La comunità assiste con orgoglio alla nascita di un'imponente opera idroelettrica, ma dietro la facciata emergono tensioni e scelte tecniche che avranno conseguenze drammatiche negli anni a venire.</p>
                    </div>
                </div>
            </section>
        </div>
    </div>
</main>

<style>
    .cause {
        display:flex;
        align-content:center;
        justify-content:center;
        text-align:center;
        padding:0 160px
    }
</style>
