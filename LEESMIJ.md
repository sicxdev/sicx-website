# sicx.nl — website met beheerscherm (Pages CMS)

## Mappen
- site/                  de website (dit publiceert Netlify)
- site/content/          de inhoud die je in Pages CMS aanpast
  - investments.json     de investeringen
  - site.json            achtergrondkleur, bedrijfsnaam, info-tekst, KvK, e-mail
- site/media/logos/      logo's van investeringen
- .pages.yml             de formulieren van Pages CMS
- netlify.toml           vertelt Netlify dat de site in de map "site" staat

## Aanpassen
Log in op https://app.pagescms.org, kies de repository en pas aan onder
"Investeringen" of "Site-instellingen". Na opslaan staat de wijziging binnen
een minuut online.

## Tips
- Logo's: SVG (of PNG) met een donker logo op een transparante achtergrond.
- Achtergrondkleur: een hexcode zoals #161719. Het favicon en de
  deelafbeelding blijven #161719; die zijn vaste bestanden.
- Een investering tijdelijk verbergen: zet "Tonen op de website" uit.
