<p align="center"><img src="laz2omap_logo.png" width="160" alt="Laz2omap logo"></p>

# Laz2omap

**Draft orienteering maps from lidar, for OpenOrienteering Mapper.**
Laz2omap finds the lidar of your area, downloads it, and makes a draft map (ISOM 2017-2 / ISSprOM 2019) that you
then check in the field and finish in OpenOrienteering Mapper. **[🗺 See where the lidar is](https://laz2omap.github.io/laz2omap/)**

<p align="center"><a href="https://github.com/laz2omap/laz2omap/releases"><img src="https://img.shields.io/github/downloads/laz2omap/laz2omap/total?label=downloads&amp;color=e8417d" alt="Total downloads of every Laz2omap release"></a></p>

**Latest version: [Laz2omap 5.53.0](https://github.com/laz2omap/laz2omap/releases/latest)** (2026-11-25): [what's new](https://github.com/laz2omap/laz2omap/releases/latest) / **Dernière version : [Laz2omap 5.53.0](https://github.com/laz2omap/laz2omap/releases/latest)** (2026-11-25) : [nouveautés](https://github.com/laz2omap/laz2omap/releases/latest)

<p align="center"><img src="cycle_en.png" width="600" alt="Laz2omap produces and adjusts the draft map, you check it in the field, finish it in OpenOrienteering Mapper, and bring bulk adjustments back to Laz2omap"></p>

## Download (Windows)

**[⬇ Download the latest Laz2omap-Setup.exe](https://github.com/laz2omap/laz2omap/releases/latest)**

1. On the release page, under **Assets**, click **Laz2omap-Setup-X.Y.Z.exe**.
2. Double-click it. If Windows shows *Windows protected your PC*, click **More info → Run anyway**.
3. Click **Next**, then **Install**. Laz2omap opens; next time, start it from the desktop or the Start menu.

No administrator password, nothing else to install. Your maps and settings go in **Documents\Laz2omap**.
To update, run the newer Setup: your lidar, maps and settings stay.

**Windows only for now.** Want it on Linux or macOS? [Ask for it here](https://github.com/laz2omap/laz2omap/issues/new?template=1-idea.yml&title=Linux%20%2F%20macOS%20version&labels=enhancement,platform): requests decide what comes next.

The guides (English cheat sheet and French *pense-bête*) are on the same release page, and in the Start menu once
Laz2omap is installed.

## Téléchargement (Windows)

<p align="center"><img src="cycle_fr.png" width="600" alt="Laz2omap produit et ajuste l'ébauche de carte, vous la vérifiez sur le terrain, la finissez dans OpenOrienteering Mapper, et revenez à Laz2omap pour les ajustements d'ensemble"></p>

**[⬇ Télécharger le dernier Laz2omap-Setup.exe](https://github.com/laz2omap/laz2omap/releases/latest)**

1. Sur la page de la version, sous **Assets**, cliquez **Laz2omap-Setup-X.Y.Z.exe**.
2. Double-cliquez-le. Si Windows affiche *Windows a protégé votre ordinateur*, cliquez **Informations
   complémentaires → Exécuter quand même**.
3. Cliquez **Suivant**, puis **Installer**. Laz2omap s'ouvre ; ensuite, lancez-le depuis le Bureau ou le menu Démarrer.

Pas de mot de passe administrateur, rien d'autre à installer. Vos cartes et réglages vont dans **Documents\Laz2omap**.
Pour mettre à jour, lancez le Setup plus récent : votre lidar, vos cartes et vos réglages restent.

**Windows seulement pour l'instant.** Vous le voulez sur Linux ou macOS ? [Demandez-le ici](https://github.com/laz2omap/laz2omap/issues/new?template=1-idea.yml&title=Linux%20%2F%20macOS%20version&labels=enhancement,platform) : les demandes décident de la suite.

## Ideas or problems? / Des idées ou un problème ?

**[💡 Suggest an idea / Proposer une idée](https://github.com/laz2omap/laz2omap/issues/new?template=1-idea.yml)**
&nbsp;·&nbsp;
**[🐞 Report a problem / Signaler un problème](https://github.com/laz2omap/laz2omap/issues/new?template=2-problem.yml)**
&nbsp;·&nbsp;
**[🌍 Request a country / Demander un pays](https://github.com/laz2omap/laz2omap/issues/new?template=3-country.yml)**

A short form opens (a free GitHub account is needed to send it). English or French. See what others asked in
[Issues](https://github.com/laz2omap/laz2omap/issues). / Un court formulaire s'ouvre (un compte GitHub gratuit est
nécessaire pour l'envoyer). En anglais ou en français.

## Where the lidar is / Où est le lidar

**[🗺 Open the interactive coverage map / Ouvrir la carte interactive](https://laz2omap.github.io/laz2omap/)**: click a country to see where its lidar
comes from and where to download it. / cliquez un pays pour voir d'où vient son lidar et où le télécharger.

<p align="center"><a href="https://laz2omap.github.io/laz2omap/"><img src="coverage_map.png" width="760" alt="Lidar coverage map: pink = Laz2omap downloads it, blue = available from the provider"></a></p>

**Pink:** Laz2omap downloads the lidar for you. **Blue:** the lidar is available from the provider; Laz2omap shows you
where to get it, then makes the map from your .laz tiles. / **Rose :** Laz2omap télécharge le lidar pour vous.
**Bleu :** le lidar est disponible chez le fournisseur ; Laz2omap vous montre où l'obtenir, puis fait la carte avec vos
tuiles .laz.

### [🌍 Request a country / Demander un pays](https://github.com/laz2omap/laz2omap/issues/new?template=3-country.yml)

Your country missing, or better lidar elsewhere? Ask for it: the most requested come first. Already asked?
[Add a 👍 to it](https://github.com/laz2omap/laz2omap/issues?q=is%3Aissue+label%3Acountry). / Votre pays manque, ou
un meilleur lidar existe ailleurs ? Demandez-le : les plus demandés passent en premier. Déjà demandé ?
[Ajoutez-y un 👍](https://github.com/laz2omap/laz2omap/issues?q=is%3Aissue+label%3Acountry).

## Licence

Laz2omap: PolyForm Noncommercial 1.0.0 (free for clubs, events and personal use; commercial use needs a separate
licence). Guides: CC BY-NC 4.0. © 2026 Jerome Grenier Desbiens.
