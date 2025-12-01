# Flask Web Application – Website-Verwaltungssystem für Unternehmen (verschlüsselte Version)

## Projekteinführung

Dies ist eine **verschlüsselte Version** eines Enterprise-Website-Managementsystems, das auf Basis des Flask-Frameworks entwickelt wurde.Der Kerncode wurde von PyArmor verschleiert und verschlüsselt, um geistige Eigentumsrechte zu schützen.Das System unterstützt Mehrsprachen (Chinesisch und Englisch), Benutzerauthentifizierung, Produkt- und Nachrichtenverwaltung, Anzeige von Unternehmensinformationen und andere Funktionen.

## Anwendungs-Screenshot

Das Folgende ist ein Screenshot der Hauptoberfläche der Anwendung:

### Zuhause
![首页](screenshots/index.png)

### Management-Hintergrund
![管理后台](screenshots/admin_dashboard.png)

## Versionshinweise

Bei dieser Version handelt es sich um eine Basisverschlüsselungsversion, die umfassende Verwaltungsfunktionen für Unternehmenswebsites bietet.Wenn Sie Folgendes benötigen:

- **Vollständige Quellcodeversion**: Enthält unverschlüsselten vollständigen Quellcode, um die Sekundärentwicklung zu erleichtern
- **Maßgeschneiderte Funktionsentwicklung**: Funktionsanpassung und -erweiterung entsprechend Ihren spezifischen Anforderungen
- **Technische Supportdienste**: Erhalten Sie professionellen technischen Support und Wartungsdienste

Bitte kontaktieren Sie uns über die untenstehenden Kontaktinformationen und wir werden Ihnen detaillierte Pläne und Angebote unterbreiten.

## Verschlüsselungsfunktionen

- **Code-Schutz**: Kern-Python-Dateien (app.py, init_db.py, models.py) werden verschleiert und verschlüsselt
- **Laufzeitschutz**: Verwenden Sie die PyArmor-Laufzeitumgebung, um zu verhindern, dass Code dekompiliert wird
- **Volle Funktionalität**: Der verschlüsselte Code behält alle ursprünglichen Funktionen und Merkmale bei
- **Unterstützung mehrerer Sprachen**: integrierte Umschaltfunktion für Chinesisch und Englisch

## Dateien einschließen

```
/
├── app.py                  # Verschlüsselter Hauptanwendungseintrag
├── init_db.py              # Verschlüsseltes Datenbankinitialisierungsskript
├── models.py               # Verschlüsselte Datenmodelle
├── babel.cfg               # Babel-Internationalisierungskonfiguration
├── pyarmor_runtime_000000/ # PyArmor-Laufzeitunterstützungsdateien
├── static/                 # Statische Ressourcendateien (CSS, JS, Bilder)
├── templates/              # HTML-Vorlagendateien
├── translations/           # Mehrsprachige Übersetzungsdateien
└── instance/               # Datenbankverzeichnis (wird beim ersten Start automatisch erstellt)
```

## Schnellstart

### Umweltanforderungen

- Python 3.9 oder höher
- Installierte Abhängigkeitspakete:
- Flasche 3.0.0+
- Flask-SQLAlchemy 3.1.1+
- Flask-Login 0.6.3+
- Flask-Babel 4.0.0+
- Werkzeug 3.0.1+

### Abhängigkeiten installieren

Wenn die erforderlichen Abhängigkeiten noch nicht installiert sind, installieren Sie sie bitte zuerst:

```bash
pip install flask flask-sqlalchemy flask-login flask-babel werkzeug
```

### Führen Sie die Anwendung aus

1. **Datenbank initialisieren**

Vor der ersten Ausführung muss die Datenbank initialisiert werden:

```bash
   python init_db.py
   ```

2. **Starten Sie die Anwendung**

```bash
   python app.py
   ```

3. **Zugriff auf die App**

Öffnen Sie den Browser und besuchen Sie: http://127.0.0.1:5000

## Gebrauchsanweisung

### Website besuchen

1. Öffnen Sie den Browser und besuchen Sie http://127.0.0.1:5000
2. Verwenden Sie die Schaltfläche zum Umschalten der Sprache in der oberen rechten Ecke, um zwischen Chinesisch und Englisch zu wechseln

### Management-Hintergrund

1. Besuchen Sie http://127.0.0.1:5000/admin/login
2. Melden Sie sich mit dem Administratorkonto an (Standardbenutzername und Passwort: admin/admin123).
3. Produkte, Neuigkeiten und Unternehmensinformationen können im Management-Hintergrund verwaltet werden

## Funktionsbeschreibung

### Front-End-Funktionen

- **Home**: Firmenprofil und Hauptprodukte anzeigen
- **Über uns**: Firmendetails anzeigen
- **Produktanzeige**: Durchsuchen Sie alle Produktlisten
- **Branchen-Updates**: Sehen Sie sich die neuesten Nachrichten und Informationen an
- **Sprachumschaltung**: Unterstützt das Umschalten zwischen Chinesisch und Englisch

### Hintergrundfunktionen verwalten

- **Produktverwaltung**: Produkte hinzufügen, bearbeiten, löschen
- **Nachrichtenverwaltung**: Nachrichten veröffentlichen, bearbeiten, löschen
- **Unternehmensinformationen**: Grundlegende Unternehmensinformationen aktualisieren
- **Benutzerauthentifizierung**: sicheres Anmeldesystem

## Screenshot-Anleitung

Um den besten README-Anzeigeeffekt zu erzielen, wird empfohlen, Screenshots gemäß den folgenden Richtlinien zu erstellen und hinzuzufügen:

1. **Screenshots-Ordner erstellen**: Erstellen Sie den Ordner „screenshots/“ im Verzeichnis „dist/“.
2. **Screenshot-Größe**: Verwenden Sie einen Screenshot mit einer Auflösung von 1920 x 1080 oder 1366 x 768, um sicherzustellen, dass der Inhalt deutlich sichtbar ist
3. **Screenshot-Inhalt**:
- Startseite: Zeigt die vollständige Homepage-Oberfläche an, einschließlich Navigationsleiste und Hauptinhaltsbereich
- Sprachwechsel: Zeigt den vergleichenden Effekt des Wechsels zwischen Chinesisch und Englisch (es können Screenshots mit geteiltem Bildschirm verwendet werden).
- Produktanzeige: Produktliste und Details zu einzelnen Produkten anzeigen
- Nachrichtenseite: Nachrichtenliste und Nachrichtendetails anzeigen
- Management-Backend: Zeigt das Dashboard und die Funktionsoberfläche an, nachdem sich der Administrator angemeldet hat
4. **Screenshot-Format**: Verwenden Sie das PNG-Format für beste Qualität
5. **Dateibenennung**: Speichern Sie den Screenshot entsprechend dem in der README-Datei angegebenen Dateinamen (index.png, language_switch.png usw.).

## Notizen

1. **Dateiintegrität**: Bitte stellen Sie sicher, dass alle Dateien korrekt heruntergeladen wurden, insbesondere das Verzeichnis „pyarmor_runtime_000000“ und sein Inhalt

2. **Datenbankdatei**:
- Die Datenbankdatei wird automatisch im Verzeichnis „Instanz“ erstellt
- Wenn Sie Daten sichern müssen, sichern Sie bitte regelmäßig die Datei „instance/site.db“.

3. **Mehrsprachige Unterstützung**:
- Alle Übersetzungsdateien sind im Verzeichnis „translations“ enthalten
- Informationen zum Hinzufügen neuer Übersetzungssprachen finden Sie in der Originalprojektdokumentation

4. **Betriebsumgebung**:
- Stellen Sie sicher, dass die Python-Version nicht niedriger als 3.9 ist
- Stellen Sie sicher, dass alle erforderlichen Abhängigkeiten installiert sind

5. **Sicherheitstipps**:
- Bei der Bereitstellung in einer Produktionsumgebung ändern Sie bitte das Standard-Administratorkennwort.
- Erwägen Sie die Verwendung eines WSGI-Servers (z. B. Gunicorn) anstelle des Entwicklungsservers
- Konfigurieren Sie geeignete Firewall-Regeln

## Bereitstellungsempfehlungen

### Entwicklungsumgebung

Verwenden Sie den in Flask integrierten Entwicklungsserver (siehe Schnellstart oben).

### Produktionsumgebung

1. **WSGI-Server verwenden**:
```bash
   pip install gunicorn
   gunicorn -w 4 -b 0.0.0.0:8000 app:app
   ```

2. **Reverse-Proxy verwenden**:
- Konfigurieren Sie Nginx oder Apache als Reverse-Proxy
- Richten Sie ein SSL-Zertifikat ein, um HTTPS zu aktivieren

3. **Datenbankoptimierung**:
- Erwägen Sie die Verwendung von PostgreSQL oder MySQL anstelle von SQLite
- Konfigurieren Sie den regulären Sicherungsmechanismus

## Fehlerbehebung

### FAQ

1. **Anwendung kann nicht gestartet werden**:
- Prüfen Sie, ob die Python-Version die Anforderungen erfüllt
- Bestätigen Sie, dass alle abhängigen Pakete korrekt installiert sind
- Überprüfen Sie, ob das Verzeichnis „pyarmor_runtime_000000“ existiert und vollständig ist

2. **Sprachumschaltung funktioniert nicht**:
- Bestätigen Sie, dass das Verzeichnis „translations“ und sein Inhalt vollständig sind
- Überprüfen Sie, ob die Browser-Cookie-Einstellungen zulässig sind

3. **Datenbankverbindungsfehler**:
- Bestätigen Sie, dass das Verzeichnis „Instanz“ vorhanden ist und über Schreibberechtigungen verfügt
- Versuchen Sie, „init_db.py“ erneut auszuführen, um die Datenbank zu initialisieren

### Protokollansicht

Beim Start der Anwendung werden Protokollinformationen auf der Konsole ausgegeben.Wenn Sie auf Probleme stoßen, können Sie diese Protokolle auf weitere Informationen überprüfen.

## Lizenz

[MIT License](LICENSE)

## Kontaktinformationen

Wenn Sie Fragen oder Anregungen haben oder die Entwicklung einer Vollversion/benutzerdefinierten Funktion benötigen, wenden Sie sich bitte über die folgenden Methoden an:

- **E-Mail**: austinlive666@gmail.com (empfohlen)
- **Discord**:[https://discord.gg/7AN9PuGn](https://discord.gg/7AN9PuGn)

---

Vielen Dank, dass Sie dieses Projekt nutzen!