# Vibrostase

Sons qui imitent l'état vibratoire (EV) pour aider à le provoquer à la frontière du sommeil, avec suivi du corps pendant la séance.

## Android : installer l'appli (recommandé)

1. Ouvre **[la dernière version](https://github.com/Aresh1674/vibrostase-web/releases/latest)** sur le téléphone et touche le fichier `vibrostase-….apk`.
2. Ouvre le fichier téléchargé. Android demande d'autoriser le navigateur à installer des applis : accepte.
   Si Play Protect prévient que l'appli est inconnue : **Plus de détails › Installer quand même** (elle ne vient pas du Play Store).
3. Au premier lancement, autorise les **notifications** (séance en arrière-plan).
4. Paramètres Android › Applis › Vibrostase › Batterie › **Sans restriction**.
5. Mises à jour : installe la nouvelle version **par-dessus**, sans désinstaller. Désinstaller efface tes séances.

L'appli Android est la plus complète : son qui tient écran verrouillé, mouvements mesurés écran éteint, montre cardio en Bluetooth, envoi des données d'analyse.

## iPhone et ordinateur : version web

Ouvre **https://aresh1674.github.io/vibrostase-web/**. Sur iPhone : Safari › Partager › **Sur l'écran d'accueil**.

Limites de la version web : garde l'écran allumé (« Écran noir » l'assombrit), sinon le son s'arrête ; pas de montre en Bluetooth dans Safari ; les données d'analyse s'exportent à la main.

## Contenu du dépôt

| Chemin | Rôle |
|---|---|
| `index.html` | L'appli (même page que l'APK) |
| `sons/` | Les 101 enregistrements intégrés (CC0, Freesound) et `SOURCES.txt` |
| `tuto.mp4` | La vidéo de prise en main (Réglages › Aide) |

Rien d'autre ne doit être déposé à la racine : la page cherche les sons dans `sons/`. Ce dépôt est public : il ne contient ni clé ni mot de passe.
