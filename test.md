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

![Florisoft Webservice Instellen](https://github.com/user-attachments/assets/8d73221a-32a1-4ee2-96a6-56484e709c07)

![Florisoft Webservice Configuratie](https://github.com/user-attachments/assets/b6e2b600-f8e5-4701-809a-0e2edda190bb)

### Stap 3: Server instellen
Ga naar `Webservice > Server` en vul de servergegevens in.

![Florisoft Webservice Server](https://github.com/user-attachments/assets/301aea44-4d73-45cd-9365-13c70170b5b0)

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

![Etrade Webservice Server](https://github.com/user-attachments/assets/301aea44-4d73-45cd-9365-13c70170b5b0)

### Stap 4: Informatie communiceren
Nadat alles is ingesteld, geef de volgende gegevens door aan de aanvrager zodat zij deze aan hun klant kunnen doorgeven:

```plaintext
Beste aanvrager,

De instellingen zijn goed gezet. Je kunt de onderstaande gegevens doorgeven aan de klant:

- Gebruikersnaam: (vul hier de gebruikersnaam in)
- Wachtwoord: (vul hier het webshop wachtwoord in)
- URL: https://vmp.flowerwebshop.net/service.asmx (de URL voor Etrade)
```
