# Installer la préversion NextExplorer

## Avant de commencer

Cette préversion technique vise Windows 11 x64 avec Chrome. L’installateur est
non signé ; une alerte ou un blocage Windows reste possible. L’installation
complète sur un Windows neuf n’est pas encore validée. Utilisez d’abord un dossier
de démonstration et conservez vos sauvegardes.

Téléchargez les fichiers uniquement depuis les
[releases officielles](https://github.com/Gremy44/NextExplorer-Downloads/releases).
Les fichiers sont gratuits. N’utilisez pas les archives « Source code » de GitHub
pour installer l’application.

## Installation

1. Téléchargez `NextExplorer-<version>-Setup.exe` et, si vous souhaitez contrôler
   l’intégrité du fichier, `SHA256SUMS.txt` de la même release.
2. Lancez l’installateur, choisissez Chrome et conservez l’identifiant prérempli.
   Examinez les changements annoncés, puis installez pour votre compte Windows.
3. Ouvrez `chrome://extensions`, activez **Mode développeur**, puis choisissez
   **Charger l’extension non empaquetée**.
4. Sélectionnez `%LOCALAPPDATA%\Programs\NextExplorer\package\dist`.
5. Épinglez NextExplorer et ouvrez son panneau. Vérifiez **Compagnon connecté**,
   puis choisissez votre dossier de démonstration.

L’extension et le compagnon doivent provenir de la même release. Ne chargez pas
une seconde copie de l’extension depuis un autre dossier. Le parcours sans mode
développeur sera disponible après la publication Chrome Web Store.

L’archive `NextExplorer-<version>-extension.zip` est fournie pour examiner ou
charger séparément l’extension. Elle ne remplace pas l’installation du compagnon.
Le chemin installé ci-dessus reste le parcours recommandé pour cette préversion.

## Vérifier une empreinte, si nécessaire

Dans PowerShell, utilisez `Get-FileHash -Algorithm SHA256 -LiteralPath` suivi du
chemin du fichier téléchargé. Comparez le résultat à la ligne correspondante de
`SHA256SUMS.txt`. Une empreinte identique vérifie l’intégrité du téléchargement ;
elle ne remplace pas une signature d’éditeur.

## Moteurs et limites

Le paquet initial n’embarque pas FFmpeg, ImageMagick, ExifTool ou 7-Zip. Certains
aperçus, conversions et archives restent donc indisponibles jusqu’à l’installation
du moteur correspondant. Les réglages de l’extension indiquent les moteurs
détectés ; leur préparation reste un parcours avancé dans cette préversion.

Le compagnon possède les droits de votre compte Windows. Les tâches autorisées
peuvent continuer après fermeture de Chrome. La console n’est pas un bac à sable.
Le glisser-déposer et l’insertion dépendent aussi du site cible.

## Mettre à jour ou réparer

Terminez vos traitements et fermez la console avant une mise à jour. Téléchargez
le nouvel installateur, lancez-le puis rechargez l’extension dans
`chrome://extensions`. Désactivez et réactivez l’extension pour renouveler sa
connexion au compagnon.

L’assistant conserve les moteurs déjà installés et l’ancienne copie du compagnon
lorsque la mise à jour le nécessite. Si la liaison ne fonctionne plus, ouvrez
**NextExplorer → Installer ou réparer** dans le menu Démarrer. Signalez tout échec
sans publier de fichier personnel ni de journal brut contenant des chemins privés.

## Désinstaller

Terminez les traitements, désactivez les règles automatiques et fermez Chrome.
Retirez NextExplorer dans les applications Windows puis supprimez son extension
depuis `chrome://extensions`. Le retrait conserve les documents et les éléments de
récupération prévus par le compagnon ; ce n’est pas un effacement complet de ses
données locales.
