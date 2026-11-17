# Plume : installateurs

Plume est un éditeur de bureau pour écrire et publier les articles d'un blog Markdown.

Ce dépôt ne contient que les installateurs. Dernière version : onglet **Releases**, ou directement
https://github.com/ExoKayn/plume-releases/releases/latest

| Système | Fichier |
| --- | --- |
| Windows | `Plume-<version>-win-x64.exe` |
| macOS, puce Apple (M1 et suivantes) | `Plume-<version>-mac-arm64.zip` |
| macOS, processeur Intel | `Plume-<version>-mac-x64.zip` |
| Linux | `Plume-<version>-linux-x86_64.AppImage` |

Plume signale lui-même les nouvelles versions au démarrage.

Les fichiers ne sont pas signés : au premier lancement, Windows et macOS avertissent. Windows : « Informations
complémentaires » puis « Exécuter quand même ». macOS : décompresser le `.zip`, glisser Plume dans Applications, puis
Réglages Système, Confidentialité et sécurité, « Ouvrir quand même » (si l'application est dite « endommagée » :
`xattr -cr /Applications/Plume.app` dans le Terminal). Linux : rendre l'AppImage exécutable puis l'ouvrir.
