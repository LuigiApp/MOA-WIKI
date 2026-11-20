# 07 – Governance & Controls

## Obiettivo della fase

Definire chi prende le decisioni su ciascuno use case e con quali controlli, in funzione del livello di rischio.

## Ruoli e responsabilità

| Ruolo | Responsabilità |
| --- | --- |
| AI Steering Committee | Indirizzo strategico, definizione delle priorità di portfolio, allocazione delle risorse. |
| Business Sponsor | Responsabile del valore: detiene il business case e i benefici attesi. |
| Product Owner | Responsabile della soluzione: requisiti, backlog e rilascio dell'agente. |
| IT Owner | Responsabile tecnico: dati, integrazioni e operatività. |
| AI Working Team | Responsabile tecnologico: architettura, modelli e piattaforme. |

## Decisioni governate

- **Portfolio:** inserimento degli use case, assessment, priorità, budget.
- **Execution:** POC, Pilot, go-live, scaling.
- **Value:** definizione dei KPI, validazione del valore, estensione o chiusura.
- **Risk:** accettazione del rischio, accesso ai dati, livello di autonomia dell'agente.

Per ogni decisione si indicano chi decide, chi contribuisce, chi approva e quali evidenze sono necessarie: MOA Score, Process Risk Gate, Value Realization.

## Campi da compilare

| Campo | Significato | Esempio |
| --- | --- | --- |
| Use Case ID | Collegamento allo use case. | UC-023 |
| Risk Class | Classe di rischio risultante dal Process Risk Gate (capitolo 06). | Green, Yellow, Orange, Red |
| Livello di Approvazione | Chi deve approvare in funzione della Risk Class. | Business Sponsor + IT Owner |
| Governance minima | Set minimo di controlli richiesti. | Review periodica, audit log |
| Organo Decisionale | Persona o organo che formalizza l'approvazione. | AI Steering Committee |
| Controlli richiesti | Controlli definiti in base alla Risk Class. | Human-in-the-loop, monitoraggio |

## Livelli di approvazione per Risk Class

| Risk Class | Chi approva | Controlli |
| --- | --- | --- |
| Green | Da definire | Controlli standard |
| Yellow | Business Sponsor + IT Owner | Light review, logging, KPI monitoring |
| Orange | Business Sponsor + approfondimento a cura del cliente | Formal review, human-in-the-loop, monitoraggio continuo |
| Red | AI Steering Committee | Full controls, audit trail, gate di rilascio |

**Strumento:** foglio Governance & Controls. Si compila dopo il Process Risk Gate, da cui arriva la Risk Class.
