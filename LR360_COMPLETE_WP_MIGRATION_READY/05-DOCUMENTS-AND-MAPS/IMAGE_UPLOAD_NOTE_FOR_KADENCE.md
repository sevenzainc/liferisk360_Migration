# Image Use Note for Kadence / WordPress

The standalone HTML preview pages already reference images from `/wp-content/uploads/liferisk360/assets/images/`.

When publishing page snippets inside Kadence Custom HTML blocks, upload the images in `/wp-content/uploads/liferisk360/assets/images/` to the WordPress Media Library or to a public folder on your site, then update each image `src` path if needed.

If you keep the same folder path under your site root, the snippets can continue to use paths such as:

```html
<img src="/wp-content/uploads/liferisk360/assets/images/youth-skate-path.jpg" alt="Youth moving forward">
```

If you upload images to the Media Library, replace the path with the WordPress media URL, for example:

```html
<img src="https://yourdomain.com/wp-content/uploads/2026/05/youth-skate-path.jpg" alt="Youth moving forward">
```

Images are placed in safe, positive contexts only: confidence, movement, teamwork, readiness, community, and life direction. Avoid placing identifiable youth images beside sensitive or negative risk labels.
