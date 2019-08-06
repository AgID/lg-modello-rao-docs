Le Linee Guida
============

Scopo
-----

Le presenti Linee Guida, sono emesse ai sensi dell’articolo 71 del
decreto legislativo 7 marzo 2005, n. 82 e successive modifiche e
integrazioni (di seguito CAD).

Struttura
---------

Le presenti Linee Guida sono integrate dall’Allegato Tecnico:

-  *Token* R.A.O. Pubblico;

-  Tabella messaggi *token* R.A.O. pubblico inviati dall’IdP.

Gruppo di lavoro
----------------

La redazione del documento è stata curata dal gruppo di lavoro composto
da:

-  **Agenzia per l’Italia Digitale**

-  **Aruba S.p.A.**

-  **CSI Piemonte**

-  **Infocert S.p.A.**

-  **Lepida S.p.A.**

-  **Poste Italiane S.p.A.**

-  **Provincia Autonoma di Bolzano**

-  **Provincia Autonoma di Trento**

-  **Regione Piemonte**

-  **Register.it S.p.A.**

-  **Sielte S.p.A.**

-  **TI Trust Technologies S.r.l.**

-  **Team per la Trasformazione Digitale**

Soggetti destinatari
--------------------

   Le presenti linee guida sono applicabili ai:

-  a) soggetti di cui all’art. 2, comma 2, lett. a) del CAD che intendono,
   con proprie risorse, effettuare l’identificazione della persona
   fisica, di seguito utente, in qualità di R.A.O. pubblico del sistema
   SPID\ *;*

-  b) gestori di identità digitale, di seguito IdP, che intendono avvalersi
   delle procedure di identificazione effettuate dai soggetti di cui al
   punto precedente.

Riferimenti e sigle
===================

Riferimenti Normativi
---------------------

-  **[Reg. UE n.910/2014]** Regolamento (UE) n. 910/2014 del 23 luglio
   2014 in materia di identificazione elettronica e servizi fiduciari
   per le transazioni elettroniche nel mercato interno e che abroga la
   direttiva 1999/93/CE;

-  **[D.Lgs. 82/2005]** Decreto legislativo 7 marzo 2005, n. 82 e s.m.i.
   recante “Codice dell’amministrazione digitale”;

-  **[DPCM 24 ottobre 2014]** recante “Definizione delle caratteristiche
   del sistema pubblico per la gestione dell’identità digitale di
   cittadini e imprese (SPID), nonché dei tempi e delle modalità di
   adozione del sistema SPID da parte delle pubbliche amministrazioni e
   delle imprese.”;

-  **[Regolamento recante le regole tecniche]** (articolo 4, comma 2,
   DPCM 24 ottobre 2014) e s.m.i.;

-  **[Regolamento recante le modalità attuative per la realizzazione
   dello SPID]** (articolo 4, comma 2, DPCM 24 ottobre 2014) e s.m.i.

Termini e definizioni
---------------------

Di seguito si riportano gli ACRONIMI che verranno utilizzati nella
presente Linee Guida:

-  **[Agenzia]** Agenzia per l’Italia Digitale

-  **[Brochure]** documenti realizzati ed aggiornati dagli IdP,
   reperibili sul sito ufficiale SPID che spiegano brevemente la *user
   experience* e le caratteristiche del servizio offerto.

-  **[CAD]** Codice Amministrazione Digitale, D.Lgs 7 marzo 2005, n. 82

-  **[IdP]** Identity Provider o gestore di identità digitale SPID

-  **[R.A.O.]** Registration Authority Office

-  **[Sistema]** il sistema applicativo in uso dai RAO pubblici,
   predisposto in conformità all’allegato “\ *Token* R.A.O. Pubblico”,
   per la compilazione della scheda anagrafica, la formazione e
   trasmissione dei *token* sulla base dei modelli di riferimento di cui
   al par.3.6

-  **[SPID]** Sistema Pubblico di Identità Digitale

-  **[sub CA]** Subordinate certificate authority

-  **[Token]** I *token* contengono i dati dell’utente di cui al par.
   3.3 e sono formati in conformità all’allegato “\ *Token* R.A.O.
   Pubblico”


Modello di R.A.O. pubblico
===================

Comunicazione all’Agenzia
-------------------------

   I soggetti di cui al par. 1.4 lett. a) presentano istanza all’Agenzia
   al fine di essere riconosciuti come R.A.O. pubblico del sistema SPID.

   Gli IdP informano l’Agenzia che intendono avvalersi delle procedure
   di identificazione effettuate dai R.A.O. pubblici del sistema SPID.

   L’Agenzia rende disponibile ad entrambi i predetti soggetti un
   sigillo elettronico di cui al par. 3.12.

Modalità di riconoscimento
--------------------------

   L’operatore di un R.A.O. pubblico deve verificare l’identità
   personale dell’utente tramite un documento d’identità valido e, in
   qualità di pubblico ufficiale, è esonerato dall’acquisizione
   dell’immagine fotostatica del documento stesso.

   Tali verifiche sono effettuate con le modalità e i controlli previsti
   dalla normativa vigente in materia di rilascio dell’identità digitale
   della persona fisica ai sensi dell’art. 7, comma 2, lett. a) del DPCM
   24 ottobre 2014 e s.m.i..

   L’operatore effettuato il riconoscimento *de visu*, compila nel
   sistema di cui al par. 3.4 una scheda anagrafica con i dati
   dell’utente di cui al par. 3.3.

Dati dell’utente
----------------

I dati dell’utente sono composti da:

1. attributi identificativi SPID:

-  nome,

-  cognome,

-  luogo di nascita,

-  provincia di nascita,

-  data di nascita,

-  sesso,

-  codice fiscale,

-  estremi del documento d’identità utilizzato ai fini
   dell'identificazione in corso di validità.

2. attributi secondari SPID:

-  numero di telefonia mobile,

-  indirizzo di posta elettronica,

-  domicilio fisico,

-  se disponibile, domicilio digitale (casella PEC).

3. ulteriori informazioni anagrafiche:

-  numero seriale della Tessera Sanitaria o del tesserino del Codice
   Fiscale in corso di validità;

-  nazione di nascita;

-  nazione del domicilio fisico.

Sistema 
--------

   L’operatore compila la scheda anagrafica dell’utente nel sistema.

   Il sistema garantisce di collocare temporalmente la compilazione
   della scheda anagrafica e di individuare l’operatore.

Processo di riconoscimento
--------------------------

   L’operatore compila nel sistema una scheda anagrafica con i dati
   dell’utente di cui al par. 3.3.

   Il sistema:

1. salva la scheda anagrafica nel formato di interscambio concordato
   generando il *token in chiaro*;

2. genera una *passphrase* secondo le modalità indicate al par. 3.11 e
   cifra il *token in chiaro* ottenendo il *token cifrato;*

3. associa il codice fiscale dell’utente al *token cifrato* e
   restituisce il *token completo;*

4. appone il sigillo elettronico, di cui al par. 3.12, del R.A.O.
   pubblico al *token completo* ed ottiene il *token sigillato*.

..

   A seguito della trasmissione del *token sigillato*, effettuata in
   base ai modelli di riferimento di cui al par. 3.6, l’operatore
   consegna all’utente metà della *passphrase* in modalità cartacea e
   metà viene inviata all’indirizzo email fornito dall’utente unitamente
   alle indicazioni per consultare le brochure, realizzate ed aggiornate
   dagli IdP, reperibili sul sito ufficiale SPID.

   L’operatore informa l’utente che il *token sigillato* può essere
   utilizzato entro e non oltre 30 giorni.

Modelli di riferimento
----------------------

   Sono previsti due modelli di riferimento che i R.A.O. pubblici
   possono mettere a disposizione dell’utente.

-  a) L’operatore può informare l’utente della possibilità di scegliere il
   proprio IdP a sportello, in questo caso il *token sigillato* è
   inviato all’IdP prescelto;

-  b) In mancanza della predetta possibilità o in caso di mancata scelta da
   parte dell’utente, il *token sigillato* è inviato all’utente via
   email all’indirizzo di posta elettronica fornito.

Rilascio dell’identità digitale da parte dell’IdP
-------------------------------------------------

   L’utente si collega al sito dell’IdP e seleziona la modalità di
   rilascio con “identificazione tramite P.A.”.

   Nel caso in cui sia applicabile il modello di riferimento di cui alla
   lett. a) del par. 3.6, l’utente immette il proprio codice fiscale per
   permettere all’IdP di recuperare il proprio *token sigillato*.

   Nel caso in cui sia applicabile il modello di riferimento di cui alla
   lett. b) del par. 3.6, l’utente esegue l’upload del proprio *token
   sigillato*.

   L’IdP verifica sigillo e periodo di validità del *token sigillato*.
   L’IdP richiede l’inserimento della *passphrase* per decifrare il
   *token cifrato*. Superati i 5 tentativi errati di inserimento della
   *passphrase* il *token* non è più accettato dall’IdP.

   L’IdP estrae i dati dell’utente di cui al par. 3.3, ed effettua la
   verifica dell’effettivo possesso del cellulare indicato da parte
   dell’utente.

Verifiche e rilascio dell’identità
----------------------------------

   L’IdP utilizza i dati dell’utente di cui al par. 3.3 per compilare la
   scheda anagrafica collegata all’identità ed effettua le verifiche
   previste dalla normativa vigente in materia di rilascio dell’identità
   digitale SPID.

   Ogni IdP rilascia l’identità SPID secondo le proprie modalità.

Responsabilità R.A.O. pubblico
------------------------------

   I R.A.O. pubblici si assumono la responsabilità della corretta
   verifica dell’identità personale dell’utente e sono tenuti a
   mantenere nel tempo le evidenze per individuare il singolo operatore
   che ha effettuato il riconoscimento dell’utente.

   I R.A.O. pubblici si impegnano a formare adeguatamente gli operatori
   incaricati alla verifica dell’identità degli utenti, fornendo agli
   stessi ogni informazione in merito alle procedure applicative e alle
   responsabilità di natura civile e penale nelle quali potrebbero
   incorrere nello svolgimento di tale attività.

Responsabilità IdP
------------------

   L’IdP deve porre in essere tutte le attività necessarie al fine di
   interoperare con il sistema di cui al par. 3.4.

   L’IdP che rilascia l’identità deve mantenere evidenze atte a
   dimostrare che la singola identità è stata rilasciata sulla base
   dell’identificazione di cui al par. 3.7.

   L’IdP può essere responsabile o corresponsabile dell’incorretto
   rilascio di un’identità digitale se non ha correttamente ottemperato
   alle verifiche di cui al par. 3.8.

   L’IdP è esonerato dall’obbligo previsto dall’art. 7, comma 5, del
   DPCM 24 ottobre 2014.

Generazione della *passphrase*
------------------------------

   La lunghezza della *passphrase* è di 12 caratteri generati in maniera
   casuale e che deve contenere:

-  Almeno una lettera maiuscola;

-  Almeno una lettera minuscola;

-  Almeno un carattere numerico;

-  Almeno un carattere speciale tra quelli elencati: ! $ ? # = \* + - .
   :

Sono esclusi i caratteri confondibili come i, l, 1, L, o, 0, O.

Ai fini del processo di cui al par. 3.5 la *passphrase* è divisa in due
parti da 6 caratteri ciascuno.

Sigillo elettronico
-------------------

L’Agenzia emette due sub CA dedicate rispettivamente per i soggetti
individuati come R.A.O. pubblici e per gli IdP, utili alla generazione
dei certificati dei sigilli elettronici.

Detti certificati sono caratterizzati dalla presenza dei seguenti OID
registrati dall’Agenzia (OID 1.3.76.16):

• 1.3.76.16.4.20 per i certificati dei sigilli elettronici degli IdP;

• 1.3.76.16.4.21 per i certificati dei sigilli elettronici dei R.A.O.
pubblici.

Tali sigilli sono utilizzati sia per l’instaurazione di un canale di
comunicazione tra i predetti soggetti che per sigillare il *token
completo*.

