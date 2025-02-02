## Python op je eigen computer
<!--REF\label{/informatie/installatie}-->

In dit vak gaan we met Python werken. We werken met scripts en macro's. 
Waarschijnlijk heb je eerder al, bijvoorbeeld bij Inleiding Programmeren, je eigen versie van python geïnstalleerd met Anaconda en heb je al een programma, zoals Visual Studio code waarin je de scripts kunt schrijven. 

Hieronder staan instructies om een nieuwe python omgeving te maken in anaconda waarin we in dit vak gaan werken. Hierbij hoort ook een testfile om te kijken of alle pakketten goed zijn geïnstalleerd. 

**Mocht je nog helemaal geen installatie hebben** dan vind je onderaan de pagina instructies om Anaconda en Visual Studio code te installeren. Houd er wel rekening mee dat we voor dit vak voorkennis van programmeren verwachten. 

### De DAS omgeving
Als je nog geen Anaconda hebt geïnstalleerd, doe dat dan eerst met de instructies onderaan de pagina, en kom dan hier terug. 

> 1. **Start een terminal**<br> 
> Je moet eerst een terminal openen. Dit kan op verschillende manieren. <br>
<!-- >  - Open Visual Studio Code en type de sneltoets combinatie  Ctrl + \` (tegelijk de Ctrl of command toets met een \`). Je kan ook een terminal openen vanuit het menu.<br>-->
>  - MacOS: Applications -> Utilities -> Terminal<br>
>  - Windows: Start -> Anaconda3 -> Anaconda Prompt
> 
> 2. **Maak een nieuwe conda omgeving voor DAS**<br>
> Met het volgende commando heb je een nieuwe python omgeving gemaakt speciaal voor dit vak. 
>
> 			conda create -n das matplotlib numpy lmfit -c conda-forge 
> 
> 3. **Maak een nieuwe map aan voor DAS**<br>
> 	- Ga naar een geschikte map op je computer (bijvoorbeeld Natuur-Sterrenkunde -> jaar 1) en maak daar een nieuwe map aan voor DAS
> 
> 4. **Open je nieuwe map voor DAS in Visual Studio Code**<br>
> 	- Open Visual Studio Code
> 	- Ga naar file -> open folder en kies de map voor DAS
> 
> 5. **Instellingen Visual Studio Code - Windows Computer**<br>
> 	- Kies file -> preferences -> settings of druk op ctrl-, (control komma)
> 	- Type bovenin het zoekvenster 'terminal integrated default profile windows'. Je ziet nu de juiste setting bovenaan staan. 
> 	- De instelling staat standaar op null, maar kies command prompt. 
> 
> 6. **Installeer de python-extensie voor Visual Sutio Code**<br>
> 	- Ga naar het 'blokjes' icoon in de linkerbalk en zoek de python extensie *of* open een terminal en type: 'code --install-extension ms-python.python'
> 
> 7. **Activeer je nieuwe conda omgeving**<br>
>  - Activeer in Visual Studio de das conda omgeving door eerst een *Command Palette* te openen met (Cmd+Shift+p) in MacOS en (Ctrl+Shift+p) in Windows. Je typt dan *Python: Select Interpreter*. Scroll dan in de lijst naar beneden om je net (in punt 2.) gemaakte **das** omgeving te vinden (waarschijnlijk onderaan).<br>
> Het activeren hoef je, als het goed is, maar één keer te doen. Als je VSCode afsluit en weer opstart wordt de das omgeving vanzelf weer geactiveerd. Je kan dit zelf controleren, linksonder in de blauwe balk zie je als het goed is het volgende staan: Python 3.10.0 64-bit ('das':conda)
> 8. **Controleren of je in de juiste omgeving zit**<br>
>  nu of je omgeving werkt door een testfile te runnen. Download de [testfile](AllePakketten.py), voeg hem toe aan je werkfolder voor dit vak en probeer hem te draaien. Dit kan je in VSCode op verschillende manieren doen. Een handige manier door de file eerste te openen en dan op de 'play' button te drukken (rechtsboven, gekantelde driehoekje). Je hoort, na een tijdje, de volgende output in de terminal te zien: 
> 
> 			Even controleren of je installatie helemaal werkt... 
> 			... Je bent geslaagd!
> 
> Als je deze output niet ziet, dan is er een probleem met je
> installatie. Neem dan contact op met de assistent.


### Een nieuwe python/editor installatie

Als het goed is heb je in het eerste periode het vak Inleiding programmeren gevolgd. Als het goed is zou alles goed moeten werken en kan je terug naar boven gaan om een DAS omgeving te creëren. Volg deze instructie dus alleen als je nog geen Anaconda of editor hebt geïnstalleerd.

#### Stap 1: Anaconda

Dit pakket kunt je downloaden op de [website](https://www.anaconda.com/products/distribution). 
Kies daar voor de “Anaconda Individual Edition”. De download is vrij groot, het kan dus even duren voordat het klaar is!

Zodra de download klaar is, moet je het gedownloade bestand uitvoeren. Volg dan de installatieinstructies en kies waar nodig voor “Install for me only”; 

**Let op: het is belangrijk om het laatste venster (Advanced Installation Options) de tweede optie _Add Anaconda3 to my PATH environment variable_ aan te vinken! Het is aan te raden om alles aan te vinken**

![Anaconda setup window](anacondasetupwindow.png){:width="50%"}<br>

#### Stap 2: Visual Studio Code

Dit pakket kun je downloaden op de website van [Microsoft](https://code.visualstudio.com/). Ook hier geldt dat je het bestand nog moet uitvoeren en installeren. Je hoeft niks aan te passen aan de installatie-opties. Heb je een Mac? Dan wordt het programma in je Downloads-map gezet. Je kunt het vanuit daar gewoon opstarten, maar je kan het ook even naar de Applications folder verplaatsen.

Op de [website](https://progns.proglab.nl/python/installatie/computer) van Inleiding programmeren vind je tips hoe je visual studio code kunt gebruiken. 

