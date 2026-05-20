# LifeRisk360 Complete WordPress Migration Package

This ZIP has been rebuilt so the HTML, CSS, JavaScript, and image paths point to the WordPress folder path below:

`/wp-content/uploads/liferisk360/assets/`

## 1. Upload folder using WP File Manager

Upload this folder:

`01-UPLOAD-TO-WP-FILE-MANAGER/liferisk360/`

into:

`public_html/wp-content/uploads/`

Final path must be:

`public_html/wp-content/uploads/liferisk360/assets/`

Use lowercase `liferisk360`. Do not use `Liferisk360`.

## 2. Test the image path

Open this URL in your browser:

`https://liferisk360.com/wp-content/uploads/liferisk360/assets/images/youth-skate-path.jpg`

If the image opens, your folder path is correct.

## 3. Add the CSS

Copy all content from:

`02-WP-CODE-SNIPPETS/liferisk360-global-css-paste-into-additional-css.css`

Paste into:

`Appearance → Customize → Additional CSS`

Alternative: paste it into WPCode as a CSS snippet.

## 4. Add the JavaScript

Copy all content from:

`02-WP-CODE-SNIPPETS/liferisk360-global-js-paste-into-wpcode.js`

Paste into:

`WPCode → Add Snippet → JavaScript Snippet`

Set it to load site-wide or only on LifeRisk360 pages.

## 5. Create WordPress pages

Use the page list in:

`05-DOCUMENTS-AND-MAPS/wp-migration-page-checklist.csv`

For each WordPress page:

1. Open the page.
2. Add a Custom HTML block.
3. Copy the matching file from `03-PASTE-INTO-WORDPRESS-PAGES/`.
4. Paste into the Custom HTML block.
5. Update the page.

## 6. Homepage file

For the Home page, paste:

`03-PASTE-INTO-WORDPRESS-PAGES/index-wp-section.html`

into the Home page Custom HTML block.

## 7. Important folder rule

The folder name must be exactly:

`liferisk360`

not:

`Liferisk360`

because some hosting servers treat uppercase and lowercase as different paths.

## 8. What not to paste into WordPress pages

Do not paste the full files from `04-REFERENCE-FULL-HTML-PREVIEW/` into WordPress pages. Those are reference/preview files.

Use only the files in:

`03-PASTE-INTO-WORDPRESS-PAGES/`

## 9. If a hero image still does not show

Check these three items:

1. The image opens directly at the test URL above.
2. The page HTML is pasted inside a Custom HTML block.
3. The CSS file has been pasted into Additional CSS or WPCode.
