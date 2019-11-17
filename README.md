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

1. **Domain Understanding**: this phase is fundamental for **identifying the Stakeholders** and for studying _Application Domain_ and _Business Organization_.
2. **Requirements Elicitation**: this phase regards researching and discovering the requirements of a system.

## **DOMAIN UNDERSTANDING: IDENTIFYING THE STAKEHOLDERS**

The core subject of **Domain Understanding** is to find a representative set of **Stakeholders** required in order to understand _from_ them and _with_ them what is required for the _Software TO-BE_ to accomplish.

As it is known from literature, there are some relevant aspects to consider for **Stakeholders** selection; some of them are:

1. Their position in the target organization.
2. Their role in making decision about the _System TO-BE_.
3. Their exposure to the perceived problem or required need.
4. Their level of Domain expertise.

With these key aspects in mind, a first set of **Stakeholders** was chosen; _it is important to note_ that since **Requirements Engineering** is an iterative process, more **Stakeholders** could be added to the list after **Requirements Elicitation** or after a full cycle of development.

> **STAKEHOLDERS LIST**

1. **Product Owner: the professor in charge of the project**: a professor was appointed from the University to handle the management of the project obtained from the _public competition_. They will keep in touch with the developers during all the stages of development to guide and help them. Furthermore, they are helping to set up the project thanks to their knowledge and experience in Project Managing: this is the reason why they are a mandatory _Stakeholder_ to consider in the **Requirements Engineering**.
2. **Developers Team**: they are a necessary _Stakeholder_ because their input is mandatory **before** the development start in order to estimate the _requirements_ and decide the technologies for the development (for instance, are they more confident with hybrid or native development?).
3. **Head of IT of the University of Milano-Bicocca**: this _Stakeholder_ was considered required for many reasons: with their expertise they could guide the developers through problems of legal values, economic values, etc. In addition, they could help identifying other useful _Stakeholders_ (for instance, a _Stakeholder_ that could provide the developers a Server for the App Database). Lastly, they could help the developers with some exposure through existing systems of the _University of Milano-Bicocca_.
4. **Students from the University of Milano-Bicocca**: they are the most important _Stakeholder_ as they are the final user; they are split in two classes:
	1. **Students who search for private lessons**.
	2. **Students who offer private lessons**.
5. **UX/UI Expert**: could be a useful _Stakeholder_ since the main focus of the Mobile App is offering a modern, immediate but complete feel.

## **REQUIREMENTS ELICITATION: ELICITATION STRATEGY OVERVIEW**

This section provides an in-depth description of the elicitation activities plan.

As previously mentioned, **Requirements Elicitation** is the second step of **Requirements Engineering** and its objective is researching and discovering the requirements of a system, mostly (but not exclusively) by interacting with the identified _Stakeholders_ through different **Elicitation Techniques**.

**Elicitation Techniques** can be classified into two classes:

1. **Artefact-Driven Elicitation Techniques**: some of these techniques comprehend:
	1. **Background Study**: it is used to gain knowledge about the software domain.
	2. **Questionnaires**: they provide access to subjective information quickly, cheaply and, if needed, remotely. They are also helpful for preparing better focused _Interviews_.
	3. **Prototypes and Mock-ups**: they allow concrete (but, of course, limited) exploration of the _Software TO-BE_.
	4. And more.
2. **Stakeholder-Driven Elicitation Techniques**: some of these techniques comprehend:
	1. **Interviews**: they are the primary technique for knowledge elicitation. There are two types of interviews:
		1. **Structured Interviews**: they are focused on a specific purpose and thus they must provide a predetermined set of questions.
		2. **Unstructured Interviews**: they allow for free discussion and do not need a predetermined set of questions.
	2. **Group Sessions**: they can be **Structured** and **Unstructured** and generally concede wider exploration of issues and ideas coming from the _Stakeholders_.
	3. And more.

A standard **Elicitation Strategy** usually starts with a complete analysis of the _Software AS-IS_, in order to find a set of weaknesses that need to be addressed by the software solution that is going to be developed; in this case, though, since **UNIMIB Tutoring Assistant** is a __to-be-developed__ _Mobile Application_, a good approach to start with **Requirements Elicitation** is to gain knowledge about the software domain through a **Background Study**.

Given this assuption, the chosen **Elicitation Strategy** for **UNIMIB Tutoring Assistant** is structured as it follows:
1. **Background Study**: to gain knowledge about the software domain, mostly through the analysis of system in the same domain (the domain of private lessons). The main objective of this activity is to discover some features that will render **UNIMIB Tutoring Assistant** unique in its domain, and produce _requirements_ starting from them.
2. **Questionnaire for students from the University of Milano-Bicocca**: the questionnaire aims to collect as much data as possible from the final users: the students. It will be divided in two sections to separate students offering private lessons from students who are in need of private lessons. It will be required that the students are enrolled to the _University of Milano-Bicocca_ because they could offer insight about some difficulties related to the University (for instance, availability of study halls); no other restriction is needed for the sample to be adequate to required needs. For the questionnaire to be effective, the questions will be short, weighting and mostly closed-ended to avoid that their compiling proves laborious. The questionnaire will be created through Google Forms and submitted to students with the help of **the professor in charge of the project**. The data collected will be used to produce particular _requirements_ based on the final users needs.
3. **Interview with the Head of IT of the University of Milano-Bicocca**: the interview with the _Head of IT_ should be the first one to be executed as it is needed to find potential criticalities of legal values, economic values, etc. and it can give insight on how to treat them. The interview should be **Unstructured** and its output would be a set of _feasible_ and _necessary_ requirements for what is the University concern.
4. **Interview with a sample of students who offer and receive private lessons (not necessarily from the University of Milano-Bicocca)**: this interview will heavily use the output from the _questionnaire_ in order to gain information from the students sample. For this interview, the students are considered **experts of domain** and not **final users**. The interview will be **Structured**, as a set of questions will be presented to the interviewed. The expected output of this activity is a set or _requirements_ focused on the private lessons domain.
5. **Interview with an UX/UI Expert**: the interview with the _UX/UI Expert_ should be the last one to be executed. The expertise of the _UX/UI Expert_ should help produce _requirements_ to improve the UX/UI of the _Mobile Application_ (the UX/UI is needed to be as performant as possible, as stated in the Application Overview). Since the objective of this interview is to obtain as many informations as possible from the interviewed expertise, the interview should be **Unstructured**.

Below, a visual representation of the **Elicitation Strategy**:

![](assets/ES.png)

In the next sections will be presented in-depth considerations about three activities of the elicitation plan: **Background Study**, **Questionnaire for students from the University of Milano-Bicocca** and **Interview with a sample of students who offer and receive private lessons (not necessarily from the University of Milano-Bicocca)**.

## **BACKGROUND STUDY**

//TODO

## **PRESENTATION OF QUESTIONNAIRE**

//TODO

## **RESULT OF THE QUESTIONNAIRE**

//TODO

## **PRESENTATION OF INTERVIEW**

//TODO

## **RESULT OF THE INTERVIEW**

//TODO