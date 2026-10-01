# Karusensei Solarized Light

Thème clair pour Visual Studio Code : une interface **crème très pâle**, dans
l'esprit de Solarized Light, autour de la coloration syntaxique de Bluloco Light.

Deux variantes :

- **Karusensei Solarized Light**
- **Karusensei Solarized Light Italic** : commentaires, mots-clés et `this` / `self` en italique.

C'est le pendant clair de [Karusensei Graphite Dark](https://github.com/karusensei/karusensei-graphite-dark-vscode-theme) :
mêmes principes d'interface, transposés sur fond clair.

## Principes

- **Des crèmes, pas des gris.** Tous les gris de l'interface de Bluloco Light sont
  remplacés par des tons crème (teinte jaune autour de 45°), en conservant leur
  hiérarchie. L'échelle complète est dans [palette.md](palette.md).
- **L'éditeur au centre.** Le fond de l'éditeur (`#fdf9ee`) est aussi celui de la
  barre latérale, des panneaux et de l'onglet actif. La barre d'onglets est un peu
  plus soutenue (`#f4eedd`) : l'onglet sélectionné semble se prolonger dans
  l'éditeur.
- **Une seule couleur pour le cadre.** La barre d'activité et la barre d'état
  partagent `#efe8d3`, y compris au survol et sur l'élément actif. Seule l'icône
  change d'état, sans carré de fond. La ligne courante reprend ce même ton.
- **Des champs plus clairs que le fond.** Champs de saisie, listes déroulantes et
  notifications (`#fffcf4`) ressortent comme du papier posé sur la page.
- **Repères discrets.** Les règles verticales et les repères d'indentation
  (`#f0e9d6`) se devinent sans attirer l'œil. Le repère du bloc courant ressort un
  peu plus (`#e0d7bf`).
- **L'accent bleu de Bluloco Light** (`#0099e1`) pour ce qui est actif : liseré de
  l'onglet, élément actif de la barre d'activité, badges.

## Interface

| Rôle                                         | Hex       |
| -------------------------------------------- | --------- |
| Fond de l'éditeur, panneaux, onglet actif    | `#fdf9ee` |
| Barre d'onglets, onglets inactifs            | `#f4eedd` |
| Onglet survolé                               | `#f1ebd8` |
| Barre d'activité, barre d'état, ligne courante | `#efe8d3` |
| Champs de saisie, notifications              | `#fffcf4` |
| Règles, repères d'indentation                | `#f0e9d6` |
| Bordures                                     | `#e3dbc4` |
| Barre de titre                               | `#d8cfb5` |
| Texte principal                              | `#383a42` |
| Texte secondaire                             | `#a0a1a7` |
| Accent                                       | `#0099e1` |

## Syntaxe

La coloration syntaxique est celle de Bluloco Light 3.10.0, **sans aucune
modification**.

| Portée                     | Hex       |
| -------------------------- | --------- |
| Texte                      | `#383a42` |
| Commentaire                | `#a0a1a7` |
| Mot-clé                    | `#0098dd` |
| Fonction, méthode          | `#23974a` |
| Propriété                  | `#a05a48` |
| Chaîne                     | `#c5a332` |
| Nombre                     | `#ce33c0` |
| Constante                  | `#823ff1` |
| Balise                     | `#275fe4` |
| Attribut de balise         | `#df631c` |
| Classe, type, interface    | `#d52753` |
| Opérateur, ponctuation     | `#7a82da` |

## Installation

Le thème n'est pas publié sur le Marketplace. Pour l'installer depuis les sources :

```bash
npx @vscode/vsce package
code --install-extension karusensei-solarized-light-1.0.0.vsix
```

Choisir ensuite **Karusensei Solarized Light** avec `Preferences: Color Theme`.

Pour le modifier en direct, ouvrir ce dossier dans VS Code et lancer la configuration
**Extension** (`F5`) : la fenêtre de développement recharge le thème à chaque
enregistrement.

## Origine et licence

Karusensei Solarized Light est dérivé de [Bluloco Light](https://github.com/uloco/theme-bluloco-light)
d'uloco, dont il reprend la coloration syntaxique telle quelle. L'interface a été
reprise : passage aux tons crème, fond d'éditeur et hiérarchie des surfaces
redéfinis, onglets, barres et repères retravaillés. Les tons s'inspirent de
[Solarized](https://ethanschoonover.com/solarized/) d'Ethan Schoonover.

Comme le thème d'origine, il est distribué sous licence
[GNU LGPL v3](LICENSE.txt).
