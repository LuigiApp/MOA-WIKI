# 08 – Value Realization

## Obiettivo della fase

Definire come verrà misurato il valore generato da ogni agente.

**Regola.** Se non sappiamo misurare il valore, non possiamo dichiarare che l'agente genera valore.

## Campi da compilare nel foglio Value Realization

| Campo | Significato | Esempio |
| --- | --- | --- |
| Business Sponsor · Product Owner · IT Owner | Responsabili del valore, della soluzione e della parte tecnica. | Direttore Commerciale · Responsabile CRM · IT Manager |
| KPI principale | Indicatore primario che misura il miglioramento. | Tempo medio preparazione visita |
| Baseline | Situazione attuale prima dell'agente. | 45 minuti |
| Target | Risultato atteso. | 20 minuti |
| Metodo di osservazione | Come il KPI viene misurato. | Survey, CRM, log, Power BI |
| Frequenza | Ogni quanto si misura. | Mensile |
| Formula economica | Come si passa dal KPI agli euro. | Volume × Delta KPI × Costo unitario |
| Economic Value | Valore economico annualizzato, in euro. | 25.000 € |

Actual, Delta, Volume, Costo unitario e Confidence Level non hanno una colonna dedicata nel foglio: sono gli elementi su cui si costruisce la formula economica.

## Esempio – Visit Preparation Agent

| Campo | Valore |
| --- | --- |
| KPI | Tempo medio preparazione visita |
| Baseline | 45 minuti |
| Target | 20 minuti |
| Metodo di osservazione | Log CRM |
| Frequenza | Mensile |
| Formula economica | 1.000 visite × 30 minuti risparmiati × 50 €/ora |
| Economic Value | 25.000 € annui |

**Strumento:** foglio Value Realization, una riga per ciascuno use case attivato.
