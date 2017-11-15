# Batdistribution2017
Dette er et prosjekt på utbredelse hos flaggermus i Norge. I denne mappen finnes noe data samlet inn på prosjektet frem til og med 2017. I tillegg vises det R-koder som er brukt for å se om prediktiv modellering kan bidra til å øke "kunnskapen" om flaggermusenes utbredelse i Norge. Målet med prosjektet (litt frem i tid) er å kunne angi en sannsynlighet for en bestemt art, diversitet, aktivitet osv i alle arealer i hele landet. 

## Innhold
Denne mappen inneholder følgende;

**Datasett** samlet inn med ultralydlydloggere, med ferdige prediktorvariabler for dvergflaggermus og diversitet. Dette er to av mange responsvariabler som etter hvert skal med i analyser. Resten av datasettene gjøres ikke tilgjengelig i 2017.

**Modeller** for et pilotprosjekt som har som formål å predikere utbredelse hos dvergflaggermus og en generell modell for flaggermusdiversitet. Dette er ikke en endelige modeller, men viser noe av potensialet for denne tilnærmingen med et ufullstendig datasett. Ikke alle prediktorvariabler finnes som shape/raster filer pr 2017. Det blir derfor ikke brukt tid på fine-tuning av modellene.

**Prediktorer** som anvendes er knyttet til klima, habitat, topografi og lattitude. Det finnes en egen tekstfil (predictors.txt) som beskriver hva disse står for og hvor de er hentet fra via GIS verktøy. Merk at dette ikke er det endelige settet med prediktorer. Feks har jeg ikke inkludert en generell habitatvariabel - hvilket nok vil hjelpe modellene.

**Kart** Det legges til figurer produsert i QGIS som viser hvor dataene stammer fra. Pr 2017 er det vesentlige geografiske skjevheter med tanke på hvor dataene er samlet inn.

**Merk** altså at dette er en *pilotstudie* og ikke endelige data eller endelige modeller. Jeg har derfor tatt litt lett på enkelte ting. Det endelig datasettet skal inneholde mer enn 400 datapunkt (pr i dag er det 282). Man kan vente vesentlige endringer i forhold til både valg av modeller, variabler og prediksjoner når prosjektet sluttføres i ikke så alt for fjern fremtid.

**Hvis** noen vil leke seg med dataene, så gjør gjerne det ^ô^
