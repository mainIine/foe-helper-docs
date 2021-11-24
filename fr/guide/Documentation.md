---
description: Structure of a docu and its code
---

# Documentation

## Créer le fichier

Créer un nouveau fichier ``README.md`` vide dans un répertoire au nom du module du Helper. Comme exemple, vous pouvze regarder dans le répertoire ``/de/erweiterung/kostenrechner``.
Il y a aussi un répertoire caché pour les images. Les copies d'écran du calculateur de coût seront enregistrées là.

{% hint style="info" %}
Un ``README.md`` n'apparait pas dans l'URL, il est traité comme un index.*. If it is necessary to divide a module into several pages, use unique lower case names without special characters or spaces.
{% endhint %}

Ce fichier/chemin doit être ajouté dans ``/SUMMARY.md`` dans le répertoire Root.

```markdown
* [Aide](francais/guide/README.md)
  * [Github](francais/guide/github.md)
  * [Markdown](francais/guide/markdown.md)
  * [Write a docu](francais/guide/documentation.md)
```

Gitbook then renders the correct structure from this and automatically generates the links.

## Structure

The subtitle of the page itself always appears at the top. Here is the title of this page

```markdown
---
description: Structure of a docu and its code
---
```

Only then comes the first headline:
```markdown
# Documentation
```

From here on, you can simply write.
