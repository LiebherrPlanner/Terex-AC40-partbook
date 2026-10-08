# TEREX AC40 PartBook — GitHub Pages

Static web edition derived from the supplied Docware/ETK Terex AC40 package.

## Deploy
1. Upload the contents of this folder to a GitHub repository.
2. GitHub → Settings → Pages → Deploy from branch → `main` → `/ (root)`.
3. Open the generated GitHub Pages URL.

No PHP, Node.js, Java, Tomcat, H2 or MySQL is required.

## Important
The JSON and image files are derived from the supplied PartBook database. Confirm that you have the right to publish the catalog data publicly before enabling a public GitHub repository.

## Data
- catalogs.json — catalog/sheet records
- parts.json — part rows
- images.json — catalog-to-diagram mapping
- hotspots.json — diagram hotspot records (`N` = part position, `G` = catalog/group link)
- image-meta.json — inferred Docware hotspot coordinate canvas dimensions used to place hotspots correctly on the resized web images
