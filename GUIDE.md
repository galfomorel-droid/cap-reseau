# Cap Réseau — mémo pour Charles

**Adresse :** https://galfomorel-droid.github.io/cap-reseau/

## Première connexion (ta copine)
1. Ouvrir l'adresse, toucher **« Première fois ? Créer un compte »**, saisir son e-mail et un mot de passe (8 caractères minimum).
2. L'installer sur l'écran d'accueil :
   - **iPhone** : Partager → « Sur l'écran d'accueil »
   - **Android** : menu ⋮ → « Ajouter à l'écran d'accueil »
3. Sur un autre appareil, même adresse, même e-mail et même mot de passe : elle retrouve les mêmes données.

## Une fois son compte créé
Fermer les inscriptions, pour que personne d'autre ne puisse créer de compte : Supabase → projet **cap-reseau** → Authentication → Sign In / Providers → décocher **Allow new users to sign up** → Save. (Claude peut le faire.)

## Mot de passe oublié
Le service d'e-mail gratuit de Supabase n'envoie pas d'e-mails aux utilisateurs. Pour réinitialiser son mot de passe, demande à Claude, ou : Supabase → Authentication → Users → son compte → « Reset password ».

## Bon à savoir
- **0 €** : GitHub Pages (hébergement) et Supabase (offre gratuite, base en Europe).
- Un projet Supabase gratuit **se met en pause après 7 jours sans aucune utilisation**. Utilisée régulièrement, l'appli reste active. Si elle est en pause, il suffit de la relancer depuis le tableau de bord Supabase.
- Les rendez-vous ont un bouton **« Ajouter à mon agenda »**, qui crée un fichier à ouvrir avec l'agenda du téléphone.
- Publier une modification : commit, puis `git push` dans ce dossier.
