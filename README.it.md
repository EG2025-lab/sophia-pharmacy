# SOPHIA

La beta professionale distribuita è **0.7.101-beta**, riservata alle persone approvate dal titolare. Google identifica la persona; le nuove richieste attendono l’autorizzazione. La qualifica professionale resta autodichiarata. **Attivazione automatica, pagamenti reali e addebiti delle risposte sono inattivi.** La Home Stealth conserva sondaggio e lista facoltativa, senza pulsanti di accesso all’app. [Stato corrente](docs/STATUS.md).

Le versioni 99–101 migliorano lettura delle quantità nel FI, qualificazione di confezione/canale, percorso clinico con Actions prima e revisione documentale. La correttiva 101 aggiunge codifica reversibile degli array annidati nello storage, osservazioni private minimizzate dei costi anche sui futuri fallimenti e lettura senza modello per richieste naturali strettamente limitate all’identificazione AIC. Superati **1.539 controlli Python offline**, con 13 nuovi inclusi, e confrontati 159 file runtime nel container. Sono verifiche tecniche: **nessuna nuova domanda reale sulla 101**, secondo il limite di quattro invii del titolare.

Sulla versione precedente **100 sono state inviate esattamente quattro domande nuove in chat reali separate**: identità del medicinale, ricetta ripetibile, eccipienti FI e letteratura clinica negli adulti. Tre risposte complete in **22,06 s, 8,04 s e 59,74 s** backend. La risposta FI è fallita nel salvataggio finale dopo i controlli del motore: resta una consegna fallita. Osservate dodici chiamate modello, compresa la ricerca web. La correzione è stata verificata offline e pubblicata senza un altro replay reale. Questi riscontri non sono un confronto controllato di velocità, uno SLA o una prova di ripetibilità generale.

La correzione di storage conserva dati originali e hash alla rilettura; non approva affermazioni né aggira i controlli delle fonti. La consegna incompleta della 100 non viene rinominata risposta riuscita della 101. Riconciliazione chimica/dei sali, copertura più ampia e accettazione professionale indipendente mantengono i propri limiti. La validazione clinica umana non è completata.

**Router adattivo attivo:** Luna senza ragionamento per estrazioni delimitate osservate, Terra senza ragionamento per composizione documentale delimitata e Sol low o medium controllato per contesto non delimitato, clinica, conflitti e revisione indipendente. Tutti e tre osservati sulla 100. Nel caso clinico Actions e letture API hanno preceduto il recupero web dichiarato; verifiche di accesso hanno impedito nuove letture web, quindi la risposta usa abstract Action e dichiara i limiti di testo integrale e attualità. Non sono dimostrati risparmi di cache, continuità generale o parità con FarmAI.

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
