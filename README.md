# newtab

Generates a static HTML page to use as the browser's new-tab page, from a SQLite bookmarks database: every bookmark becomes a link, grouped and ordered by category, styled by a `homepage.css` beside the output.

```bash
./bookmarkhomepage      # reads ~/.GTD/Bookmarks/bookmarks.db, writes ~/.GTD/Bookmarks/myhomepage.html
```

The database needs a table `tbl1 (name, url, category)`. Point the browser's new-tab or home page at `myhomepage.html`.

Its successor, a native macOS launcher over the same kind of database, is [bookmarks-launcher](https://github.com/gregoryjayuk/bookmarks-launcher).
