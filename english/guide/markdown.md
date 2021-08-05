# Markdown in the docs

The complete documentation is written in markdown code. Here are some examples:

### Headings

| Markdown | HTML | Rendered Output |
| ----------- | ----------- | ----------- |
| \# Heading level 1 | &lt;h1>Heading level 1&lt;/h1> | <h1>Heading level 1</h1> |
| \## Heading level 2 | &lt;h2>Heading level 2&lt;/h2> | <h2>Heading level 2</h2> |
| \### Heading level 3 | &lt;h3>Heading level 3&lt;/h3> | <h3>Heading level 3</h3> |
| \#### Heading level 4 | &lt;h4>Heading level 4&lt;/h4> | <h4>Heading level 4</h4> |
| \##### Heading level 5 | &lt;h5>Heading level 5&lt;/h5> | <h5>Heading level 5</h5> |

### Bilder

Screenshots können ebenfalls eingereicht werden. Für die Vereinheitlichung kann es sein das wir Grafiken mit unseren eigenen ersetzten.

The images are always stored in the same folder level in a ```.images``` directory. They are then linked in this way:

```markdown
![Test image](https://github.com/mainIine/foe-helper-docs/raw/master/english/guide/.images/app48.png)
```
Gerendert
![Test image](https://github.com/mainIine/foe-helper-docs/raw/master/english/guide/.images/app48.png)

### Links

Links are always converted automatically and do not require any extra code.