# Not A Standard — Website

Human factors security and intelligence. [notastandard.org](https://notastandard.org)

## Structure

```
index.html          — Main site (single-page)
CNAME               — Custom domain configuration
resources/          — PDFs, slide decks, downloadable assets
```

## Updating content

Edit `index.html` directly. Changes go live within ~60 seconds of pushing to `main`.

To add a resource (PDF, slide deck):
1. Drop the file in `resources/`
2. Add a link in the Resources section of `index.html`
3. Commit and push

## Forms

Contact and subscribe forms handled by [Formspree](https://formspree.io). 
Submissions arrive in the linked inbox. Hidden `_form_type` field distinguishes contact vs subscribe.
