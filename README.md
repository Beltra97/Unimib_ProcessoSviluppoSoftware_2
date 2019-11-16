# **UNIMIB Tutoring Assistant - Elicitation Strategy**


## **Group 25 - Composition:** 

* Bettini Ivo Junior (806878) @ i.bettini@campus.unimib.it
* Beltramelli Fabio (816912) @ f.beltramelli@campus.unimib.it
* Tramontana Giuseppe (765917) @ g.tramontana@campus.unimib.it

## **GitLab Repository**
[2019_assignment2_unimib_tutoring_assistant](https://gitlab.com/i.bettini/2019_assignment2_unimib_tutoring_assistant)

## **APPLICATION OVERVIEW**

**UNIMIB Tutoring Assistant** is a to-be-developed _Mobile Application_ aiming to provide a simple yet powerful tool for handling private tutoring among students of the _University of Milano-Bicocca_.

The core concept behind this application is to allow students to offer and to search for private lessons in a modern, simple and immediate way, thus creating a trusted **network** of _teachers_ and _students_.

**UNIMIB Tutoring Assistant** was born from a _public competition_ published by **Regione Lombardia** and won by the _University of Milano-Bicocca_. The competition was created in order to experiment a software solution to automate private tutoring between students of (at least initially) the same premises; the automation objectives are many: for instance, collecting of statistical data and helping off-premise students organize better their schedules.

Group 25 was formed by three students of the _University of Milano-Bicocca_ that won a scholarship for an internship dedicated to the development of the mobile application.

The _public competition_ did not come with an in-depth list of requirements for the software to be met; instead, it described the application at high-level by providing a ideal workflow that will be presented in this overview.

Before presenting the overview, though, it is fundamental to introduce the different types of user that will be interacting with the system.
**UNIMIB Tutoring Assistant** will be an application for handling private tutoring, so two key types of user need to be defined:
1. Users who search for private lessons
2. Users who offer private lessons

Since the application aims to build a social network, another type of user will be necessary, even though it will operate on a Back-Office Environment:
1. Administrators

Regarding the two key users for the Mobile Application, it will be required for them to **register** to the service and fill in their profile with some mandatory information: _personal data_, _personal snapshot_ and _field of study/interest_.

After **logging in**, they can choose to _Search for Private Lessons_ (filtered, at least initially, by chosen _field of study/interest_) or to _Offer Private Lessons_ by compiling a form with some mandatory and optional information.

An user in need of a private lesson can start to schedule a meeting with an offerer. During the scheduling the application will allow the users to send _instant messages_ to communicate and to _check reviews_ about the other user, other than, of course, negotiate the _date of meeting_ and other _meeting details_.

After a certain time after a scheduled meeting, both actors will be able to send a review about the meeting in order to give future users a better way to find an appropriate match for their needs.

In the ideal scenario, the application will be presented to the higher-ups of the University in order to be officially promoted.

## **REQUIREMENT ENGINEERING**

The first step of _Software Development_ is **Requirements Engineering**. **Requirements Engineering** is fundamental in order to fully understand and define what the _Software TO-BE_ should accomplish in a **context** full of determined _assumptions_ and _properties_. Its output is a **set of requirements** for the _Software TO-BE_.

The focus of this document is defining and documenting the first two steps of **Requirements Engineering**:
1. **Domain Understading**: this phase is fundamental for **identifying the Stakeholders** and for studying _Application Domain_ and _Business Organization_.
2. **Requirements Elicitation**: this phase regards researching and discovering the requirements of a system.

## **DOMAIN UNDERSTANDING: IDENTIFYING THE STAKEHOLDERS**

The core subject of **Domain Understading** is to find a representative set of **Stakeholders** required in order to understand _from_ them and _with_ them what is required for the _Software TO-BE_ to accomplish.

As it is known from literature, there are some relevant aspects to consider for **Stakeholders** selection; some of them are:
1. Their position in the target organization.
2. Their role in making desition about the _System TO-BE_.
3. Their exposure to the perceived problem or required need.
4. Their level of Domain expertise.

With these key aspects in mind, a first set of **Stakeholders** was chosen; _it is important to note_ that since **Requirements Engineering** is an iterative process, more **Stakeholders** could be added to the list after **Requirements Elicitation** or after a full cycle of development.

> **Stakeholders List**

1. **Product Owner: the professor in charge of the project**: a professor was appointed from the University to handle the management of the project obtained from the _public competition_. They (Editor's note: the professor's gender is irrelevant for this document) will keep in touch with the developers during all the stages of development to guide and help them. Furthermore, they are helping to set up the project thanks to their knowledge and experience in Project Managing: this is the reason why they are a mandatory _Stakeholder_ to consider in the **Requirements Engineering**.
2. **Developers Team**: they are a necessary _Stakeholder_ because their input is mandatory **before** the development start in order to estimate the _requirements_ and decide the technologies for the development (for instance, are they more confident with hybrid or native development?).
3. **Head of IT of the University of Milano-Bicocca**: this _Stakeholder_ was considered required for many reasons: with their expertise they could guide the developers through problems of legal, economic, etc. values. In addition, they could help identifying other useful _Stakeholders_ (for instance, a _Stakeholder_ that could provide the developers a Server for the App Database). Lastly, they could help the developers with some exposure through existing systems of the _University of Milano-Bicocca_.
4. **Students from the University of Milano-Bicocca**: they are the most important _Stakeholder_ as they are the final user; they split in two classes:
	1. **Students who search for private lessons**.
	2. **Students who offer private lessons**.
5. **UX/UI Expert**: could be a useful _Stakeholder_ since the main focus of the Mobile App is offering a modern, immediate but complete feel.

## **REQUIREMENTS ELICITATION: ELICITATION STRATEGY OVERVIEW**

A standard **Elicitation Strategy** usually starts with a complete analysis of the _Software AS-IS_, in order to find a set of weaknesses that need to be addressed by the software solution that is going to be developed; in this case, though, since **UNIMIB Tutoring Assistant** is a __to-be-developed__ _Mobile Application_, a good approach to start with **Requirements Elicitation** is to gain knowledge about the software domain through a **Background Study**.

//TODO: Ampliare, specificare seconda fase: artifact-driven (questionario, scegliere studenti principalmente della bicocca perché possono esserci problematicità specifiche. intervista con domande chiuse e brevi per ridurre costi e non scocciare l'intervistato che comunque è uno studente e non ha voglia. parlare anche del metodo di distribuzione fisico (link distribuito come?)) e prima fase: stakeholder-driven (intervista (l'intervista può essere strutturata e non, è usata per raccogliere reqs parlando con stakeholders/cliente))

//Modifica del file italiano, va bene? ho specificato le tecniche di elicitazione.

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

//TODO: img: assets/SE.png

## **BACKGROUND STUDY**

//TODO: **Background Study** is an ARTEFACT-DRIVEN ELICITATION TECHNIQUE
//TODO: Aggiungere Refs e qualche info in più se possibile

Il mondo delle ripetizioni è un mondo vasto, le bacheche dell'università e i siti internet sono pieni di annunci di persone che cercano o che vogliono erogare ripetizioni. 
Esistono già siti come TrovaRipetizoni, piattaforma creata da degli studenti che cerca di creare una rete molto ampia (tutta Italia) e quindi non ancora può fornire una copertura adeguata o applicazioni come Bravoapp, che fornisce la possibilità di sottoscrivere abbonamenti mensili per gli insegnanti e di effettuare ricerche gratuite per chi cerca ripetizioni.
Un altro caso di studio è SuperProf.it, anche questo sito permette di cercare degli studenti che facciano ripetizioni in una zona selezionata. Un punto di forza di questa piattaforma è sicuramente la possibilità di dare lezioni online, attraverso l'utilizzo di Skype, Hangouts o FaceTime. In questo modo è possibile seguire/fornire una ripetizione direttamente da casa propria. 
Un'app molto simile, che permette di tenere lezioni anche a grandi distanze è iTeach, essa utilizza internet per gestire la comunicazione tra le parti.
Il nostro obiettivo è differenziarci un minimo da questi applicativi, localizzandoci in un luogo preciso, dando la possibilità anche a chi eroga una ripetizione di poter lasciare un feedback (cosa che non accade in altri applicativi esistenti) e quindi cercando di agevolare l'esperienza universitaria dei nostri studenti sotto ogni aspetto.
Questa applicazione può essere un ulteriore possibilità di contatto e condivisione tra università e studenti.

## **PRESENTATION OF INTERVIEW**

//TODO

## **RESULT OF THE INTERVIEW**

//TODO

## **PRESENTATION OF QUESTIONNAIRE**

//TODO

## **RESULT OF THE QUESTIONNAIRE**

//TODO

## **---DRAFT PARTS---**

(Conference call con i vari team altra attività elicitazione?? per me si)

// se mettiamo gli stakeholders che dico io va modificata la parte sotto

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

EVENTUALI CONFERENCE CALL/INTERVISTE

QUESTIONARIO UTENTI FINALI 

Il questionario verrà somministrato dopo aver realizzato l'intervista, aver utilizzato le risposte ottenute per craere 
dei requisiti e in base anche ai consigli ottenuti dal rettore. 
Somministreremo il questionario attraverso un form di google e avrà il compito di ottenere informazioni utili 
sull'aspetto pratico dell'applicazione.

Il questionario è stato creato in modo da ricercare e trovare possibili modifiche e/o aggiunte da fare 
all'applicazione in base alle preferenze, caratteristiche e abitudini dei possibili utilizzatori finali.