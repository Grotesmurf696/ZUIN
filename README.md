# ZUIN
*ZUIN helpt kinderen en ouders meer te weten te komen en bevorderd communicatie over energieverbruik in huis* 

🛠️ Built by ``Sam Verkimpe``  & ``Maxim Depever`` & ``Jitse Van Laer ``  
🔥 Supervised by ``prof. dr. Bas Baccarne``, ``Yannick Christiaens`` & ``Wouter Devriese``    
🌱 Grown at ``Ghent University`` 🏛️ ``Industrial Design Engineering`` ([project overview](https://github.com/basbaccarne/human-centered-design))       

*Latest update: 12/12/2025*   

## General overview
ZUIN is een systeem van interactieve producten voor kinderen, interfaces voor de ouders en meetapperatuur voor jouw huis. 

Het bevordert de kennis over energieverbruik bij kinderen, terwijl ze op een speelse en interactieve manier zuinig leren vebruiken. Ook initieert het de interactie tussen ouder en kind om zo ook hun een steentje te laten bijdragen.

Kinderen weten vaak niet hoe energieverbruik echt in elkaar zit en welk apparaat nu het meeste verbruikt. Niet alleen de kinderen maar ook de ouders weten niet dat hun dagelijkse routines soms roet in het energieverbruik gooien. 

Aan het midden van ZUIN ligt het horloge. Dit horloge is gemaakt voor kinderen. Het horloge wordt gebruikt als normaal uurwerk doorheen de dag, maar wanneer de kinderen thuis komen krijgt dit horloge een extra functie. Een virtuele en speelse interface waardat op een overzichtelijke manier een beeld wordt geschept van het ogenblikkelijk energieverbruik in huis.
<p align="center">
  <img src="img\Eerste_Prototypes.JPG" width="80%">
</p>

## Introductie
Energieverbruik in huishoudens vormt een belangrijk maatschappelijk en ecologisch vraagstuk. Hoewel technologische oplossingen zoals digitale meters en monitoring-applicaties steeds vaker worden ingezet, blijft het energieverbruik voor veel gebruikers abstract en moeilijk te interpreteren. In gezinscontexten wordt dit probleem nog complexer, omdat energieverbruik het resultaat is van gedeelde routines en gedragingen, waarbij ook kinderen een belangrijke maar vaak onbewuste rol spelen.

Kinderen groeien op in een wereld waarin energie vanzelfsprekend beschikbaar is, zonder een duidelijk begrip van herkomst, kost of impact. Op school wordt wel een basis van milieubewustzijn aangeleerd, maar vooral het voorbeeld en de druk van de ouders maakt effectief verschil (Aguirre-Bielschowsky et al., 2018) [^1] . Klassieke energiefeedback — zoals apps, grafieken en cijfers — sluiten nauwelijks aan bij de leefwereld van kinderen. Bovendien ervaren ook de ouders het energieverbruik vaak als een “black box”: ze krijgen wel cijfers te zien, maar missen concrete, begrijpbare aanknopingspunten om hun dagelijks gedrag bij te sturen. Energie wordt ervaren als iets onzichtbaars: het is er altijd, komt uit het stopcontact, en verdwijnt weer zonder duidelijke koppeling tussen gedrag en gevolg. Dit maakt het moeilijk om duurzame gewoontes aan te leren, zeker bij jonge gebruikers.

Vanuit deze problematiek werd **ZUIN** ontwikkeld: een **interactief** systeem dat energieverbruik op een **speelse** en **begrijpbare** manier zichtbaar maakt voor kinderen, en tegelijk de **dialoog tussen ouder en kind** stimuleert. Het project focust niet op het technisch optimaliseren van installaties, maar op **bewustmaking, educatie en langdurige gedragsverandering** via dagelijkse **interactie en betekenisvolle** feedback.



## Inhoudstafel

1. [Methodologie](./docs/methodologie.md)
2. [Discovery](./docs/discovery.md)
3. [Definition](./docs/definition.md)
4. [Design Requirements](./docs/design_requirements.md)
5. [Bill of materials](./docs/bom.md)

## Methodologie
In dit onterwerpproces werd het **Tripel Diamond model gevolgd**. Hierin stelt de eerste diamond de **discovery-fase** voor, de tweede diamond staat voor de **definition-fase** en de derde diamond wordt in het tweede semester uitgewerkt als een **develop- en deliver-fase**.

<p align="center">
  <img src="img\Double Diamond.png" width="80%">

### 1. Discover
In de eerste fase wordt er opzoek gegaan naar het probleem. Via **benchmarking** werden bestaande producten geanalyseerd en vergeleken. Aanvullende **interviews** onderzochten hoe gezinnen energie gebruiken en begrijpen. Met behulp van **desk research** werd onderzocht welke toestellen het meeste energie verbruiken en welke verbruikers vaak vergeten worden. Hieruit bleek dat energieverbruik voor de meeste mensen onzichtbaar en verwarrend is, bestaande oplossingen te complex zijn, en dat vooral (ook) kinderen onvoldoende betrokken worden. Conclusie: er is nood aan een eenvoudige, visuele en kindvriendelijke manier om energieverbruik zichtbaar te maken en zo duurzaam gedrag te stimuleren.

### 2. Definition
De tweede fase van het onterwerpproces staat centraal rond het vinden van de juiste oplossing. In twee waves worden prototypes iteratief ontworpen en geëvalueerd. Deze fase start met het maken van een **storyboard**, om zo het doel van het product te visualiseren. In **wave 1** worden 3 prototypes getest door middel van een **user feedback sessions** en **dot-voting**. Verder werkend op de verkregen kennis uit wave 1, start **wave 2**. Hier worden mogelijke interfaces getoond, en werd via **Wizard of Oz - testing** gekeken welke interface het meest intuïtief werkt voor kinderen.  

## Discovery

### Doelstelling
Het doel van de discoveryfase is inzicht krijgen in hoe mensen binnen het huishouden omgaan met energieverbruik en welke impact dit heeft op hun dagelijks leven. Er wordt onderzocht in welke mate bewoners hun energieverbruik begrijpen, of zij deze kennis toepassen in hun gedrag en of dit daadwerkelijk leidt tot energiebesparing.

Daarnaast wordt extra aandacht besteed aan de rol van kinderen, aangezien zij vaak onbewuste energieverbruikers zijn. Het onderzoek bekijkt hoe hun gedrag bijdraagt aan het totale energieverbruik en op welke manier zij op een eenvoudige en positieve manier betrokken kunnen worden bij het besparen van energie.

Concreet wordt onderzocht:

  * Hoe wordt energieverbruik ervaren en begrepen?
  * Waar ontstaan frustraties en onduidelijkheden omtrent dit thema?
  * Leidt energie-inzicht tot gedragsverandering?
  * Welke vorm van feedback motiveert mensen om te besparen?
  * Hoe kunnen kinderen op een speelse manier betrokken raken?

Het project focust niet op het rechtstreeks reduceren van energieverbruik, maar op bewustmaking, met als doel langdurige gedragsverandering en uiteindelijke energiebesparing.

### Materiaal en methoden

#### Benchmarking

Benchmarking werd toegepast om bestaande oplossingen rond energiebewustzijn te analyseren en te vergelijken. Hierbij werd onderzocht welke producten vandaag ingezet worden om energieverbruik inzichtelijk te maken en welke sterktes en zwaktes deze systemen vertonen.

#### Interviews

Aan de hand van interviews werd nagegaan hoe bewust mensen omgaan met hun energieverbruik, welke impact dit op hen heeft en welke personen binnen het huishouden het meeste verbruiken. Daarnaast werd onderzocht welke triggers mensen motiveren om energie te besparen.

#### Desk research

Via deskresearch werd onderzocht welke toestellen het meeste energie verbruiken en welke verbruikers vaak vergeten worden, wat leidt tot onbewust en inefficiënt energiegebruik.

### Resultaten

#### Benchmarking

Uit de benchmarkanalyse blijkt dat bestaande oplossingen zich vooral richten op het meten en visualiseren van energieverbruik, vaak via complexe interfaces en applicaties. Hierdoor zijn deze systemen weinig toegankelijk voor een jong of niet-technisch publiek, terwijl ook zij een belangrijke rol spelen in het huishoudelijk energieverbruik.

De meeste producten focussen op data en grafieken, maar slagen er onvoldoende in om energieverbruik begrijpbaar en motiverend te maken. Vooral eenvoud, gebruiksgemak en betrokkenheid van kinderen ontbreken in het huidige aanbod. 

Volgende tabel toont een selectie van de meest interessante benchmarks:

| Nr. | Naam / Merk | Functie | Technologie | Doel | Prijs | Sterktes | Zwaktes |
|----|-------------|---------|-------------|------|-------|----------|---------|
| 1 | Niko startskit met Home Control | Informatie over elektriciteits- en gasverbruik | Solar modus, real-time info via app | Overzicht geven en helpen verbruik te verminderen | €390 | Automatische opwekking van stekkers bij zonne-energie | Info enkel via app |
| 2 | Pitt & Co Energiemeter | Meet verbruik en berekent kosten | Vermogen- en spanningsmeter | Energiekosten doen dalen | €26,95 | Kostenberekening | Werkt maar voor 1 stopcontact |
| 3 | Gologi slimme stekker | Apparaten slim maken | App, voice control, countdown | Apparaten op afstand bedienen | €15 | Stembediening, energiemonitoring | Slechts 1 toestel tegelijk |
| 4 | Smart Plug | Stekker add-on met schakelaar | App, voice control | Apparaten op afstand bedienen | €22 | Geen extra benodigdheden | Slechts 1 toestel tegelijk |
| 5 | Homewizard Energy Display | Visualisatie van verbruik | Inzicht stroom, teruglevering, gas | Bewustmaken van verbruik | €60 | Plaatsbaar scherm, customize | Veel grafieken → verwarrend |
| 6 | Homewizard P1 | Visualisatie van verbruik | P1-plug, real-time app | Bewustmaken van verbruik | €25 | Gebruiksvriendelijk, goedkoop | Veel grafieken → verwarrend |


#### Interviews

Uit de interviews blijkt dat de meeste respondenten moeite hebben om een correct en concreet beeld te vormen van hun elektriciteitsverbruik. Hoewel ze willen besparen, gebeurt dit meestal reactief, op basis van gevoel of na een hoge eindfactuur, en niet structureel.

Respondenten die gebruikmaken van slimme meters ervaren meer controle, maar geven aan dat de feedback vaak te technisch is en op dagelijkse basis weinig houvast biedt. Daarnaast werd duidelijk dat energieverbruik binnen een huishouden door meerdere personen wordt beïnvloed. In gezinnen spelen kinderen hierbij een grote rol, terwijl zij zich vaak niet bewust zijn van de gevolgen van hun gedrag. Dit zorgt bij ouders voor frustratie, omdat hun inspanningen niet altijd effect hebben.

Terugkerende uitspraken zijn onder andere:

  * “Je krijgt een bedrag, maar weet niet waar het vandaan komt.”
  * “Ik besef pas wat ik betaal als de factuur er is.”
  * “Apps tonen veel grafieken, maar ik weet niet wat ik ermee moet doen.”

Financiële motivatie blijkt de sterkste drijfveer voor energiebesparing; ecologische overwegingen spelen meestal een secundaire rol. De meeste respondenten staan open voor een hulpmiddel, op voorwaarde dat het betaalbaar, niet-invasief, eenvoudig en begrijpbaar voor kinderen is.

#### Desk research

Uit de deskresearch blijkt dat het grootste deel van het huishoudelijk energieverbruik veroorzaakt wordt door ruimteverwarming, warmwaterproductie en grote huishoudtoestellen. Hoewel deze verbruikers bekend zijn, wordt hun impact vaak onderschat omdat het verbruik verspreid is over meerdere toestellen en momenten.

Daarnaast vormt sluipverbruik een belangrijk maar vaak vergeten probleem. Apparaten zoals routers, laders, televisies en computers blijven continu energie verbruiken, zelfs wanneer ze niet actief gebruikt worden. Individueel lijkt dit verbruik beperkt, maar gezamenlijk vormt het een aanzienlijk aandeel van het totale energieverbruik.

Ook minder evidente systemen zoals ventilatie, circulatiepompen, aquariums en verwarmde ongebruikte ruimtes worden vaak over het hoofd gezien. Zonder metingen blijven deze verbruikers onzichtbaar.

Terugkerende patronen uit de deskresearch zijn:

  * Energieverbruik is grotendeels onzichtbaar.
  * Sluipverbruik wordt sterk onderschat.
  * Gebruikers zien geen duidelijke link tussen gedrag en impact.
  * Gedeelde verantwoordelijkheid leidt tot inefficiënt gebruik.

### Conclusies

#### Benchmarks

Bestaande producten focussen voornamelijk op dataverzameling en grafische weergave, maar onvoldoende op eenvoud en motivatie. Veel systemen vereisen een app, zijn complex of richten zich slechts op één toestel. Geavanceerde systemen zijn vaak duur en moeilijk te installeren. Dit toont aan dat er ruimte is voor een visueel eenvoudige en toegankelijke oplossing, geschikt voor alle bewoners, inclusief kinderen. Ook is het opmerkelijk dat er momenteel geen concrete toestellen op de markt zijn met als doel kinderen te leren of te helpen besparen. Hieruit blijkt dat er nog steeds een duidelijke leemte in de markt bestaat die kan worden opgevuld.

#### Interviews

Uit de interviews blijkt dat bewoners willen besparen, maar dat een gebrek aan inzicht, feedback en gedeelde verantwoordelijkheid dit belemmert. De energiefactuur wordt ervaren als een “black box” en leidt vooral tot tijdelijke, reactieve gedragsveranderingen. Er is nood aan realtime, begrijpbare feedback die ook kinderen aanspreekt, en aan een betaalbare, niet-invasieve oplossing.

#### Desk research

De literatuur bevestigt dat energieverbruik vooral wordt gedreven door verwarming, warm water en grote toestellen, aangevuld met een aanzienlijk aandeel sluipverbruik. Zonder duidelijke en visuele feedback blijft energieverbruik abstract. Vooral in gezins- en cohousingcontexten is er nood aan eenvoudige, centrale en laagdrempelige hulpmiddelen die duurzame gedragsverandering ondersteunen.


## Definition

### Doelstellingen
In deze fase is het belangrijk om het juiste te ontwerpen (‘designing the right thing’). Het product moet kinderen motiveren om het te gebruiken en zo bewuster te worden over verbruik en duurzaamheid. 

  * Met welk speelgoed spelen kinderen graag?
  * Wat motiveert kinderen?


### Materiaal en methoden

De definition-fase werd gestart met een sprintday, waarop dieper werd ingegaan op de feedback van de discovery-fase. Er werd een storyboard opgesteld, om een duidelijker zicht te krijgen op het doel van het product. Het product maakt kinderen op een speelse manier bewust over het alledaagse verbruik in huis, en motiveert ze om een steentje bij te dragen aan het verminderen ervan. 

<p align="center">
  <img src="img\Storyboard.jpg" width="80%">

Vervolgens werd dit idee fysiek uitgewerkt door drie quick and dirty prototypes. In wave 1 werden deze prototypes gevalideerd door een user feedback session.  
  * **Beer** : Deze knuffelbeer heeft een scherm geïntegreerd in de buik, waar de interface op kan verschijnen.
  * **Horloge** : Deze slimme horloge werkt buitenshuis als een normale horloge waar enkel de tijd op gezien kan worden. Vanaf de horloge thuis komt, zal er een ledje branden om aan te geven of er veel wordt verbruikt. Op                     het scherm zelf zal een interface komen.
  * **Tamagotchi** : Dit apparaatje is een compacte console waarop de interface te zien is.

<p align="center">
  <img src="img\Beer.JPG" width="45%">
  <img src="img\Tamagotchi.JPG" width="45%">
</p>
<p align="center">
  <img src="img\Tamagotchi_alleen.JPG" width="45%">
  <img src="img\Display Ouders.JPG" width="45%">
</p>
Om wave 1 vlot te kunnen starten, werd er gebeld met een expert vanuit Comon. Hier werd afgetoetst wat de goede leeftijdscategorie is voor onze doelgroep. Hij vertelde dat kinderen vanaf 5 jaar al gehoord hebben van het begrip energieverbruik. De doelgroep werd dus gedefineerd op kinderen van de lagere school (5 - 12 jaar). 
Verder vertelde hij dat gemification slechts werkt voor 2-4 weken. Hij raadde aan om een betekenisvolle interactie (zoals feedback) te creëren. 
Kinderen houden van dingen die veranderen, verrassen en verhalend zijn. 



> #### Wave 1 : user feedback sessions (N=5)
> In de eerste wave van de definition-fase werd onderzocht welk speelgoed kinderen aanspreekt. Op dag van de wetenschap werd een standje opgezet met de drie prototypes. Gezinnen konden hier vrijwillig deelnemen aan een kort interview. Er werden zowel jongens als meisjes geïnterviewd uit de lagere school.
> 
> <p align="center">
  <img src="img\Interview_wave1 (1).jpg" width="45%">
</p>



Vervolgens werd de interface van het product bepaald. Dit werd op verschillende manieren in Figma uitgewerkt. 

> #### Wave 2 : usability testing met wizard-of-oz-benadering (N=5)
> De 2e wave staat centraal rond intuïtief gebruik. Op 6/12/2025 werden enkele testen afgenomen met kinderen in de Krook in Gent. De testpersonen kregen de verschillende interfaces voorzich, en werden gevraagd om telkens 3 taken uit te voeren:
>  * Identificeer een kamer met “brand” (hoog energieverbruik) en 'blus' deze door fysiek een lamp uit te schakelen
>  * Ga opzoek naar het fantasie-eiland
>  * Zoek een verhaaltje in de interface
> Elke taak werd per interface opnieuw uitgevoerd om het effect van herhaling op begrip en navigatie te meten. 
>
> <p align="center">
  <img src="img\IMG_6032 (1).jpg" width="45%">
</p>


### Resultaten 

#### Wave 1 : user feedback sessions (N=5)
Uit de interviews blijkt dat zowel kinderen als ouders duidelijk waarde zien in een speels en visueel systeem dat kinderen stimuleert om bewuster met energie om te gaan. Het prototype van het horloge komt hierbij het sterkst naar voren als favoriet. Kinderen verkiezen dit omdat het draagbaar is, altijd bij hen blijft en directe feedback geeft via kleuren, eilandjes en LED-effecten. Voor kinderen die meer spelgericht zijn, blijft een speelconsole/Tamagotchi-achtige oplossing aantrekkelijk, vooral door het spel- en verzorgelement. De beer is daarentegen het minst populair en wordt slechts overwogen wanneer het concept minder dierlijk en meer technisch (robotachtig) wordt vormgegeven.

De belangrijkste functie die kinderen motiveert, is visuele en speelse feedback: kleurveranderingen, brandende of gelukkige eilandjes, LED-lichtjes en kleine beloningen. De gamification zorgt ervoor dat kinderen actief willen helpen en zelfs hun ouders aanspreken op energiegebruik. Extra fun-elementen zoals personalisatie, spelletjes en geluid versterken deze motivatie.

Ouders staan positiever tegenover het educatieve doel van het concept dan tegenover het fysieke product zelf. Koopbereidheid is beperkt, vooral door bezorgdheden rond afval, prijs en onnodige hardware. Velen zien meer in een app- of hybride oplossing, waarbij hardware minimaal blijft. Ze vinden het essentieel dat het systeem eenvoudig, duurzaam en niet overladen met smart functies is. Feedback zoals kleur, trilling of subtiel geluid is gewenst, maar zonder overmatige notificaties of straling.

#### Wave 2 : usability testing met wizard-of-oz-benadering (N=5)
Uit de testen konden enkele algemene observaties gehaald worden. Zo heeft herhaling een sterke positieve invloed op begrip en zelfstandigheid. Bijvoorbeeld het brand-icoontje dat steeds terug kwam motiveerde de kinderen zelfstand de lichten te doven, maar vereiste eerst een duidelijke uitleg. Het verhaaltje vinden was bij de drie interfaces vaak moeilijk, hier is dus een structureel probleem in de informatie-architectuur. Verder is de tekstgrootte te klein voor kinderen om te lezen. Hierdoor is het moeilijker bepaalde info te vinden en het vehaaltje te lezen. Dit merkten ook de ouders op. 

Specifiek per interface was bij UI1 de eerste interactie verwarrend door de onduidelijkheid van het brand-icoontje. Ook de swipe-interactie ward pas spontaan toegepast bij tweede poging. De kinderen gaven aan dat ze graag een personalisatie-optie willen. 
De navigatie bij UI2 ging opmerkelijk vlotter door de bekendheid met het concept. Echter kwam de drop-down menu onduidelijk over waardoor de taak van het verhaaltje zoeken hulp nodig had bij het voltooien. 
UI3 was de interface waar het meeste enthousiasme over was. Toch was de menu eerder verwarrend en is de test vroegtijdig stop gezet door een bug waardoor de knop om het verhaaltje te openen het scherm blokkeerde. 


### Conclusies & implicaties
Een draagbaar, visueel en spel-georiënteerd ontwerp maakt het meest kans om kinderen te engageren, terwijl ouders vooral eenvoud, duurzaamheid en educatieve waarde verwachten. Een horloge met spelelementen, eventueel gekoppeld aan een app, lijkt de meest beloftevolle richting om beide groepen te overtuigen.
Herhaling is essentieel om gebruikers het energieconcept en de navigatie correct te laten begrijpen. Dit impliceert dat het nieuwe product moet inzetten op een duidelijkere informatie-architectuur, waarbij verhaaltjes en kernfunctionaliteiten sneller en intuïtiever vindbaar zijn. Daarnaast zijn visuele verbeteringen, zoals grotere tekst en heldere iconen, noodzakelijk om de toegankelijkheid te verhogen. Motiverende elementen zoals de brand-metafoor blijken effectief, maar vereisen een duidelijke introductie via onboarding. 

### PRD-ZUIN

| **ID** | **Design requirement** | **Bron** | **Datum** | **Al geïntegreerd** |
| :--- | :--- | :--- | :--- | :--- |
| **Groep 1: Educatie en bewustwording** | | | | |
| 1.1 | Het product moet kinderen inzicht geven in energieverbruik op een speelse manier | Userinterview Wave 1 | 23/11/2025 | Ja |
| 1.2 | Feedback moet aantonen in welke kamer er veel verbruikt wordt | Userinterview Wave 1 | 23/11/2025 | Ja |
| 1.3 | Het systeem moet ouders stimuleren om samen met kinderen energie te besparen | Userinterview Wave 1 | 23/11/2025 | Neen |
| 1.4 | Het product moet educatieve waarde hebben en bijdragen | Userinterview Wave 1 | 23/11/2025 | Ja |
| 1.5 | Er moet een duidelijke onboarding/uitleg zijn voor de iconen en functies | Usability Test Wave 2 | 06/12/2025 | Neen |
| **Groep 2: Gamification en motivatie** | | | | |
| 2.1 | Het product moet visuele spel-elementen bevatten | Userinterview Wave 1 | 23/11/2025 | Ja |
| 2.2 | Er moet positieve feedback worden gegeven | Userinterview Wave 1 | 23/11/2025 | Ja |
| 2.3 | Het product moet kinderen motiveren door emotionele elementen | Userinterview Wave 1 | 23/11/2025 | Ja |
| 2.4 | Personalisatie moet mogelijk zijn in de interface | Userinterview Wave 1 | 23/11/2025 | Ja |
| 2.5 | Moet extra fysieke triggers bevatten | Userinterview Wave 1 | 23/11/2025 | Ja |
| 2.6 | De interface moet een motiverende metafoor (zoals de "brand") bevatten | Usability Test Wave 2 | 06/12/2025 | Ja |
| 2.7 | Personalisatie-opties moeten worden uitgebreid om engagement te verhogen | Usability Test Wave 2 | 06/12/2025 | Neen |
| **Groep 3: Hardware en Duurzaamheid** | | | | |
| 3.1 | Het product moet draagbaar zijn | Userinterview Wave 1 | 23/11/2025 | Ja |
| 3.2 | Het product moet eenvoudig zijn | Userinterview Wave 1 | 23/11/2025 | Ja |
| 3.3 | Het product moet compact zijn | Userinterview Wave 1 | 23/11/2025 | Ja |
| 3.4 | Geen overbodige smart-technologie | Userinterview Wave 1 | 23/11/2025 | Ja |
| 3.5 | Het product moet betaalbaar zijn | Userinterview Wave 1 | 23/11/2025 | / |
| **Groep 4: Feedback en interface** | | | | |
| 4.1 | Het product moet duidelijke visuele feedback geven | Userinterview Wave 1 | 23/11/2025 | Kan beter |
| 4.2 | Het product moet extra fysieke feedback geven | Userinterview Wave 1 | 23/11/2025 | Neen |
| 4.3 | Feedback moet duidelijk maar niet opdringerig zijn | Userinterview Wave 1 | 23/11/2025 | Kan beter |
| 4.4 | Beloningen | Userinterview Wave 1 | 23/11/2025 | Ja |
| 4.5 | Tekstgrootte en iconen moeten geoptimaliseerd zijn voor leesbaarheid door kinderen | Usability Test Wave 2 | 06/12/2025 | Neen |
| 4.6 | De interface moet intuïtieve navigatie (zoals swipes) ondersteunen die na herhaling duidelijk is | Usability Test Wave 2 | 06/12/2025 | Kan beter |
| **Groep 5: Connectiviteit en app-integratie** | | | | |
| 5.1 | Het systeem moet werken als een app | Userinterview Wave 1 | 23/11/2025 | Ja |
| 5.2 | App voor ouders | Userinterview Wave 1 | 23/11/2025 | Neen |
| 5.3 | De app moet inzicht geven in verbruik en educatieve tips aanbieden | Userinterview Wave 1 | 23/11/2025 | Ja en Neen |
| 5.4 | De informatie-architectuur moet herzien worden; verhaaltjes moeten eenvoudig vindbaar zijn | Usability Test Wave 2 | 06/12/2025 | Neen |
| 5.5 | Onduidelijke dropdown-menu's moeten worden vermeden in de navigatiestructuur | Usability Test Wave 2 | 06/12/2025 | Neen |







## Kritische reflectie
Max. 500 woorden

## Noot inzake het gebruik van AI
AI werd ingezet om de opnamebestanden die we tijdens de interviews en testen maakten, om te zetten in een uitgeschreven tekst en dit samen te vatten. Dit gebruikten we ter ondersteuning van de notities die ook werden gemaakt, om zo geen enkele info te missen en al onze aandacht te besteden aan de gebruikers. 
Verder werd AI ook ingeschakeld om efficiënt via Figma Make enkele interfaces te ontwerpen. Op deze manier konden we veel sneller starten met de gebruikerstesten om te begrijpen wat de gebruiker nu echt wilt en wat absoluut niet.  

## Bijlagen
### Discovery
* Literatuuronderzoek (N=x)
  * [Protocol](url)
  * [Rapport](url)
* Interviews (N=x)
  * [Protocol](url)
  * [Rapport](url)
    
### Definition
* User testing wave 1 (N=5)
  * [Protocol](https://ugentbe-my.sharepoint.com/:b:/g/personal/sam_verkimpe_ugent_be/IQC8tEje_yFzSamdKWDDOaGFAbIKFai_KvVj0mNIbBrrtQk?e=JygQLY)
  * [Rapport](https://ugentbe-my.sharepoint.com/:b:/g/personal/sam_verkimpe_ugent_be/IQD9Kj5Tx0cIRJQROee65qW5Adg2_tDG4xOJkzBVwp7rk9g?e=vG1YrG)
* User testing wave 2 (N=5)
  * [Protocol](url)
  * [Rapport](https://ugentbe-my.sharepoint.com/:b:/g/personal/sam_verkimpe_ugent_be/IQBBSVxjt0VdSLub2Noc09yTAXX5JLwwVX3_3C1DV2oT8Ro?e=hxkX0X)

## Licentie 

This repository contains both software and design materials created as part of an industrial design energineering project at Ghent University.

- **Software and code:** [MIT License](./LICENSE-MIT)  
- **Design, documentation, CAD, and media:** [CC BY 4.0 License](./LICENSE)
  
You are free to reuse and build upon this work, both commercially and non-commercially, as long as proper attribution is given to the original authors.

## Bronnen
 [^1]: Aguirre-Bielschowsky, I., Lawson, R., Stephenson, J., & Todd. S. (2018). _Kids and Kilowatts: Socialisation, energy efficiency, and electricity consumption in New Zealand_. Energy Research & Social Science, 44, 178-186. https://www.sciencedirect.com/science/article/pii/S2214629618303803
