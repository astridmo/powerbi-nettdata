# Nettdata for Power BI
Denne repositorien inneholder filer som benyttes for å inkludere kraftnettet på Vestlandet i kart-visualiseringer i Power BI for BKK.

## Bruk
Azure-kartene i Tilknytningssak-rapporten og TPV-rapporten har kraftnettet til Statnett, og evt. BKK i bakgrunn. Kraftnettet er lagt til som et referanselag til Azure-kartet.

Filene som blir brukt som referanselag er lagret under mappene `assets/output`, og er 2 ulike geojson-filer. 

For å få riktig URL:
* Gå inn på filen her på GitHub
* Trykk på **RAW** oppe til høyre
* Kopier URL-en og lim denne inn i Power BI.

Eksempel på link til transmisjonsnett: **https://raw.githubusercontent.com/astridmo/powerbi-nettdata/refs/heads/main/assets/output/linjer_trafo_transmisjon.geojson**

__Kilder:__
Data er for kraftlinjer og transformatorstasjoner er hentet fra NVE Atlas.
Data for kommunegrenser er hentet herfra: https://github.com/robhop/fylker-og-kommuner/tree/main 



