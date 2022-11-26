# Markdown nei documenti

La documentazione completa è scritta in codice markdown. Ecco alcuni esempi:

### Intestazioni

| Markdown | HTML | Output renderizzato |
| ----------- | ----------- | ----------- |
| \# Intestazione livello 1 | &lt;h1>Intestazione livello 1&lt;/h1> | <h1>Intestazione livello 1</h1> |
| \## Intestazione livello 2 | &lt;h2>Intestazione livello 2&lt;/h2> | <h2>Intestazione livello 2</h2> |
| \#### Intestazione livello 3 | &lt;h3>Intestazione livello 3&lt;/h3> | <h3>Intestazione livello 3</h3> |
| \#### Intestazione livello 4 | &lt;h4>Intestazione livello 4&lt;/h4> | <h4>Intestazione livello 4</h4> |
| \###### Intestazione livello 5 | &lt;h5>Intestazione livello 5&lt;/h5> | <h5>Intestazione livello 5</h5> |

---

### Immagini

È anche possibile inviare screenshot. Per uniformità, possiamo sostituire la grafica con la nostra.

Le immagini sono sempre memorizzate nello stesso livello di cartella in una directory ```.images```. Sono poi collegati in questo modo:

```markdown
![Test image](https://github.com/mainIine/foe-helper-docs/raw/master/it/guida/.images/app48.png)
```
Risultato:

![Test image](https://github.com/mainIine/foe-helper-docs/raw/master/it/guida/.images/app48.png)

---

### Collegamenti

I collegamenti vengono sempre convertiti automaticamente e non richiedono alcun codice aggiuntivo.

---

### Suggerimenti

I suggerimenti possono essere creati con la seguente sintassi:

```markdown
{% hint style="info" %}
Hello world
{% endhint %}
```

Sono possibili questi valori: `info`, `success`, `danger` e `warning`

Esempi:

{% hint style="info" %}
Suggerimento informativo
{% endhint %}

{% hint style="success" %}
Suggerimento di successo
{% endhint %}

{% hint style="danger" %}
Suggerimento di pericolo
{% endhint %}

{% hint style="warning" %}
Suggerimento di avvertimento
{% endhint %}

---

