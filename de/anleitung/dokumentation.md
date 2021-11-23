---
description: Struktur der Doku und sein Code
---

# Dokumentation

## Erzeugen einer Datei

Erstelle eine neue leere ``README.md`` Datei in einem Ordner, der nach einem Modul des Helfers benannt ist. Als Beispiel kannst Du Dir das Verzeichnis ``/de/erweiterung/kostenrechner`` anschauen.
Dort ist ebenfalls schon ein versteckter Bilderordner. Dort hinein kommen dann Screenshots vom Kostenrechner.

{% hint style="info" %}
Eine README.md wird nicht in der URL auftauchen, Sie wird als eine index.* behandelt. Ist es notwendig ein Modul in mehrere Seiten zu unterteilen, dann benutze eindeutige kleingeschrieben Namen ohne Sonderzeichen oder Leerstellen
{% endhint %}

Die ``/SUMMARY.md`` im Wurzelverzeichnis muss dann um diese Datei/Pfad ergänzt werden.

Hier ein Beispiel für die englischen Hinweise zur Doku-Erstellung.
```markdown
* [Helping out](en/guide/README.md)
  * [Github](en/guide/github.md)
  * [Markdown](en/guide/markdown.md)
  * [Write a docu](en/guide/documentation.md)
```

Gitbook rendert daraus die korrekte Struktur und generiert automatisch die Links.

## Struktur

Der Untertitel der Seite selbst erscheint immer am Anfang. Hier ist der Titel dieser Seite

```markdown
---
description: Struktur der Doku und sein Code
---
```

Erst dann kommt die erste Überschrift:
```markdown
# Documentation
```

Von hier an kannst Du einfach schreiben. Wie genau der Code aussehen kann, siehst Du unter 
