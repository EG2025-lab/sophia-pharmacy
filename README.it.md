# SOPHIA

La beta professionale distribuita è **0.7.103-beta**, riservata alle persone approvate dal titolare. Google identifica la persona; la qualifica professionale resta autodichiarata. **Attivazione automatica, pagamenti reali e addebiti delle risposte sono inattivi.** La Home Stealth conserva sondaggio e lista facoltativa, senza pulsanti di accesso all’app. [Stato corrente](docs/STATUS.md).

**La lettura rapida dei documenti alimenta una risposta AI.** Per i quesiti ammessi su uno–quattro codici esatti, la lettura verificata di RCP/FI precede GPT-6.1 Sol con ragionamento low, che deve rispondere alla domanda del farmacista senza incollare sezioni intere. Resta obbligatoria la revisione semantica indipendente. La sola identificazione del medicinale ha un contratto separato e delimitato. Il percorso clinico anticipa l’acquisizione ammessa delle informazioni sostanziali prima della revisione finale; il legame con le fonti istituzionali è più rigoroso. Sono correzioni implementate, non guadagni di velocità già misurati.

Sulla versione precedente **102 sono state inviate esattamente tre domande in chat reali separate**, riprese da feedback storici. Tutte consegnate: acquisizione RCP/FI in **5,08 s senza modello**, risposta normativa parziale in **70,55 s** e sintesi clinica delimitata in **122 s**. Il titolare ha rifiutato il formato letterale del primo caso: non è un esempio riuscito della risposta AI richiesta. Nel caso normativo manca ancora il corpo corrente della tabella ministeriale. Nel caso clinico Actions/API hanno preceduto il recupero web dichiarato, con letture di ISS/NICE. Sedici chiamate modello hanno ricevute d’uso; stima prudenziale **1,15 USD**, non fattura né prezzo generale per risposta.

La 103 ha superato **1.664 controlli offline**, senza esclusioni, e il confronto esatto di **170 file runtime** in un container senza rete. **Nessuna nuova domanda reale sulla 103**, nel rispetto del limite del titolare. Utilità delle correzioni, latenza della sintesi AI e ripetibilità generale restano da misurare; validazione clinica umana incompleta e apertura professionale generale **NO-GO**. Una fonte ufficiale bloccata resta una lacuna dichiarata, senza presentare una copia scaduta come vigente.

Lo storico è prioritario, con paginazione completa, ricerca per titolo e aggiornamento al ritorno nell’app. Le 101 chat attive del titolare coincidevano con Firebase prima dei tre nuovi invii. La voce **Algoritmo Clinico beta** spiega in modo versionato routing, selezione dei documenti e revisione. Le correzioni di sicurezza preservano i confini di accesso. Quattordici lezioni metodologiche curate da FarmAI vengono selezionate localmente con provenienza: non è addestramento automatico né uso di vecchie risposte come fatti clinici attuali. GPT originali e plugin Business FarmAI conservano il contenuto **0.7.7.155** e non sono stati ritestati in questo lavoro.

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
