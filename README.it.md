# SOPHIA

La beta distribuita è **0.7.109-beta**, riservata agli utenti approvati dal titolare; pagamenti e addebiti restano inattivi. [Stato corrente](docs/STATUS.md).

Rimosso il tetto fisso alle chiamate AI. Richieste di strumenti identiche senza nuove informazioni canoniche portano alla composizione verificata, evitando ulteriori trasporti. I percorsi documentali AIFA e Normativa evitano la duplicazione obbligatoria tra sintesi iniziale e dettaglio. Restano tempo, annullamento, budget delle fonti, privacy, binding e revisione semantica. **1.724 controlli offline** superati; nessuna domanda reale al modello sulla109.

Sei ripetizioni reali108: **due risposte utili nello scope, una locale parziale e tre richieste fallite**, una con sintesi verificata visibile. Actions e web hanno collaborato nella risposta vaccinale provinciale. Due casi interrotti dal tetto alle chiamate; uno bloccato da un identificatore nel testo generato.39 chiamate interne, stima prudenziale2,108USD, non fattura; somma dei tempi maggiore rispetto alla106. Nessun miglioramento generale di efficienza dimostrato.

Correttezza109, continuità, costo/tempo reali e ripetibilità ancora da misurare. La specifica stringa del blocco di output108 non è conservata; nessun filtro privacy disattivato. Nessun uso generale al banco, parità con FarmAI o validazione clinica umana dichiarati. FarmAI GPT originali e plugin Business conservano contenuto **0.7.7.155**.

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
