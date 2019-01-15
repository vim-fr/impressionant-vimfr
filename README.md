# impressionant-vimfr
Une liste de modules et outils utilisés par la communauté #vim-fr @ freenode

## Modules vim
 * [ctrlpvim/ctrlp.vim](https://github.com/ctrlpvim/ctrlp.vim) Permet d'éditer n'importe quel fichier se trouvant dans n'importe quel répertoire rapidement
 * [tpope/vim-fugitive](https://github.com/tpope/vim-fugitive) Permet de gérer un repository `git` directement depuis vim.
 * [tpope/vim-surround](https://github.com/tpope/vim-surround) Module ajoutant des fonctions d'édition de bloque de texte _encadrant_.
 Par exemple, faire `cs"'` pour modifier `"Bonjour monde"` en `'Bonjour monde'`.
 * [tpope/vim-commentary](https://github.com/tpope/vim-commentary) Module permettant de mettre ou d'enlever des commentaires.
 Le module gère les différents format de commentaire selon le langage utilisé.
 Pour commenter une ligne, rien de plus simple : `gcc`
 On peut également commenter avec un mouvement vim, par exemple pour commenter un paragraphe : `gcip`
 * [vim-airline/vim-airline](https://github.com/vim-airline/vim-airline) Bar de status simple & légère
 * [myusuf3/numbers.vim](https://github.com/myusuf3/numbers.vim) Permet de changer la numération de ligne selon le mode de vim.

## Ligne de commande

### Liste d'outils pour les fichiers:

* [bat](https://github.com/sharkdp/bat) commande pour remplacer `cat` qui permet de visionner rapidement le contenu d'un fichier avec la coloration syntaxique.
* [exa](https://the.exa.website/) une alternative moderne à la commande `ls` avec une large variété d'options.
* [pastebinit](https://github.com/skorokithakis/pastebinit) est un outil permettant d'envoyer le contenu d'un fichier texte sur différents services de pastebin.

### Outils réseau
* [youtube-dl](https://rg3.github.io/youtube-dl/) permet de télécharger des vidéos en ligne de commande. Il supporte de nombreux hébergeurs. Une liste exhaustive des hébergeurs est disponible [ici](https://rg3.github.io/youtube-dl/supportedsites.html).

### Outils système
* [iperf3](https://github.com/esnet/iperf) est très utile pour diagnostiquer votre débit entre 2 points précis. Une liste de serveurs iperf publique est disponible [ici](https://iperf.fr/iperf-servers.php).
* [htop](https://hisham.hm/htop/) est un moniteur de processus interactif. Celui-ci se veut être l'évolution de `top`.

## Config des membres de #vim-fr

* [ChOcO-Bn](https://github.com/chocobn69/dotfiles) Archlinux, i3-wm, zsh, kitty, ...
