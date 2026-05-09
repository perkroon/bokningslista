# Bokningslista för tvättstuga

En enkel webbsida som genererar utskriftsbara bokningsscheman för en gemensam tvättstuga.

Öppna `index.html` i en webbläsare. Sidan visar automatiskt 12 månader framåt från dagens datum. Skriv ut med Cmd+P (Mac) eller Ctrl+P (Windows) och välj liggande A4.

Om markeringarna inte syns i utskriften, aktivera "Skriv ut bakgrunder" (eller motsvarande) i utskriftsdialogen. Vissa webbläsare (Chrome) gillar att skriva ut sidhuvuden och sidfötter, men dessa kan också stängas av.

Enklare ändå är att öppna följande länk i webbläsaren: https://perkroon.github.io/bokningslista/

Endast testad i ett fåtal webbläsare och med en enda skrivare.

## Bokningsregler

- **Lördag och söndag före kl. 12.00** – tvättstugan får ej användas (markerad med mönster).
- **Fredag kl. 20.00–22.00** – obokningsbar tid, först till kvarn (markerad med grått).

## Framtida förbättringar

- Dynamisk konfiguration: definiera vilka tidsintervall som ska gälla per dag, och specialregler för vissa dagar.
