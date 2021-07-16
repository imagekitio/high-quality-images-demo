# DEMO APP - DISPLAYING HIGH-QUALITY IMAGES ON WEBSITES

## Steps to run
1. Clone the repo. 
2. Run `npm install` in the root of the repo folder.
3. Run `node index.js`.

This will start a server on port 3000 on your system which can be accessed from `https://localhost:3000` in your browser.

## Comparing image quality
The templates used to render the images are available inside the `views` folder. The actual product template that is displayed on the `/product-listing` page is present in the folder `views/mixins`.

By default, the page has a two-column layout with the images in the left column loading at a fixed size (`small`) on both desktop and mobile, and the right column using a responsive image tag to load the right image across devices. This is done by `product.pug` and `product_responsive.pug` templates respectively. The template used for the left or the right column can be changed in the last two lines of `views/partials/products.pug`.

To visually compare the image quality, you can try zooming in on the page from your browser, or by using an extension in Chrome like 'Magnifying Glass'.

## Data for this demo
The data, including the information about the images used in the demo, can be found inside the folder `data`. The actual pre-resized images can be found in the folder `static/images/` in two sizes `small` (300 x 300px) and `large` (800 x 800px)


