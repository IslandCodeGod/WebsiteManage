[English](README_en.md)|[German](README_de.md)|[中文](README_zh.md)|[日本語](README_ja.md)|[Русский](README_ru.md)|[한국어](README_ko.md)|[Español](README_es.md)|[Français](README_fr.md)|[Italiano](README_it.md)|[Português](README_pt.md)|Nederlands|[Polski](README_pl.md)|[العربية](README_ar.md)|[हिन्दी](README_hi.md)|[ไทย](README_th.md)|[Svenska](README_sv.md)|[Türkçe](README_tr.md)|[Tiếng Việt](README_vi.md)

# Flask Web Application - Beheersysteem voor bedrijfswebsites (gecodeerde versie)

## Projectintroductie

Dit is een **gecodeerde versie** van een bedrijfswebsitebeheersysteem dat is ontwikkeld op basis van het Flask-framework. De kerncode is door PyArmor versluierd en gecodeerd om intellectuele eigendomsrechten te beschermen.Het systeem ondersteunt meertalige (Chinees en Engels), gebruikersauthenticatie, product- en nieuwsbeheer, weergave van bedrijfsinformatie en andere functies.

## Schermafbeelding van applicatie

Het volgende is een screenshot van de hoofdinterface van de applicatie:

### Thuis
![首页](screenshots/index.png)

### Managementachtergrond
![管理后台](screenshots/admin_dashboard.png)

## Release-opmerkingen

Deze versie is een basisversleutelingsversie die volledige beheerfuncties voor bedrijfswebsites biedt.Als je nodig hebt:

- **Volledige broncodeversie**: Bevat niet-gecodeerde volledige broncode om secundaire ontwikkeling te vergemakkelijken
- **Aangepaste functieontwikkeling**: aanpassing en uitbreiding van functies volgens uw specifieke behoeften
- **Technische ondersteuningsservices**: ontvang professionele technische ondersteuning en onderhoudsservices

Neem contact met ons op via onderstaande contactgegevens en wij bezorgen u gedetailleerde plannen en offertes.

## Coderingsfuncties

- **Codebescherming**: Core Python-bestanden (app.py, init_db.py, models.py) zijn onduidelijk en gecodeerd
- **Runtimebescherming**: gebruik de PyArmor-runtimeomgeving om te voorkomen dat code wordt gedecompileerd
- **Volledige functionaliteit**: de gecodeerde code behoudt alle originele functionaliteit en kenmerken
- **Meertalige ondersteuning**: ingebouwde Chinese en Engelse schakelfunctie

## Bestanden opnemen

```
/
├── app.py                  # Gecodeerde hoofdtoepassingsinvoer
├── init_db.py              # Gecodeerd database-initialisatiescript
├── models.py               # Gecodeerde datamodellen
├── babel.cfg               # Internationaliseringsconfiguratie van Babel
├── pyarmor_runtime_000000/ # PyArmor runtime-ondersteuningsbestanden
├── static/                 # Statische bronbestanden (CSS, JS, afbeeldingen)
├── templates/              # HTML-sjabloonbestanden
├── translations/           # Meertalige vertaalbestanden
└── instance/               # Databasedirectory (automatisch aangemaakt bij eerste run)
```

## Snel aan de slag

### Milieuvereisten

- Python 3.9 of hoger
- Geïnstalleerde afhankelijkheidspakketten:
- Kolf 3.0.0+
- Kolf-SQLAlchemy 3.1.1+
- Kolf-login 0.6.3+
- Kolf-Babel 4.0.0+
- Werkzeug 3.0.1+

### Installeer afhankelijkheden

Als de vereiste afhankelijkheden nog niet zijn geïnstalleerd, installeer deze dan eerst:

```bash
pip install flask flask-sqlalchemy flask-login flask-babel werkzeug
```

### Voer de applicatie uit

1. **Initialiseer database**

Voordat de database voor de eerste keer wordt uitgevoerd, moet deze worden geïnitialiseerd:

```bash
   python init_db.py
   ```

2. **Start de applicatie**

```bash
   python app.py
   ```

3. **Toegang tot app**

Open de browser en ga naar: http://127.0.0.1:5000

## Gebruiksaanwijzing

### Bezoek website

1. Open de browser en ga naar http://127.0.0.1:5000
2. Gebruik de taalwisselknop in de rechterbovenhoek om te schakelen tussen Chinees en Engels

### Managementachtergrond

1. Ga naar http://127.0.0.1:5000/admin/login
2. Log in met het beheerdersaccount (standaard gebruikersnaam en wachtwoord: admin/admin123)
3. Producten, nieuws en bedrijfsinformatie kunnen op de managementachtergrond worden beheerd

## Functiebeschrijving

### Front-end-functies

- **Home**: bedrijfsprofiel en belangrijkste producten weergeven
- **Over ons**: Toon bedrijfsgegevens
- **Productweergave**: blader door alle productvermeldingen
- **Industrie-updates**: bekijk het laatste nieuws en informatie
- **Taalwisseling**: Ondersteunt het schakelen tussen Chinees en Engels

### Achtergrondfuncties beheren

- **Productbeheer**: producten toevoegen, bewerken en verwijderen
- **Nieuwsbeheer**: nieuws publiceren, bewerken en verwijderen
- **Bedrijfsinformatie**: update basisbedrijfsinformatie
- **Gebruikersauthenticatie**: beveiligd inlogsysteem

## Handleiding voor screenshots

Om het beste README-weergave-effect te krijgen, wordt aanbevolen schermafbeeldingen te maken en toe te voegen volgens de volgende richtlijnen:

1. **Maak screenshots map**: Maak de map `screenshots/` in de map `dist/`
2. **Screenshotgrootte**: gebruik een screenshot met een resolutie van 1920x1080 of 1366x768 om ervoor te zorgen dat de inhoud duidelijk zichtbaar is
3. **Schermafbeeldinginhoud**:
- Startpagina: geeft de volledige startpagina-interface weer, inclusief navigatiebalk en hoofdinhoudgebied
- Taalwisseling: toon het vergelijkende effect van het schakelen tussen Chinees en Engels (schermafbeeldingen op gesplitst scherm kunnen worden gebruikt)
- Productweergave: weergave van de productlijst en details van individuele producten
- Nieuwspagina: toon nieuwslijst en nieuwsdetails
- Beheerbackend: toont het dashboard en de functionele interface nadat de beheerder heeft ingelogd
4. **Screenshot-indeling**: gebruik de PNG-indeling voor de beste kwaliteit
5. **Bestandsnaamgeving**: sla de schermafbeelding op volgens de bestandsnaam die is opgegeven in de README (index.png, taal_switch.png, enz.)

## Opmerkingen

1. **Bestandsintegriteit**: zorg ervoor dat alle bestanden correct zijn gedownload, vooral de map `pyarmor_runtime_000000` en de inhoud ervan

2. **Databasebestand**:
- Het databasebestand wordt automatisch aangemaakt in de map `instance`
- Als u een back-up van uw gegevens wilt maken, maak dan regelmatig een back-up van het bestand `instance/site.db`

3. **Meertalige ondersteuning**:
- Alle vertaalbestanden zijn opgenomen in de map `translations`
- Raadpleeg de originele projectdocumentatie om nieuwe vertaaltalen toe te voegen

4. **Bedrijfsomgeving**:
- Zorg ervoor dat de Python-versie niet lager is dan 3.9
- Zorg ervoor dat alle noodzakelijke afhankelijkheden zijn geïnstalleerd

5. **Veiligheidstips**:
- Wijzig bij implementatie in een productieomgeving het standaard beheerderswachtwoord.
- Overweeg het gebruik van een WSGI-server (zoals Gunicorn) in plaats van de ontwikkelingsserver
- Configureer de juiste firewallregels

## Implementatieaanbevelingen

### Ontwikkelomgeving

Gebruik de ingebouwde ontwikkelingsserver van Flask (weergegeven in de snelle start hierboven).

### Productieomgeving

1. **Gebruik de WSGI-server**:
```bash
   pip install gunicorn
   gunicorn -w 4 -b 0.0.0.0:8000 app:app
   ```

2. **Gebruik omgekeerde proxy**:
- Configureer Nginx of Apache als een reverse proxy
- Stel een SSL-certificaat in om HTTPS in te schakelen

3. **Database-optimalisatie**:
- Overweeg om PostgreSQL of MySQL te gebruiken in plaats van SQLite
- Configureer een regulier back-upmechanisme

## Problemen oplossen

### Veelgestelde vragen

1. **Applicatie kan niet worden gestart**:
- Controleer of de Python-versie aan de eisen voldoet
- Controleer of alle afhankelijke pakketten correct zijn geïnstalleerd
- Controleer of de directory `pyarmor_runtime_000000` bestaat en compleet is

2. **Taalomschakeling werkt niet**:
- Bevestig dat de map `translations` en de inhoud ervan compleet zijn
- Controleer of browsercookies-instellingen zijn toegestaan

3. **Fout met databaseverbinding**:
- Bevestig dat de directory `instance` bestaat en schrijfrechten heeft
- Probeer `init_db.py` opnieuw uit te voeren om de database te initialiseren

### Logweergave

Wanneer de applicatie start, wordt loginformatie naar de console uitgevoerd. Als u problemen ondervindt, kunt u deze logboeken raadplegen voor meer informatie.

## Licentie

[MIT License](LICENSE)

## Contactgegevens

Als u vragen of suggesties heeft of een volledige versie/aangepaste functieontwikkeling nodig heeft, kunt u op de volgende manieren contact opnemen:

- **E-mail**: austinlive666@gmail.com (aanbevolen)
- **Onenigheid**:[https://discord.gg/7AN9PuGn](https://discord.gg/7AN9PuGn)

---

Bedankt voor het gebruik van dit project!