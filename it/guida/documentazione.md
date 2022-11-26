---
descrizione: Struttura di un documento e del suo codice
---

# Documentazione

## Crea il file

Crea un nuovo file ``README.md`` vuoto in una cartella che prende il nome da un modulo dell'helper. Ad esempio, puoi guardare la directory ``/de/erweiterung/kostenrechner``.
C'è anche una cartella di immagini nascosta. Gli screenshot del calcolatore dei costi verranno inseriti lì.

{% hint style="info" %}
Un ``README.md`` non apparirà nell'URL, sarà trattato come un indice.*. Se è necessario dividere un modulo in più pagine, utilizzare nomi univoci minuscoli senza caratteri speciali o spazi.
{% endhint %}

Questo file/percorso deve quindi essere aggiunto a ``/SUMMARY.md`` nella directory principale.

```markdown
* [Aiuto](italiano/guida/README.md)
  * [Github](italiano/guida/github.md)
  * [Markdown](italiano/guida/markdown.md)
  * [Scrittura della documentazione](italiano/guida/documentazione.md)
```

Gitbook esegue quindi il rendering della struttura corretta da questo e genera automaticamente i collegamenti.

## Struttura

Il sottotitolo della pagina stessa appare sempre in alto. Ecco il titolo di questa pagina

```markdown
---
descrizione: Struttura di un documento e del suo codice
---
```

Solo allora arriva il primo titolo:
```markdown
# Documentazione
```

Da qui in poi, puoi semplicemente scrivere.
