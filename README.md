# Ponmatha Chemicals Website

## Products page (image-free list)
Products are listed as clean cards showing only the **product name** and its **certification / documentation badges**
(GOTS V-7.0, OEKO-TEX, ZDHC, MSDS, TDS). Badges appear only where the brochure shows them for that product; products without
a listed reference show "Documentation on request". A key explaining each badge sits above the catalogue.
- No image is used inside product cards. Each of the 8 categories keeps one banner photo as its heading.
  For a fully image-free page set `SHOW_CATEGORY_BANNER_IMAGES = false` at the top of `js/products.js`.
- Edit products or badges in `js/products.js` (the `CATEGORIES` list).
- "Request Quote" opens `contact.html#contact-form` with the product and category prefilled.
