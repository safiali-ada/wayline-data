# Wayline data

Offline timetable bundles for the Wayline iOS app, rebuilt nightly from open data.
The app downloads them from this repo's releases; nothing here is edited by hand.

| City | Release | Sources |
|---|---|---|
| Rome | [`bundle-rome`](../../releases/tag/bundle-rome) | Roma Servizi per la Mobilità (Atac and partners: bus, tram, metro), Trenitalia regional trains |

Each release holds `<city>.manifest.json` (version, size, SHA-256) and the matching
`<city>-<timestamp>.sqlite.deflate` (a SQLite database, raw DEFLATE).

## Attribution
- Dati: Roma Servizi per la Mobilità — Atac
- Orari Trenitalia via CCISS NAP, GTFS by Clément Desouche ([trenitalia-gtfs](https://github.com/deryclem/trenitalia-gtfs)), CC BY 4.0
