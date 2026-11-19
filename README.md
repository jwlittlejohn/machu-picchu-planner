# Machu Picchu trip planner

A single-page planner comparing five small-group Peru trips for six adults travelling in August 2027 from Toronto and Ottawa.

- **The trips:** three from Intrepid (Classic Peru, Premium Peru, Inca Encounter) and two from G Adventures (Amazon to Andes with Machu Picchu by Train; National Geographic Journeys: Machu Picchu and the Amazon).
- **Altitude terraces:** a bar for each night of the selected trip, showing how high you sleep.
- **Side by side:** price, length, route, what's included.
- **The places:** Lima, the Amazon, Cusco, the Sacred Valley, Aguas Calientes, Machu Picchu and Lake Titicaca.
- **Cost for six:** tour plus flights, editable as real quotes come in.
- **Help us decide:** two questions that narrow it to one trip.

## Editing

Everything is in `index.html`. Trip data is the `TRIPS` array and place descriptions are the `PLACES` object, both near the top of the script. Change a price there and the table, cost bars and recommendation all update.

## Caveats

Compiled November 18, 2026. Intrepid prices are August 2027 sale prices as quoted to the group. G Adventures prices are converted from US list prices and are estimates until confirmed. Night-by-night order for the two G Adventures trips is inferred from their tour pages.

## Publishing

Served with GitHub Pages from the `main` branch root.
