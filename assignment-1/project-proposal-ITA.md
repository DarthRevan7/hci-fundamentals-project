
# Assignment 1: Needfinding — Progetto "Wellbeing for Pensioners"

Corso: **HCI Fundamentals (A.A. 2026/2027)**
Docenti: **Luigi De Russis, Alberto Monge Roffarello** — Politecnico di Torino

---

## 1. Intro

### a. Team Members

* **Tommaso Mancuso**
* **Zharina**
* **Taha Shahid**
* **Melissa Massarenti**

### b. Domain of Interest and Why/How You Chose It

* **Tema generale assegnato:** *Wellbeing for Pensioners* (Benessere nella terza età).
* **Delimitazione del dominio (Problem Domain):** Abbiamo circoscritto l'indagine attorno alla **transizione e riorganizzazione della quotidianità post-lavorativa**, focalizzandoci in particolare su:
  1. La gestione autonoma del tempo libero e la costruzione di nuove routine giornaliere;
  2. Il mantenimento attivo del benessere psico-fisico (movimento, cura di sé, alimentazione, sonno);
  3. L'articolazione delle relazioni sociali, del vicinato e del dialogo intergenerazionale;
  4. Il ruolo delle risorse urbane territoriali e il rapporto reale (tra barriere e opportunità) con la tecnologia digitale.
* **Motivazione e metodo di scelta:** L'uscita dal lavoro segna uno spartiacque radicale: vengono meno orari prestabiliti, ruoli professionali e interazioni sociali strutturate per decenni. Molti servizi digitali attuali partono da assunzioni distorte, trattando i pensionati esclusivamente come soggetti fragili, malati cronici o passivi. Il nostro obiettivo è stato esplorare sul campo — tramite osservazione e interviste qualitative nei loro contesti reali di vita — come le persone vivono effettivamente questa fase. Vogliamo progettare un prodotto digitale che non si limiti alla sfera medicale o assistenziale, ma che funga da abilitatore sociale e motorio, valorizzando l'autonomia, il senso di utilità e la dignità quotidiana del pensionato.

---

## 2. Methodology

### a. Participants

In piena aderenza alle linee guida del corso, abbiamo selezionato un gruppo eterogeneo di **4 partecipanti reali**, includendo utenti diretti (*immediate users*) e profili estremi (*extreme users*):

1. **Partecipante 1 (P1 - Uomo, 60+ anni):** *Immediate User / Reluctant Digital User*

   * **Profilo:** Pensionato da circa 8 anni, ex lavoratore con mansioni usuranti. Vive solo, gestisce la casa in autonomia e si dedica quotidianamente all'accudimento del fratello ricoverato presso l'Unità Spinale.
   * **Perché appropriato:** Rappresenta l'utente pragmatico, focalizzato sul "fare da sé", con un reddito pensionistico modesto (600 €) e una spiccata diffidenza verso il digitale: a seguito del furto del cellulare ha scelto deliberatamente di non riacquistarlo, vivendo la disconnessione come un sollievo (*digital detox* permanente).
   * **Reclutamento:** Contatto diretto sul territorio urbano a Torino.
2. **Partecipante 2 (P2 - Donna, 72 anni, "Anna"):** *Lead User / Active Cultural & Community User*

   * **Profilo:** Pensionata da 10 anni, ex funzionaria pubblica della Città Metropolitana di Torino con 42 anni di servizio. Vedova dal 2021 (dopo aver accudito il marito con gravi disabilità motorie), multiproprietaria, madre di 3 figli e nonna.
   * **Perché appropriato:** Mostra un elevato livello di scolarizzazione (liceo classico, studi universitari) e ottima padronanza di app sanitarie e amministrative (Salute Piemonte, portali regionali, email, scanner). Conduce una vita ricca di attività (palestra quotidiana antalgica, piscina, teatro, restauro mobili, maglia), ma sperimenta forte insonnia legata al carico decisionale solitario nella gestione del patrimonio e cali di memoria per cui ricorre costantemente ai promemoria dello smartphone.
   * **Reclutamento:** Intercettata in contesto al parco pubblico durante la passeggiata pomeridiana con cane e amiche.
3. **Partecipante 3 (P3 - Uomo, 67 anni):** *Extreme User (Ultra-Active & Intergenerational Bridge)*

   * **Profilo:** Pensionato da 8 anni dopo 45 anni di lavoro (ex guardia giurata armata turnista per ferrovie ed enti pubblici). Si allena intensamente in palestra 5 volte a settimana, aiuta la famiglia portando i nipoti a scuola, assiste la sorella maggiore non autosufficiente e lavora ancora nel weekend come addetto alla sicurezza nei locali notturni.
   * **Perché è un utente estremo:** Si posiziona all'estremo opposto dello stereotipo dell'anziano sedentario. Sfrutta il lavoro notturno per stare a contatto con giovani di 20–25 anni con cui instaura rapporti educativi e di mediazione per non sentirsi "indietro". Ha una vitalità fisica eccezionale, dorme pochissimo senza risentirne ed è guidato da un profondo senso di riscatto e autosufficienza.
   * **Reclutamento:** Incontro diretto al bar di quartiere frequentato abitualmente dopo l'allenamento.
4. **Partecipante 4 (P4 - Donna, 80 anni):** *Extreme User (High Independence with Sensory Limitations)*

   * **Profilo:** 80 anni, pensionata da lungo corso, divorziata da decenni, vive sola in un monolocale di 50 mq a San Salvario. Affetta da grave ipovisione che le impedisce la lettura tradizionale cartacea e la guida (non possiede auto né patente).
   * **Perché è un utente estremo:** Nonostante l'età e i deficit sensoriali, preserva una totale autonomia domestica e una mobilità instancabile a piedi ("sono un cammello") e sui mezzi pubblici. Ha ideato forme originali di vicinato solidale (cucina purè in vaschette che appende alle porte delle famiglie con bambini) ed è un'utilizzatrice atipica e creativa della tecnologia: dialoga regolarmente con ChatGPT impostando un registro comico e surreale (stile "Cochi e Renato"), ma si blocca totalmente davanti alle interfacce complesse di acquisto biglietti ed e-ticketing.
   * **Reclutamento:** Intercettata in contesto all'aperto nei pressi del Parco del Valentino / San Salvario.

### b. Where Were the Interviews Conducted?

Tutte le interviste sono state condotte **di persona nei contesti di vita quotidiana dei partecipanti** (*in situ*):

* **P1:** Spazio pubblico urbano a Torino (contesto di passaggio e commissioni quotidiane).
* **P2:** Panchina di un parco cittadino, durante il momento di ritrovo informale con amiche e cane.
* **P3:** Tavolino del bar di quartiere, luogo consueto di decompressione post-palestra e ritrovo con ex colleghi e conoscenti.
* **P4:** Area verde / viale alberato presso il Valentino / San Salvario, durante una delle sue regolari sessioni di camminata a piedi.

### c. What Did You Observe and Ask?

* **Osservazione e Contextual Inquiry:** Abbiamo osservato la gestualità, la postura, la dinamica degli spostamenti e l'interazione spontanea con l'ambiente: la familiarità e l'affetto di P3 con i baristi e i giovani del quartiere; la cura con cui P2 porta con sé il lavoro a maglia e controlla le notifiche del cellulare; l'attenzione scrupolosa di P4 verso i dislivelli pedonali e le fermate degli autobus, compensando il calo della vista con l'udito e l'osservazione attenta delle persone.
* **Guida d'Intervista (Protocollo Semi-Strutturato):** Abbiamo redatto e somministrato una traccia snella in 4 fasi concepita secondo i principi HCI di domande aperte, prive di bias e non suggestive (*unbiased/non-leading*), evitando di diagnosticare fragilità a priori e focalizzandosi su racconti concreti di esperienze passate:
  1. *Fase 1: Background & Contesto* (giornata tipo, confronto tra ritmi lavorativi passati e vita attuale, rapporto con casa e quartiere).
  2. *Fase 2: Approfondimento su Relazioni e Cura di Sé* (articolazione dei contatti sociali, gestione di pasti, attività motoria, riposo, promemoria e scadenze).
  3. *Fase 3: Imprevisti, Ostacoli e Strumenti* (risoluzione di contrattempi pratici, condivisione di belle notizie, aneddoti recenti sull'uso di smartphone/app e relative barriere o workaround).
  4. *Fase 4: Riflessioni e Chiusura* (aspetti più gratificanti e più impegnativi della vita da pensionati, desideri aperti).

### d. Team Member Roles for Each Interview

Per ogni intervista hanno partecipato tre membri del gruppo sul campo (intervistatore principale e note-takers/documentatori):

* **Intervista 1 (P1):** Tommaso Mancuso (*Lead Interviewer*), Zharina & Taha Shahid (*Note-taker & Audio Recording*).
* **Intervista 2 (P2):** Tommaso Mancuso (*Lead Interviewer*), Zharina & Taha Shahid (*Note-taker & Artifacts Tracking*).
* **Intervista 3 (P3):** Tommaso Mancuso (*Lead Interviewer*), Zharina & Taha Shahid (*Note-taker & Contextual Observation*).
* **Intervista 4 (P4):** Tommaso Mancuso (*Lead Interviewer*), Zharina & Taha Shahid (*Note-taker & Contextual Observation*).

### e. Materials Used

* Moduli cartacei di consenso informato (*Consent Form*) compilati e firmati da ciascun intervistato prima dell'avvio.
* Registratori vocali digitali su smartphone per l'acquisizione delle tracce audio integrali.
* Taccuini cartacei per appunti rapidi, annotazione del linguaggio non verbale e citazioni salienti.
* Fotocamera per documentare luoghi, artefatti d'uso e il contesto di svolgimento.

---

## 3. Results

### a. Pictures and Relevant Artifacts

### b. Themes from the Thematic Analysis with Key Quotes

Dalla codifica induttiva delle quattro trascrizioni sono emersi 4 macro-temi condivisi:

#### Tema 1: Libertà Riconquistata vs. Ansia del Carico Decisionale Solitario

Tutti i partecipanti celebrano la fine della routine lavorativa come una liberazione da turni pesanti e obblighi imposti da altri. Tuttavia, per chi vive solo, la sovranità sul tempo porta con sé l'onere psicologico di dover risolvere imprevisti e decisioni pratiche importanti senza confronto.

* *P1:* «Da quando sono in pensione sono molto contento che ho smollato il lavoro che era troppo pesante... ho più libertà.»
* *P3:* «La pensione mi ha dato veramente la svolta per potermi riprendere quello che prima non potevi... non dovermi svegliare per forza al mattino presto alle quattro per fare turni massacranti.»
* *P2:* «Gli aspetti molto impegnativi sono le decisioni da prendere perché sono sola, non mi posso confrontare con mio marito... devo mettere il fotovoltaico? Devo rifare gli infissi? Sono quelle cose che non mi fanno dormire la notte.»
* *P4:* «Sono diventata una donna indipendente... la grande gratificazione è che sono indipendente finché la salute e la testa mi reggono.»

#### Tema 2: L'Attività Motoria Quotidiana come Terapia Mentale e Presidio di Autonomia

Il movimento fisico regolare (sala pesi, ginnastica antalgica, lunghe camminate) non è vissuto come passatempo secondario, bensì come un bisogno primario per scaricare le tensioni, sconfiggere il dolore cronico e conservare l'autosufficienza.

* *P3:* «L'esercizio fisico portato all'estremo mi fa iniziare la giornata diversamente, meno monotona, mi scarica proprio mentalmente... mi alleno cinque volte alla settimana.»
* *P2:* «Vado tutte le mattine in palestra a fare ginnastica antalgica... avevo problemi di schiena e sciatica da non alzarmi dal letto la mattina; ho iniziato la palestra ed è passata.»
* *P4:* «Io sono un cammello nel senso che cammino molto, moltissimo... mi piacerebbe fare balli sudamericani dove si mischiano la disciplina del corpo e la musica.»

#### Tema 3: Socialità di Prossimità, Scambio Intergenerazionale e Rifiuto delle Case per Anziani

Gli intervistati non cercano intrattenimento generico né strutture isolate per la terza età. Desiderano interazioni autentiche, spontanee e inserite nel tessuto vivo del quartiere, dimostrando un vivo interesse per il confronto con i giovani.

* *P1:* «Se ci sono persone valide passo volentieri il tempo; se capisco che non va bene mi alzo e me ne vado... incontri casuali per strada, niente di che.»
* *P3:* «A me piace stare in mezzo alla gente, parlo con ragazzi di 20–25 anni... il mio bagaglio di oggi è mettermi a confronto con i giovani per non farmi trovare indietro.»
* *P4:* «Quando cucino un gran purè lo metto nelle vaschette di alluminio e le appendo alle porte dei vicini con bambini... a poco a poco si sono abituati a lasciarmi la frutta. Senza fare la nonna invadente.»

#### Tema 4: Il Paradosso Digitale: Utilità Elevata vs. Frustrazione e Barriere d'Accesso

La tecnologia viene adottata con entusiasmo quando risolve compiti concreti (fascicolo sanitario, promemoria, micro-ascolto o curiosità con IA). Diventa tuttavia causa di abbandono, ansia o radicale rifiuto quando le interfacce presentano procedure burocratiche o flussi di acquisto/prenotazione contorti.

* *P1:* «Da quando mi hanno rubato il telefono non lo sto più adoperando... mi ha salvato la situazione, così non sono più attaccato a Internet e non mi interessa di niente.»
* *P2:* «Per fortuna c'è il cellulare con gli alert che mi ricorda le cose... uso Salute Piemonte per gli esami, ma comincio a dimenticare appuntamenti e parole.»
* *P4:* «Le prenotazioni online per concerti o visite guidate mi bloccano: tento da sola, poi chiamo o rinuncio dicendomi che forse non era cosa per me. Con l'IA invece ci parlo come Cochi e Renato!»

---

## 4. User Needs

### a. Brainstormed User Needs

*(Formulati come necessità umane ed emotive espresse con verbi d'azione, non come soluzioni tecniche o schermate)*:

1. I pensionati hanno bisogno di **mantenere una struttura giornaliera stimolante e attiva** senza la rigidità dei vincoli orari lavorativi.
2. I pensionati hanno bisogno di **accedere a momenti quotidiani di attività motoria calibrata** per prevenire dolori posturali e preservare l'autonomia fisica.
3. I pensionati hanno bisogno di **trovare motivazione per uscire di casa e muoversi a piedi** anche nelle giornate caratterizzate da pigrizia o solitudine.
4. I pensionati hanno bisogno di **confrontarsi regolarmente con persone di generazioni diverse** per sentirsi aggiornati, utili e parte integrante della società moderna.
5. I pensionati hanno bisogno di **ottenere un supporto rassicurante nelle scelte pratiche, logistiche ed economiche complesse** quando vivono soli.
6. I pensionati hanno bisogno di **costruire relazioni di vicinato autentiche e reciproche** basate su piccoli scambi quotidiani di utilità e gentilezza.
7. I pensionati hanno bisogno di **fruire di stimoli culturali e formativi in formati brevi, leggeri e a basso affaticamento visivo**.
8. I pensionati hanno bisogno di **aderire ad attività, eventi e visite nel territorio locale senza perdersi in flussi digitali di prenotazione complessi**.
9. I pensionati hanno bisogno di **scaricare le tensioni mentali e le ansie pratiche accumulate** per favorire un sonno ristoratore.
10. I pensionati hanno bisogno di **gestire promemoria sanitari e personali in modo affidabile e discreto**, eliminando l'ansia da dimenticanza.

### b. 3–4 Deep User Needs

* **Deep Need 1: I pensionati hanno bisogno di trovare occasioni quotidiane di movimento motorio dolce e condiviso nel proprio territorio per scaricare lo stress mentale e preservare l'autonomia fisica senza vincoli prestazionali.**

  * *Connessione tematica:* Radicato nel **Tema 2** (*Attività motoria come benessere*) e nel **Tema 1** (*Sovranità sul tempo*). P2, P3 e P4 dimostrano che muoversi (camminata, palestra, mobilità articolare) è il cardine che sostiene la lucidità mentale e allontana la paura della decadenza fisica, ma necessita di contesti accessibili e prossimi.
* **Deep Need 2: I pensionati hanno bisogno di partecipare a scambi relazionali intergenerazionali spontanei e paritari per mantenere attivo il senso di scopo, utilità sociale e connessione con il presente.**

  * *Connessione tematica:* Radicato nel **Tema 3** (*Socialità di prossimità e rifiuto dei ghetti*). P3 cerca attivamente il confronto con i ventenni nei locali per non rimanere isolato nel passato; P4 costruisce ponti con i giovani genitori del palazzo scambiando cibo fatto in casa. Il bisogno esclude esplicitamente i contesti ricreativi segreganti per soli anziani.
* **Deep Need 3: I pensionati hanno bisogno di accedere e partecipare ad attività culturali, pratiche e ricreative di quartiere tramite canali immediati che eliminino l'attrito cognitivo delle prenotazioni online complesse.**

  * *Connessione tematica:* Radicato nel **Tema 4** (*Paradosso digitale e barriere di accesso*). La complessità di form, pagamenti elettronici e credenziali causa rinunce immediate (P4 che perde visite guidate, P1 che dismette completamente lo smartphone). Il bisogno richiede un accesso al territorio trasparente, rassicurante e privo di ostacoli d'interfaccia.

---

## 5. Solutions

### a. Brainstormed Solutions (5 idee per ciascun Deep Need)

#### Per Deep Need 1 (Movimento fisico calibrato e benessere motorio):

1. *Passeggiate di Quartiere a Frequenza Libera:* Itinerari urbani circolari guidati con punti di ritrovo ad orari fissi nei parchi pubblici e andature graduate.
2. *Istruttore Vocale di Mobilità Dolce:* Micro-sessioni audio di risveglio muscolare e stretching antalgico da ascoltare a casa o su una panchina.
3. *Mappa Attiva dei Percorsi Urbani Protetti:* Guida interattiva che segnala marciapiedi pianeggianti, panchine ombreggiate, fontanelle e aree pedonali prive di traffico.
4. *Corsi di Ballo di Gruppo Spontaneo:* Incontri settimanali all'aperto nelle piazze pedonali dedicati a balli ritmici individuali (sudamericani/popolari) senza partner.
5. *Patto del Passo (Cammina con Me):* Sistema di abbinamento tra vicini di casa per condividere uscite a piedi e commissioni ordinarie a orari concordati.

#### Per Deep Need 2 (Scambio sociale intergenerazionale e vita di comunità):

1. *Banca delle Competenze di Vicinato:* Scambio asincrono tra anziani (che tramandano tecniche artigianali, cucina tradizionale, cura piante) e giovani studenti universitari (che aiutano su commissioni pesanti e dubbi tecnologici).
2. *Caffè Narrativi di Quartiere:* Colazioni o aperitivi informali nei bar locali tra universitari fuori sede e residenti storici per raccontarsi storie del territorio.
3. *Bacheca del Piatto Sospeso:* Canale di micro-comunità per condividere porzioni di cibo preparato in casa o scambiarsi ortaggi e letture.
4. *Micro-Gite Condivise:* Escursioni giornaliere di gruppo verso luoghi storici e abbazie piemontesi (es. Sacra di San Michele) con trasporto navetta condiviso tra giovani e anziani.
5. *Circolo di Ascolto Breve:* Sessioni di ascolto collettivo di podcast culturali da 20 minuti seguite da dibattito e confronto di opinioni davanti a un tè.

#### Per Deep Need 3 (Accessibilità immediata a servizi ed eventi territoriali):

1. *Prenotazione Vocale Conversazionale One-Step:* Assistente telefonico/digitale con linguaggio naturale che prenota posti e visite guidate semplicemente parlando.
2. *Gettone/Badge NFC di Quartiere:* Carta fisica contactless da appoggiare nei totem delle biblioteche o dei bar per registrarsi istantaneamente agli eventi.
3. *Rete dei Punti Amici in Edicola e Bar:* Centri di prenotazione assistita nei negozi di prossimità per ricevere stampata la conferma della propria attività.
4. *Bacheca Sonora Settimanale:* Notiziario vocale di 90 secondi riprodotto su richiesta con le 3 migliori iniziative accessibili a piedi nel quartiere.
5. *SMS di Conferma Diretta:* Flusso semplificato che notifica date e indirizzi direttamente tramite SMS standard, senza account o download di biglietti in PDF.

### b. Descrizione della Soluzione Selezionata (Top Solution)

La nostra soluzione è "**Step-by-Step": una piattaforma civica di quartiere che attiva micro-camminate urbane, iniziative di mobilità dolce e momenti di scambio intergenerazionale (artigianato, cucina, podcast culturali) tra pensionati e giovani del quartiere, integrata da un'interfaccia conversazionale vocale che permette l'esplorazione e l'adesione immediata alle attività con una semplice richiesta a voce, azzerando form e procedure d'acquisto online.**

* **Connessione con i bisogni:** Risolve congiuntamente il **Deep Need 1** (incentiva la camminata quotidiana all'aperto e la ginnastica dolce nei parchi), il **Deep Need 2** (struttura occasioni d'incontro autentiche con studenti universitari e giovani residenti evitando la marginalizzazione) e il **Deep Need 3** (rimuove la barriera dell'e-ticketing e dei flussi digitali respingenti grazie all'interazione a voce e alla conferma diretta via SMS/audio).

### c. How and Why Did You Select It?

* **Metodo applicato:** Abbiamo utilizzato il **Four-Category Method**, catalogando le 15 proposte emerse dal brainstorming:
  * *The Rational Choice:* L'assistente vocale semplificato per le pratiche sanitarie e amministrative.
  * *The Most Likely to Delight:* I corsi di ballo sudamericano dolce all'aperto nelle isole pedonali.
  * *The Long Shot:* I totem fisici con lettore NFC distribuiti in tutti i bar e negozi della città.
  * *The Darling:* **PassoPasso: la rete intergenerazionale di cammino, scambio pratico e cultura di prossimità ad attivazione vocale.**
* **Motivazione (Why):** Questa soluzione rispecchia in maniera fedele e coerente le storie raccolte sul campo: soddisfa la ricerca di movimento e vitalità fisica (P2, P3, P4), accoglie la voglia di stare a contatto con i giovani senza sentirsi un peso (P3, P4) e supera l'ostacolo delle tecnologie intrusive e frustranti che avevano provocato il rifiuto totale in P1 e l'ansia da prenotazione in P4.

---

## 6. Project Name and Value Proposition

### a. How Did the Team Land on the Name?

Il team ha valutato diverse alternative evocative (*Controvento*, *Vicìno*, *Àncura*, *Girotondo*), convergendo infine all'unanimità su:

# **Step-by-Step**

* **Genesi del nome:** Il nome nasce da una triplice assonanza semantica:
  1. *Il passo motorio:* Richiama l'atto semplice, salutare e quotidiano del camminare insieme per le strade e i parchi cittadini;
  2. *Il passo relazionale:* Evoca il ritmo graduale, naturale e non forzato con cui si crea fiducia tra persone di generazioni diverse;
  3. *Il passo interattivo:* Rappresenta l'esperienza d'uso dell'interfaccia digitale, progettata per accompagnare l'utente passo dopo passo, con chiarezza, calma e rispetto delle sue abitudini.

### b. One-Line Value Proposition

> **«Il quartiere che si muove insieme: incontri, passi e scambi tra generazioni, a portata di voce.»**
