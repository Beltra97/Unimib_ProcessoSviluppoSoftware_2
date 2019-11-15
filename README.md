# **UNIMIB Tutoring Assistant - Elicitation Strategy**


## **Group 25 - Composition:** 

* Bettini Ivo Junior (806878) @ i.bettini@campus.unimib.it
* Beltramelli Fabio (816912) @ f.beltramelli@campus.unimib.it
* Tramontana Giuseppe (765917) @ g.tramontana@campus.unimib.it

## **Date**
13/11/2019

## **GitLab Repository**
[2019_assignment2_unimib_tutoring_assistant](https://gitlab.com/i.bettini/2019_assignment2_unimib_tutoring_assistant)

## **APPLICATION OVERVIEW**

**UNIMIB Tutoring Assistant** is a to-be-developed _Mobile Application_ aiming to provide a simple yet powerful tool for handling private tutoring among students of the _University of Milano-Bicocca_.
The core concept behind this application is to allow students to offer and to search for private lessons in a modern, simple and immediate way, thus creating a trusted **network** of _teachers_ and _students_.

**UNIMIB Tutoring Assistant** was born from a _public competition_ published by **Regione Lombardia** and won by the _University of Milano-Bicocca_. The competition was created in order to experiment a software solution to automate private tutoring between students of (at least initially) the same premises; the automation objectives are many: for instance, collecting of statistical data and helping off-premise students organize better their schedules.
Group 25 was formed by three students of the _University of Milano-Bicocca_ that won a scholarship for an internship dedicated to the development of the mobile application.
The _public competition_ did not come with an in-depth list of requirements for the software to be met; instead, it described the application at high-level by providing a ideal workflow that will be presented in this overview.

Before presenting the overview, it is fundamental to introduce the different types of user that will be interacting with the system.
**UNIMIB Tutoring Assistant** will be an application for handling private tutoring, so two key types of user need to be defined:
1. Users who search for private lessons
2. Users who offer private lessons

Since the application aims to build a social network, another type of user will be necessary, even though it will operate on a Back-Office Environment:
1. Administrators

Regarding the two key users for the Mobile Application, it will be required for them to **register** to the service and fill their profile with some mandatory information: _personal data_, _personal snapshot_ and _field of study/interest_.
After **logging in**, they can choose to _Search for Private Lessons_ (filtered, at least initially, by chosen _field of study/interest_) or _Offer Private Lessons_ by compiling a form with some mandatory and optional informations.
An user in need of a private lesson can start to schedule a meeting with an offerer. During the scheduling the application will allow the users to send _instant messages_ to communicate and to _check reviews_ about the other user, other than, of course, negotiate the _date of meeting_ and other _meeting details_.
After a certain time after every meeting, both actors will be able to send a review about the meeting in order to give future users a better way to find an appropriate match for their needs.

In the ideal scenario, the application will be presented to the higher-ups of the University in order to be officially promoted.

## **REQUIREMENT ENGINEERING**

The first step of _Software Development_ is **Requirements Engineering**. **Requirements Engineering** is fundamental in order to fully understand and define what the _Software TO-BE_ should accomplish in a **context** full of determined _assumptions_ and _properties_.
In **Requirements Engineering**, **Requirements Elicitation** is the practice of researching and discovering the requirements of a system.
A standard **Elicitation Strategy** usually starts with a complete analysis of the _Software AS-IS_, in order to find a set of weaknesses that need to be addressed by the software solution that is going to be developed; in this case, though, since **UNIMIB Tutoring Assistant** is a to-be-developed _Mobile Application_, a good approach to start with **Requirements Elicitation** is to gain knowledge about the software domain through a **Background Study**.

## **BACKGROUND STUDY**

//TODO: **Background Study** is an ARTEFACT-DRIVEN ELICITATION TECHNIQUE
//TODO: Aggiungere Refs e qualche info in più se possibile

Il mondo delle ripetizioni è un mondo vasto, le bacheche dell'università e i siti internet sono pieni di annunci di persone che cercano o che vogliono erogare ripetizioni. 
Esistono già siti come TrovaRipetizoni, piattaforma creata da degli studenti che cerca di creare una rete molto ampia (tutta Italia) e quindi non ancora può fornire una copertura adeguata o applicazioni come Bravoapp, che fornisce la possibilità di sottoscrivere abbonamenti mensili per gli insegnanti e di effettuare ricerche gratuite per chi cerca ripetizioni.
Un altro caso di studio è SuperProf.it, anche questo sito permette di cercare degli studenti che facciano ripetizioni in una zona selezionata. Un punto di forza di questa piattaforma è sicuramente la possibilità di dare lezioni online, attraverso l'utilizzo di Skype, Hangouts o FaceTime. In questo modo è possibile seguire/fornire una ripetizione direttamente da casa propria. 
Un'app molto simile, che permette di tenere lezioni anche a grandi distanze è iTeach, essa utilizza internet per gestire la comunicazione tra le parti.
Il nostro obiettivo è differenziarci un minimo da questi applicativi, localizzandoci in un luogo preciso, dando la possibilità anche a chi eroga una ripetizione di poter lasciare un feedback (cosa che non accade in altri applicativi esistenti) e quindi cercando di agevolare l'esperienza universitaria dei nostri studenti sotto ogni aspetto.
Questa applicazione può essere un ulteriore possibilità di contatto e condivisione tra università e studenti.

## **ELICITATION STRATEGY OVERVIEW**

// TODO: comunque anche background study fa parte dell'elicitation; in questo caso è ok metterlo a priori ma va giustificata la cosa
//TODO: Ampliare, specificare seconda fase: artifact-driven (questionario, scegliere studenti principalmente della bicocca perché possono esserci problematicità specifiche. intervista con domande chiuse e brevi per ridurre costi e non scocciare l'intervistato che comunque è uno studente e non ha voglia. parlare anche del metodo di distribuzione fisico (link distribuito come?)) e prima fase: stakeholder-driven (intervista (l'intervista può essere strutturata e non, è usata per raccogliere reqs parlando con stakeholders/cliente))

Dopo una prima analisi del background, si procede a parlare con il CEO del progetto e a decidere la strategia migliore per ottenere informazioni dagli stakeholders. 
Una volta ottenute tutte le informazioni necessarie, se questi requisiti non vanno in conflitto con quanto richiesto dal CEO si può procedere con la creazione dell'applicazione.
Se l'applicazione creata è fattibile allora si può concludere lo studio.
Segue uno schema riassuntivo della strategia:

//TODO: img: assets/SE.png

## **STAKEHOLDERS**

//TODO: DomUnderstandingAndReqElicitation.pdf->P4 ===> Introduzione di perché sono stati scelti i stakeholder (=ispirandosi alla letteratura è stato scelto X perché Y), Rivedere gli stakeholder (non serve filtro di età)

L'applicazione si rivolge principalmente agli studenti dell'università Milano-Bicocca, con la possibilità di estendersi in molti altri atenei italiani.

Gli stakeholder interessati sono:

* CEO: si tratta del committente dell'applicazione, in quanto finanzia tutta l'attività di sviluppo, di integrazione e si relaziona direttamente con l'ateneo.

* UTENTE: si tratta dell'attore principale dell'applicazione, può essere uno studente che ha bisogno di aiuto oppure uno studente che eroga ripetizioni.

* UNIVERSITÀ: essa potrebbe incentivare l'utilizzo dell'applicazione fornendo delle aule in cui ritrovarsi e magari creando delle classi di ripetizioni con più studenti contemporaneamente.

* TEAM DI SVILUPPO: composto da programmatori ed ha l'obiettivo di realizzare l'applicazione mobile, disponibile sia su Android che su iOS.

## **PLAN**

//TODO

## **PRESENTATION OF INTERVIEW**

//TODO

## **RESULT OF THE INTERVIEW**

//TODO

## **PRESENTATION OF QUESTIONNAIRE**

//TODO

## **RESULT OF THE QUESTIONNAIRE**

//TODO