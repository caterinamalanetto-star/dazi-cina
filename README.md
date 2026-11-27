# Dazi e Cina – dataviz Radar QN

Quattro dataviz interattive (HTML + D3 v7) nello stile Radar. Ogni numero viene da documenti istituzionali allegati.

| Pagina | Contenuto | Dati |
|---|---|---|
| `mappa-usa/` | Dazi Usa proposti il 25 novembre 2026 su 14 economie (cartogramma a tessere) | `data/ustr-dazi-proposti-2026-11-25.csv` |
| `dazi-bev/` | Dazi compensativi Ue sulle auto elettriche cinesi | `data/dazi-bev-ue.csv` |
| `pacchi/` | Calendario delle misure sui piccoli pacchi (Ue e Usa) | `data/pacchi-calendario.csv` |
| `ue-cina/` | Commercio Ue con i principali partner, terzo trimestre 2026 | `data/eurostat-q3-2026-partner.csv` |

## Fonti
Ustr (comunicato 25 novembre 2026; avvisi Ue e Cina); Commissione europea (reg. 2024/2754, decisione 2026/328, reg. 2026/1200, reg. delegato 2026/2152); Consiglio Ue (reg. 2026/382); Cbp (91 FR 37789); Eurostat (Q3 2026); Il Sole 24 Ore (1 novembre 2026, per l'abrogazione del contributo italiano e il commento al regolamento).

## Limiti
- Mancano dati ufficiali sulle importazioni di auto per alimentazione.
- Le tessere della mappa non sono in scala geografica.
- Il saldo Ue-Cina nel grafico è calcolato da Radar (importazioni meno esportazioni).
- Per le economie diverse da Ue e Cina la mappa riporta solo la proposta base e l'eventuale aliquota con accordo (comunicato Ustr).
