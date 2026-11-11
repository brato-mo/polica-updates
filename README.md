# polica-updates: kanal za ažuriranja

Ovdje su samo potpisani APK-ovi aplikacije i `version.json`, koji aplikacija čita da ponudi ažuriranje. Izvorni kod,
ključevi, adrese servera i lični podaci nisu ovdje.

- `prod/`: prava aplikacija (paket `ba.polica`).
- `test/`: TEST verzija (paket `ba.polica.test`, instalira se pored prave i nikad je ne zamjenjuje).

`version.json` ima broj verzije, kratki opis izmjena, veličinu, SHA-256 i adresu APK-a. Prije instalacije aplikacija
provjerava veličinu, SHA-256, ime paketa, versionCode i isti potpisni certifikat kao instalirana verzija. Android
uvijek traži potvrdu korisnika, a podaci aplikacije ostaju.
