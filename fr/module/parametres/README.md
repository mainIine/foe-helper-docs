# Gestion des Paramètres 

![Îcone](./.images/Icon_001.png)

Ce module permet de gérer les paramètres généraux de l'application



## <a name="Structure"></a>Structure

![Structure](./.images/Structure.png)

Le module est partagé en 4 onglets qui gérent différents aspects du module

* A propos - Information générale sur le module
* Envois - Paramètre pour enregister les données de la guilde
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
* Forum du site web [forum]https://discuss.foe-helper.com/)
* Discord [Chanel](https://discord.com/invite/z97KZq4)
* Github [Github](https://github.com/mainIine/foe-helfer-extension/issues)

## <a name="Envois"></a>Onglet Envois

![Gestion des données de guilde](./.images/envois.png)

Opt-in pour envoyer les données de la ville au [planificateur de ville](../././site_web/planificateur_cite/README.md) sur le [site web](https://foe-helper.com/citymap/overview)

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


### Filtre du marché

![Filtre du marché](./.images/fenetre_4.png)

Active / désactive l'ouverture du [filtre du marché](../marche/README.md) 

### Calculatrice GM

![Utilisation de la calculatrice GM interne](./.images/fenetre_5.png)

Si cette option est activée, vous pouvez utiliser la calculatrice GM interne aussi pour les GM des autres joueurs.

### Calculatrice pour le prix d'événement

![Calculatrice pour prix d'évènement](./.images/fenetre_6.png)

Active / désactive l'ouverture de la fenêtre pour le meilleur rendement lors des évènements pour le prix du jour

### Aide au combat

![Aide au combat](./.images/fenetre_7.png)

Lors des combats automatiques, une fenêtre vient vous avertir qu'il ne reste que des voyous après la 1ère vague



