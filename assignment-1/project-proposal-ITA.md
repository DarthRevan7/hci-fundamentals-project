
# Assignment 1: Needfinding — Progetto "Wellbeing for Pensioners"

Corso: **HCI Fundamentals (A.A. 2026/2027)**

Docenti: **Luigi De Russis, Alberto Monge Roffarello** — Politecnico di Torino

## 1. Intro

### a. Team Members

* **Tommaso Mancuso**
* **Zharina Saden**
* **Taha Shahid**
* **Melissa Massarenti**

### b. Domain of Interest and Why/How You Chose It

* **Tema generale assegnato:** *Wellbeing for Pensioners* (Benessere nella terza età).
* **Delimitazione del dominio (Problem Domain):** Abbiamo circoscritto l'indagine attorno alla **transizione e riorganizzazione della quotidianità post-lavorativa**, focalizzandoci in particolare su:

  1. La gestione autonoma del tempo libero e la costruzione di nuove routine giornaliere;
  2. Il mantenimento attivo del benessere psico-fisico (movimento dolce, cura di sé, alimentazione, sonno);
  3. L'articolazione delle relazioni sociali, del vicinato e del dialogo intergenerazionale;
  4. Il ruolo delle risorse urbane territoriali e il rapporto reale (tra barriere e opportunità) con la tecnologia digitale.
* **Motivazione e metodo di scelta:** L'uscita dal lavoro segna uno spartiacque radicale: vengono meno orari prestabiliti, ruoli professionali e interazioni sociali strutturate per decenni. Molti servizi digitali attuali partono da assunzioni distorte, trattando i pensionati esclusivamente come soggetti fragili, malati cronici o passivi. Il nostro obiettivo è stato esplorare sul campo — tramite osservazione e interviste qualitative nei loro contesti reali di vita — come le persone vivono effettivamente questa fase. Vogliamo progettare un prodotto digitale che non si limiti alla sfera medicale o assistenziale, ma che funga da abilitatore sociale e motorio, valorizzando l'autonomia, il senso di utilità e la dignità quotidiana del pensionato.

## 2. Methodology

### a. Participants

In piena aderenza alle linee guida del corso, abbiamo selezionato un gruppo eterogeneo di **5 partecipanti reali**, includendo utenti diretti (*immediate users*) e profili estremi (*extreme users*):

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
5. **Partecipante 5 (P5 - Donna, pensionata):** *Immediate User (Leisure-Oriented, Low-Pace & Tech-Frustrated)*

   * **Profilo:** Pensionata da tempo dopo una carriera in ambito impiegatizio/lavorativo noioso e routinario. Vive da sola in centro/zona semi-centrale, non possiede auto per scelta economica, ama la lentezza mattutina, segue lezioni di Pilates online per non dover andare in palestra, legge giornali e libri cartacei, fa attenzione alla spesa al mercato contadino e difende il proprio diritto a "non fare niente".
   * **Perché appropriato:** Rappresenta una figura emblematica del neopensionato non iper-attivo: si autodefinisce pigra, rifiuta l'ansia da prestazione delle agende piene e ha un rapporto fortemente conflittuale con smartphone e siti web (preferisce i vecchi stradari cartacei rispetto a Google Maps, non sopporta le app che sostituiscono i siti e trova frustranti le interfacce generiche che chiedono "è stata utile questa pagina?").
   * **Reclutamento:** Intercettata in contesto urbano di quartiere / bar-pasticceria.

### b. Where Were the Interviews Conducted?

Tutte le interviste sono state condotte **di persona nei contesti di vita quotidiana dei partecipanti** (*in situ*):

* **P1:** Spazio pubblico urbano a Torino (contesto di passaggio e commissioni quotidiane).
* **P2:** Panchina di un parco cittadino, durante il momento di ritrovo informale con amiche e cane.
* **P3:** Tavolino del bar di quartiere, luogo consueto di decompressione post-palestra e ritrovo con ex colleghi e conoscenti.
* **P4:** Area verde / viale alberato presso il Valentino / San Salvario, durante una delle sue regolari sessioni di camminata a piedi.
* **P5:** Tavolino all'aperto presso locale/pasticceria di quartiere, durante una pausa caffè e lettura giornale.

### c. What Did You Observe and Ask?

* **Osservazione e Contextual Inquiry:** Abbiamo osservato la gestualità, la postura, la dinamica degli spostamenti e l'interazione spontanea con l'ambiente: la familiarità e l'affetto di P3 con i baristi e i giovani del quartiere; la cura con cui P2 porta con sé il lavoro a maglia e controlla le notifiche del cellulare; l'attenzione scrupolosa di P4 verso i dislivelli pedonali e le fermate degli autobus, compensando il calo della vista con l'udito e l'osservazione attenta delle persone; la calma e il distacco di P5, che tiene con sé giornali cartacei, consulta con diffidenza lo smartphone e difende le proprie abitudini analogiche.
* **Guida d'Intervista (Protocollo Semi-Strutturato):** Abbiamo redatto e somministrato una traccia snella in 4 fasi concepita secondo i principi HCI di domande aperte, prive di bias e non suggestive (*unbiased/non-leading*), evitando di diagnosticare fragilità a priori e focalizzandosi su racconti concreti di esperienze passate:

  1. *Fase 1: Background & Contesto* (giornata tipo, confronto tra ritmi lavorativi passati e vita attuale, rapporto con casa e quartiere).
  2. *Fase 2: Approfondimento su Relazioni e Cura di Sé* (articolazione dei contatti sociali, gestione di pasti, attività motoria, riposo, promemoria e scadenze).
  3. *Fase 3: Imprevisti, Ostacoli e Strumenti* (risoluzione di contrattempi pratici, condivisione di belle notizie, aneddoti recenti sull'uso di smartphone/app e relative barriere o workaround).
  4. *Fase 4: Riflessioni e Chiusura* (aspetti più gratificanti e più impegnativi della vita da pensionati, desideri aperti).

### d. Team Member Roles for Each Interview

Per ogni intervista hanno partecipato i membri del gruppo sul campo (intervistatore principale e note-takers/documentatori):

* **Intervista 1 (P1):** Tommaso Mancuso (*Lead Interviewer*), Zharina & Taha Shahid (*Note-taker & Audio Recording*).
* **Intervista 2 (P2):** Tommaso Mancuso (*Lead Interviewer*), Zharina & Taha Shahid (*Note-taker & Artifacts Tracking*).
* **Intervista 3 (P3):** Tommaso Mancuso (*Lead Interviewer*), Zharina & Taha Shahid (*Note-taker & Contextual Observation*).
* **Intervista 4 (P4):** Tommaso Mancuso (*Lead Interviewer*), Zharina & Taha Shahid (*Note-taker & Contextual Observation*).
* **Intervista 5 (P5):** Tommaso Mancuso (*Lead Interviewer*), Taha Shahid (*Note-taker & Contextual Observation*).

### e. Materials Used

* Moduli cartacei di consenso informato (*Consent Form*) compilati e firmati da ciascun intervistato prima dell'avvio.
* Registratori vocali digitali su smartphone per l'acquisizione delle tracce audio integrali.
* Taccuini cartacei per appunti rapidi, annotazione del linguaggio non verbale e citazioni salienti.
* Fotocamera per documentare luoghi, artefatti d'uso e il contesto di svolgimento.

## 3. Results

### a. Pictures and Relevant Artifacts

* **Foto 1 (Contesto P2):** Borsa con kit per il lavoro a maglia (golfini per i nipotini) e agenda promemoria dello smartphone per scadenze mediche.
* **Foto 2 (Contesto P3):** Borsone della palestra e tavolino del bar dove scambia chiacchiere con coetanei e giovani lavoratori.
* **Foto 3 (Contesto P4):** Tessera Abbonamento Musei e smartphone utilizzato per audiolibri a puntate brevi e chat con intelligenza artificiale.
* **Foto 4 (Contesto P5):** Quotidiano cartaceo, mappa cittadina stampata e schermo del telefono con ricerche browser e lezioni streaming.
* **Foto 5 (Contesto mobilità urbana):** Fermata della linea bus/tram e piste ciclabili di quartiere.

### b. Themes from the Thematic Analysis with Key Quotes

Dalla codifica induttiva delle 5 trascrizioni sono emersi 4 macro-temi condivisi:

#### Tema 1: Libertà Riconquistata vs. Sovraccarico Mentale / Difesa della Lentezza

Tutti i partecipanti celebrano la fine del lavoro come una liberazione irrinunciabile: eliminare la sveglia al mattino e gli orari imposti rappresenta il vertice del benessere. Tuttavia, emergono due polarità: chi fatica a gestire in solitudine decisioni pratiche importanti (P2) e chi rivendica con fermezza il diritto al riposo, alla pigrizia e al "non fare niente" senza sentirsi in dovere di riempire l'agenda (P5).

* *P1:* «Da quando sono in pensione sono molto contento che ho smollato il lavoro che era troppo pesante... ho più libertà.»
* *P3:* «La pensione mi ha dato veramente la svolta per potermi riprendere quello che prima non potevi... non dovermi svegliare per forza al mattino presto alle quattro per fare turni massacranti.»
* *P2:* «Gli aspetti molto impegnativi sono le decisioni da prendere perché sono sola, non mi posso confrontare con mio marito... devo mettere il fotovoltaico? Devo rifare gli infissi? Sono quelle cose che non mi fanno dormire la notte.»
* *P4:* «Sono diventata una donna indipendente... la grande gratificazione è che sono indipendente finché la salute e la testa mi reggono.»
* *P5:* «Non dover più mettere la sveglia la mattina per me è stata una liberazione... da quando sono in pensione mi dedico molto di più a fare niente, non sono di quelli super impegnati che devono fare sempre qualcosa.»

#### Tema 2: Il Movimento Dolce come Pilastro di Salute Mentale e Fisica (Rifiuto della Rigidezza Forzata)

L'attività fisica (palestra pesi, corsi antalgici, camminate sostenute, Pilates) è percepita come l'unico vero scudo contro il declino fisico e il dolore articolare. Tuttavia, emerge una netta preferenza per forme di esercizio flessibili, non competitive e vicine a casa: dalla palestra intensa (P3) alla ginnastica terapeutica (P2), fino alle lunghe passeggiate a piedi (P4) e alle lezioni domestiche online seguite senza vincoli d'orario (P5).

* *P3:* «L'esercizio fisico portato all'estremo mi fa iniziare la giornata diversamente, meno monotona, mi scarica proprio mentalmente... mi alleno cinque volte alla settimana.»
* *P2:* «Vado tutte le mattine in palestra a fare ginnastica antalgica... avevo problemi di schiena e sciatica da non alzarmi dal letto la mattina; ho iniziato la palestra ed è passata.»
* *P4:* «Io sono un cammello nel senso che cammino molto, moltissimo... mi piacerebbe fare balli sudamericani dove si mischiano la disciplina del corpo e la musica.»
* *P5:* «Faccio Pilates online a casa per pigrizia, così non devo neanche andare fino alla palestra... mi muovo così, altrimenti se uno non si muove poi resta arrugginito.»

#### Tema 3: Socialità di Prossimità Selettiva, Scambio Intergenerazionale e Rifiuto dei "Ghetti"

Nessun intervistato cerca una socialità artificiale o club ricreativi segreganti per anziani. Il bisogno comune è una socialità autentica, su misura, basata sul vicinato solidale (P4), su incontri casuali ma di qualità (P1), sul confronto formativo e rassicurante con i giovani (P3) e sulla possibilità di chiudere la porta di casa per godersi la solitudine quando lo si desidera (P5).

* *P1:* «Se ci sono persone valide passo volentieri il tempo; se capisco che non va bene mi alzo e me ne vado... incontri casuali per strada, niente di che.»
* *P3:* «A me piace stare in mezzo alla gente, parlo con ragazzi di 20–25 anni... il mio bagaglio di oggi è mettermi a confronto con i giovani per non farmi trovare indietro.»
* *P4:* «Quando cucino un gran purè lo metto nelle vaschette di alluminio e le appendo alle porte dei vicini con bambini... a poco a poco si sono abituati a lasciarmi la frutta. Senza fare la nonna invadente.»
* *P5:* «A me piace stare con le persone e chiacchierare, ma poi mi piace anche molto stare da sola: chiudere la porta, dire 'il mondo sta fuori' e non avere la pressione di dover sempre socializzare.»

#### Tema 4: Il Paradosso Digitale: Utilità Pratica vs. Frustrazione, Invasività e Rifiuto dell'App-Centrismo

Tutti gli intervistati riconoscono l'utilità del supporto digitale quando risolve bisogni concreti (servizi medici, avvisi, micro-dialoghi con AI). Tuttavia, emerge una saturazione evidente: interfacce contorte, acquisti online complessi e l'obbligo forzato di scaricare app per ogni banale operazione generano frustrazione, portando alla rinuncia (P4), al ritorno nostalgico alla carta e alle vecchie mappe (P5) o al rifiuto categorico dello smartphone (P1).

* *P1:* «Da quando mi hanno rubato il telefono non lo sto più adoperando... mi ha salvato la situazione, così non sono più attaccato a Internet e non mi interessa di niente.»
* *P2:* «Per fortuna c'è il cellulare con gli alert che mi ricorda le cose... uso Salute Piemonte per gli esami, ma comincio a dimenticare appuntamenti e parole.»
* *P4:* «Le prenotazioni online per concerti o visite guidate mi bloccano: tento da sola, poi chiamo o rinuncio dicendomi che forse non era cosa per me. Con l'IA invece ci parlo come Cochi e Renato!»
* *P5:* «Tutto adesso va sulle applicazioni: ma come facevamo a vivere senza le applicazioni? Sui siti non trovi un accidente e Google Maps fa quello che vuole lui e non quello che voglio io: la vecchia cartina della città era molto più rapida e chiara.»

## 4. User Needs

### a. Brainstormed User Needs

*(Formulati come necessità umane ed emotive espresse con verbi d'azione, non come soluzioni tecniche o schermate):*

1. I pensionati hanno bisogno di **mantenere una struttura giornaliera stimolante e attiva** senza subire la rigidità di orari lavorativi imposti.
2. I pensionati hanno bisogno di **accedere a opportunità quotidiane di attività motoria dolce e calibrata** per prevenire dolori posturali e preservare l'autonomia fisica.
3. I pensionati hanno bisogno di **trovare stimoli e motivazione per muoversi e uscire di casa** anche nelle giornate caratterizzate da pigrizia, stanchezza o solitudine.
4. I pensionati hanno bisogno di **confrontarsi regolarmente con persone di generazioni diverse** per sentirsi aggiornati, utili e parte integrante della società moderna.
5. I pensionati hanno bisogno di **ricevere un supporto confidenziale e rassicurante nelle scelte pratiche, logistiche ed economiche complesse** quando vivono da soli.
6. I pensionati hanno bisogno di **costruire relazioni di vicinato autentiche e reciproche** basate su piccoli scambi quotidiani di utilità e gentilezza.
7. I pensionati hanno bisogno di **fruire di stimoli culturali e formativi in formati brevi, leggeri e a basso affaticamento visivo e cognitivo**.
8. I pensionati hanno bisogno di **aderire ad attività ed eventi nel proprio territorio locale senza perdersi in flussi digitali di prenotazione complessi**.
9. I pensionati hanno bisogno di **orientarsi nella città e nei servizi di prossimità con percorsi chiari e diretti**, senza subire la dispersività e gli automatismi indesiderati delle app di navigazione.
10. I pensionati hanno bisogno di **scaricare le tensioni mentali e le ansie pratiche accumulate** per favorire un sonno ristoratore.
11. I pensionati hanno bisogno di **gestire promemoria sanitari e personali in modo affidabile e discreto**, eliminando l'ansia da dimenticanza.
12. I pensionati hanno bisogno di **vivere il proprio tempo libero con lentezza e ritmi rilassati**, preservando momenti di tranquillità individuale senza l'obbligo di iper-socializzare.

### b. 3–4 Deep User Needs

* **Deep Need 1: I pensionati hanno bisogno di trovare occasioni quotidiane di movimento motorio dolce e condiviso nel proprio territorio per scaricare lo stress mentale e preservare l'autonomia fisica senza vincoli prestazionali.**

  * *Connessione tematica:* Radicato nel **Tema 2** (*Attività motoria come benessere*) e nel **Tema 1** (*Sovranità sul tempo*). P2, P3, P4 e P5 dimostrano che muoversi (camminata, palestra, mobilità antalgica, Pilates) è il perno che sostiene la lucidità mentale e allontana la paura della decadenza fisica, ma necessita di contesti flessibili, accessibili ed esenti da rigidità orarie o logistiche.
* **Deep Need 2: I pensionati hanno bisogno di partecipare a scambi relazionali intergenerazionali e di vicinato spontanei e paritari per mantenere attivo il senso di scopo, utilità sociale e connessione con il presente.**

  * *Connessione tematica:* Radicato nel **Tema 3** (*Socialità di prossimità e rifiuto dei ghetti*). P3 cerca attivamente il confronto con i ventenni nei locali per non rimanere isolato nel passato; P4 costruisce ponti con i giovani genitori del palazzo scambiando cibo fatto in casa; P1 e P5 valorizzano le interazioni genuine e occasionali di quartiere. Il bisogno esclude esplicitamente i contesti ricreativi segreganti per soli anziani e rispetta il confine della privacy domestica.
* **Deep Need 3: I pensionati hanno bisogno di accedere e partecipare ad attività culturali, pratiche e ricreative di quartiere tramite canali immediati che eliminino l'attrito cognitivo delle prenotazioni online e l'iper-frammentazione delle app.**

  * *Connessione tematica:* Radicato nel **Tema 4** (*Paradosso digitale e barriere di accesso*). La proliferazione di form, account, mappe digitali poco trasparenti ed e-ticketing contorto genera frustrazione e abbandono (P4 rinuncia alle visite, P5 rifiuta le app e usa la cartina di carta, P1 ha dismesso lo smartphone). Il bisogno richiede un accesso al territorio trasparente, rassicurante e privo di ostacoli d'interfaccia.

## 5. Solutions

### a. Brainstormed Solutions (5 idee per ciascun Deep Need)

#### Per Deep Need 1 (Movimento fisico calibrato e benessere motorio):

1. *Passeggiate di Quartiere a Frequenza Libera:* Itinerari urbani circolari guidati con punti di ritrovo ad orari fissi nei parchi pubblici e andature graduate, senza obbligo di frequenza fissa.
2. *Istruttore Vocale di Mobilità Dolce:* Micro-sessioni audio di risveglio muscolare, stretching antalgico e respirazione da ascoltare a casa sul divano o su una panchina.
3. *Mappa Attiva dei Percorsi Urbani Protetti:* Guida interattiva e stampabile che segnala marciapiedi pianeggianti, panchine ombreggiate, fontanelle e aree pedonali prive di traffico e rumori.
4. *Corsi di Ballo di Gruppo Spontaneo:* Incontri settimanali all'aperto nelle piazze pedonali dedicati a balli ritmici individuali (sudamericani/popolari) senza partner.
5. *Patto del Passo (Cammina con Me):* Sistema di abbinamento tra vicini di casa per condividere uscite a piedi e commissioni ordinarie a orari concordati.

#### Per Deep Need 2 (Scambio sociale intergenerazionale e vita di comunità):

1. *Banca delle Competenze di Vicinato:* Scambio asincrono tra anziani (che tramandano tecniche artigianali, maglia, cucina tradizionale, cura piante) e giovani studenti universitari (che offrono supporto tecnologico o commissioni pesanti).
2. *Caffè Narrativi di Quartiere:* Colazioni o aperitivi informali nei bar e circoli locali tra universitari fuori sede e residenti storici per condividere storie del territorio.
3. *Bacheca del Piatto Sospeso:* Canale di micro-comunità condominiale per condividere porzioni di cibo preparato in casa o scambiarsi ortaggi freschi del mercato.
4. *Micro-Gite Condivise:* Escursioni giornaliere di gruppo verso luoghi storici e abbazie piemontesi (es. Sacra di San Michele) con trasporto navetta condiviso tra giovani e anziani.
5. *Circolo di Ascolto Breve:* Sessioni di ascolto collettivo di podcast culturali da 20-30 minuti seguite da dibattito e confronto di opinioni davanti a un tè o caffè.

#### Per Deep Need 3 (Accessibilità immediata a servizi ed eventi territoriali):

1. *Prenotazione Vocale Conversazionale One-Step:* Assistente telefonico/digitale con linguaggio naturale che prenota posti e visite guidate semplicemente parlando a voce, senza moduli o credenziali.
2. *Gettone/Badge NFC di Quartiere:* Carta fisica contactless da appoggiare nei totem delle biblioteche o dei bar per registrarsi istantaneamente agli eventi.
3. *Rete dei Punti Amici in Edicola e Bar:* Centri di prenotazione assistita nei negozi di prossimità per ricevere stampata su carta la conferma della propria attività o la mappa dell'itinerario.
4. *Bacheca Sonora Settimanale:* Notiziario vocale di 90 secondi riprodotto su richiesta con le 3 migliori iniziative accessibili a piedi nel quartiere, privo di notifiche invasive.
5. *SMS di Conferma Diretta:* Flusso semplificato che notifica date e indirizzi direttamente tramite SMS standard, senza account o download di biglietti in PDF.

### b. Descrizione della Soluzione Selezionata (Top Solution)

La nostra soluzione è **"PassoPasso": una piattaforma civica di quartiere che attiva micro-camminate urbane, iniziative di mobilità dolce e momenti di scambio intergenerazionale (artigianato, cucina, podcast culturali) tra pensionati e giovani del quartiere, integrata da un'interfaccia conversazionale vocale che permette l'esplorazione e l'adesione immediata alle attività con una semplice richiesta a voce, azzerando form e procedure d'acquisto online.**

* **Connessione con i bisogni:** Risolve congiuntamente il **Deep Need 1** (incentiva la camminata quotidiana all'aperto e la ginnastica dolce nei parchi rispettando i ritmi individuali), il **Deep Need 2** (struttura occasioni d'incontro autentiche con studenti universitari e giovani residenti evitando la segregazione e rispettando i momenti di quiete) e il **Deep Need 3** (rimuove la barriera dell'e-ticketing e la dispersione delle app commerciali grazie all'interazione a voce naturale e alla notifica diretta essenziale).

### c. How and Why Did You Select It?

* **Metodo applicato:** Abbiamo utilizzato il **Four-Category Method**, catalogando le 15 proposte emerse dal brainstorming:

  * *The Rational Choice:* L'assistente vocale semplificato per le pratiche sanitarie e amministrative.
  * *The Most Likely to Delight:* I corsi di ballo sudamericano dolce all'aperto nelle isole pedonali.
  * *The Long Shot:* I totem fisici con lettore NFC distribuiti in tutti i bar ed edicole della città.
  * *The Darling:* **Step-by-Step: la rete intergenerazionale di cammino, scambio pratico e cultura di prossimità ad attivazione vocale.**
* **Motivazione (Why):** Questa soluzione rispecchia in maniera fedele e organica tutte le sfaccettature emerse sul campo: soddisfa la ricerca di movimento e vitalità fisica (P2, P3, P4, P5), accoglie la voglia di stare a contatto con i giovani senza sentirsi un peso o un utente "da assistere" (P3, P4), rispetta il bisogno di lentezza e discrezione (P5) e supera l'ostacolo delle tecnologie intrusive e frustranti che avevano provocato il rifiuto totale in P1, l'ansia da prenotazione in P4 e l'insofferenza per le app in P5.

## 6. Project Name and Value Proposition

### a. How Did the Team Land on the Name?

Il team ha valutato diverse alternative evocative (*Controvento*, *Vicìno*, *Àncura*, *Girotondo*), convergendo infine all'unanimità su:

# **Step-By-Step**

* **Genesi del nome:** Il nome nasce da una triplice assonanza semantica:

  1. *Il passo motorio:* Richiama l'atto semplice, salutare e quotidiano del camminare insieme per le strade e i parchi cittadini;
  2. *Il passo relazionale:* Evoca il ritmo graduale, naturale e non forzato con cui si crea fiducia tra persone di generazioni diverse;
  3. *Il passo interattivo:* Rappresenta l'esperienza d'uso dell'interfaccia digitale, progettata per accompagnare l'utente passo dopo passo, con chiarezza, calma e rispetto delle sue abitudini.

### b. One-Line Value Proposition

> **«Il quartiere che si muove insieme: incontri, passi e scambi tra generazioni, a portata di voce.»**
