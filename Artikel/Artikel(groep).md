# Artikel/Artikelgroep opslagen per sortingskenmerken

Volg de stappen om artikelen van verschillende potmaat of steellengte een ander prijspercentage te geven, zodat een grotere maat meer zal kosten, bijvoorbeeld 12% van de originele prijs.

**STAP 1:**Ga naar constanten>Artikelen>Artikel gegevens> Artikelnummers.

![image](https://github.com/user-attachments/assets/73cbd173-a522-4cf1-8e91-026a0995866c)


**STAP 2:** Selecteer het artikel dat je wilt aanpassen  
![image](https://github.com/user-attachments/assets/05a1dbc5-c971-43f4-a002-3eaf4b2ca4b0)

**STAP 3:** Druk op de rechter muisknop en selecteer 'Open artikel'  
![image](https://github.com/user-attachments/assets/244bcb63-a5c9-4d6b-9fac-f079a61463e3)

**STAP 4:** Druk dan op het pijltje hier weergegeven:  
![image](https://github.com/user-attachments/assets/0c7770c4-ac21-4b44-877a-0214272a6c69)

**STAP 5:** Je komt in een nieuw venster en druk dan op dit knopje  
![image](https://github.com/user-attachments/assets/f937fbaf-02b4-4cbc-93b7-c362eb969827)

**STAP 6:** Hier zie je de lengte bij 'S1' en de extra kosten in percentage van de originele prijs in 'Perc.Opslag'. In dit voorbeeld is 12% gebruikt.  
![image](https://github.com/user-attachments/assets/125049ae-6bcd-4ee3-95c9-1f222177809a)

**STAP 7:** Vergeet je artikel niet te koppelen aan een DebGrp (DebiteurGroep). In dit voorbeeld hebben we '11' gebruikt.  
![image](https://github.com/user-attachments/assets/ef637e8c-57e5-4170-a90c-1196bbf53560)

---

Nu hebben we de artikelen aangepast en is het tijd om de debiteur zo in te stellen dat er voor andere maten of lengtes een extra percentage moet worden betaald.

**STAP 9:** Ga naar constanten>Organen > Debiteurgegevens > Debiteuren en selecteer een debiteur  
![image](https://github.com/user-attachments/assets/fe138756-6eef-48d0-aa46-95e1be501891)


**STAP 10:** Als je een debiteur hebt geopend, ga dan naar Financieel > Prijzen  
![image](https://github.com/user-attachments/assets/d4075e30-0445-48b8-801a-e3ad765c520c)

**STAP 11:** Pas 'Opslagcategorie per VBN-artikelgroep' aan zodat het gelijk staat aan stap 9. In dit voorbeeld is dat '11', maar dit is afhankelijk van de gekozen instelling.  
![image](https://github.com/user-attachments/assets/09617010-768d-42d5-949f-637c911cf127)

**STAP 12:** We gaan nu de 'Prijsconfiguratie' goed instellen. Druk op het pijltje aangegeven met rood om een venster te openen.  
![image](https://github.com/user-attachments/assets/12032635-e26e-41eb-a5df-ea721c9ef165)

Druk vervolgens op 'Stappen instellen'. Er zal een venster openen.  
![image](https://github.com/user-attachments/assets/9a4bcab1-514d-4609-a4bd-d583f0f3d581)

Druk nu op 'Opslag toevoegen'. Er zal een venster openen.  
![image](https://github.com/user-attachments/assets/17edee29-c571-4682-b094-7a3ccdf05a4c)

Op dit venster druk je op 'Artikel(groep)Opslag'.  
![image](https://github.com/user-attachments/assets/951ce4f5-5d4b-40b3-b52a-2c5f56a14767)

Als het goed is, wordt je uit dit venster gehaald en moet het volgende zichtbaar zijn.  
![image](https://github.com/user-attachments/assets/e39223c5-2b5c-4744-a020-1e1da31a78c3)

We willen 'Afronden: __ (decimalen)' op 2 zetten.  
![image](https://github.com/user-attachments/assets/711c1bf0-7b62-4caa-aefd-0de6869ed9d2)

Druk op de '3Debiteur voorraadartikelgroepopslag' en druk bovenin op 'stap omlaag' tot deze op '8Debiteur voorraadartikelgroepopslag' staat, dus regel 8.  
![image](https://github.com/user-attachments/assets/17006819-35d3-4e8e-bb64-ba09470befb0)

---

We gaan nu terug naar de debiteur en navigeren naar Internet > Internet toegang. Druk op 'Toegankelijke voorraden'.  
![image](https://github.com/user-attachments/assets/5d87b2ae-135a-45fe-9079-15e4a12f8449)

Zoek de voorraad waarin de artikelen staan die je wilt aanpassen en vink de kolom 'O' aan.  
![image](https://github.com/user-attachments/assets/31bb13b6-0653-452e-ae14-58ebb62dc416)

Nu gaan we terug naar de debiteur en zoeken we onder Opslagen > Opslagen.  
![image](https://github.com/user-attachments/assets/00f6343a-790e-407a-b85c-c22f1c21668a)

Het laatste wat we moeten doen, is de systeeminstelling 'ArtikelOpslagenzoekenAdv' aanzetten. Ga naar het hoofdscherm van Florisoft en druk bovenaan op 'Onderhoud'.  
![image](https://github.com/user-attachments/assets/5615a040-ec5b-40b8-87a0-739c4c1f5c3e)

Druk nu op 'Setup system'. Er zal een venster verschijnen.  
![image](https://github.com/user-attachments/assets/ef5a58a6-3bb4-4470-8a06-a4ad3d6f419d)

Open de 'Geavanceerd' kolom en voer de admin pin in.  
![image](https://github.com/user-attachments/assets/b5ec3144-fae5-4c6f-b3aa-4ce20b013957)

Dit venster zal nu verschijnen met alle systeeminstellingen.  
![image](https://github.com/user-attachments/assets/fb26472e-60ce-4ad5-8686-8934edeb0a45)

Druk dan op F3 om te zoeken.

Zoek de instelling 'artikelOpslagenzoekenAdv' en zet deze op 'True'.  
![image](https://github.com/user-attachments/assets/a9856306-b85e-48e7-8a3d-6e873b7319f4)

Alles staat nu goed en de artikelen zullen nu ook gebruik maken van de gegeven precentages.
