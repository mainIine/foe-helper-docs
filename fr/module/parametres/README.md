# Gestion des Paramètres 

![Îcone](./.images/Icon_001.png)

Ce module permet de gérer les paramètres généraux de l'application


## <a name="Structure"></a>Structure

![Structure](./.images/Structure.png)

Le module est partagé en 4 onglets qui gérent différents aspects du module

* A propos - Information générale sur le module
* Envois - Opt-in pour l'envoi des données pour le planificateur de ville
* Fenêtres - Permet d'activer ou désactiver certaines fenêtres
* Inteface - Gère l'aspect du module


## <a name="propos"></a>Onglet A Propos

### A Propos 

![A Propos](./.images/Structure.png)

Divers informations sur l'assistant.

#### Traduction

vous pouvez participer à la traduction via le site [weblate](http://i18n.foe-helper.com/)

### Version

![Version](./.images/propos_1.png)

vous y trouverez des informations imporantes sur :

#### Version du module
#### Votre ID de joueur FoE
#### Votre ID de guilde
#### Votre ID du monde sur lequel vous êtes avec ce module

### Aide

![Aide](./.images/propos_2.png)

Vous affiche les différentes aides disponible pour l'emploi de ce module

* Site web [Foe-Helper.com](https://foe-helper.com/)
* Forum du site web [forum](https://discuss.foe-helper.com/)
* Discord [Chanel](https://discord.com/invite/z97KZq4)
* Github [Github](https://github.com/mainIine/foe-helfer-extension/issues)

## <a name="Envois"></a>Onglet Envois

![Gestion des données de guilde](./.images/envois.png)

Opt-in pour l'envoi des données pour le [planificateur de ville](../.././site_web/planificateur_cite/README.md) sur le [site web](https://foe-helper.com/citymap/overview)

## <a name="fenetre"></a>Onglet Fenêtres

Dans cet onglet, vous allez pouvoir gérer le comportement de certaines fenêtres

### Négociations

![Assistant négociations](./.images/fenetre_1.png)

Active / désactive l'ouverture de l'[assistant négociation](../negociation/README.md) lors d'une négociation. Ne fonctionne pas en Champ de bataille. <br>L'aide n'est pas admise par InnoGames sur le Champ de bataille.

### Investissement PF

![Investissement PF](./.images/fenetre_2.png)

Active / désactive l'ouverture du résumé des investissments PF lors de la visite de l'hôtel de ville -> Grands Monuments


### Export de la trésorie de guilde

![Export de la trésorie de guilde](./.images/fenetre_3.png)

Active / désactive l'assistant permettant d'exporter les modifications de la trésorie de guilde

Quand cet assistant est actif, une fenêtre s'ouvre vous permettant d'exporter le journal des contributions de ressources.

![Journal des contributions](./.images/tresorie_guilde.png)<br>
via la page principale de votre guilde.

#### Fonctionnement de l'assistant Export

![Assistant Export](./.images/Export.png)

l'assistant a un menu Configuration qui est une redondance de la fonction activation / désactivation de ce menu.
![Configuration Export Trésorie](./.images/param_export_treso.png)

vous devez parcourir toutes les pages du journal pour lire les informations. Sauter à la dernière, ne suffit pas.<br>
![Lire le journal](./.images/lire_journal.png)

{% hint style="danger" %}
Attention à ne pas revenir en arrière dans la lecture des pages, sinon les informations seront à double dans le résultat final.
{% endhint %}

Si vous vous trompez, vous pouvez effacer les données enregistrées au moyen du bouton "Réinitialiser" et recommencer à zéro la lecture.
L'export en CSV se fait via le bouton "Export".


### <a name="marche"></a>Filtre du marché

![Filtre du marché](./.images/fenetre_4.png)

Active / désactive l'ouverture du [filtre du marché](../marche/README.md) 

### Calculatrice GM

![Utilisation de la calculatrice GM interne](./.images/fenetre_5.png)

Si cette option est activée, vous pouvez utiliser la [calculatrice GM interne](../calculatrice_gm_interne/README.md) aussi pour les GM des autres joueurs.

### Calculatrice pour le prix d'événement

![Calculatrice pour prix d'évènement](./.images/fenetre_6.png)

Active / désactive l'ouverture de la fenêtre pour le meilleur rendement lors des évènements pour le prix du jour

### Aide au combat

![Aide au combat](./.images/fenetre_7.png)

Lors des combats automatiques, une fenêtre vient vous avertir qu'il ne reste que des voyous après la 1ère vague

### <a name="galaxie"></a>Galaxie bleue

![Assistant Galaxie Bleue](./.images/fenetre_8.png)

Active / désactive l'ouverture de l'[aide Galaxie bleue](../galaxie-bleue/README.md) lors de la récolte de la galaxie bleue

### Activité PO / MO

![Assistant PO / MO](./.images/fenetre_9.png)

Active / désactive l'enregistrement des [événements PO / MO](../motivation/README.md).

{% hint style="info" %}
Si la coche n'est pas mise, alors l'îcone de l'assistant PO / MO ](./.images/icone_po_mo.png) dans le menu disparaît même si l'[îcone est active](#icone_active) dans le menu de l'assistant
{% endhint %}

### <a name="inf_tech"></a>Info Technique

![Info Technique](./.images/fenetre_10.png)

Active / désactive l'affichage des [Infos techniques](../info_technique/README.md) au chargement du jeu

### Fermer toutes les fenêtres

![Dialogue Fermer toutes les fenêtres](./.images/fenetre_11.png)

Quand cette option est choisie, une fenêtre<br>
![Fenêtre Affiche / Ferme tout](./.images/ferme_tout_1.png)
s'affiche sur votre écran

#### Fonctionnement du dialogue Fermer toutes les fenêtres

![Fenêtre complète](./.images/ferme_tout_2.png)

En mettant la souris sur la fenêtre, s'affiche la partie basse de l'image avec une option de configuration.

![Configuration](./.images/param_ferme_tout.png)

Description de la configuration :

	* Bouton Fermer tout (Croix X sur fond rouge) -> ferme toutes les fenêtres
	* Bouton Cacher tout (Oeil sur fond vert) -> cache la barre de menu 
	* Changer la taille des boutons
	* Changer l'alignement des boutons (horizontal ou vertical)
	* Exclure de la fermeture (permet de garder ces fenêtres ouvertes malgrès Fermet tout)
	* Fermeture automatique en cas de bataille

La fenêtre peut être déplacée en cliquant/tenant sur zone marquée "titre"

### Bloqueur de négociation

![Bloqueur de négociation](./.images/fenetre_12.png)

Active / désactive le bloqueur de négociation sur la carte de campagne<br>
![bloquer de négociation](./.images/bloquer_nego.png)

### Info de l'éclaireur

![Info de l'éclaireur](./.images/fenetre_13.png)

Affiche automatiquement la fenêtre d'[info de l'éclaireur](../eclaireur/README.md)<br> 

### Badge des 2000 quêtes

![Badge des 2000 quêtes](./.images/fenetre_14.png)

Active / désactive l'affichage du badge qui affiche le nombre de quêtes réccurentes effectuées<br>
![Badge des 2000 quêtes](./.images/badge.png)

### Lien des joueurs

![Lien des joueurs](./.images/fenetre_15.png)

Permet d'afficher un lien ![](./.images/lien.png) vers le site web [foe.scoredb.io](https://foe.scoredb.io)/monde/guilde/nom du joueur a chaque fois qu'un nom de joueur est affiché dans tous les modules.

### Cacher l'assistant pendant les batailles

![Cacher l'assistant](./.images/fenetre_16.png)

Active / désactive l'affichage pendant les batailles. Ne fonctionne que si l'assistant est sous [forme de boite](#boite)

### Assistant Aztèque

![Assistant Aztèque](./.images/fenetre_17.png)

Active / désactive l'affichage de l'assistant lors du début d'un [mini-jeu Aztèque](../azteque/README.md)

## Interface

Cet onglet permet de gérer l'aspect visuel du module


### Langue

![Gestion de la langue](./.images/interface_1.png)

Une fois votre langue d'interface choisie, le jeu est rechargé automatiquement

### Position du menu

![Position du menu](./.images/interface_2.png)

permet d'afficher le menu FOE-Assistant à différents endroits

* Bas de l'écran
* Droite de l'écran
* <a name ="boite"></a>En fenêtre


![bas](./.images/interface_2_1.png)
![droite](./.images/interface_2_2.png)
![Fenetré](./.images/interface_2_3.png)

Une fois votre position de menu choisie, le jeu est rechargé automatiquement

{% hint style="warning" %}
En fonction de votre résolution / taille d'écran (fenêtre de jeu), le menu se mettra en mode Fenêtre automatiquement
{% endhint %}
	
### Contenu du menu

Permet de gérer quelles îcones sont affichés dans la barre de menu

![Menu](./.images/interface_3_1.png)

Pour désactiver l'affichage, il suffit de faire un clic sur l'icone voulue (entourée d'un liseré vert). Elle s'enlève automatiquement et directement du menu.

![Icone désactivée](./.images/interface_3.png)<br>
Les îcones désactivées sont affichées avec un bord rouge dans l'interface de gestion du menu.
Les îcones avec un <a name="icone_active"></a>liséré vert sont actives.

### Largeur / longeur du Menu

![Nombre d'îcone affichée dans le menu](./.images/interface_4.png)

Par exemple avec le chiffre 3, comme dans l'image ci-dessus, le menu s'affiche ainsi<br>
![Menu 3](./.images/interface_4_1.png)


{% hint style="warning" %}
En fonction de votre résolution / taille d'écran (fenêtre de jeu) ou **zoom**, le menu peut afficher un autre nombre d'îcone.
{% endhint %}

### Position des fenêtres

![Effacer la position des fenêtres](./.images/interface_5.png)

L'assistant enregistre automatiquement la position de vos fenêtres et les rouvres au même endroit. Si votre résolution, taille d'écran change entre-temps, il se peut que la fenêtre s'ouvre en dehors de la zone visible.

Le bouton "Supprimer" va réafficher par défaut toutes les fenêtres sur le centre de l'écran.

### Importer / exporter les données

![Import / export](./.images/interface_6.png)

Cet onglet vous permet d'exporter vos paramètres de jeu et toutes les données de votre PC sur un autre PC ou dans un autre navigateur.

#### Utilisation

le bouton "ouvrir l'outil d'import / export" ouvre cette fenêtre

![outil d'import / export](./.images/interface_6_1.png)

L'onglet Exporter permet d'exporter les données sous la forme d'un fichier Zip qui se trouvera pas défaut sur votre PC dans "Téléchargement"
![fichier zip](./.images/interface_6_2.png)

L'onglet Importer vous permet d'importer un fichier Zip afin de charger sur votre PC. 

![Importer](./.images/interface_6_3.png)

### Activer les sons

![Gestion des sons](./.images/interface_7.png)

Active les sons dans tous les modules. A noter, que sur certains modules, le son pourra être désactivé via le menu du module ![](./.images/haut-parleur.png)

### Notifications

![Notifications](./.images/interface_8.png)

Active / désactive toutes les notifications de l'assistant

### Emplacement des notifications

![Emplacement des notifications](./.images/interface_9.png)

Vous pouvez choisir à quel endroit de la fenêtre apparaissent les notifications du jeu
![Lieu possible](./.images/place_notif.png)

### Notifications multiples

![Nombre de notifications](./.images/interface_10.png)

avec 3 :

![](./.images/interface_10_1.png)

### Charger la version Beta

![version Beta](./.images/interface_11.png)

Vous permet de charger la version Beta de l'assistant en cliquant sur le lien jaune surligné. Le chargement démarre automatiquement.

{% hint style="warning" %}
La version Beta ne doit pas être employée sur le même navigateur que la version Beta
{% endhint %}

