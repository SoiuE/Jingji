# Jingji Supply website

A responsive static front end for Wenzhou Jingji Trading Co., Ltd., designed as a sourcing and buying-solutions site for U.S. retail buyers.

## Run locally

Open `index.html` in a browser or serve this folder with any static web server. No build step or framework dependency is required.

## Main pages

- `index.html` — sourcing-focused landing page
- `products.html` — filterable product collection
- `product.html?id=apparel-shirt` — product detail page (the product id selects the item)
- `cart.html` — local sourcing shortlist with editable quantities

## Product shortlist

Add-to-bag state is stored in the browser's local storage. The bag is a sourcing shortlist, not an ecommerce checkout: the site does not process payment, guarantee stock, or publish fixed prices. The email action prepares a shortlist inquiry to `JINJI231@163.com`.

Product descriptions and specs are illustrative sourcing concepts and should be confirmed against actual offerings before publication. Product photos are saved under `assets/products/` for self-hosting; review each image's source license and attribution requirements before commercial use.

## Inquiry form

The home page inquiry form opens the visitor's default email application with a prepared message. It does not submit data to a server. Connect a form service or backend if direct web submissions are required.
