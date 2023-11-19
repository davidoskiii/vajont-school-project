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
            <section use:scrollRef={'storia'}>
                <h2>Ricostruzione Storica</h2>
                <div class="history-paragraph-start start-history m-5"></div>
            </section>
            <section>
                <div class="history-paragraph-image">
                    <div class="sibling-image m-5">
                        <img class="image-carousel rounded-image-400" src="https://progettodighe.it/reportage/il-progetto-grande-vajont/planimetria-della-diga-del-vajont_huf048845edc6f2cf72bb224e8e40da66b_60651_1280x640_fill_q75_box_smart1.jpg" alt="elicottero disastro">
                    </div>
                    <div class="m-5">
                        <h1>La storia della diga</h1>
                        <p>Negli anni ‘40 la Società Adriatica per l’Energia Elettrica, ebbe l’idea di creare un bacino idroelettrico tra I comuni di Erto e Casso in provincia di Pordenone. Il progetto era quello di sfruttare la forza dell’acqua con la realizzazione di quella che all’epoca, con i suoi 265 metri di altezza, fu definitiva “la diga più alta del mondo”. Il progetto della diga del Vajont venne a far parte del cosiddetto “Grande Vajont”, un complesso che riuniva e collegava diversi bacini idroelettrici nelle valli circostanti. Fu ideato e realizzato dalla SADE societa’ che sarebbe in seguito divenuta proprietà dell’Ente Nazionale Energia Elettrica.</p>
                    </div>
                </div>
            </section>
            <section>
                <div class="history-paragraph-image">
                    <div class="m-5">
                        <h1>Scelta sbagliata del territorio</h1>
                        <p>Entra nel cuore di una delle pagine più oscure della storia italiana. Scopri la narrazione completa del disastro del Vajont, una tragedia che ha sconvolto il mondo nel 1963. Attraverso una sequenza cronologica dettagliata e testimonianze dirette, questa sezione rivelerà gli eventi che hanno portato a una catastrofe senza precedenti, gettando luce sui protagonisti sulle decisioni cruciali e sulle conseguenze durature che hanno segnato questa epocale tragedia. Inoltre le persone che vennero a conoscenza dell'imbroglio furono silenziate lasciando accadere l'inevitabile.</p>
                    </div>
                    <div class="sibling-image m-5">
                        <img class="image-carousel rounded-image" src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a9/Monte_Toc.jpg/1280px-Monte_Toc.jpg" alt="elicottero disastro">
                    </div>
                </div>
            </section>
            <section>
                <div class="history-paragraph-image">
                    <div class="m-5">
                        <h1>Giochi di potere e i timori di un popolo</h1>
                        <p>La diga del Vajont fu terminata in circa tre anni e l’invaso iniziò ad essere colmato, senza neppure aspettare di ottenere il permesso dal governo. La SADE del resto era un’azienda molto influente e nemmeno la Commissione di collaudo rilevò mai aspetti negativi nell’operato dei responsabili.
                            Nel frattempo gli abitanti della vallata del Vajont dovettero affrontare questa nuova realtà che, se da una parte prometteva di portare lavoro e benessere in un luogo fino ad allora legato all’economia povera della montagna contadina, dall’altro invadeva case, terreni e possedimenti attraverso una serie di compravendite ed espropri effettuati spesso con arroganza e indifferenza.
                            Quasi nessuno ascoltò le rimostranze degli ertani e nemmeno diede importanza ai timori che iniziavano a nascere dopo aver sentito forti boati e scosse sismiche che causavano anche fratture del terreno nella valle. Una delle poche persone che volle dare veramente voce alle proteste dei paesani fu la giornalista bellunese Tina Merlin che scrisse diversi articoli, nei quali raccolse e raccontò le testimonianze e le paure degli abitanti, preoccupati e oppressi e fu sempre lei a lanciare l’allarme per l’altissimo rischio che si stava correndo. </p>
                    </div>
                </div>
            </section>
            <section>
                <div class="history-paragraph-image">
                    <div class="m-5">
                        <h1>Paleofrana e analisi geologica</h1>
                        <p>Prima della grande frana ci furono già dei segnali inquietanti: nel 1959, 3 milioni di metri quadrati di roccia franarono nel bacino di Pontesei, uno dei bacini del sistema del Grande Vajont; non ci furono danni ma si accese il campanello d’allarme degli addetti ai lavori e non solo.
                            Il campanello di allarme divenne ancor più forte con il 4 novembre del 1960 quando ci fu un’altra frana piu’ piccola proprio nel bacino della diga del Vajont. Non ci furono danni o vittime perché l’acqua non superò la diga ma da quel momento lo stesso Carlo Semenza cominciò ad essere seriamente preoccupato.
                            Sul monte Tóc si aprì la lunga spaccatura a forma di “M” dalla quale si muoverà il tremendo crollo del 1963.  
                            A questo punto entrano in scena due dei personaggi principali della storia: il geologo Leopold Muller e Edoardo Semenza (figlio di Carlo Semenza) che avevano un’interpretazione diversa del tipo di frana e del tipo di pericolo.
                            Muller era un gigante, Edoardo era di gran lunga meno titolato: un ragazzo sulla trentina, da poco laureato
                            Muller riteneva che la frana fosse una frana geologicamente recente, e che fosse caratterizzata da un movimento lento, come un ghiacciaio. Invece, secondo il giovane Edoardo, che andò ad analizzare con gli occhi ogni metro quadro della montagna, la frana era una paleofrana, cioè vecchia, che esisteva da chissà quanto tempo. Secondo lui avrebbe potuto distaccarsi improvvisamente, scivolando con un movimento relativamente repentino, e finire nel bacino causando onde mostruose e danni inimmaginabili.
                            Edoardo sembrò il "catastrofista" della situazione e infatti nessuno gli diede troppo conto: era troppo giovane e troppo inesperto affinché la sua teoria fosse presa in seria considerazione.</p>
                    </div>
                    <div class="sibling-image m-5">
                        <img class="image-carousel rounded-image" src="https://staticgeopop.akamaized.net/wp-content/uploads/sites/32/2021/10/immagine-1-argilla-1.jpg?im=Resize,width=570;" alt="elicottero disastro">
                    </div>
                </div>
            </section>
            <section>
                <div class="history-paragraph-image">
                    <div class="sibling-image m-5">
                        <VideoEmblem url="https://drive.google.com/file/d/1cKUY5uFmX3n8Tys5AgAWZw7bxMi42Rc0/preview"/>
                    </div>
                    <div class="m-5">
                        <h1>Scivolamento della roccia nella Diga</h1>
                        <p>La frana si muoveva di circa 3 cm al giorno, Muller pensò che la velocità della frana dipendeva da quanta acqua era presente nel lago artificiale della diga. Più acqua c’era, più la frana si muoveva velocemente, il motivo era legato alla presenza di un livello argilloso, al di sotto di uno strato di roccia calcarea.
                            Quindi si provo’ a far diminuire il livello dell’acqua, facendo questo infatti si passò da 3 cm al giorno a 1 mm al giorno.
                            L’idea fu quella di far scivolare il materiale roccioso nell’acqua in modo lento e controllato riempiendo e svuotando il lago.
                            A giugno del 1963 il livello di piena del bacino raggiunse i 700 m s.l.m riportando la frana a uno scivolamento di 5 mm al giorno.
                            In quel periodo ci fu un passaggio di consegne nella gestione dell’impianto dal privato al pubblico, e proprio in quel periodo il livello del bacino venne abbassato con ritardo: l’acqua arrivò fino a circa 710 m s.l.m e la frana raggiunse una velocità di 2 cm al giorno. Solo il 26 settembre del 1963 il bacino venne riportato al livello di sicurezza, ma era ormai troppo tardi.</p>
                    </div>
                </div>
            </section>
            <section>
                <div class="history-paragraph-image">
                    <div class="m-5">
                        <h1>9 ottobre 1963: La catastrofe del Vajont</h1>
                        <p>Alle 22.39 del 9 ottobre 1963 l’immane frana di più di due chilometri fece crollare nel lago del Vajont una massa di circa 300 milioni di metri cubi di roccia e terra che sollevò una colossale ondata di 48 milioni di metri cubi d’acqua. L’onda si alzò ed esplose in tre flussi: uno lambì e risparmiò Casso, un altro andò a colpire alcune località di Erto che si trovavano sulla sponda del lago –Pinéda (Ruáva), Prada, Marzana, Lirón, San Martino, Le Spesse, Fraséign, Il Cristo – spazzandole via. Il terzo piombò su Longarone con forza devastante, distruggendola completamente.
                            L’acqua, trascinò con sé famiglie, uomini, donne, bambini, case, terreni,boschi, animali, vite intere cancellate nel tempo di soli quattro minuti.
                            Fu una strage: il bilancio delle vittime fu di quasi 2000 morti, annientati assieme a un territorio, una storia e una cultura che non hanno mai più riacquistato le loro fattezze originarie.</p>
                    </div>
                    <div class="sibling-image m-5">
                        <img class="image-carousel rounded-image" src="https://upload.wikimedia.org/wikipedia/it/4/4d/Disastro_Vajont.jpg" alt="elicottero disastro">
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
