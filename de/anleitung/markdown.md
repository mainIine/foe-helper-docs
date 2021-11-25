# Markdown in den Dokumenten

Die gesamte Dokumentation ist in Markdown-Code geschrieben. Hier sind einige Beispiele:

### Überschriften

| Markdown | HTML | Gerendert |
| ----------- | ----------- | ----------- |
| \# Überschrift 1 | &lt;h1>Überschrift 1&lt;/h1> | <h1>Überschrift 1</h1> |
| \## Überschrift 2 | &lt;h2>Überschrift 2&lt;/h2> | <h2>Überschrift 2</h2> |
| \### Überschrift 3 | &lt;h3>Überschrift 3&lt;/h3> | <h3>Überschrift 3</h3> |
| \#### Überschrift 4 | &lt;h4>Überschrift 4&lt;/h4> | <h4>Überschrift 4</h4> |
| \##### Überschrift 5 | &lt;h5>Überschrift 5&lt;/h5> | <h5>Überschrift 5</h5> |

---

### Images

Es können auch Screenshots eingereicht werden. Aus Gründen der Einheitlichkeit können wir Grafiken durch unsere eigenen ersetzen.

Die Bilder werden immer auf der gleichen Ordnerebene in einem ```.images```-Verzeichnis gespeichert. Sie werden dann auf diese Weise verlinkt:

```markdown
![Test image](./.images/app48.png)
```
Gerendert

![Test image](./.images/app48.png)

---

### Links

Links werden immer automatisch umgewandelt und erfordern keinen zusätzlichen Code.

---

### Hints

Hinweise können mit der folgenden Syntax erstellt werden:

```markdown
{% hint style="info" %}
Hello world
{% endhint %}
```

Diese Werte sind möglich: `info`, `success`, `danger` & `warning`

Beispiele:

{% hint style="info" %}
Info
{% endhint %}

{% hint style="success" %}
Erfolg
{% endhint %}

{% hint style="danger" %}
Error/Fehler
{% endhint %}

{% hint style="warning" %}
Warnung
{% endhint %}

---

