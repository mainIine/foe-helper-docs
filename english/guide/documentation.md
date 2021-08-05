---
description: Structure of a docu and its code
---

# Documentation

## Create the file

Create a new empty ``xxxx.md`` file. The name of this file should not contain any umlauts, special characters or spaces. It is also important to keep to the default folder structure.

In the ``/SUMMARY.md``, this page is then linked as in the default structure.

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
