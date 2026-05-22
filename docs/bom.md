## Bill of materials

Welkom op de pagina over het fysiek prototyping van het ZUIN systeem.
Hieronder vinden jullie een overzicht van de materialen die we gebruiken en de bedoeling van het systeem.

### ZUIN systeem

Het ZUIN systeem bestaat uit 2 delen, de hub en de wearable. In theorie zou de hub alle data van de slimme teller binnen moeten krijgen, aan de hand van een ML model voorspellingen moeten maken en zo het verbruik van het huishouden moeten begrijpen. De hub zou dan via een BLE signaal alle belangrijke info naar de wearable sturen die fungeert als een soort slave in het systeem. De wearable is een soort van horloge dat op een speelse manier alle informatie meedeelt aan het kind zodat het kind hierop kan reageren. Het is de bedoeling dat we deze functionaliteit zo goed mogelijk nabootsen in ons prototype. 

Momenteel hebben we een hub die signalen via BLE doorstuurt naar het horloge. Het horloge beeld dan de belangrijke info op het ronde scherm af.

// foto toevoegen

### Bill of Materials

#### Deel 1: Hub
|Buy or make | Component | Hoeveelheid | Prijs | Opmerkingen |
| :---: | :--- | :---: | :---: | :--- |
| Buy | Arduino Nano IOT 33| 1 | 23.90 |Voor het sturen van signalen en interactie met schakelaars|
| Buy | Grove Arduino Nano shield| 1 |Voor het makkelijk connecteren van componenten tijdens prototyping|
| Buy | Grove button |1 |- | Voor het uitschakelen van fictieve lampen |
| Buy | Grove Led | 2 | Voor het tonen van states |
| Buy | Grove 16X2 LCD screen | Voor het tonen van teksten |
| Make | Onderkant van casing | 1 | - | PLA FDM 3D print [Stp](cad\Develop 2\SV-Hub_Onderkant-001.stp)| 
| Make | Bovenkant van casing | 1 | - | PLA FDM 3D print [Stp](cad\Develop 2\SV-Hub_Bovenkant-001.stp)| 
