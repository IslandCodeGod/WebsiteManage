# Flask Web Application - Sistema di gestione dei siti Web aziendali (versione crittografata)

## Introduzione al progetto

Si tratta di una **versione crittografata** di un sistema di gestione di siti Web aziendali sviluppato sulla base del framework Flask.Il codice principale è stato offuscato e crittografato da PyArmor per proteggere i diritti di proprietà intellettuale.Il sistema supporta multilingue (cinese e inglese), autenticazione dell'utente, gestione di prodotti e notizie, visualizzazione di informazioni aziendali e altre funzioni.

## Schermata dell'applicazione

Di seguito è riportato uno screenshot dell'interfaccia principale dell'applicazione:

### Casa
![首页](screenshots/index.png)

### Background gestionale
![管理后台](screenshots/admin_dashboard.png)

## Note sulla versione

Questa versione è una versione di crittografia di base che fornisce funzioni complete di gestione del sito Web aziendale.Se hai bisogno:

- **Versione completa del codice sorgente**: contiene il codice sorgente completo non crittografato per facilitare lo sviluppo secondario
- **Sviluppo di funzioni personalizzate**: personalizzazione ed espansione delle funzioni in base alle vostre esigenze specifiche
- **Servizi di supporto tecnico**: ottieni supporto tecnico professionale e servizi di manutenzione

Vi preghiamo di contattarci tramite le informazioni di contatto riportate di seguito e vi forniremo piani dettagliati e preventivi.

## Funzionalità di crittografia

- **Protezione del codice**: i file Core Python (app.py, init_db.py, models.py) sono offuscati e crittografati
- **Protezione runtime**: utilizza l'ambiente runtime PyArmor per impedire la decompilazione del codice
- **Funzionalità completa**: il codice crittografato mantiene tutte le funzionalità e le caratteristiche originali
- **Supporto multilingue**: funzione di commutazione cinese e inglese integrata

## Includi file

```
/
├── app.py                  # Voce dell'applicazione principale crittografata
├── init_db.py              # Script di inizializzazione del database crittografato
├── models.py               # Modelli di dati crittografati
├── babel.cfg               # Configurazione dell'internazionalizzazione Babel
├── pyarmor_runtime_000000/ # File di supporto del runtime PyArmor
├── static/                 # File di risorse statici (CSS, JS, immagini)
├── templates/              # File modello HTML
├── translations/           # File di traduzione multilingue
└── instance/               # Directory del database (creata automaticamente alla prima esecuzione)
```

## Avvio rapido

### Requisiti ambientali

- Python 3.9 o versione successiva
- Pacchetti di dipendenze installati:
- Pallone 3.0.0+
- Flask-SQLAlchemy 3.1.1+
- Accesso a Flask 0.6.3+
- Flask-Babel 4.0.0+
- Lavoro 3.0.1+

### Installa le dipendenze

Se le dipendenze richieste non sono ancora installate, installarle prima:

```bash
pip install flask flask-sqlalchemy flask-login flask-babel werkzeug
```

### Esegui l'applicazione

1. **Inizializza database**

Prima di essere eseguito per la prima volta, il database deve essere inizializzato:

__CODICE_BLOCCO_2__

2. **Avvia l'applicazione**

```bash
   python app.py
   ```

3. **Accedi all'app**

Aprire il browser e visitare: http://127.0.0.1:5000

## Istruzioni per l'uso

### Visita il sito web

1. Aprire il browser e visitare http://127.0.0.1:5000
2. Utilizzare il pulsante di cambio lingua nell'angolo in alto a destra per passare dal cinese all'inglese

### Background gestionale

1. Visita http://127.0.0.1:5000/admin/login
2. Accedi con l'account amministratore (nome utente e password predefiniti: admin/admin123)
3. Prodotti, notizie e informazioni aziendali possono essere gestiti in background gestionale

## Descrizione della funzione

### Funzioni front-end

- **Home**: Visualizza il profilo dell'azienda e i principali prodotti
- **Chi siamo**: mostra i dettagli dell'azienda
- **Visualizzazione prodotto**: sfoglia tutti gli elenchi di prodotti
- **Aggiornamenti di settore**: visualizza le ultime notizie e informazioni
- **Cambio lingua**: supporta il passaggio dal cinese all'inglese

### Gestisci le funzioni in background

- **Gestione prodotti**: aggiungi, modifica, elimina prodotti
- **Gestione notizie**: pubblica, modifica, elimina notizie
- **Informazioni aziendali**: aggiorna le informazioni aziendali di base
- **Autenticazione Utente**: sistema di accesso sicuro

## Guida alle schermate

Per ottenere il miglior effetto di visualizzazione README, si consiglia di creare e aggiungere screenshot secondo le seguenti linee guida:

1. **Crea cartella screenshot**: crea la cartella `screenshots/` nella directory `dist/`
2. **Dimensioni screenshot**: utilizza uno screenshot con risoluzione 1920x1080 o 1366x768 per garantire che il contenuto sia chiaramente visibile
3. **Contenuto dello screenshot**:
- Home page: visualizza l'interfaccia completa della home page, inclusa la barra di navigazione e l'area del contenuto principale
- Cambio lingua: mostra l'effetto comparativo del passaggio tra cinese e inglese (è possibile utilizzare screenshot a schermo diviso)
- Visualizzazione prodotti: visualizza l'elenco dei prodotti e i dettagli dei singoli prodotti
- Pagina Notizie: visualizza l'elenco delle notizie e i dettagli delle notizie
- Backend di gestione: visualizza la dashboard e l'interfaccia funzionale dopo che l'amministratore ha effettuato l'accesso
4. **Formato screenshot**: utilizza il formato PNG per la migliore qualità
5. **Nominazione file**: salva lo screenshot in base al nome file specificato nel file README (index.png, Language_switch.png, ecc.)

## Note

1. **Integrità dei file**: assicurati che tutti i file siano stati scaricati correttamente, in particolare la directory `pyarmor_runtime_000000` e i suoi contenuti

2. **File di database**:
- Il file del database verrà creato automaticamente nella directory "istanza".
- Se è necessario eseguire il backup dei dati, eseguire regolarmente il backup del file `instance/site.db`

3. **Supporto multilingue**:
- Tutti i file di traduzione sono inclusi nella directory "translations".
- Per aggiungere nuove lingue di traduzione, fare riferimento alla documentazione del progetto originale

4. **Ambiente operativo**:
- Assicurati che la versione di Python non sia inferiore alla 3.9
- Assicurati che tutte le dipendenze necessarie siano installate

5. **Suggerimenti per la sicurezza**:
- Quando si distribuisce in un ambiente di produzione, modificare la password dell'amministratore predefinita.
- Considera l'utilizzo di un server WSGI (come Gunicorn) invece del server di sviluppo
- Configurare le regole firewall appropriate

## Consigli per la distribuzione

### Ambiente di sviluppo

Utilizza il server di sviluppo integrato Flask (mostrato nella guida di avvio rapido sopra).

### Ambiente di produzione

1. **Utilizza il server WSGI**:
```bash
   pip install gunicorn
   gunicorn -w 4 -b 0.0.0.0:8000 app:app
   ```

2. **Utilizza proxy inverso**:
- Configura Nginx o Apache come proxy inverso
- Configura il certificato SSL per abilitare HTTPS

3. **Ottimizzazione del database**:
- Considera l'utilizzo di PostgreSQL o MySQL invece di SQLite
- Configurare il meccanismo di backup regolare

## Risoluzione dei problemi

### Domande frequenti

1. **Non è possibile avviare l'applicazione**:
- Controlla se la versione Python soddisfa i requisiti
- Confermare che tutti i pacchetti dipendenti siano installati correttamente
- Controlla se la directory `pyarmor_runtime_000000` esiste ed è completa

2. **Il cambio di lingua non funziona**:
- Conferma che la directory "translations" e il suo contenuto siano completi
- Controlla se le impostazioni dei cookie del browser sono consentite

3. **Errore di connessione al database**:
- Conferma che la directory "istanza" esista e disponga dei permessi di scrittura
- Prova a eseguire nuovamente `init_db.py` per inizializzare il database

### Visualizzazione registro

All'avvio dell'applicazione, le informazioni di registro verranno visualizzate sulla console.Se riscontri problemi, puoi controllare questi registri per ulteriori informazioni.

## Licenza

[MIT License](LICENSE)

## Informazioni di contatto

Se avete domande, suggerimenti o avete bisogno dello sviluppo di versioni complete/funzioni personalizzate, contattate tramite i seguenti metodi:

- **E-mail**: austinlive666@gmail.com (consigliato)
- **Discordia**:[https://discord.gg/7AN9PuGn](https://discord.gg/7AN9PuGn)

---

Grazie per aver utilizzato questo progetto!