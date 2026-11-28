# Changelog

All notable changes to Stint Compare. Newest first.
Ogni versione ha le note in inglese e in italiano.

<!--
HOW TO ADD A VERSION / COME AGGIUNGERE UNA VERSIONE
Copy the block below above the latest version, change the number and the date, write the changes.
The publishing script takes the text between "## [x.y.z]" and the next "## [" as the release notes.
Copia il blocco qui sotto sopra l'ultima versione, cambia numero e data, scrivi le novità.
The script adds "Verify your download" (SHA-256 of the zip + VirusTotal link) at the end of the version /
il riquadro "Verify your download" (SHA-256 dello zip + link VirusTotal) lo aggiunge lo script in fondo alla versione.

## [1.0.1] - 2026-12-01
### English
- ...
### Italiano
- ...
-->

## [1.1.0] - 2026-11-28
### English
- **SimHub dashboard**: a SimHub button at the top opens the page of "Stint Compare – SimHub Dashboard" and turns green when a newer dashboard is out; Settings > SimHub shows the version installed in SimHub and the latest published one (and whether it needs a newer Stint Compare). Also sky (`skies`) and rain (`rainPct`) for the dashboard (data contract revision 10).
- Laps tab: six boxes (best lap, ideal lap, last lap, average pace, standard deviation, fuel range); sky icon and rain % columns; "n/d" when the fuel of a lap is not known.
- Compare tab: boxes in the order best lap, average pace, consistency, fuel, tyre wear; tread left at the end of A and B for the 4 tyres (when both have it).
- Race pace: the chart only with the stints of one race; with stints of different sessions it is switched off with a note.
- Overlay: tyres above the comparison; the delta boxes show from the start; average of the cumulative = cumulative ÷ laps completed; it comes back in front of the game by itself every few seconds.
- Settings: link to the project page on GitHub.
- New option in Settings > SimHub: publish the live data for the Stint Compare plugin and dashboard in SimHub (off by default; local only, no network; never setup values). All the fields of the data contract (revision 8): laps of the stint, lap rows, reference, standings and nearby cars with names and iRating, last 5 laps, tyre stints, units and tyre colours; it keeps writing while iRacing is closed.
- Library: "Delete selected" and "Empty all" buttons; no row is highlighted by itself, so any click makes stint A.
- "Report for AI" button next to Overlay; the report never contains setup values.
- Setup saving now needs your consent (Settings), with a green/red notice on the Setup page.
- Discord button in the header.
- Tyres changed at a stop are shown tyre by tyre (4 sections, for cars that change single tyres), also for SimHub.
- Drivers are shown as "Surname F." everywhere; alternating row shades in the overlay lists and the Library.
- Lap chart: yellow, pit and race-start laps flattened to the average pace, with zoom. Sky and rain in the overlay.

### Italiano
- **Dashboard SimHub**: un tasto SimHub in alto apre la pagina di "Stint Compare – SimHub Dashboard" e diventa verde quando ne esce una versione più nuova; in Impostazioni > SimHub si vedono la versione installata in SimHub e l'ultima pubblicata (e se richiede uno Stint Compare più nuovo). In più cielo (`skies`) e pioggia (`rainPct`) per la dashboard (contratto dati revisione 10).
- Scheda Giri: sei riquadri (miglior giro, giro ideale, ultimo giro, passo medio, deviazione standard, autonomia); colonne con l'icona del cielo e la % di pioggia; "n/d" quando il consumo di un giro non è noto.
- Scheda Confronto: riquadri nell'ordine miglior giro, passo medio, consistenza, benzina, usura gomme; battistrada rimasto a fine stint di A e B per le 4 gomme (quando entrambi lo hanno).
- Passo gara: il grafico solo con gli stint di una stessa gara; con stint di sessioni diverse si spegne e spiega perché.
- Overlay: gomme sopra il confronto; i box dei delta si vedono da subito; media del cumulativo = cumulativo ÷ giri completati; torna da solo davanti al gioco ogni pochi secondi.
- Impostazioni: link alla pagina del progetto su GitHub.
- Nuova opzione in Impostazioni > SimHub: pubblica i dati in diretta per il plugin e la dashboard Stint Compare in SimHub (spenta di partenza; solo su questo PC, niente rete; mai valori del setup). Tutti i campi del contratto dati (revisione 8): giri dello stint, righe giro per giro, riferimento, classifica e auto vicine con nomi e iRating, ultimi 5 giri, stint gomme, unità e colori gomme; continua a scrivere anche con iRacing chiuso.
- Libreria: tasti "Elimina selezionati" e "Svuota tutto"; nessuna riga evidenziata da sola, così ogni clic rende lo stint A.
- Tasto "Report per AI" accanto a Overlay; il report non contiene mai i valori del setup.
- Il salvataggio del setup ora richiede il tuo consenso (Impostazioni), con un avviso verde/rosso nella pagina Setup.
- Tasto Discord in alto.
- Le gomme cambiate a una sosta si vedono una per una (4 sezioni, per le auto che le cambiano singolarmente), anche per SimHub.
- Piloti mostrati ovunque come "Cognome N."; righe a due tonalità negli elenchi dell'overlay e in Libreria.
- Grafico giri: giri in gialla, ai box e di partenza appiattiti al passo medio, con zoom. Cielo e pioggia nell'overlay.

### Verify your download / Verifica il download
- SHA-256 (`StintCompare-1.1.0.zip`): `c29fca6023d8299b05da0b850027ac1ad8a81d4c499e13130db787c9ac79cd83`
- VirusTotal: https://www.virustotal.com/gui/file/c29fca6023d8299b05da0b850027ac1ad8a81d4c499e13130db787c9ac79cd83

## [1.0.0] - 2026-11-23
### English
- First public release of Stint Compare.
- Automatic recording of every lap, yours and the opponents', with sectors, weather, traffic and pit stops.
- Overlay for VR and monitors: live comparison, tyre temperatures, race grid, gaps; it steps aside by itself in the garage.
- Tyres, degradation with end-of-stint briefing, stint comparison, race pace, setup comparison.
- Report for Claude ready to analyse.

### Italiano
- Prima versione pubblica di Stint Compare.
- Registrazione automatica di tutti i giri, tuoi e degli avversari, con settori, meteo, traffico e soste.
- Overlay per VR e monitor: confronto in diretta, temperature gomme, griglia di gara, distacchi; nel garage si fa da parte da solo.
- Gomme, degrado con briefing di fine stint, confronto tra stint, passo gara, confronto setup.
- Report per Claude pronto da analizzare.

### Verify your download / Verifica il download
- SHA-256 (`StintCompare-1.0.0.zip`): `6b70aa9e20d1520792e89578f97138849d377c629ee61e19ddb901f48a1b5dd3`
- VirusTotal: https://www.virustotal.com/gui/file/6b70aa9e20d1520792e89578f97138849d377c629ee61e19ddb901f48a1b5dd3

