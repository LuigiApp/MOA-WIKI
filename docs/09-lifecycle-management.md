# 09 – Lifecycle Management

## Obiettivo della fase

Tenere traccia di ogni agente dopo l'attivazione: in che stato si trova, quale versione è in uso, quando è stato rivisto e quando va dismesso.

## Campi da compilare nel foglio Agent Lifecycle

| Campo | Significato | Esempio |
| --- | --- | --- |
| Agent ID | Codice dell'agente nel registro. | AG-001 |
| Agent Status | Stato nel ciclo di vita. | POC, Pilot, Production, Retired |
| Versione | Versione dell'agente in uso. | v0.1 |
| Wave / Priorità | Classe che arriva dallo scoring. | Wave 1 / Priority |
| Ultima Review | Data dell'ultima revisione. | 15/01/2027 |
| Prossimo Gate | Passaggio successivo da approvare. | Kickoff / POC |
| Retirement Trigger | Condizione che porta alla dismissione. | Da definire |

## Regola

Il ciclo di vita è POC → Pilot → Production → Retired. Il Pilot è previsto solo per agenti complessi, a rischio più elevato o che richiedono un percorso di adozione strutturato; negli altri casi si passa da POC a Production.

**Strumento:** foglio Agent Lifecycle, una riga per ciascun agente attivato.
