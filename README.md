# Phone catalog
Phone catalog is a single page application that is a catalog of gadgets and their accessories. It contains a header with a menu and a search field that appears when you open certain menu items, where you need to search for products on the page. Depending on what is entered in the search field, the page will display filtered products. The search field can be cleared with one click by pressing X. Search processing is implemented with a small delay, to save resources, to process the final entered text and not search for each character.

The content of the main part of the application is loaded depending on the selected menu item. The home page has a slider banner that can be scrolled endlessly, with an auto-replacement of the image set every 5 seconds. There are also several product sliders selected according to the slider title.

Product data is downloaded from the test server using an API. The application implements the processing of API access errors and access to non-existent addresses with the output of corresponding messages to the user.

On the pages with the product catalog, a counter of the available products in this category and the ability to sort products, as well as the ability to choose the number of products to be displayed, with the corresponding division of the entire catalog into the required number of pages, are implemented.

You can download for viewing more detailed information about the product by clicking on it. Breadcrumb navigation is also implemented on the pages for convenience.

In the Favorites section, products marked by the user using the "heart" button are displayed. To remove a product from your favorites, remove the “heart” mark from the product.

The Cart section displays the products that were added there using the "Add to cart" button, which changes its appearance and inscription to "Added to cart" if the product is already in the cart. You can also remove products from the basket or change their quantity, while the total amount of the purchase is automatically recalculated. Products added to the cart are additionally stored in the localStorage of the browser so as not to lose them when the page is reloaded.

The total number of products selected for Cart/Favorites is displayed next to the corresponding icon in the Header of the application.

Footer, in addition to links, additionally contains a scroll button to the top of the page.

The design of the application is adapted to different devices with different screen sizes to ensure optimal display and interaction with the user, regardless of the device format..

The following technologies and libraries were used during creation:
-	HTML
-	CSS
-	SASS
-	BEM
- JavaScript
-	React
-	React Router
-	React Resize Detector

---
#### [DEMO LINK](https://volodymir-tymtsias.github.io/phone-catalog/)
