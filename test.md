# Wanneer is een product niet meer beschikbaar?

Aan een partij zit een ETELDAT (estimated delivery date) gekoppeld. Als je hierbij de verwerkingstijd optelt en dat tijdstip is boven de vertrektijd van de transportroute, dan zal deze partij niet meer zichtbaar zijn voor die vertrekdag.

| Partij  | ETELDAT                         | Verwerkingstijd           | Vertrektijd Klant      | Resultaat               |
|---------|----------------------------------|---------------------------|------------------------|-------------------------|
| Partij X| 05-09-2024 11:00:00              | 3,5 uur (05-09-2024)      | 13:00 (05-09-2024)     | Partij niet meer beschikbaar |
| Partij Y| 06-09-2024 11:00:00              | 1 uur (06-09-2024)        | 13:00 (06-09-2024)     | Partij beschikbaar       |

## Vertrektijd

De vertrektijd is te vinden bij de transportroute, zie afbeelding. Deze vertrektijd kan per dag verschillen.  
![image](https://github.com/user-attachments/assets/c865a3b1-23f0-49dd-a8bc-8171638cd5dd)

## ETELDAT (Estimated Delivery Date)

Dit is iets wat de kweker normaal meestuurt over de voorraadkoppel, dus dit zit gelijk aan een partij gekoppeld bij het inlezen. Wij kunnen dit zelf wel manipuleren als we dat nodig trachten. Dit doen we door een aanlevertijdenset op leveranciersniveau te koppelen. Dit bepaalt de ETELDAT voor alle partijen uit die voorraad voor die specifieke dag van de week.  
![image](https://github.com/user-attachments/assets/b33097e9-8d2a-451b-b053-32f178933c1c)

## Verwerkingstijd

Hieronder zie je de standaard verwerkingstijdenschema’s. In de omschrijving staat vermeld voor welke dagen dit geldt. Topdag is Maandag/Woensdag. Daldag is Dinsdag/Donderdag/Vrijdag.

![image](https://github.com/user-attachments/assets/80c23232-8d6d-44e4-819c-e0cf3a7c78ba)  
![image](https://github.com/user-attachments/assets/66adbb53-94d3-46db-b317-9eb5d7921d23)

In de afbeeldingen hiervoor zag je dat er voor specifieke stappen verwerkingstijd gerekend wordt. Hieronder per stap uitgelegd wanneer deze meegenomen wordt als verwerkingstijd:

### Algemeen
Deze stap wordt altijd meegenomen in de optelling.

### Lokaliseren
Geldt alleen voor partijen die nog niet op locatie gescand zijn.

### Pick Bloemen
Dit is voor de bloemen die gepicked moeten worden.

### Pick Planten
Dit is voor de planten die gepicked moeten worden.

### Inpakken
Deze stap geldt alleen voor producten die ingepakt moeten worden. Dit is te vinden bij de INPAK-code’s en dan de button “artikelgroep instellingen”. Dit zijn debiteuren in ons systeem, zie afbeelding.  
![image](https://github.com/user-attachments/assets/5cd429f6-39b3-4252-a716-ea6e05254811)

### Opbouwen
Dit gedeelte van de verwerkingstijd wordt alleen meegenomen als het onderstaande vinkje bij de transportroute aanstaat.  
![image](https://github.com/user-attachments/assets/3ee64b18-079c-4026-b9c8-a0611d7a24c8)

## Verwerkingstijd Manipuleren

Nu bestaat er ook nog een mogelijkheid om de verwerkingstijd per dag en per klant aan te passen. Dat doe je bij de “per dag” button op de debiteurkaart. Dit wordt bijvoorbeeld gedaan voor Engelse klanten om de keuring op tijd te laten gebeuren.  
![image](https://github.com/user-attachments/assets/6501d095-4781-48b7-9ab6-4879978e93d9)
