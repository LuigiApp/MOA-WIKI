# 06 – Process Risk Gate

## Obiettivo della fase

Classificare ogni agente in funzione del rischio che introduce nel processo e definire il livello minimo di controllo richiesto.

**Domanda guida.** Se questo agente sbaglia, cosa può succedere?

La Risk Class indica dove approfondire. Non sostituisce le valutazioni normative, che restano in capo al cliente.

## Criteri di punteggio

Ogni dimensione si valuta su una scala da 1 a 5, dove 1 indica un rischio basso e 5 un rischio alto.

| Dimensione | Cosa misura | 1 | 5 |
| --- | --- | --- | --- |
| Data Risk | Sensibilità dei dati utilizzati dall'agente | Dati non sensibili e affidabili, accessibili solo a utenti già autorizzati | Dati personali o riservati, di affidabilità incerta, con regole di accesso ancora da definire |
| Decision Risk | Peso delle decisioni su cui l'agente incide | Decisioni di routine, facilmente correggibili, con effetti solo interni | Decisioni difficilmente reversibili, con effetti su clienti, fornitori o dati contabili |
| Business Impact Risk | Entità del danno in caso di errore dell'agente | Un errore comporta una perdita di tempo limitata per pochi utenti | Un errore causa perdite economiche, fermi operativi o danni ai clienti |
| Autonomy Risk | Grado di autonomia dell'agente rispetto al controllo umano | L'agente consulta i dati e formula proposte; ogni azione è approvata da una persona | L'agente esegue azioni sui sistemi in autonomia, senza approvazione preventiva |
| Adoption Risk | Grado di cambiamento introdotto nel modo di lavorare | Supporto al singolo utente; il processo resta sostanzialmente invariato | Processo trasformato per un intero team; sono necessari formazione e change management |

## Risk Class

| Classe | Significato |
| --- | --- |
| Green | Basso rischio |
| Yellow | Rischio medio |
| Orange | Rischio elevato |
| Red | Rischio critico |

I controlli per ogni classe sono nel capitolo [07](07-governance-controls.md).

## Esempio – Visit Preparation Agent

| Dimensione | Punteggio | Motivazione |
| --- | --- | --- |
| Data Risk | 3 | Utilizza CRM, storico visite e informazioni sul cliente. |
| Decision Risk | 2 | Supporta il commerciale senza decidere al suo posto. |
| Business Impact Risk | 2 | Un output errato può ridurre l'efficacia della visita. |
| Autonomy Risk | 2 | Propone informazioni; la decisione resta all'utente. |
| Adoption Risk | 3 | Modifica il processo di preparazione della visita. |

**Risk Class: Yellow**

**Strumento:** foglio Process Risk Gate. A partire dai 5 punteggi, il foglio calcola Risk Score e Risk Class.
