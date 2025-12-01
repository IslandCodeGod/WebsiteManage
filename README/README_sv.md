# Flask Web Application - Företagswebbplatshanteringssystem (krypterad version)

## Projektintroduktion

Detta är en **krypterad version** av ett företagswebbplatshanteringssystem utvecklat baserat på Flask-ramverket.Kärnkoden har fördunklats och krypterats av PyArmor för att skydda immateriella rättigheter.Systemet stöder flera språk (kinesiska och engelska), användarautentisering, produkt- och nyhetshantering, visning av företagsinformation och andra funktioner.

## Skärmdump av programmet

Följande är en skärmdump av programmets huvudgränssnitt:

### Hem
![首页](screenshots/index.png)

### Ledarbakgrund
![管理后台](screenshots/admin_dashboard.png)

## Release Notes

Denna version är en grundläggande krypteringsversion som tillhandahåller kompletta funktioner för företagswebbplatshantering.Om du behöver:

- **Fullständig källkodsversion**: Innehåller okrypterad fullständig källkod för att underlätta sekundär utveckling
- **Anpassad funktionsutveckling**: Funktionsanpassning och expansion enligt dina specifika behov
- **Tekniska supporttjänster**: Få professionell teknisk support och underhållstjänster

Vänligen kontakta oss via kontaktuppgifterna nedan så ger vi dig detaljerade planer och offerter.

## Krypteringsfunktioner

- **Kodskydd**: Core Python-filer (app.py, init_db.py, models.py) är obfuskerade och krypterade
- **Runtime Protection**: Använd PyArmor runtime-miljön för att förhindra att kod dekompileras
- **Fullständig funktionalitet**: Den krypterade koden behåller alla ursprungliga funktioner och funktioner
- **Stöd för flera språk**: inbyggd växlingsfunktion för kinesiska och engelska

## Inkludera filer

```
/
├── app.py                  # Krypterad huvudapplikationspost
├── init_db.py              # Krypterad databasinitieringsskript
├── models.py               # Krypterade datamodeller
├── babel.cfg               # Babels internationaliseringskonfiguration
├── pyarmor_runtime_000000/ # PyArmor runtime-stödfiler
├── static/                 # Statiska resursfiler (CSS, JS, bilder)
├── templates/              # HTML-mallfiler
├── translations/           # Flerspråkiga översättningsfiler
└── instance/               # Databaskatalog (skapas automatiskt vid första körningen)
```

## Snabbstart

### Miljökrav

- Python 3.9 eller högre
- Installerade beroendepaket:
- Kolv 3.0.0+
- Flask-SQLAlchemy 3.1.1+
- Flask-Login 0.6.3+
- Flask-Babel 4.0.0+
- Werkzeug 3.0.1+

### Installationsberoenden

Om de nödvändiga beroendena inte är installerade ännu, installera dem först:

```bash
pip install flask flask-sqlalchemy flask-login flask-babel werkzeug
```

### Kör programmet

1. **Initiera databas**

Innan den körs för första gången måste databasen initieras:

```bash
   python init_db.py
   ```

2. **Starta programmet**

```bash
   python app.py
   ```

3. **Åtkomst app**

Öppna webbläsaren och besök: http://127.0.0.1:5000

## Bruksanvisning

### Besök webbplatsen

1. Öppna webbläsaren och besök http://127.0.0.1:5000
2. Använd språkväxlingsknappen i det övre högra hörnet för att växla mellan kinesiska och engelska

### Ledarbakgrund

1. Besök http://127.0.0.1:5000/admin/login
2. Logga in med administratörskontot (standardanvändarnamn och lösenord: admin/admin123)
3. Produkter, nyheter och företagsinformation kan hanteras i ledningsbakgrunden

## Funktionsbeskrivning

### Front-end-funktioner

- **Hem**: Visa företagsprofil och huvudprodukter
- **Om oss**: Visa företagsinformation
- **Produktvisning**: Bläddra bland alla produktlistor
- **Branschuppdateringar**: Se de senaste nyheterna och informationen
- **Språkväxling**: Stöder växling mellan kinesiska och engelska

### Hantera bakgrundsfunktioner

- **Produkthantering**: Lägg till, redigera, ta bort produkter
- **Nyhetshantering**: Publicera, redigera, ta bort nyheter
- **Företagsinformation**: Uppdatera grundläggande företagsinformation
- **Användarautentisering**: säkert inloggningssystem

## Skärmdumpguide

För att få den bästa README-visningseffekten rekommenderas det att skapa och lägga till skärmdumpar enligt följande riktlinjer:

1. **Skapa skärmdumpsmapp**: Skapa mappen `screenshots/` i `dist/`-katalogen
2. **Skärmdumpstorlek**: Använd en skärmdump med 1920x1080 eller 1366x768 upplösning för att säkerställa att innehållet är tydligt synligt
3. **Skärmdumpinnehåll**:
- Hemsida: Visar hela hemsidans gränssnitt, inklusive navigeringsfältet och huvudinnehållsområdet
- Språkväxling: Visa den jämförande effekten av att växla mellan kinesiska och engelska (skärmdumpar med delad skärm kan användas)
- Produktvisning: visa produktlista och detaljer om enskilda produkter
- Nyhetssida: visa nyhetslista och nyhetsinformation
- Management backend: visar instrumentpanelen och det funktionella gränssnittet efter att administratören har loggat in
4. **Skärmbildsformat**: Använd PNG-format för bästa kvalitet
5. **Filnamn**: Spara skärmdumpen enligt filnamnet som anges i README (index.png, language_switch.png, etc.)

## Anteckningar

1. **Filintegritet**: Se till att alla filer har laddats ner korrekt, särskilt katalogen `pyarmor_runtime_000000` och dess innehåll

2. **Databasfil**:
- Databasfilen skapas automatiskt i katalogen `instans`
- Om du behöver säkerhetskopiera data, vänligen säkerhetskopiera filen `instance/site.db` regelbundet

3. **Stöd för flera språk**:
- Alla översättningsfiler ingår i katalogen "översättningar".
- För att lägga till nya översättningsspråk, se den ursprungliga projektdokumentationen

4. **Driftsmiljö**:
- Se till att Python-versionen inte är lägre än 3.9
- Se till att alla nödvändiga beroenden är installerade

5. **Säkerhetstips**:
- När du distribuerar till en produktionsmiljö, vänligen ändra standardadministratörslösenordet.
- Överväg att använda en WSGI-server (som Gunicorn) istället för utvecklingsservern
- Konfigurera lämpliga brandväggsregler

## Implementeringsrekommendationer

### Utvecklingsmiljö

Använd Flasks inbyggda utvecklingsserver (visas i snabbstarten ovan).

### Produktionsmiljö

1. **Använd WSGI-server**:
```bash
   pip install gunicorn
   gunicorn -w 4 -b 0.0.0.0:8000 app:app
   ```

2. **Använd omvänd proxy**:
- Konfigurera Nginx eller Apache som en omvänd proxy
- Ställ in SSL-certifikat för att aktivera HTTPS

3. **Databasoptimering**:
- Överväg att använda PostgreSQL eller MySQL istället för SQLite
- Konfigurera vanlig säkerhetskopieringsmekanism

## Felsökning

### Vanliga frågor

1. **Applikationen kan inte startas**:
- Kontrollera om Python-versionen uppfyller kraven
- Bekräfta att alla beroende paket är korrekt installerade
- Kontrollera om katalogen `pyarmor_runtime_000000` finns och är komplett

2. **Språkväxling fungerar inte**:
- Bekräfta att "översättningar"-katalogen och dess innehåll är kompletta
- Kontrollera om webbläsarens inställningar för cookies är tillåtna

3. **Databasanslutningsfel**:
- Bekräfta att katalogen `instans` finns och har skrivbehörighet
- Försök att köra `init_db.py` igen för att initiera databasen

### Loggvy

När programmet startar kommer logginformation att matas ut på konsolen.Om du stöter på problem kan du kontrollera dessa loggar för mer information.

## Licens

[MIT License](LICENSE)

## Kontaktinformation

Om du har några frågor, förslag eller behöver utveckla en fullständig version/anpassad funktion, vänligen kontakta via följande metoder:

- **E-post**: austinlive666@gmail.com (rekommenderas)
- **Discord**:[https://discord.gg/7AN9PuGn](https://discord.gg/7AN9PuGn)

---

Tack för att du använder det här projektet!