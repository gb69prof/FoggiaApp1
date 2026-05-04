# FoggiaApp PWA PRO v5

Versione corretta con:

- collegamento alla Home principale sia dalla testata/logo sia dai percorsi;
- pulsante di ritorno alla Home anche in fondo alla pagina del percorso;
- lingua IT/EN disponibile dalla barra superiore;
- approfondimenti storici estesi per le quattro tappe: Origini di Foggia, Borgo Croci, Cappellone delle Croci, Museo Civico/Sistema museale;
- sottopercorsi: Storia e tappe, Cosa fare oggi, Dove mangiare;
- preferiti salvati in locale tramite localStorage;
- manifest e service worker per installazione PWA.

Per test locale aprire `index.html`; per test PWA reale usare un piccolo server locale o GitHub Pages.


## Aggiornamenti v5
- Geolocalizzazioni corrette: Piazza del Lago, Museo Civico, Cappellone delle Croci, Borgo Croci, Epitaffio, Teatro Giordano.
- I collegamenti di ritorno alla Home puntano a `index.html`, non a `index.html#...`.
- Approfondimenti storici disponibili anche in inglese tramite il pulsante lingua IT/EN.


## Aggiornamento v6.1
- Traduzione EN attiva anche per gli approfondimenti storici completi delle quattro tappe principali.
- Villa Comunale geolocalizzata a 41.4619459947452, 15.553038856888758.
- Cache del service worker aggiornata per evitare residui della versione precedente.
