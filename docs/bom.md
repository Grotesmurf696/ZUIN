## Bill of materials

Welkom op de pagina over het fysiek prototyping van het ZUIN systeem.
Hieronder vinden jullie een overzicht van de materialen die we gebruiken en de bedoeling van het systeem.

### ZUIN systeem

Het ZUIN systeem bestaat uit 2 delen, de hub en de wearable. In theorie zou de hub alle data van de slimme teller binnen moeten krijgen, aan de hand van een ML model voorspellingen moeten maken en zo het verbruik van het huishouden moeten begrijpen. De hub zou dan via een BLE signaal alle belangrijke info naar de wearable sturen die fungeert als een soort slave in het systeem. De wearable is een soort van horloge dat op een speelse manier alle informatie meedeelt aan het kind zodat het kind hierop kan reageren. Het is de bedoeling dat we deze functionaliteit zo goed mogelijk nabootsen in ons prototype. 

Momenteel hebben we een hub die signalen via BLE doorstuurt naar het horloge. Het horloge beeld dan de belangrijke info op het ronde scherm af.

// foto toevoegen

### Bill of Materials

#### Deel 1: Hub
| Buy or make | Component | Hoeveelheid | Prijs (€) | Opmerkingen |
| :---: | :--- | :---: | :---: | :--- |
| Buy | Arduino Nano 33 IoT | 1 | 23.90 | Voor het sturen van signalen en interactie met schakelaars |
| Buy | Grove Arduino Nano shield | 1 | 4.25 | Voor het makkelijk connecteren van componenten tijdens prototyping |
| Buy | Grove button | 1 | 1.80 | Voor het uitschakelen van fictieve lampen |
| Buy | Grove Led | 2 | 2.50 | Voor het tonen van states |
| Buy | Grove 16X2 LCD screen | 1 | 7.00 | Voor het tonen van teksten over de status van het huis |
| Make | Onderkant van casing | 1 | - | PLA FDM 3D print [Stp](../cad/Develop%202/SV-Hub_Onderkant-001.stp) |
| Make | Bovenkant van casing | 1 | - | PLA FDM 3D print [Stp](../cad/Develop%202/SV-Hub_Bovenkant-001.stp) |

#### Deel 2: Wearable
| Buy or make | Component | Hoeveelheid | Prijs (€) | Opmerkingen |
| :---: | :--- | :---: | :---: | :--- |
| Buy | Rond LCD-scherm met ingebouwde esp32 | 1 | 25.00 | Voor het tonen van speelse en visuele feedback aan het kind |
| Make | Onderkant van casing (Wearable) | 1 | - | PLA FDM 3D print [Stp](../cad/Develop%202/SV-Wearable_Onderkant-001.stp) (alternatieve versie: [Stp](../cad/Develop%202/SV-Wearable_Onderkant-001_1.stp)) |
| Make | Bovenkant van casing (Wearable) | 1 | - | PLA FDM 3D print [Stp](../cad/Develop%202/SV-Wearable_Bovenkant-001.stp) |
| Make | Knopje / Draairing | 1 | - | PLA FDM 3D print [Stp](../cad/Develop%202/SV-P-Knopje-001.stp) |

// nog veranderen naar de echte files!!

### schema's van de hardware

 