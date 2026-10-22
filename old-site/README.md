# Website backup

This folder contains a backup of the site source and a generated static snapshot:

- `source/` contains the website project files, excluding Git metadata and build/dependency caches.
- `site/` contains the rendered website, including `index.html`.

The static snapshot was generated from the repository source with Jekyll. To refresh it, build the site to a directory outside the repository and copy the generated files into `site/`. The `old-site` folder is excluded from normal Jekyll builds so the backup is not published as part of the live site.
