# Processo e Sviluppo Software - Assignment 2


> **COMPOSIZIONE DEL GRUPPO:** 

* Bettini Ivo Junior (matr.806878)
* Beltramelli Fabio (matr. 816912)
* Tramontana Giuseppe (matr. 765917)

Link repository: [2019_assignment2_unimib_tutoring_assistant](https://gitlab.com/i.bettini/2019_assignment2_unimib_tutoring_assistant)

> **APPLICATION OVERVIEW**

//modificare in base a idea avuta ieri sera e allineare con la versione inglese ben fatta!!


L'obiettivo di questa applicazione è di aiutare gli utenti/studenti che studiano presso
l'università degli studi di Milano Bicocca con un sistema che gestisce le ripetizioni per
studenti che frequentano la stessa facoltà.
L'idea dietro questo applicativo è quindi quella di creare una "rete" di fiducia tra gli 
utenti/studenti, dando l'opportunità ad alcuni studenti di condividere la propria conoscenza
e di iniziare a trovare un'indipendenza economica.
Questa può essere anche l'opportunità per studenti che vogliono iscriversi alla nostra università
per avere aiuto e prepare il test d'ingresso.

Ci sono due tipi di utenti:
*  Utenti che hanno bisogno di ripetizioni;
*  Utenti che erogano ripetizioni.

Entrambi gli utenti iscrivendosi all'applicazione definisco il loro ruolo, indicando la facoltà
presso la quale studiano e le materie cui hanno bisogno ripetizione o che sono disposti a spiegare.
Dopo l'iscrizione, l'utente che cerca una ripetizione contatta "l'insegnante" e si può così 
organizzare l'incontro.
Nella nostra idea, l'università potrebbe creare spazi pensati a posta per questo scopo, creando 
anche una sezione nel proprio sito o su e-learning di questo applicativo.
Alla fine della ripetizione, lo studente può rilasciare un feedback (positivo o negativo) su chi 
ha erogato la ripetizione e volendo può già organizzare un nuovo incontro.
Allo stesso tempo, l'utente che ha svolto la ripetizione può lasciare un commento sulla serietà 
dello studente, in modo da lasciare informazioni a chi in futuro erogherà ripetizioni a quello 
studente.

> **BACKGROUND STUDY**

//fare modifica scritta nel file in inglese


Il mondo delle ripetizioni è un mondo vasto, le bacheche dell'università e i siti internet sono 
pieni di annunci di persone che cercano o che vogliono erogare ripetizioni. 
Esistono già siti come TrovaRipetizoni, piattaforma creata da degli studenti che cerca di creare una 
rete molto ampia (tutta Italia) e quindi non ancora può fornire una copertura adeguata o applicazioni 
come  Bravoapp, che fornisce la possibilità di sottoscrivere abbonamenti mensili per gli insegnanti 
e di effettuare ricerche gratuite per chi cerca ripetizioni.
Un altro caso di studio è SuperProf.it, anche questo sito permette di cercare degli studenti 
che facciano ripetizioni in una zona selezionata. Un punto di forza di questa piattaforma è sicuramente
la possibilità di dare lezioni online, attraverso l'utilizzo di Skype, Hangouts o FaceTime. In
questo modo è possibile seguire/fornire una ripetizione direttamente da casa propria. 
Un'app molto simile, che permette di tenere lezioni anche a grandi distanze è iTeach, essa utilizza
internet per gestire la comunicazione tra le parti.
Il nostro obiettivo è differenziarci un minimo da questi applicativi, localizzandoci in un luogo 
preciso, dando la possibilità anche a chi eroga una ripetizione di poter lasciare un feedback (cosa
che non accade in altri applicativi esistenti) e quindi cercando di agevolare l'esperienza 
universitaria dei nostri studenti sotto ogni aspetto. 
Questa applicazione può essere un ulteriore possibilità di contatto e condivisione tra università 
e studenti.

> **ELICITATION STRATEGY OVERVIEW**

//Overview aggiornato con quanto detto su telegram, io fare interviste al rettore per i motivi detti su telegram 
e agli utenti finali per ottenere requisiti


Dopo un'analisi preliminare avvenuta nella fase di background study, si procede a decidere con il 
professore gli step da seguire per portare a termine il progetto.
L'interazione con gli stakeholders è avvenuta attraverso techiniche diverse di elicitazione, usate
per poter ottenere il maggior numero di opinioni, informazioni e consigli per poter realizzare al meglio
l'applicativo.
Per questo motivo abbiamo deciso di utilizzare due tecniche di elicitazione, una tecnica del tipo 
stakeholder-driven usata in fase preliminare, e poi una tecnica de tipo artefact-driven.
Inizialmente verrà erogata una intervista al rettore dell'università degli studi di Milano-Bicocca, utile
per ottenere informazioni e consigli su come creare l'applicazione, e un'intervista ai possibili utenti 
finali in modo da ottenere il maggior numero di informazioni utili per l'applicazione e sulle 
funzionalità che essa mette a dispozione. 
In seguito poi per ottenere un feedback su quello che è stato fatto verrà erogato un questionario ai 
possibili utenti finali per poter valutare l'aspetto pratico.
Segue uno schema riassuntivo della strategia:

> **STAKEHOLDERS**

L'applicazione si rivolge principalmente agli studenti dell'università Milano-Bicocca,
con la possibilità di estendersi in molti altri atenei italiani.
Sono stati identificati diversi stakeholders:

* CEO: si tratta del committente dell'applicazione, nel nostro caso è il professore che ci da 
il progetto da fare (giusto chiamarlo ceo?? Direi product owner)

* UTENTI FINALI: classe che comprende due tipi di utenti,uno è lo studente che ha bisogno di aiuto
l'altro è lo studente che eroga ripetizioni. (GIUSTO)

* RETTORE: Figura che collega il nostro progetto all'università, (vedi intervista)

* TEAM DI SVILUPPO: composto da programmatori ed ha l'obiettivo di realizzare l'applicazione mobile,
disponibile sia su Android che su IOS.  (GIUSTO)

* Per quanto detto nella lezione virtuale si potrebbe anche considerare come stakeholders chi gestisce 
il sito dell'università, qualcuno che gestisce l'aspetto del trattamento dei dati personali e come si diceva 
nell'audio magari possiamo evitare qualcuno che gestisce i pagamenti su carta. Bisogna capire se c'è modo
di inserire questi come stakeholders non attivi (cioè non portano requisiti).

Le interviste e il questionario verranno erogati principalmente agli stakeholders considerati attivi, come il 
rettore e la classe degli utenti finali, per individuare eventuali problemi nell'utilizzo e quindi introdurre 
la possibilità di miglioramenti futuri.
Abbiamo deciso di non erogare questo test agli sviluppatori dell'applicazione, in quanto non sarebbero 
in grado di dare risposte oggettive e/o trovare problemi nell'applicazione.

> **INTERVISTE E QUESTIONARI**

(Titolo della sezione e contenuto da rivedere)

L'intervista e i questionari saranno indirizzati rispettivamente agli stakeholders più attivi,
il rettore e alla classe degli utenti finali, in modo da identificare al meglio le opinioni e 
le esigenze degli utilizzatori.
Le informazioni che vengono ricavate  dgli utenti sopra citati, vengono considerate affidabili 
rispetto a quelle ottenibili somministrando i questionari a utenti randomici che, non utilizzando
l'applicazione, fornirebbero dati non utili al processo di elictazione.

L'intervista al rettore è stata costruita in modo da ottenere più informazioni e opinioni utili possibili
per poter realizzare al meglio un'applicazione che coniughi il rapporto tra funzionalità e soprattutto 
integrazione con l'università.

L'intervista agli utenti finali, invece, è stata strutturata in modo da ricavare più informazioni utili 
possibili per l'utilità dell'applicazione. Si prevede che con l'intervista gli sviluppatori ottengano 
risultati utili alla formazione di essa.

Da questa attivtà di elicitazione ci aspettiamo di ottenere più requisiti possibili utili per poter creare
l'applicazione, inoltre speriamo anche di ottenere informazioni a livello giuridico ed economico in base 
al regolamento di ateneo.

INTERVISTA RETTORE

(Le domande vanno ancora formulate)

* Nome, Cognome e ruolo
    -Scopo, conoscere la persona che stiamo intervistando

* Mail o numero di telefono   
    -Scopo, avere il modo di poter ricontattare la persona intervistata

* Pensiero su progetto
    -Scopo, conoscere opinione di base del rettore e dell'università

* Aspetto legale/giuridico
    -Scopo, avere informazioni adeguate per rispettare con il nostro progetto le regole di ateneo

* Aspetto economico
    -Scopo, avere un opinione sul sistema ideato per la retribuzione delle ripetizioni

* Sito internet
    -Scopo, ottenere autorizzazione a creare una sezione applicativa su e-learning e delle sezioni informative 
    sui vari siti dei corsi (per farvi capire un es. può essere Disco)

* Suggerimenti
    -Scopo, ottenere consigli e opinioni utili dal parte del rettore 

A causa del troppo tempo di attesa per ottenere un appuntamento con il rettore non siamo riusciti ad incontrare 
il rettore e non siamo riusciti a svolgere l'intervista. 

INTERVISTA UTENTI FINALI

* DA FARE

QUESTIONARIO UTENTI FINALI 

Il questionario verrà somministrato dopo aver realizzato l'intervista, aver utilizzato le risposte ottenute per craere 
dei requisiti e in base anche ai consigli ottenuti dal rettore. 
Somministreremo il questionario attraverso un form di google e avrà il compito di ottenere informazioni utili 
sull'aspetto pratico dell'applicazione.

Il questionario è stato creato in modo da ricercare e trovare possibili modifiche e/o aggiunte da fare 
all'applicazione in base alle preferenze, caratteristiche e abitudini dei possibili utilizzatori finali.


