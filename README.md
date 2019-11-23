# Ender-3 profily pro Prusa Slicer

Průša Slicer stahujte zde: [https://github.com/prusa3d/PrusaSlicer/releases](https://github.com/prusa3d/PrusaSlicer/releases).
 
Základní profil pro běžný tisk s PLA. Teploty jsou nastaveny univerzálně na 205/60. Tento profil je vhodný pro a optimalizovaný pro Ender-3 bez nějakých úprav. Pokud máte Ender-3 s nějakými úpravami, bude možná potřeba si pohrát s některými parametry tisku.

## GCODE
Startovní skript obsahuje GCODE pro očištění trysky před tiskem na levé straně tiskové plochy. Pokud tam máte sponu pro přichycení skla, doporučuji přesunout cca 3cm od levého okraje.

Koncový GCODE pak vypne větrák a nahřívání hotendu a podložky, zvedne Z osu o 30mm, přesune hotend do domovské pozice a následně vysune desku dopředu.

## Instalace
Profil přidáte do sliceru přes položku v menu `Soubor -> Importovat -> Importovat Konfiguraci`.

### Uložení profilů
Pro trvalé uložení profilů je potřeba na každé ze záložek kliknout na disketu vedle názvu profilu, a profil přejmenovat. **Bez přejmenování se vám profily neuloží**. Je potřeba toto udělat na všech záložkách, čili u `Nastavení tisku`, `Nastavení filamentu` a také u `Nastavení tiskárny`
