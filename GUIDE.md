# Mettre Cap Réseau en ligne (0 €)

L'adresse du site sera **https://galfomorel-droid.github.io/cap-reseau/**

- **GitHub Pages** héberge le site gratuitement. Le code est public, mais les données ne le sont pas : elles restent dans le Google Drive de l'utilisatrice.
- **Google** fournit la connexion, Drive et Agenda, gratuitement.

## Étape 1 — GitHub (2 clics, à faire une seule fois)

1. Créer le dépôt : https://github.com/new
   - Nom : `cap-reseau`
   - Visibilité : **Public**, obligatoire pour GitHub Pages gratuit
   - Ne rien cocher d'autre → **Create repository**
2. Claude envoie le site dans le dépôt.
3. Activer le site : dans le dépôt, ouvrir **Settings** → **Pages** → Source : **Deploy from a branch** → Branche : `main`, dossier `/ (root)` → **Save**.
   Le site est en ligne après une à deux minutes.

## Étape 2 — Autoriser la connexion Google (Google Cloud)

1. Aller sur https://console.cloud.google.com
2. Créer un **nouveau projet** nommé `Cap Réseau`, **sans compte de facturation**, pour être sûr que ça ne coûte jamais rien.
3. **API et services** → **Bibliothèque** : activer **Google Calendar API** et **Google Drive API**.
4. **Google Auth Platform** → **Commencer** :
   - Nom : `Cap Réseau`
   - E-mail d'assistance : le tien
   - Audience : **Externe**
   - Coordonnées : les tiennes → **Créer**
5. Onglet **Audience** → **Publier l'application**.
   *Si Google refuse, ajouter à la place l'adresse Gmail de ta copine dans **Utilisateurs test**.*
6. Onglet **Clients** → **Créer un client** :
   - Type : **Application Web**
   - Origines JavaScript autorisées : `https://galfomorel-droid.github.io`
   - URI de redirection autorisés : `https://galfomorel-droid.github.io/cap-reseau/`
   - **Créer**
7. Copier l'**ID client** (`…apps.googleusercontent.com`) et **l'envoyer à Claude**. Claude l'ajoute et republie le site.

## Pour ta copine

1. Ouvrir https://galfomorel-droid.github.io/cap-reseau/ sur son téléphone, puis **Se connecter avec Google**.
   Si Google affiche « application non validée » : **Paramètres avancés** → **Accéder à Cap Réseau**.
2. L'installer comme une application :
   - **iPhone** : Partager → **Sur l'écran d'accueil**
   - **Android** : menu ⋮ → **Ajouter à l'écran d'accueil**
3. Sur ordinateur : même adresse, même compte Google, mêmes données.

## Bon à savoir

- La connexion Google dure une heure et se renouvelle toute seule à l'ouverture. Si l'appli reste ouverte plus longtemps, il suffit de cliquer sur **Se reconnecter**. Rien n'est perdu.
- Réglages → **Copier la sauvegarde** permet de garder une copie de secours.
