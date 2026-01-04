---
description: Aide à choisir les bons articles dans les différentes boutiques du jeu, Permet de mettre des alarmes quand un article peut-etre acheté.
---

# Assistant Boutique

{% hint style="success" %}
Ce module peut-être activé dans [parametres](../parametres/README.md#pop-up)
{% endhint %}

![Icône](./.images/icone_001.png) 

Le module **Assistant Boutique** vous permet de retrouver facilement dans les différentes boutiques les articles qui vous intérerssent. 


## Structure

![Structure](./.images/structure.png)

La fenêtre est structurée comme suit :

- **Barre de titre** avec menu [Configuration](#configuration)
- **Zone de filtre** :
  - **Seulement les favoris** : affiche les articles [favoris](#favoris)
  - **Seulement débloqués** : affiche uniquement les articles débloqués (dans les évents)
  - **Monnaie** : Si plusieurs monnaies sont disponible dans une boutique, permet de [cacher](#Cacher-une-monnaie) les articles de la monnaie sélectionnée
- **Zone des articles** :
  - **Favoris** : Affiche si l'article est [favoris](#favoris)
  - **Alarme** : Affiche si une [alarme](#alarme) est active
  - **Offre** : Article de la boutique
  - **Cadenas** : Si l'article est bloqué car les conditions d'achat pas encore remplie
  - **Inventaire** : Le nombre d'objet dans votre propre Inventaire
  - **A l'unité** : Le prix à l'achat de l'article
  - **Manquant**  : Combien de fragments sont manquant pour compléter un objet et le coût total en monnaie
  - **Max** : Le nombre d'article maximum que vous pouvez acheter. Si des articles ont déjà été acheté, il sera noté 1/6 par exemple (pour 1 achat)


## Configuration

![Configuration](./.images/configuration.png)

L'interface de configuration est structurée comme suit :
- **Ouvrir la fenêtre automatiquement** : Si cette option est activée, ce module s'ouvrira automatiquement chaque fois que vous entrerez dans les boutiques du jeu.

## Utilisation

Afin d'avoir un oeil sur vos articles favoris, il est conseillé de mettre en favoris les articles, voir d'activer une alarme.

### Favoris

![](./.images/favori_off.png) - L'article n'est pas marqué comme favori. Un clic de souris sur l'étoile active le favori<br>
![](./.images/favori_on.png) - L'article est marqué comme favori. Un clic de souris sur l'étoile va désactiver le favori<br>

Avec le filtre **Favori**, seul ces derniers seront affichés<br>
![Filtre favori](./.images/filtre_favori.png)

### Alarme

![](./.images/alarme_off.png) - L'article n'a pas d'alarme. Un clic de souris sur la cloche va activer l'alarme<br>
![](./.images/alarme_on.png) - L'alarme est active pour l'article. Un clic de souris la désactive<br>

Quand une alarme est active, ce type de message apparait dès que les conditions sont remplies pour acquérir l'article<br>
![Message d'alerte](./.images/message_alerte.png)

Le message disparait après 1 minute environ


### Cacher une monnaie

La boutique **Championnat du Champ de bataille** a par exemple 2 monnaies. <br>
![Deux monnaies](./.images/cacher_001.png)


Vous pouvez filtrer l'une des monnaies en cliquant dessus : <br>
![Monnaie Or cachée](./.images/cacher_002.png)

Seul les articles de la monnaie Platine sont affichées.<br>

ou vice-versa <br>
![Monnaie Platinie cachée](./.images/cacher_003.png)

Si vous cliquez sur les deux monnaies, alors la liste sera vide. <br>
![Les deux monnaies cachées](./.images/cacher_004.png)

Un clic sur l'une ou l'autre, voir les deux monnaies va réafficher les articles.


## FAQ

**Q: Je ne vois pas mes packs de 50 diamants pour le championnat CbG**<br>
R: Si vous avez déjà acheté tous les packs disponible, alors l'article se trouvera tout en bas de la liste en grisé<br>
![Diamants non disponible](./.images/article_non_dispo.png)

