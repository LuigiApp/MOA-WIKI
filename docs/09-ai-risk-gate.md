# 09 – AI Risk Gate

## Obiettivo della fase

Classificare ogni agente in funzione del rischio e definire il livello minimo di controllo richiesto.

**Domanda guida.** Se questo agente sbaglia, cosa può succedere?

| Dimensione | Significato | Esempi |
| --- | --- | --- |
| Data Risk | Sensibilità dei dati utilizzati. | Low: pubblici; Medium: interni; High: clienti/personali/finanziari |
| Decision Risk | Quanto influenza le decisioni. | Informa, suggerisce, propone azioni, decide |
| Business Impact Risk | Impatto di un errore. | Perdita tempo, inefficienza, perdita economica |
| Autonomy Risk | Livello di autonomia. | 0 legge, 1 suggerisce, 2 esegue con approvazione, 3 autonomo |
| Adoption Risk | Impatto sul modo di lavorare. | Supporto individuale, nuovo processo team, trasformazione processo |

## Risk Class

| Classe | Significato | Controllo richiesto |
| --- | --- | --- |
| Green | Basso rischio | Controlli standard |
| Yellow | Rischio medio | Validazione IT Owner |
| Orange | Rischio elevato | Approvazione Steering AI |
| Red | Rischio critico | Governance dedicata e monitoraggio continuo |

## Esempio – Visit Preparation Agent

| Dimensione | Valutazione | Motivazione |
| --- | --- | --- |
| Data Risk | Medium | Usa CRM, storico visite e informazioni cliente. |
| Decision Risk | Low | Supporta il commerciale, non decide. |
| Business Impact Risk | Medium | Output errato può ridurre efficacia visita. |
| Autonomy Risk | Low | Propone informazioni, utente decide. |
| Adoption Risk | Medium | Cambia il processo di preparazione visita. |

Risk Class suggerita: Yellow – Medium Risk

## Riferimento al Calculator

Nel foglio AI Risk Gate ogni use case occupa una riga.Le dimensioni di rischio vengono valutate attraverso Data Risk, Decision Risk, Business Impact Risk,Autonomy Risk e Adoption Risk.Il Risk Score e la Risk Class vengono calcolati e utilizzati dalle successive attività di Governance & Controls.
