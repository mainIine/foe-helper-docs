---
description: Structure of a docu and its code
---

# Documentation

## Create the file

Create a new empty ``README.md`` file in a folder named after a module of the helper. As an example, you can look at the directory ``/de/erweiterung/kostenrechner``.
There is also a hidden picture folder. Screenshots of the cost calculator will be placed there.

{% hint style="info" %}
A ``README.md`` will not appear in the URL, it will be treated as an index.*. If it is necessary to divide a module into several pages, use unique lower case names without special characters or spaces.
{% endhint %}

This file/path must then be added to the ``/SUMMARY.md`` in the root directory.

```markdown
* [Helping out](english/guide/README.md)
  * [Github](english/guide/github.md)
  * [Markdown](english/guide/markdown.md)
  * [Write a docu](english/guide/documentation.md)
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
