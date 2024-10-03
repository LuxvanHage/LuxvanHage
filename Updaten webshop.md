# Updaten Webshop

## ZONDER F5

1. **Download de laatste versie via de back-office**

   Bij het downloaden van de laatste versie wordt er een zip-file op de PGS database server gezet in het mapje `BINSHOPZIP`.

2. **Voer een update en online purge uit**

   De database moet gelijk of vóór lopen qua versie.

3. **Voer Florishop updaten uit via de back-office**

   Kies de juiste webshop en kies voor updaten. Doordat de webshop in onderhoud wordt gezet (dmv app_offline), ziet de F5 dat deze instantie niet meer gezond is, en schakelt deze vervolgens 'uit'.

4. **Roep na de update de website intern op**

   Gebruik `ftg-shop02/03:poortnummer`. Poortnummers:
   - VDP, Marionette & Dexx = `6002`
   - VMP = `6005`
   - Hbx = `6008`
   - Newshop = `6010`

   Door het aanroepen van de URL, wordt de webshop gestart. Zodra de webshop volledig is opgestart, ziet de F5 dat de webshop weer gezond is en wordt hij weer 'open' gezet.

5. **Controleer de webshop op vitale functies**

   Denk aan inloggen, kopen, aanbod, etc.

## MET F5 (en/of buiten kantoortijd)

1. **Voer stap 1 en 2 uit**

   Als je buiten kantoortijd update, zal je een versie moeten vinden in de `BINSHOPZIP` op de PGS database server. `~/shared/DataPGSVDP/Binshopzip`

2. **Login op de F5**

   Ga naar `Local Traffic > Pools` (let op, misschien moet je rechtsboven aangeven dat je in `Partition FTG-SHOPS` wilt).

3. **Kies de juiste Pool**

   (FenP = VDP) en kies het tabje `Members`. Vink de node aan en zet de betreffende instantie uit d.m.v. `Force Offline`.

4. **Zet de instantie uit in IIS**

   Doe dit op applicatie-niveau, niet op site-niveau.

5. **Pak het bestand Plasshop uit**

   Dit bestand staat in `PLAS_GIVN7DVL_zip`. Hernoem de map door achter de benaming de datum van vandaag te zetten. Kopieer de inhoud van deze map over de bestanden van de webshopmap.

6. **Start de betreffende instantie in IIS en roep de URL aan**

   Controleer de webshop op vitale functies nadat de webshop volledig is herstart.

7. **Zet de instantie binnen de Pool in de F5 weer aan**

   Dit doe je door de instantie weer aan te zetten d.m.v. `Enable`.

![Webshop image 1](https://github.com/user-attachments/assets/e76ecd7d-62b3-4c3b-8972-4745761c56bb)

![Webshop image 2](https://github.com/user-attachments/assets/0f543424-784b-4df9-b81f-897adea77627)
