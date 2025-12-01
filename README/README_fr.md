[English](README_en.md)|[German](README_de.md)|[中文](README_zh.md)|[日本語](README_ja.md)|[Русский](README_ru.md)|[한국어](README_ko.md)|[Español](README_es.md)|Français|[Italiano](README_it.md)|[Português](README_pt.md)|[Nederlands](README_nl.md)|[Polski](README_pl.md)|[العربية](README_ar.md)|[हिन्दी](README_hi.md)|[ไทย](README_th.md)|[Svenska](README_sv.md)|[Türkçe](README_tr.md)|[Tiếng Việt](README_vi.md)

# Flask Web Application - Système de gestion de site Web d'entreprise (version cryptée)

## Présentation du projet

Il s'agit d'une **version cryptée** d'un système de gestion de site Web d'entreprise développé sur la base du framework Flask. Le code principal a été obscurci et crypté par PyArmor pour protéger les droits de propriété intellectuelle.Le système prend en charge plusieurs langues (chinois et anglais), l'authentification des utilisateurs, la gestion des produits et des actualités, l'affichage des informations sur l'entreprise et d'autres fonctions.

## Capture d'écran de l'application

Voici une capture d'écran de l'interface principale de l'application :

### Accueil
![首页](screenshots/index.png)

### Expérience en gestion
![管理后台](screenshots/admin_dashboard.png)

## Notes de version

Cette version est une version de cryptage de base qui fournit des fonctions complètes de gestion de sites Web d'entreprise.Si vous avez besoin de :

- **Version complète du code source** : contient le code source complet non crypté pour faciliter le développement secondaire
- **Développement de fonctions personnalisées** : personnalisation et extension des fonctions en fonction de vos besoins spécifiques
- **Services d'assistance technique** : bénéficiez de services d'assistance technique et de maintenance professionnels

Veuillez nous contacter via les coordonnées ci-dessous et nous vous fournirons des plans et des devis détaillés.

## Fonctionnalités de cryptage

- **Protection du code** : les fichiers Core Python (app.py, init_db.py, models.py) sont obscurcis et cryptés
- **Protection d'exécution** : utilisez l'environnement d'exécution PyArmor pour empêcher la décompilation du code
- **Fonctionnalité complète** : Le code crypté conserve toutes les fonctionnalités et caractéristiques d'origine
- **Support multilingue** : fonction de commutation intégrée en chinois et en anglais

## Inclure les fichiers

```
/
├── app.py                  # Entrée d'application principale cryptée
├── init_db.py              # Script d'initialisation de la base de données chiffrée
├── models.py               # Modèles de données chiffrés
├── babel.cfg               # Configuration de l'internationalisation Babel
├── pyarmor_runtime_000000/ # Fichiers de support d'exécution PyArmor
├── static/                 # Fichiers de ressources statiques (CSS, JS, images)
├── templates/              # Fichiers de modèles HTML
├── translations/           # Fichiers de traduction multilingues
└── instance/               # Répertoire de base de données (créé automatiquement lors de la première exécution)
```

## Démarrage rapide

### Exigences environnementales

- Python 3.9 ou supérieur
- Packages de dépendances installés :
- Flacon 3.0.0+
- Flask-SQLAlchemy 3.1.1+
- Connexion Flask 0.6.3+
- Flacon-Babel 4.0.0+
- Travail 3.0.1+

### Installer les dépendances

Si les dépendances requises ne sont pas encore installées, veuillez d'abord les installer :

```bash
pip install flask flask-sqlalchemy flask-login flask-babel werkzeug
```

### Exécutez l'application

1. **Initialiser la base de données**

Avant de s'exécuter pour la première fois, la base de données doit être initialisée :

```bash
   python init_db.py
   ```

2. **Lancez l'application**

```bash
   python app.py
   ```

3. **Accéder à l'application**

Ouvrez le navigateur et visitez : http://127.0.0.1:5000

## Mode d'emploi

### Visiter le site Web

1. Ouvrez le navigateur et visitez http://127.0.0.1:5000
2. Utilisez le bouton de changement de langue dans le coin supérieur droit pour basculer entre le chinois et l'anglais.

### Expérience en gestion

1. Visitez http://127.0.0.1:5000/admin/login
2. Connectez-vous avec le compte administrateur (nom d'utilisateur et mot de passe par défaut : admin/admin123)
3. Les produits, les actualités et les informations sur l'entreprise peuvent être gérés en arrière-plan de gestion

## Description de la fonction

### Fonctions frontales

- **Accueil** : Afficher le profil de l'entreprise et les principaux produits
- **À propos de nous** : afficher les détails de l'entreprise
- **Affichage du produit** : parcourez toutes les listes de produits
- **Mises à jour de l'industrie** : consultez les dernières nouvelles et informations
- **Changement de langue** : prend en charge le basculement entre le chinois et l'anglais

### Gérer les fonctions d'arrière-plan

- **Gestion des produits** : ajouter, modifier, supprimer des produits
- **Gestion des actualités** : publier, modifier, supprimer des actualités
- **Informations sur l'entreprise** : mettre à jour les informations de base sur l'entreprise
- **Authentification utilisateur** : système de connexion sécurisé

## Guide de capture d'écran

Afin d'obtenir le meilleur effet d'affichage README, il est recommandé de créer et d'ajouter des captures d'écran selon les directives suivantes :

1. **Créer un dossier de captures d'écran** : Créez le dossier `screenshots/` dans le répertoire `dist/`
2. **Taille de la capture d'écran** : utilisez une capture d'écran avec une résolution de 1 920 x 1 080 ou 1 366 x 768 pour garantir que le contenu est clairement visible.
3. **Contenu de la capture d'écran** :
- Page d'accueil : affiche l'interface complète de la page d'accueil, y compris la barre de navigation et la zone de contenu principale
- Changement de langue : montrez l'effet comparatif du basculement entre le chinois et l'anglais (des captures d'écran en écran partagé peuvent être utilisées)
- Affichage du produit : afficher la liste des produits et les détails des produits individuels
- Page Actualités : afficher la liste des actualités et les détails de l'actualité
- Backend de gestion : affiche le tableau de bord et l'interface fonctionnelle après la connexion de l'administrateur
4. **Format de capture d'écran** : utilisez le format PNG pour une meilleure qualité
5. **Nom de fichier** : enregistrez la capture d'écran en fonction du nom de fichier spécifié dans le README (index.png, language_switch.png, etc.)

## Remarques

1. **Intégrité des fichiers** : Veuillez vous assurer que tous les fichiers ont été téléchargés correctement, en particulier le répertoire `pyarmor_runtime_000000` et son contenu.

2. **Fichier de base de données** :
- Le fichier de base de données sera automatiquement créé dans le répertoire `instance`
- Si vous devez sauvegarder des données, veuillez sauvegarder régulièrement le fichier `instance/site.db`

3. **Support multilingue** :
- Tous les fichiers de traduction sont inclus dans le répertoire `translations`
- Pour ajouter de nouvelles langues de traduction, veuillez vous référer à la documentation originale du projet

4. **Environnement d'exploitation** :
- Assurez-vous que la version de Python n'est pas inférieure à 3.9
- Assurez-vous que toutes les dépendances nécessaires sont installées

5. **Conseils de sécurité** :
- Lors du déploiement dans un environnement de production, veuillez modifier le mot de passe administrateur par défaut.
- Pensez à utiliser un serveur WSGI (comme Gunicorn) au lieu du serveur de développement
- Configurer les règles de pare-feu appropriées

## Recommandations de déploiement

### Environnement de développement

Utilisez le serveur de développement intégré Flask (illustré dans le démarrage rapide ci-dessus).

### Environnement de production

1. **Utilisez le serveur WSGI** :
```bash
   pip install gunicorn
   gunicorn -w 4 -b 0.0.0.0:8000 app:app
   ```

2. **Utilisez le proxy inverse** :
- Configurer Nginx ou Apache comme proxy inverse
- Configurer le certificat SSL pour activer HTTPS

3. **Optimisation de la base de données** :
- Pensez à utiliser PostgreSQL ou MySQL au lieu de SQLite
- Configurer un mécanisme de sauvegarde régulier

## Dépannage

### FAQ

1. **L'application ne peut pas être démarrée** :
- Vérifiez si la version Python répond aux exigences
- Confirmez que tous les packages dépendants sont installés correctement
- Vérifiez si le répertoire `pyarmor_runtime_000000` existe et est complet

2. **Le changement de langue ne fonctionne pas** :
- Confirmez que le répertoire `traductions` et son contenu sont complets
- Vérifiez si les paramètres des cookies du navigateur sont autorisés

3. **Erreur de connexion à la base de données** :
- Confirmez que le répertoire `instance` existe et dispose des autorisations en écriture
- Essayez de réexécuter `init_db.py` pour initialiser la base de données

### Vue du journal

Lorsque l'application démarre, les informations du journal seront affichées sur la console. Si vous rencontrez des problèmes, vous pouvez consulter ces journaux pour plus d'informations.

## Licence

[MIT License](LICENSE)

## Coordonnées

Si vous avez des questions, des suggestions ou si vous avez besoin d'une version complète/de développement de fonctions personnalisées, veuillez nous contacter via les méthodes suivantes :

- **E-mail** : austinlive666@gmail.com (recommandé)
- **Discorde** :[https://discord.gg/7AN9PuGn](https://discord.gg/7AN9PuGn)

---

Merci d'avoir utilisé ce projet !