# SOPHIA

La beta professionale distribuita è **0.7.98-beta**, riservata alle persone autorizzate dal titolare. Google verificato identifica la persona; una nuova richiesta resta in attesa dell’approvazione. L’attivazione automatica è disabilitata e le vecchie anteprime pubbliche restano chiuse. La qualifica professionale è autodichiarata, non verificata automaticamente. **Pagamenti reali e addebiti delle risposte restano inattivi.** Il sito pubblico Stealth offre sondaggio e lista facoltativa, senza accesso all’app. [Stato corrente](docs/STATUS.md).

La 98 migliora il riconoscimento dei riferimenti normativi esatti, rimuove soltanto una copia ridondante del contesto delle fonti già completo e aggiunge una diagnostica minimizzata degli errori. Accessi, controlli di sicurezza, configurazione del modello e regole del recupero web sono preservati dalla 97. La qualificazione tecnica comprende **1.508 controlli Python offline**, con 61 mirati inclusi, e il confronto senza rete di 153 file runtime. Sono verifiche tecniche, distinte dalla valutazione delle risposte.

Sulla 98 sono state inviate esattamente **due domande di regressione note in chat reali separate della UI**: eccipienti di un medicinale e formalismi della ricetta. Entrambe hanno prodotto una risposta completa; la revisione documentale assistita da AI è positiva entro il perimetro controllato, con riserve concrete. Tempi backend: **31,04 s e 62,42 s**, con **otto chiamate modello concluse** complessive. La stima parziale dei soli token è **0,3049303 USD**, escluse cache-write non osservate, infrastruttura, servizi, imposte e revisione umana. Due osservazioni non sono un holdout cieco, un confronto controllato di velocità, uno SLA o una prova di ripetibilità generale.

Le sezioni eccipienti sostengono la risposta circoscritta, ma la riconciliazione dell’etichetta del principio attivo nel FI resta da revisionare; il gate generale della coppia documentale non è chiuso. L’esito sui formalismi vale per normale ricetta privata e due confezioni RNR verificate: l’apertura deve qualificare subito confezione e canale perché esistono anche presentazioni OSP. Accettazione professionale e validazione clinica umana restano in attesa. Nessuno dei due casi ha esercitato fallback web indipendente; la lettura diretta della Gazzetta Ufficiale tramite Action non è fallback.

Il percorso distribuito conserva **GPT-6.1 Sol low con aumento controllato a medium**, Actions prima e recupero web effettivamente letto e dichiarato dove ammesso. Router adattivo e pagamenti restano disattivati. Nei due casi 98 le Actions AIFA e normative/documentali hanno risposto; il precedente errore TLS resta un’osservazione storica, senza provare un guasto totale attuale o una disponibilità universale. Latenza, copertura più ampia e continuità restano aperte. La candidata 96 non è stata promossa dopo il replay fallito. Privacy, accessi e budget restano vincolanti.

La batteria storica completa della 0.7.88 conserva **sei risposte a tre quesiti documentali generali, ciascuno ripetuto due volte**: conservazione di un medicinale, testo integrale di un articolo di legge e informazione istituzionale generale sull’occhio secco. Verifiche tecniche e documentali assistite da AI positive nello scope; nucleo concorde nelle coppie, con variazioni di dettaglio e formulazione. Tempi complessivi osservati: AIFA **11–18 s**, Normativa **10–12 s**, Clinica con recupero web **32–35 s**. Non sono SLA, confronto controllato di velocità, ripetibilità generale o validazione clinica umana. Le risposte cliniche dichiarano copertura parziale e attualità/retraction non accertate. Diffusione professionale generale **NO-GO**. [Stato e limiti](docs/STATUS.md).

### Un collega AI per la conoscenza professionale in farmacia

SOPHIA è un progetto indipendente di **Enrico Giuliano, farmacista e Founder & Product Lead**. FarmAI resta disponibile nei GPT originali e in plugin privati Business derivati dalle copie. SOPHIA è un’app separata, con propria beta, routing e verifiche. [Differenze tra GPT, plugin e SOPHIA](docs/FARMAI_AND_SOPHIA.md).

[Raccontaci i tuoi bisogni professionali](docs/PROFESSIONAL_NEEDS_RESEARCH.md): sondaggio e lista d’attesa hanno scelte distinte. La casella della lista è facoltativa e inizialmente selezionata; togliendola si può inviare il solo sondaggio. Email necessaria soltanto per lista o colloquio scelto separatamente. I ruoli distinguono farmacista collaboratore, titolare e libero professionista. I record precedenti conservano le finalità originali; sviluppatori ed esperti AI mantengono il percorso collaborazioni.

Vogliamo ridurre il carico informativo del farmacista, aiutare a ridurre gli errori e migliorare il servizio in farmacia. Sono obiettivi di sviluppo: il loro impatto deve ancora essere misurato.

**[Sito SOPHIA](https://sophia-pharmacy.enricogiuliano.chatgpt.site/) · [Stato e architettura](https://sophia-pharmacy.enricogiuliano.chatgpt.site/transparency) · [Roadmap](https://sophia-pharmacy.enricogiuliano.chatgpt.site/roadmap) · [English](README.md)**

## Cerchiamo persone con cui costruire e valutare

| Area | Primo contributo possibile | Opportunità |
| --- | --- | --- |
| Documentazione AIFA | Identità del medicinale e della confezione; lettura separata di RCP e foglio illustrativo (FI); casi ambigui o incompleti. | [Documenti ufficiali](https://github.com/EG2025-lab/sophia-pharmacy/issues/2) |
| Normativa italiana | Fonti ufficiali, riferimenti esatti, versioni e condizioni di applicabilità. | [Ricerca normativa](https://github.com/EG2025-lab/sophia-pharmacy/issues/3) |
| Valutazione | Quesiti professionali, controllo delle citazioni e criteri di revisione del farmacista. | [Pilota proposto di 20 quesiti](https://github.com/EG2025-lab/sophia-pharmacy/issues/4) |
| Software e AI | Recupero dei documenti, parsing, orchestrazione degli strumenti e test riproducibili. | [Guida ai contributi](CONTRIBUTING.md) |

Sono benvenuti farmacisti, sviluppatori, esperti AI, ricercatori e gruppi universitari. Si può iniziare da un contributo piccolo, anche senza chiamate API a pagamento: per esempio i metadati di una coppia RCP/FI, usando il [modello vuoto](pilot/source-pair-template.json). Il lavoro viene verificato prima di diventare materiale di valutazione.

Il [pilota di 20 quesiti](pilot/README.md) è una proposta: non è ancora congelato né eseguito. Partecipazione, accessi, eventuali costi e termini della collaborazione si concordano separatamente.

## Come iniziare

1. Leggi la [guida ai contributi](CONTRIBUTING.md) e scegli una delle opportunità.
2. [Presenta una proposta](https://github.com/EG2025-lab/sophia-pharmacy/issues/new?template=collaboration.yml) indicando il tuo ruolo e un primo contributo concreto. Puoi scrivere in italiano o in inglese.
3. Per un contatto riservato, usa [Parliamone sul sito](https://sophia-pharmacy.enricogiuliano.chatgpt.site/#partners) oppure [scrivi a Enrico](mailto:enrico.giuliano000@gmail.com?subject=SOPHIA%20%E2%80%94%20collaborazione).

## Stato e confini

La versione corrente è indicata all’inizio. Il paragrafo seguente conserva lo stato storico della 0.7.80.

La beta riservata **0.7.80** sostituisce falsi blocchi linguistici e vincoli di formato, rende facoltativo il piano e conserva informazioni già controllate quando l’approfondimento non può completarsi in sicurezza. Verifiche tecniche con confini sintetici, senza nuove domande al modello. Identità delle fonti, privacy, supporto delle affermazioni e giudizio umano restano necessari. Gli esiti reali78 restano storici; utilità e latenza della80 da misurare. Voti e gate invariati. [Stato e limiti](docs/STATUS.md).

Questo repository contiene documentazione pubblica e opportunità di collaborazione; il codice dell'applicazione non è pubblicato qui. Non fornisce consigli riferiti a singoli pazienti e non dichiara certificazioni o prestazioni cliniche validate.

Nel lavoro di sviluppo utilizziamo [ToolUniverse](https://github.com/mims-harvard/ToolUniverse). Questo utilizzo non implica affiliazione, patrocinio o collaborazione confermata con Harvard o con gli autori.

Non inserire dati di pazienti, credenziali o materiale riservato in issue, discussioni o contributi pubblici. [Informativa privacy](https://sophia-pharmacy.enricogiuliano.chatgpt.site/privacy.html).

La supervisione operativa è aggiornata separatamente dall’app. Il [riesame dello stato](docs/STATUS.md#current-operational-reference) documenta riferimenti di versione, consolidamento degli avvisi e copia da riesaminare, senza aumentare i voti di maturità.
