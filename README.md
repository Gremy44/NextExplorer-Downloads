# NextExplorer

**Vos fichiers locaux, vos pages web et votre terminal dans le même espace.**

Préparer une publication, déposer des documents sur un site, retrouver les liens
d’un projet ou lancer un outil de développement : NextExplorer rapproche votre
explorateur de ce que vous faites déjà dans Chrome.

Le **panneau latéral** garde vos fichiers à côté du site ouvert. La **vue complète**
offre des onglets de dossiers, un double panneau, des aperçus et une console.
Vos fichiers restent sur votre ordinateur.

**[Télécharger la préversion gratuite](https://github.com/Gremy44/NextExplorer-Downloads/releases)**
· [Installer](INSTALLATION.md) · [Toutes les fonctions](FONCTIONNALITES.md)
· [La suite du projet](#la-suite-du-projet)

## Déposer un fichier sans quitter la page

Ouvrez votre dossier dans le panneau NextExplorer, puis **glissez le nom du
fichier vers la zone de dépôt du site**. Pas besoin de le collecter ou de cocher
une case au préalable. La page reste visible pendant la navigation dans vos dossiers.

Utile pour joindre un document, ajouter un visuel dans un outil web ou déposer
un livrable. Le geste utilise le glisser-déposer natif de Windows ; le site reçoit
le fichier et l’original reste à sa place.

[![Vrai panneau Chrome à côté d’une page ayant reçu le fichier](images/panneau-web.png)](images/panneau-web.png)

*Capture réelle du navigateur, 1920 × 1111. La page témoin est locale et ne
téléverse rien. Sur un service réel, le dépôt peut déclencher un envoi immédiat.
Un fichier par geste ; le site doit accepter le dépôt, son format et sa taille.*

Le panneau permet aussi de **collecter des fichiers venant de plusieurs dossiers**,
de garder des liens et de préparer une sélection pour un formulaire compatible.
Sa vue **Page** rapproche le dossier de travail et la page courante.

## Un explorateur complet quand vous avez besoin de place

Passez en pleine page pour ouvrir plusieurs dossiers en **onglets**, parcourir
deux emplacements côte à côte et ajuster la largeur des panneaux. Choisissez
l’affichage qui vous convient : icônes, liste, détails, mosaïques, contenu ou
colonnes de dossiers, avec tri et filtres.

[![Explorateur à onglets, aperçu Markdown et métadonnées](images/explorateur-1920.png)](images/explorateur-1920.png)

*1920 × 1080 · Un document sélectionné, son aperçu et ses informations.
Les captures utilisent uniquement un projet fictif. Cliquez pour les ouvrir en grand.*

Le volet **Aperçu et détails** permet de consulter les fichiers compatibles,
leurs métadonnées et leurs actions rapides. Il se redimensionne, s’agrandit et
accueille aussi l’analyse d’espace disque et la console.

[![Deux dossiers côte à côte, avec des affichages différents](images/double-panneau-1920.png)](images/double-panneau-1920.png)

*1920 × 1080 · Garder une source et une destination visibles dans le même onglet.*

## La console, directement dans le dossier du projet

Dans la vue complète, **Aperçu → Console** ouvre un vrai terminal PowerShell.
Lancez vos commandes, Git, vos scripts ou un outil en ligne de commande déjà
installé, tout en gardant les fichiers à portée de vue.

Par exemple : ouvrez le dossier du code, lancez **Codex CLI** dans la console,
puis travaillez dans ce répertoire sans ouvrir une autre fenêtre de terminal.

[![Codex CLI réellement lancé dans le dossier Site web](images/codex-1920.png)](images/codex-1920.png)

*1920 × 1080 · Écran d’accueil réel de Codex CLI dans un dépôt de démonstration.
Aucune demande au modèle n’a été envoyée pour cette capture.*

- **Suivre le dossier** adapte PowerShell à la navigation lorsque l’invite est
  disponible. Une commande ou une saisie en cours diffère ce changement.
- **Désactivez le suivi** pour garder votre terminal dans un projet précis.
- Masquer le volet conserve la session ; fermer la page l’arrête.
- Choisissez une palette et une police : Ubuntu, Dracula, Nord, Solarized,
  LCD rétro, apparence de l’interface ou couleurs personnalisées.

Codex est un **outil externe**, à installer et à configurer séparément selon
[sa documentation](https://developers.openai.com/codex/cli/).
Son compte, sa connexion et ses éventuels coûts dépendent de sa configuration ;
NextExplorer ne fournit ni abonnement Codex ni modèle d’IA intégré.
Un agent déjà lancé reste dans son répertoire ; la navigation ne le déplace pas.
Les commandes s’exécutent avec vos droits Windows et restent hors de
l’annulation des opérations de l’explorateur.

## Retrouver tout le contexte d’un projet

Un **espace hybride** enregistre les dossiers ouverts, leur disposition, la
collecte, les liens du projet, des pages et groupes d’onglets du navigateur,
ainsi qu’une petite liste de tâches.

Reprenez un projet avec ses ressources locales et ses références web, plutôt
que de reconstruire ce contexte à chaque session. La réouverture des pages
reste un choix explicite. Les espaces s’exportent sans copier les fichiers.

Vous pouvez également garder une page, un lien, une sélection ou une image
dans votre parcours de collecte et relier les références web à vos fichiers.
La capture PDF d’une page dispose de sa propre permission optionnelle.

## Ranger, retrouver et préparer vos fichiers

| Besoin | Ce que propose NextExplorer |
| --- | --- |
| Repérer un dossier | Favoris, accès rapides, couleurs et symboles personnalisés. |
| Classer sans déplacer | Tags colorés multiples, renommables, accessibles entre dossiers. |
| Retrouver un contenu | Recherche textuelle locale dans un dossier choisi ; fichiers, liens et espaces réunis dans la recherche. |
| Comprendre un ensemble | Regroupements par format, nom, date, taille, origine web ou relations enregistrées. |
| Repérer les répétitions | Copies identiques par empreinte et rapprochements d’images similaires, sans suppression automatique. |
| Préparer un dépôt web | Préparation d’images, copies de sortie, collecte et insertion dans les formulaires compatibles. |
| Transformer des médias | Conversion image/vidéo adaptée au type, préréglages, rotation, annotation et découpe selon les formats et moteurs disponibles. |
| Travailler sur des PDF | Aperçu, annotation, rotation et assemblage pour les documents compatibles. |
| Gérer des archives | Création ZIP/7z et extraction ZIP/7z/RAR selon le moteur installé. |
| Ranger les téléchargements | Règles par critères et destination ; automatisation uniquement pour les règles activées explicitement. |
| Suivre les opérations | Activité, progression, historique, pause et annulation selon l’opération ; tâches autorisées poursuivies par le compagnon. |
| Garder ses habitudes | Raccourcis, palette de commandes, préférences de vues et export/import des réglages pris en charge. |

**[Consulter le guide détaillé des fonctionnalités et de leurs limites](FONCTIONNALITES.md).**
La recherche est lexicale : elle n’utilise pas de modèle sémantique.
Certains aperçus et traitements nécessitent des moteurs complémentaires,
absents du téléchargement initial.

## Voir ce qui prend de la place

Les disques affichent leur espace disponible. L’analyse d’un dossier présente
les fichiers et sous-dossiers dans une carte visuelle, avec tailles et détails
au survol. Le résultat reste dans le volet d’aperçu pendant la navigation.

[![Carte d’occupation du dossier dans le volet redimensionné](images/espace-disque-1920.png)](images/espace-disque-1920.png)

*1920 × 1080 · Analyse réelle du petit projet fictif ; aucun fichier personnel scanné.*

## La suite du projet

La version actuelle pose les bases. Les évolutions suivantes sont prévues ou
à l’étude ; **elles ne sont pas incluses dans la préversion téléchargée**.

| Axe | Ce que nous voulons apporter | Prochaine validation |
| --- | --- | --- |
| **IA locale facultative** | Suggérer un classement d’après le contenu des documents et des images, puis retrouver des fichiers par leur sens. À terme, exploiter les consignes d’une page pour préparer les fichiers à y déposer. | Comparer de petits modèles, mesurer leur utilité et leurs besoins matériels. Moteur et modèle encore à choisir ; téléchargement explicite et dossiers autorisés par l’utilisateur. |
| **Refonte progressive du design et de l’ergonomie** | Une interface plus claire et plus légère : mieux hiérarchiser les actions, harmoniser les outils et affiner le panneau latéral comme la vue complète, dans la continuité de Material 3. | Tester les parcours, la lisibilité, l’accessibilité et les différentes largeurs de fenêtre. |
| **Davantage de formats en aperçu** | Étendre la consultation locale des documents bureautiques, tableaux, images et formats spécialisés, à partir d’un inventaire de 100 formats courants. | Corriger les raccordements incomplets, commencer par les lecteurs réutilisables, puis qualifier chaque format avec de vrais fichiers et de gros volumes. |

Parmi les pistes d’aperçu : documents DOCX/ODT, tableaux XLSX/ODS, meilleure
présentation des CSV et, selon les moteurs retenus, aperçus HEIC, PSD ou RAW.
Il s’agit de **consulter le contenu**, pas de remplacer leurs logiciels d’édition.
L’inventaire de 100 formats guide les priorités ; ce n’est pas une annonce de
compatibilité universelle.

**La priorité reste de fiabiliser la base gratuite et son installation**, puis
de valider l’apport de l’IA. Les parcours classiques resteront utilisables sans
modèle. L’IA intégrée devra traiter les fichiers localement, sans repli cloud
implicite ; son périmètre et sa compatibilité seront annoncés après essais.
La console avec Codex montrée plus haut est un usage distinct, déjà possible.

Une future offre Pro pourra regrouper des capacités avancées si leur gain est
démontré. Aucun tarif ni calendrier de livraison n’est fixé ici ; les fonctions
gratuites de la version reçue restent utilisables selon sa licence.

## Essayer la préversion

**[Téléchargements et notes de version](https://github.com/Gremy44/NextExplorer-Downloads/releases)**

- Cible initiale : **Windows 11 x64 et Chrome**, interface française.
- Deux composants : l’extension Chrome et le compagnon Windows.
- Aucun compte NextExplorer, abonnement NextExplorer ou modèle d’IA requis.
- Extension à charger manuellement : elle n’est pas encore sur le Chrome Web Store.

Il s’agit d’une **préversion technique gratuite**, à essayer sur des fichiers de
démonstration. La recette complète de l’installateur sur Windows propre reste
à effectuer. L’installateur et le compagnon sont **non signés** ; Windows peut
afficher une alerte ou bloquer leur lancement. Les empreintes SHA256 sont fournies.
Suivez le [guide d’installation](INSTALLATION.md).

## Gratuit et local

Usage personnel et professionnel gratuit selon la [licence](LICENSE).
Le code applicatif reste privé ; ce dépôt public contient la documentation,
les téléchargements et les retours. Les archives automatiques « Source code »
de GitHub correspondent à ce dépôt documentaire.

Une future offre Pro pourra apporter des fonctions distinctes. Les fonctions
gratuites de la version reçue restent utilisables selon sa licence.

NextExplorer traite localement vos fichiers, index et réglages, sans compte
NextExplorer ni télémétrie. Les sites et outils externes que vous utilisez ont
leurs propres connexions et conditions. Voir la [confidentialité](CONFIDENTIALITE.md).

## Aide et retours

- [Installation, mise à jour et retrait](INSTALLATION.md).
- [Guide des fonctionnalités](FONCTIONNALITES.md).
- [Historique des versions](CHANGELOG.md).
- [Signaler un problème](https://github.com/Gremy44/NextExplorer-Downloads/issues/new/choose).
- [Composants tiers](THIRD_PARTY.md).

Éditeur : **Gremy44**. Ne joignez pas de document personnel, de commande
confidentielle ou de chemin nominatif dans un ticket public.
