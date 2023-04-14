# Beth's Anti-Transphobia Library

This is the repository my anti-transphobia library.

If you're just looking to go straight to the website, [click here](https://bethylamine.github.io/).

The purpose of this website is to catalog, archive, and in any way aid in making useful sources available and accessible to everyone who is responding to, debunking or otherwise engaging with transphobia online.

## API

There is a REST API you can use to search the library and return results, which @WhatIsAWomanBot uses for its `search` keyword.

For example:

```
>>> import json, requests
>>> API_KEY = "<your API key>"
>>> query = "rowling"
>>> response = requests.get(f"https://api.beth.lgbt/pages/?q={query}", headers={"x-api-key": API_KEY})
>>> results = json.loads(response.content.decode('utf-8'))
>>> for result in results:
...     print(f"{result['parent']}: {result['title']} -- {result['url']}")
...
Figureheads: J. K. Rowling -- https://beth.lgbt/library/figureheads/rowling
Moral Panic: Recycled Homophobia -- https://beth.lgbt/library/moral-panic/homophobia
```

To get an API key, please [DM me on Twitter](https://twitter.com/bethylamine).

---

This website uses [Jekyll] and the [Just the Docs] theme, built and published on [GitHub Pages].

[Jekyll]: https://jekyllrb.com
[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[GitHub Pages]: https://docs.github.com/en/pages
