---
title: "Software intelligenza artificiale: come proteggere i dati"
excerpt: "Software intelligenza artificiale e dati sensibili: rischi per le PMI, misure pratiche e l'AI in locale per proteggere l'azienda."
date: 2026-11-25
category: ai
source: outrank
outrankId: "25d7a053-b376-4ae7-b60b-1f9050a2fa78"
ai: true
---
Il preventivo è quasi pronto. Prima di inviarlo, qualcuno dell'ufficio commerciale incolla il testo in uno strumento gratuito di intelligenza artificiale e chiede di renderlo più chiaro. La frase scorre meglio, il cliente risponde il giorno dopo, nessuno ci fa caso.

Dentro quel documento c'erano il listino riservato, lo sconto applicato a quel cliente e i nomi dei referenti. Sono finiti in una casella di testo che non ha un responsabile, non ha un registro e non si sa bene dove conservi le copie.

L'AI entra nelle PMI italiane così, non da un reparto IT con un progetto formale. La domanda che il titolare pone non è tecnica. Chiede se i dati dell'azienda sono al sicuro. La risposta onesta è che dipende da tre cose, e nessuna riguarda il modello linguistico che genera le frasi. Dipende da **quali dati entrano nel sistema**, da **chi li può vedere** e da **dove restano**. Le tre domande vanno affrontate in quest'ordine.

## Indice
- [Cosa fa un software di intelligenza artificiale con i dati dell'azienda](#cosa-fa-un-software-di-intelligenza-artificiale-con-i-dati-dellazienda)
- [Quali dati sono sensibili in una PMI](#quali-dati-sono-sensibili-in-una-pmi)
  - [Lo stesso dato, tre livelli diversi](#lo-stesso-dato-tre-livelli-diversi)
- [I rischi principali per una PMI che usa l'AI](#i-rischi-principali-per-una-pmi-che-usa-lai)
- [Dove devono restare i dati](#dove-devono-restare-i-dati)
- [Come proteggere i dati in sette passi](#come-proteggere-i-dati-in-sette-passi)
- [Come collaudare il software con domande reali](#come-collaudare-il-software-con-domande-reali)
- [Un progetto pilota su un solo processo](#un-progetto-pilota-su-un-solo-processo)

## Cosa fa un software di intelligenza artificiale con i dati dell'azienda

Un software di intelligenza artificiale in azienda fa una cosa semplice. Legge documenti, dati e messaggi, ne ricava una risposta o una bozza, la restituisce a chi lavora. Tutto il resto è contorno.

Il modo più rapido per capire il rischio è pensare a un nuovo collaboratore a cui viene consegnata la chiave dell'archivio. **La chiave apre tutte le stanze che quel badge consente, non solo quelle che servono al suo lavoro.** Se è la chiave del direttore, il collaboratore leggerà anche i verbali riservati, le offerte non ancora inviate e la contestazione di un cliente scontento. Non per male, semplicemente perché può.

Il punto di partenza è sempre questo passaggio di consegne tra un sistema e una parte dell'archivio aziendale.

![Una donna sorridente che lavora al computer con un assistente virtuale robotico che gestisce vari flussi di dati.](/blog-images/software-intelligenza-artificiale/1.webp)

**Il modello non è il software.** Il modello elabora il linguaggio, riconosce schemi, genera testo. Il software decide quali documenti raggiungono quel modello, con quali permessi e con quale traccia. Quando un titolare chiede dove finiscono i dati, la risposta sta nel secondo pezzo, non nel primo. È per questo che due aziende possono usare lo stesso modello e avere livelli di rischio completamente diversi.

Vale la pena liberarsi di un'idea diffusa: i dati si muovono a ogni richiesta, non solo quando qualcuno carica un file. Aprire l'assistente, formulare una domanda, farsi preparare una bozza, sincronizzare il gestionale. Ognuno di questi gesti è un passaggio di informazione, anche se nessuno ha trascinato niente in una cartella.

La materia prima, del resto, è già in casa. Già nel 2014 il **37,2%** delle imprese italiane usava software ERP per condividere automaticamente informazioni tra aree aziendali e il **28,2%** usava un CRM per gestire i dati dei clienti, secondo la [rilevazione Istat sull'uso delle tecnologie ICT nelle imprese](https://www.istat.it/en/microdata/survey-on-information-and-communication-technology-ict-usage-in-enterprises/). L'AI non crea un archivio nuovo, si siede sopra quello che c'è.

La novità è la velocità con cui si aggiunge un livello sopra quella base. L'Istat rileva che nel 2025 il **16,4%** delle imprese con almeno 10 addetti utilizzava almeno una tecnologia di IA, contro l'8,2% nel 2024 e il 5,0% nel 2023, come emerge dai [dati Istat sull'uso dell'intelligenza artificiale nelle imprese italiane](https://statistiche.bancaditalia.it/argomenti/firms/the-use-of-artificial-intelligence-in-italian-companies). In due anni la quota è più che triplicata e comprende analisi dei dati, automazione, elaborazione del linguaggio e riconoscimento di immagini.

> **La domanda giusta non è se l'AI è sicura.** È quali documenti raggiunge, chi può leggerli e dove restano dopo che la risposta è stata generata.

## Quali dati sono sensibili in una PMI

Prima di discutere dove mettere i dati, serve sapere quali pesano. In una PMI la classificazione si fa in un'ora, con la tabella qui sotto, e vale per qualsiasi strumento, non solo per l'AI.

**Tipi di dato in una PMI e livello di attenzione**

| Tipo di dato | Esempi tipici | Perché è sensibile | Livello di attenzione |
|---|---|---|---|
| Dati personali di clienti e dipendenti | anagrafiche, codici fiscali, contatti, buste paga | obblighi GDPR e sanzioni in caso di perdita o uso improprio | Alto |
| Dati sanitari | referti, cartelle di pazienti, schede di animali collegate a un proprietario | categoria particolare ai sensi del GDPR | Molto alto |
| Listini e condizioni commerciali | listini, sconti riservati, margini, condizioni per fornitori | un concorrente che li conosce erode il vantaggio competitivo | Alto |
| Contratti e offerte in corso | contratti firmati, preventivi non ancora accettati, clausole | vincoli legali e trattative aperte | Alto |
| Dati finanziari e fiscali | bilanci, fatture, IBAN, dichiarazioni | frodi, obblighi fiscali, dati bancari | Alto |
| Know-how tecnico | procedure interne, formule, disegni, ricette | patrimonio difficile da ricostruire se esce | Medio-alto |
| Comunicazioni interne | email, chat di gruppo, verbali di riunione | possono contenere dati personali e giudizi su persone | Medio |

Il livello di attenzione non è una graduatoria morale dei documenti. È un'indicazione su quanto controllo serve prima di collegare quella categoria a un sistema che legge e risponde.

### Lo stesso dato, tre livelli diversi

Un listino prezzi in mano a un serramentista è un documento commerciale serio: contiene sconti per categoria di cliente e margini. In mano a uno studio medico lo stesso foglio vale poco. In una cartella di paziente, invece, poche righe di testo pesano più di cento pagine di listino, perché rientrano nelle categorie particolari del GDPR e richiedono cautele che nessun preventivo richiede.

Le schede degli animali sono il caso che confonde più spesso. Da sole non sono dati sanitari di persone. Diventano dati personali nel momento in cui si collegano al nome del proprietario, e da lì seguono le regole dei dati personali come qualsiasi altra informazione riconducibile a una persona.

C'è poi una categoria che nessuno classifica mai, ed è quella più insidiosa: le comunicazioni interne. Una chat di gruppo tra responsabili contiene giudizi su persone, accordi non scritti, motivi reali di una decisione. Se l'assistente documentale la indicizza insieme ai manuali tecnici, il primo utente che fa una domanda generica può ricevere un pezzo di quella conversazione.

> **Regola pratica:** se non sai indicare chi è il responsabile di un documento, quel documento non è pronto per entrare in un assistente AI.

La sequenza corretta è sempre la stessa: classificare, poi collegare. Un dato che nessuno ha classificato finisce nel sistema quasi sempre per errore, non per scelta.

## I rischi principali per una PMI che usa l'AI

Sette situazioni ricorrono nelle aziende che iniziano a usare l'AI. Ognuna ha un esempio concreto e un segnale d'allarme che si può verificare in mezz'ora, senza competenze tecniche.

1. **Dati inviati a servizi esterni senza sapere dove finiscono.** Il titolare incolla un listino in uno strumento gratuito per farsi riassumere il documento e ottenere una sintesi da girare al commerciale. Segnale d'allarme: nessuno in azienda sa quali strumenti vengono usati né quali condizioni contrattuali hanno.
2. **Permessi troppo ampi.** L'assistente documentale risponde a un addetto vendite citando i verbali riservati della direzione, perché l'indice non distingue i reparti. Segnale d'allarme: tutti gli utenti vedono tutti i documenti.
3. **AI ombra.** Un impiegato usa l'app personale sul telefono per riassumere le email di un cliente e ritrovare un indirizzo. Segnale d'allarme: qualcuno chiede di "usare il telefono" perché sul computer è più complicato.
4. **Risposte basate su documenti obsoleti.** Una scheda tecnica superata di due revisioni finisce dentro un preventivo, con misure che non valgono più. Segnale d'allarme: nessun responsabile sa indicare quale versione sia quella valida né da quando.
5. **Mancanza di tracciabilità.** Nessuno riesce a ricostruire chi ha chiesto cosa e da quale fonte è arrivata una risposta finita in una trattativa. Segnale d'allarme: non esistono registri consultabili.
6. **Approvazione assente.** Una bozza generata dal sistema parte verso il cliente senza che una persona l'abbia letta. Segnale d'allarme: le bozze vengono inviate direttamente dallo strumento.
7. **Dipendenza da un fornitore.** I dati e le elaborazioni stanno in un formato che non si riesce a esportare, e cambiare strumento significherebbe ricominciare da zero. Segnale d'allarme: il contratto non prevede l'esportazione completa.

Vale la pena notare una asimmetria. I rischi dal numero quattro al sei non hanno nulla a che vedere con la tecnologia scelta: nascono da come è organizzato il lavoro. Una scheda obsoleta resta obsoleta anche in un sistema perfetto, e una bozza senza approvazione resta una bozza senza approvazione.

> **Il segnale d'allarme più affidabile è sempre lo stesso.** Se nessuno in azienda sa rispondere alla domanda su chi usa quale strumento con quali dati, il problema esiste già, prima ancora dell'AI.

Molti di questi rischi si correggono con regole chiare, non con software aggiuntivo. Ed è per questo che la decisione su dove stanno i dati arriva dopo, mai prima.

## Dove devono restare i dati

Pensiamo a due modi di avere un consulente. Con il **cloud generico** si telefona a un esperto esterno: pratico, disponibile subito, e per parlargli bisogna raccontargli il problema, con i dettagli del caso. Con il **sistema in locale** il consulente sta in ufficio, siede a un tavolo e consulta solo gli schedari che gli sono stati assegnati, senza portare niente fuori dalla porta.

![Confronto tra i modelli di archiviazione dati su cloud generico e sistema in locale per aziende.](/blog-images/software-intelligenza-artificiale/2.webp)

Il modello AI può girare in locale, sui computer o su un server dentro l'azienda, e i dati non escono dall'impresa. È la differenza architetturale che conta più di qualsiasi elenco di funzioni.

**Servizio cloud generico e AI in locale a confronto**

| Aspetto | Servizio cloud generico | AI in locale |
|---|---|---|
| Dove viaggiano i dati | server del fornitore, spesso fuori dall'azienda | computer o server interno all'impresa |
| Controllo dei permessi | impostato dal fornitore, con margini limitati | definito dall'azienda per ruolo e reparto |
| Tracciabilità | dipende dal contratto e dalle funzioni disponibili | log di domande, fonti e approvazioni conservati in azienda |
| Manutenzione | in gran parte a carico del fornitore | richiede backup, aggiornamenti e un responsabile interno |
| Caso d'uso adatto | domande generiche su informazioni pubbliche | documenti riservati, listini, dati di clienti |

Il confronto aiuta a capire anche il punto di integrazione. L'Istat rileva che il **56,0%** delle imprese utilizza almeno un software aziendale tra ERP, CRM o Business Intelligence, rispetto al 48,7% del 2023, secondo il [comunicato Istat su imprese e ICT per l'anno 2025](https://www.istat.it/comunicato-stampa/imprese-e-ict-anno-2025/). Un assistente collegato a questi sistemi prepara una bozza di offerta o aggiorna la scheda cliente senza ricopiatura manuale. Un'applicazione separata, invece, moltiplica le duplicazioni e produce dati incoerenti tra un archivio e l'altro.

L'esecuzione in locale riduce l'invio di documenti all'esterno, ma non è gratuita in termini di attenzione. Servono backup regolari, un responsabile interno che controlli accessi e aggiornamenti, e un piano per il giorno in cui quella persona è in ferie.

Il cloud resta la scelta ragionevole per un uso diverso: domande generiche, riassunti di testi pubblici, idee su una comunicazione. Nessuno deve rinunciarci. Deve solo smettere di essere il posto dove finisce un listino riservato.

Lo stesso confronto, raccontato a voce, in questo breve video.

[Guarda il video su YouTube](https://www.youtube.com/watch?v=8OzhUt-i5B0)

Prima di firmare con un fornitore cloud, cinque domande hanno una risposta verificabile nel contratto.

- **Dove vengono conservati i dati**, in quale paese e presso quale infrastruttura.
- **Se il trattamento è conforme al GDPR**, con un accordo scritto che lo dichiari.
- **Se i dati aziendali servono ad addestrare il modello**, e in caso affermativo con quale possibilità di opporsi.
- **Quali log sono disponibili**, per quanto tempo e con quale livello di dettaglio.
- **In quale formato si possono esportare** documenti, indici e storico delle domande.

La regola che tiene insieme tutto: più il documento è riservato, più il sistema che lo legge dovrebbe restare sotto il controllo dell'azienda.

## Come proteggere i dati in sette passi

La sequenza seguente funziona in una PMI da venti persone come in uno studio professionale. Ogni passo ha un motivo e un errore tipico che lo rende inutile.

La figura qui sotto riassume il percorso completo.

![Una procedura in sette passi illustrata per guidare le aziende nella protezione e gestione sicura dei dati.](/blog-images/software-intelligenza-artificiale/3.webp)

**1. Mappare i dati e assegnare il livello di attenzione.** Si parte da un workshop con chi lavora sui processi, più qualche intervista, per capire dove stanno i documenti e chi li usa davvero. L'errore tipico è farlo fare solo al titolare, che conosce i documenti ufficiali e ignora quelli veri, cioè le cartelle sul desktop del commercialista e il gruppo WhatsApp dei responsabili.

**2. Definire chi può vedere cosa, per ruolo e reparto.** Prima di collegare qualsiasi documento all'assistente, non dopo. Il permesso lasciato aperto "per comodità, tanto siamo in pochi" è la causa più frequente di una risposta che non doveva uscire.

**3. Scegliere dove gira il software in base alla riservatezza dei dati.** Se il sistema legge listini, cartelle o contratti, la scelta si restringe. Se serve solo per bozze di comunicazioni generiche, il cloud va benissimo ed è più rapido da adottare.

**4. Scrivere una regola semplice per i dipendenti.** Una pagina, non un manuale: quali strumenti si possono usare, con quali dati, e cosa non si carica mai. La regola comunicata a voce e mai messa per iscritto viene dimenticata in due settimane.

**5. Attivare log, backup e aggiornamenti con un responsabile indicato per nome.** Senza una persona incaricata, i registri si accumulano e nessuno li guarda. Il rischio qui è silenzioso: tutto sembra funzionare finché un giorno serve ricostruire cosa è successo e non c'è niente da leggere.

**6. Formare il personale con esempi reali dell'azienda.** Prendere un preventivo vero, una email vera, una scheda tecnica vera, e mostrare cosa sarebbe successo con una domanda diversa. Il messaggio da far passare è uno: l'AI propone, la persona decide e firma.

**7. Rivedere le regole ogni sei mesi**, o prima se cambia un processo, un fornitore o un reparto. L'errore più comune è considerare la classificazione un lavoro fatto una volta per sempre. Cambia un listino, entra un collaboratore, si chiude un contratto con un nuovo fornitore, e i permessi di ieri non descrivono più l'azienda di oggi.

Una nota sul passo uno, che è quello che quasi tutti saltano. Vale la pena farlo con metodo, perché la mappatura non serve solo all'AI: serve a capire chi dipende da quale informazione e quanto l'azienda sia esposta se quella persona si assenta per un mese.

## Come collaudare il software con domande reali

La verifica non si fa sulle brochure. Si fa ponendo al sistema le domande che il personale pone ogni giorno, e osservando cosa restituisce.

La tecnologia più diffusa in questo momento è l'analisi dei documenti di testo. Secondo i primi risultati del Censimento permanente delle imprese, nel 2025 il **18,8%** delle imprese italiane con almeno 10 addetti utilizzava tecnologie AI dedicate all'analisi dei documenti di testo, come riporta il [comunicato Istat sui primi risultati del Censimento permanente delle imprese](https://www.istat.it/wp-content/uploads/2026/10/CS_Cens_imprese2025.pdf). È il caso d'uso più maturo, e anche il più esposto, perché lavora direttamente sull'archivio.

Il funzionamento si spiega in tre passaggi. I documenti vengono indicizzati, cioè ridotti a porzioni consultabili. Quando arriva una domanda, il sistema recupera le porzioni pertinenti. Il modello genera poi una risposta vincolata a quel contenuto, senza inventare liberamente. Questa catena si chiama ricerca aumentata da recupero, o RAG.

Qui entra in gioco un dettaglio che molti trascurano. Se l'indicizzazione conserva i metadati di reparto, versione, data di validità e livello di riservatezza, il sistema può limitare la ricerca ai documenti autorizzati per quell'utente. Se i metadati non ci sono, il sistema non ha modo di distinguere la procedura valida da quella superata, né un verbale della direzione da un manuale tecnico.

**Verifiche prima di affidare dati a un software AI**

| Verifica | Come eseguirla | Risultato da pretendere |
|---|---|---|
| Correttezza della risposta | confrontare la risposta con il documento originale | risposta coerente con il testo, senza invenzioni |
| Presenza della fonte | chiedere su quale documento si basa la risposta | titolo, versione e data del documento indicati |
| Informazione mancante | fare una domanda su un dato assente dall'archivio | il sistema ammette di non sapere, senza inventare |
| Rispetto dei permessi | far chiedere a un utente non autorizzato un dato riservato | accesso negato e nessuna traccia del dato nella risposta |
| Dove restano i dati | verificare che durante l'uso non partano invii verso servizi esterni | nessun trasferimento verso l'esterno non previsto |

La riga più importante è la terza. Un sistema che ammette di non sapere è più affidabile di uno che risponde sempre, perché il personale impara a fidarsi dei casi in cui la risposta arriva con la fonte.

Un ultimo avvertimento sul metodo. Un collaudo superato su dieci domande scelte dal titolare non dimostra nulla, perché quelle dieci domande sono le più facili e le più note. Il test va ripetuto con utenti diversi, compreso quello che lavora da meno tempo e che formulerà le domande nel modo meno prevedibile.

## Un progetto pilota su un solo processo

La tentazione, dopo aver letto tutto questo, è fermarsi. La tentazione opposta è partire in grande. Nessuna delle due conviene.

Conviene scegliere **un solo processo**: la ricerca di documenti tecnici, la preparazione di un preventivo, l'inserimento delle email nel CRM. Il percorso parte dalla mappatura dei dati e dei processi, misura la situazione attuale, introduce l'AI su quel processo e misura di nuovo i risultati. La misurazione prima e dopo è ciò che distingue un pilota da una prova generica.

Le tappe di un percorso AI sono cinque: **Analisi, Progetto pilota, Sviluppo, Crescita** e **La vetta**, quest'ultima facoltativa. Le tappe di ogni progetto, però, si definiscono insieme dopo il primo incontro, sulla base dei processi e dei dati dell'azienda, perché due imprese dello stesso settore raramente hanno lo stesso punto di partenza.

Su questo terreno Creattiva, azienda di Milano che sviluppa software e soluzioni AI per le imprese italiane, affianca l'analisi e il progetto pilota, con modelli che girano sul server del cliente e risposte che indicano la fonte documentale utilizzata.

Prima della riunione, tre domande valgono più di un preventivo: **quale processo** fa perdere più tempo, **quali dati** tocca, **chi approva** il risultato prima che esca dall'azienda. Se le risposte sono tre, si può iniziare. Se sono confuse, il pilota servirebbe solo a confondere meglio.

---

Se vuoi capire da dove partire senza impegnare l'intera organizzazione, Creattiva analizza i processi e i dati della tua azienda e avvia un progetto pilota su un solo processo, con modelli AI che lavorano sul tuo server e risposte che indicano sempre la fonte. Il punto di partenza è un incontro in cui mettiamo sul tavolo documenti, permessi e responsabilità prima di parlare di tecnologia. Puoi vedere come lavoriamo e richiedere un primo confronto visitando [Creattiva](https://www.creattiva.com).
