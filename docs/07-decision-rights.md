# 07 – Governance & Controls

## Obiettivo della fase
Definire chi prende le decisioni su ciascuno use case e con quali controlli, in funzione del livello di rischio.

## Ruoli e Responsabilità

| Ruolo | Responsabilità |
| --- | --- |
| Steering Committee AI | Indirizzo strategico, definizione delle priorità di portfolio, allocazione delle risorse. |
| Business Sponsor | Responsabile del valore: detiene il business case e i benefici attesi. |
| Product Owner | Responsabile della soluzione: requisiti, backlog e rilascio dell'agente. |
| IT Owner | Responsabile tecnico: dati, integrazioni e operatività. |
| AI Working Team | Responsabile tecnologico: architettura, modelli e piattaforme. |

## Decisioni governate

- **Portfolio:** inserimento use case, assessment, priorità, budget.
- **Execution:** POC, Pilot,  go-live, scaling.
- **Value:** KPI, validazione valore, estensione o chiusura.
- **Risk:** accettazione rischio, accesso dati, autonomia agente.

Per ogni decisione si indicano chi decide, chi contribuisce, chi approva e quali evidenze sono necessarie: MOA Score, Process Risk Gate, Value Realization.

## Campi da compilare

| Campo | Significato | Esempio |
| --- | --- | --- |
| Use Case ID | Collegamento allo use case. | UC-023 |
| Risk Class | Classe di rischio risultante dal Process Risk Gate. | Green, Yellow, Orange, Red |
| Livello di approvazione | Chi deve approvare in funzione della Risk Class. | Business Sponsor + IT Owner |
| Governance minima | Set minimo di controlli richiesti. | Review periodica, audit log |
| Organo Decisionale | Persona o organo che formalizza l'approvazione. | Steering Committee AI |
| Controlli richiesti | Controlli definiti in base alla Risk Class. | Human-in-the-loop, monitoraggio |

## Livelli di approvazione per Risk Class

| Risk Class | Chi approva | Controlli |
| --- | --- | --- |
| Green | Da definire | Controlli standard |
| Yellow | Business Sponsor + IT Owner | Light review, logging, KPI monitoring |
| Orange | Business Sponsor + revisione del rischio | Formal review, human-in-the-loop, monitoraggio continuo |
| Red | AI Steering Committee | Full controls, audit trail, gate di rilascio |

Nel Calculator: foglio Governance & Controls, da compilare dopo il Process Risk Gate.
