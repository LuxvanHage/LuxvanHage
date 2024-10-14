# Handleiding: VMP-koppeling instellen voor klanten van een debiteur

In deze handleiding laten we zien hoe je een VMP-koppeling instelt voor klanten van een debiteur, zodat zij planten of bloemen van ons (FTG) kunnen bestellen. We behandelen twee scenario's:
1. Een debiteur die gebruikmaakt van Florisoft.
2. Een debiteur die geen gebruikmaakt van Florisoft (Etrade).

---

## Uitleg voor debiteur met Florisoft

### Stap 1: Debiteur zoeken
Ga naar `Constanten > Organen > Debiteurgegevens > Debiteur`. Zoek de debiteur op waarmee je de koppeling wilt instellen en open deze.

### Stap 2: Webservice instellen
Ga naar `Internet > Webservice > Aanbiedingen` en vul hier de gegevens voor de Florisoft webservice in.

![image](https://github.com/user-attachments/assets/fb7c519b-ea46-400c-a592-a84a314cfd78)

![Florisoft Webservice Configuratie](https://github.com/user-attachments/assets/b6e2b600-f8e5-4701-809a-0e2edda190bb)

### Stap 3: Server instellen
Ga naar `Webservice > Server` en vul de servergegevens in.

![image](https://github.com/user-attachments/assets/7b22b54c-9620-41fe-b851-62f7fd0e5c79)


### Stap 4: Informatie communiceren
Nadat alles is ingesteld, geef de volgende gegevens door aan de aanvrager zodat zij deze aan hun klant kunnen doorgeven:

```plaintext
Beste aanvrager,

De instellingen zijn goed gezet. Je kunt de onderstaande gegevens doorgeven aan de klant:

- Gebruikersnaam: (debnr)
- Wachtwoord: (webshop wachtwoord)
- URL: https://vmp.flowerwebshop.net/service.asmx (de URL voor Florisoft)
```
## Uitleg voor debiteur zonder Florisoft (Etrade)

### Stap 1: Debiteur zoeken
Ga naar `Constanten > Organen > Debiteurgegevens > Debiteur`. Zoek de debiteur op waarmee je de koppeling wilt instellen en open deze.

### Stap 2: Webservice instellen
Ga naar `Internet > Webservice > Aanbiedingen` en vul hier de gegevens in voor de Etrade webservice.

![Etrade Webservice Instellen](https://github.com/user-attachments/assets/55b6faf3-e7ce-4593-840d-993ad901b800)

![Etrade Webservice Configuratie](https://github.com/user-attachments/assets/b6e2b600-f8e5-4701-809a-0e2edda190bb)

### Stap 3: Server instellen
Ga naar `Webservice > Server` en vul de servergegevens in.

![image](https://github.com/user-attachments/assets/a4de5841-e9d8-483c-af31-7606b70ab749)


### Stap 4: Informatie communiceren
Nadat alles is ingesteld, geef de volgende gegevens door aan de aanvrager zodat zij deze aan hun klant kunnen doorgeven:

```plaintext
Beste aanvrager,

De instellingen zijn goed gezet. Je kunt de onderstaande gegevens doorgeven aan de klant:

- Gebruikersnaam: (vul hier de gebruikersnaam in)
- Wachtwoord: (vul hier het webshop wachtwoord in)
- URL: https://vmp.flowerwebshop.net/service.asmx (de URL voor Etrade)
```
