# Booknest

Booknest is a responsive, browser-based book discovery website. HTML, CSS, and JavaScript are maintained as separate files.

## Features

- Discover and search books from the Gutendex free ebook catalog.
- Filter by topic and language and sort catalog results.
- Save books to **My shelf** using browser local storage.
- Open each book's official Project Gutenberg page to see available reading and download options.
- Read locally selected PDF, EPUB, TXT, and HTML files in **My reader**. The selected file is processed in the browser and is not uploaded.
- Responsive layout for desktop and mobile screens.

## Files

- `index.html` — page structure
- `style.css` — layout, colors, and responsive styling
- `script.js` — catalog, shelf, navigation, and local reader behavior

## Run locally

Open a terminal in this project folder and run:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000. Book catalog search needs an internet connection.

## Publish with GitHub Pages

1. Open the repository's **Settings**.
2. Choose **Pages** in the sidebar.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select branch `main` and folder `/(root)`, then click **Save**.

After Pages finishes publishing, the site URL will appear in the Pages settings.

## Sources and copyright

Catalog API: https://gutendex.com/

Books link to their official Project Gutenberg landing pages: https://www.gutenberg.org/. Copyright status can vary by country; check the applicable terms before downloading or redistributing an individual book.
