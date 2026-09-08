# mm2026-statistika — MM 2026 ennustusmängu statistika-plakat (ARHIIV)

Sõprade MM 2026 ennustusmängu lõpukokkuvõte: 96 mängu, 215 väravat, 16 ennustajat. Kaks staatilist lehte, avalik GitHub Pages: **https://aimarraid-netizen.github.io/mm2026-statistika/** (repo PUBLIC — sisu on sõprade eesnimed, teadlik valik nagu aquariumil). Mäng on läbi (juuli 2026), projekt on arhiiv; elav ennustusakvaarium sama mängu kohta oli `~/projects/aquarium/`.

## Failid
- `index.html` — "Statistika-trivia" plakat; kõik faktid on HTML-i sisse kirjutatud (fetch'i pole). Fondid Google Fontsist (avalik leht, CDN on siin OK — serveri sisevõrgus mitte).
- `profiilid.html` — "Psühhoanalüüs": 16 ennustaja karakterileht, lingitud plakatilt.
- `World Cup 2026 (1).xlsx` — lähteandmed (mängu tabel); `mm2026-bar-chart-race.csv/.xlsx` — kumulatiivsed punktid ennustaja × päev (11.06–19.07.2026) bar-chart-race'i tarvis (väline tööriist, lehel ei kasutata).

## Muutmine
Muuda HTML-i otse → commit → push = deploy (Pages deploy-from-branch). Öine auto-push katab. Numbrid tulevad xlsx-ist käsitsi — kui fakt muutub, kontrolli xlsx-ist, mitte mälust.
