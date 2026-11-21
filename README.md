# markdown

Renders CommonMark to HTML, with the GitHub extensions for tables, strikethrough, task lists, and autolinks.

```lus nocheck
local markdown = require("https://atmosp.here/2.0/markdown.lus")

print(markdown.render("# Lus\n\nA *small* language. See <https://lus.dev>.\n"))
--> <h1>Lus</h1>
--> <p>A <em>small</em> language. See <a href="https://lus.dev">https://lus.dev</a>.</p>
```

The package requires Lus 2.0. It declares no permissions. It calls no `pledge` of its own, so the program that loads it keeps control of its permissions.

The reference is in the doc comments of `markdown.lus`. Run `lus doc markdown.lus` to print it.
