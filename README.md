[<img src="https://github.com/magepow/themeforest/blob/master/shopify/shopify_affiliate.jpg" >](https://shopify.pxf.io/VyL446)

## Magento 2 Categories Extension Free
**Magento 2 Categories Extension Free** allows you to take the shortest way to lead customers to their target pages. With this extension, you can show subcategories on category pages and choose the layout to display them as the grid or list. Aside from that, you also can show the hot categories or simply the chosen categories on the Homepage or any CMS page. 

**Categories extension free by Magepow** is very easy to configure and manage, with no coding needed and responsive ready. With this extension, you can suggest to customers more content/products you have on your store and make an eye-catching look.

For example, your online store is selling a wide range of subcategories such as Tops, bottoms, pants, bags, jackets... might dozens of categories but you want when your customers come to your store, you want them to buy or know most of some products types that you concentrate more than normal products. 

![Magento 2 Categories Free](https://github.com/magepow/magento-2-categories/blob/master/media/magento-2-categories-5.png)

So this extension can help you show on the top of the page the hot categories are chosen from categories collection or show them on the top of the category pages to recommend to customers.

[![Latest Stable Version](https://poser.pugx.org/magepow/categories/v/stable)](https://packagist.org/packages/magepow/categories)
[![Total Downloads](https://poser.pugx.org/magepow/categories/downloads)](https://packagist.org/packages/magepow/categories)
[![Daily Downloads](https://poser.pugx.org/magepow/categories/d/daily)](https://packagist.org/packages/magepow/categories)

### Buy it
  [Buy it on Magepow](https://magepow.net/magento-2-categories-extension.html)
  
### 1. Highlight Features
| Features  | Free Version  | Pro Version |
| :------------ |:---------------:| :-----:|
|Display optional subcategories on **Home page**|:white_check_mark:|:white_check_mark:|
|Display the subcategories as slider layout on the Home page|X|:white_check_mark:|
|Display optional subcategories on **Category page**|:white_check_mark:|:white_check_mark:|
|Display the subcategories as slider layout on the Categories page|X|:white_check_mark:|
|Display optional subcategories on **Product page**|X|:white_check_mark:|
|Display optional subcategories on **Shopping Cart page**|X|:white_check_mark:|
|Add or remove categories for the home pape and category pages as desired|:white_check_mark:|:white_check_mark:|
|Add or remove categories on each page as desired|X|:white_check_mark:|
|Multiple positions show categories|X|:white_check_mark:|
|Subcategory characteristics on homepage and category page vary with 2 <br /> independent installers|:white_check_mark:|:white_check_mark:|
|Subcategory block characteristics on each page can be individually <br /> customized using 'Category Pro Rule'|X|:white_check_mark:|
|**Grid layout**|:white_check_mark:|:white_check_mark:|
|**List layout**|:white_check_mark:|:white_check_mark:|
|**Slider layout**|X|:white_check_mark:|
|Sort the subcategories by **Name**|:white_check_mark:|:white_check_mark:|
|Sort the subcategories by **Page Title**|:white_check_mark:|:white_check_mark:|
|Sort the subcategories by **Location**|:white_check_mark:|:white_check_mark:|
|Sort the subcategories by **Creation Date**|:white_check_mark:|:white_check_mark:|
|Sort the subcategories by **Admin tree**|X|:white_check_mark:|
|Display subcategory with **Block Title**|:white_check_mark:|:white_check_mark:|
|Display subcategory with **Description**|:white_check_mark:|:white_check_mark:|
|Display subcategory with **Thumbnail**|:white_check_mark:|:white_check_mark:|
|Display subcategory with **Item Amount**|:white_check_mark:|:white_check_mark:|
|Full responsive design|:white_check_mark:|:white_check_mark:|
|Customize Responsive Information|X|:white_check_mark:|
|Display different categories with customer groups <br /> (Not logged in, General, Wholesale, Retailer)|X|:white_check_mark:|
|Free Support|X|:white_check_mark:|

![Magento 2 Categories Free](https://github.com/magepow/magento-2-categories/blob/master/media/magento-2-categories-7.jpg)

Display optional subcategories on Home page

![Magento 2 Categories Free](https://github.com/magepow/magento-2-categories/blob/master/media/magento-2-categories-9.jpg)

Display optional subcategories on Category page

![Magento 2 Categories Free](https://github.com/magepow/magento-2-categories/blob/master/media/magento-2-categories-8.jpg)

Display optional subcategories on Product page

![Magento 2 Categories Free](https://github.com/magepow/magento-2-categories/blob/master/media/magento-2-categories-6.jpg)

Display optional subcategories on Shopping Cart page

See more: [Demo](https://demo.magepow.net/categoriespro/)

[![Magento 2 Categories Free](https://github.com/magepow/magento-2-categories/blob/master/media/Mgento-2-category-4.jpg)](https://magepow.com/magento-2-categories-extension.html) [![Magento 2 Categories Pro](https://github.com/magepow/magento-2-categories/blob/master/media/magento-2-categories-3.jpg)](https://magepow.com/magento-2-categories-extension.html)

### 2. How to install Magento 2 Categories extension Free
#### ✓ Install Magepow Categories via composer (recommend)
Run the following command in Magento 2 root folder:

```
composer require magepow/categories
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy -f
```

### 3. Magepow Categories user guide
**SubCategories extension free for Magento** allows customers access the categories quickly and conveniently, stimulating users to click on the categories because of the beautiful interface.

#### Enable Magepow Categories
Go to `Admin Panel > Stores > Settings > Configuration > Magepow > Categories`

Select `Yes` to enable module.
#### Setting Magepow SubCategories
Go to `Admin Panel > Stores > Settings > Configuration > Magepow > Categories`

 * Two layouts available (Grid or List).
 * Ability to sort subcategories by "Name", "Page Title", "Position", and "Created Date".
 * Ability to show subcategories heading or not and to type in the heading text.
 * Ability to show or not category description.
 * Select categories that do not display subcategories.
 
![config-module-img](https://github.com/magepow/magento-2-categories/blob/master/media/magento-2-categories-10.jpg)

The home page also has the same settings as the category page, except that: 

* The home page can choose the display categories instead of excluding the display category.
* The home page can order the categories by 'custom sort', which will display in the order ids appear in the config value.
   You can curate this by manually setting the ids in the env.php file to override admin based config.
   ```
   ./bin/magento config:set -e magepow_categories/home_page/category_select "64,72,73,1052,68,69,70,1046,65,88,311"
   ``` 
 * Select the categories displayed on the home page.

![config-module-img](https://github.com/magepow/magento-2-categories/blob/master/media/magento-2-categories-11.jpg)

### This Is Result In Frontend
#### In homepage

![config-module-img](https://github.com/magepow/magento2-categories/blob/master/media/frontend_home.png)
 
#### In categories page

![config-module-img](https://github.com/magepow/magento2-categories/blob/master/media/frontend_category.png)
 
### [How does Magento 2 Categories work?](https://www.youtube.com/watch?v=k3A7PBh-NbQ&lc=UgzCFSLUqlD6cl__PH54AaABAg)
## Donation

If this project help you reduce time to develop, you can give me a cup of coffee :) 

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/paypalme/alopay)


**[Our Website](https://magepow.net)**

**[Our Magento 2 Extensions](https://magepow.net/extensions.html)**

* [Magento 2 Recent Order Notification](https://magepow.net/magento-2-recent-order-notification.html)

* [Magento 2 Categories Extension](https://magepow.net/magento-2-categories-extension.html)

* [Magento 2 Sticky Cart](https://magepow.net/magento-sticky-add-to-cart.html)

* [Magento 2 Lazy Load](https://magepow.net/magento-2-lazy-load-extension.html)

* [Magento 2 Lookbook Pin Products](https://magepow.net/lookbook-pin-products.html)

* [Magento 2 Ajax add to cart](https://magepow.net/magento-2-ajax-add-to-cart.html)

* [Magento 2 Speed Optimizer](https://magepow.net/magento2-speed-optimizer.html)

* [Magento 2 Quick Edit](https://magepow.net/magento-2-quick-edit.html)

* [Magento 2 Product Zoom](https://magepow.net/magento-2-product-zoom.html)

* [Magento 2 Layered Navigation Advanced](https://magepow.net/magento-2-layered-navigation-advanced.html)

* [Magento 2 Product Tags](https://magepow.net/magento-2-product-tags.html)

* [Special Promotion for Magento 2](https://magepow.net/magento-2-special-promotion-extension.html)

* [Magento 2 Size Chart](https://magepow.net/magento-2-size-chart.html)

* [Magento 2 Auto related products](https://magepow.net/magento-2-auto-related-products.html)

* [Magento 2 Sitemap Exclusion](https://magepow.net/magento-2-sitemap-exclusion.html)

* [Magento 2 Mega Menu](https://magepow.net/magento-2-mega-menu.html)

* [Magento 2 Sitemap](https://magepow.net/magento-2-sitemap.html)

* [Magento 2 Ajax Wishlist](https://magepow.net/magento-2-ajax-wishlist.html)

* [Magento 2 PDF Invoice Frontend](https://magepow.net/magento-2-pdf-invoice-frontend.html)

* [Magento 2 Bundle Pack](https://magepow.net/magento-2-bundle-product.html)

* [Magento 2 Product Zoom 360](https://magepow.net/magento-2-product-zoom-360.html)

**[Our Magento 2 services](https://magepow.com/magento-services.html)**

* [PSD to Magento 2 Theme Conversion](https://alothemes.com/psd-to-magento-theme-conversion.html)

* [Magento 2 Speed Optimization Service](https://magepow.com/magento-speed-optimization-service.html)

* [Magento 2 Security Patch Installation](https://magepow.com/magento-security-patch-installation.html)

* [Magento 2 Website Maintenance Service](https://magepow.com/website-maintenance-service.html)

* [Magento 2 Professional Installation Service](https://magepow.com/professional-installation-service.html)

* [Magento 2 Upgrade Service](https://magepow.com/magento-upgrade-service.html)

* [Magento 2 Customization Service](https://magepow.com/customization-service.html)

* [Hire Magento 2 Developer](https://magepow.com/hire-magento-developer.html)

**[Our Magento 2 Themes](https://alothemes.com/)**

* [Expert Multipurpose Responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/expert-premium-responsive-magento-2-and-1-support-rtl-magento-2-/21667789)

* [Gecko Premium Responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/gecko-responsive-magento-2-theme-rtl-supported/24677410)

* [Milano Fashion Responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/milano-fashion-responsive-magento-1-2-theme/12141971)

* [Electro 2 Responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/electro2-premium-responsive-magento-2-rtl-supported/26875864)

* [Electro Responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/electro-responsive-magento-1-2-theme/17042067)

* [Pizzaro Food responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/pizzaro-food-responsive-magento-1-2-theme/19438157)

* [Biolife organic responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/biolife-organic-food-magento-2-theme-rtl-supported/25712510)

* [Market responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/market-responsive-magento-2-theme/22997928)

* [Kuteshop responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/kuteshop-multipurpose-responsive-magento-1-2-theme/12985435)

* [Bencher - Responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/bencher-responsive-magento-1-2-theme/15787772)

* [Supermarket Responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/supermarket-responsive-magento-1-2-theme/18447995)

**[Our Shopify Themes](https://themeforest.net/user/alotheme)**

* [Dukamarket - Multipurpose Shopify Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/dukamarket-multipurpose-shopify-theme/36158349)

* [Ohey - Multipurpose Shopify Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/ohey-multipurpose-shopify-theme/34624195)

* [Flexon - Multipurpose Shopify Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/flexon-multipurpose-shopify-theme/33461048)

**[Our Shopify App](https://apps.shopify.com/partners/maggicart)**

* [Magepow Infinite Scroll](https://apps.shopify.com/magepow-infinite-scroll)

* [Magepow Promotionbar](https://apps.shopify.com/magepow-promotionbar)

* [Magepow Size Chart](https://apps.shopify.com/magepow-size-chart)

**[Our WordPress Theme](https://themeforest.net/user/alotheme/portfolio)**

* [SadesMarket - Multipurpose WordPress Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/sadesmarket-multipurpose-wordpress-theme/35369933)
