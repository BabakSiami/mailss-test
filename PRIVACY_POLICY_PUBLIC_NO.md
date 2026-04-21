# Personvernside (offentlig) - ferdig mal

Sist oppdatert: 2026-04-21

## Slack Flash Alert - Personvern

Slack Flash Alert er et lokalt nettleserverktøy for Slack Web. Verktøyet er uoffisielt og er ikke tilknyttet Slack Technologies, LLC.

## Hva verktøyet gjør
Verktøyet viser tydelige varsler for nye meldinger i kanaler brukeren selv velger i Slack Web.

## Hvilke data som behandles
- Kanal-ID-er som brukeren velger
- Workspace-ID fra Slack URL
- Innstillinger (for eksempel lyd på/av og varsel-tider)
- Meldingsinnhold som vises i den åpne Slack-fanen for å kunne lage lokale varsler

## Hvordan data brukes
- Kun for å vise varsler i brukerens egen nettleser
- Ingen bruk til annonser, profilering eller analyse

## Deling av data
- Ingen deling med tredjepart
- Ingen ekstern backend for denne utvidelsen

## Lagring
- Innstillinger lagres lokalt i `chrome.storage.local`
- Data blir i brukerens nettleserprofil med mindre brukeren selv sletter data/profil

## Tillatelser
- `storage`: lagre innstillinger lokalt
- `tabs`: finne aktiv Slack-fane
- `scripting`: kjøre innholdsskript i Slack-fanen
- `https://app.slack.com/*`: nødvendig for funksjon i Slack Web

## Sletting av data
Bruker kan slette data ved å:
1. Åpne utvidelsens innstillinger
2. Tømme kanalvalg
3. Eventuelt fjerne utvidelsen fra nettleseren

## Kontakt
For spørsmål: [kontakt Babak Siami.](mailto: babak.siami@fvn.no)
