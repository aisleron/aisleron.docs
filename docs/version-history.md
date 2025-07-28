---
title: Version History
nav_order: 40
---

# Aisleron Version History

## [2025.6.0](https://github.com/aisleron/aisleron/releases/tag/v2025.6.0) - 30 Jul 2025

### Enhancements
* Added support for loyalty card lookups via [Catima — Loyalty Card Wallet](https://catima.app/).
* Introduced Russian language support.
* Updated target SDK to Android 15 (API level 35) for improved compatibility.

### Bug Fixes
* Resolved an issue where the bottom list item’s checkbox was obscured by the floating action button (FAB) ([GitHub](https://github.com/aisleron/aisleron/issues/24)).
* Fixed a problem preventing .sqlite backup files from opening on Android 15 ([GitHub](https://github.com/aisleron/aisleron/issues/22)).


## [2025.5.0](https://github.com/aisleron/aisleron/releases/tag/v2025.5.0) - 30 Jun 2025

### Enhancements
* Added an option to show or hide the default aisle in a shop.
* Improved visibility settings: unmapped products are now hidden when the default aisle is hidden ([GitHub](https://github.com/aisleron/aisleron/issues/21), [GitHub](https://github.com/aisleron/aisleron/issues/23)).
* Introduced expand/collapse functionality for aisles.
* Added an option to show or hide empty aisles, with empty aisles hidden by default ([GitHub](https://github.com/aisleron/aisleron/issues/18)).
* Enabled editing a shop directly from the shopping list.
* Added an option to sort a list by name.
* Added explanatory text to blank lists to clarify why no items are shown.

### Bug Fixes
* Improved the reliability of long-press actions on shopping list items ([GitHub](https://github.com/aisleron/aisleron/issues/20)).


## [2025.4.5](https://github.com/aisleron/aisleron/releases/tag/v2025.4.5) - 18 Apr 2025

* Add French and Polish translations from Hosted Weblate.

## [2025.4.4](https://github.com/aisleron/aisleron/releases/tag/v2025.4.4) - 01 Apr 2025

* Initial F-Droid release.

## [2025.4.0](https://github.com/aisleron/aisleron/releases/tag/v2025.4.0) - 21 Mar 2025

### Enhancements

* Tweak the navigation drawer header to be more space efficient

### Bug Fixes

* Fix Product List Selected Item is not deselected when tapping another item ([GitHub](https://github.com/aisleron/aisleron/issues/3))
* Fix Action Mode is not dismissed when invoking a Fab action ([GitHub](https://github.com/aisleron/aisleron/issues/7)).
* Fix Action Bar Title doesn't change after selecting a different product list item ([GitHub](https://github.com/aisleron/aisleron/issues/5)).
* Fix Product List Selected Item is not deselected when tapping the back arrow or back button ([GitHub](https://github.com/aisleron/aisleron/issues/4)).
* Fix Selecting an item in the All Shops list doesn't highlight the selected Shop ([GitHub](https://github.com/aisleron/aisleron/issues/6))
* Fixed issues with contextual action bar on the Shop list page

## [2025.3.0](https://github.com/aisleron/aisleron/releases/tag/v2025.3.0) - 17 Mar 2025

### Enhancements

* Change 'In Stock' Nav Bar option to 'Home Stock' for clearer terminology ([GitHub](https://github.com/aisleron/aisleron/issues/1)).

### Bug Fixes

* Fix "Add Product to Aisle" button shows in All Shops list ([Github](https://github.com/aisleron/aisleron/issues/2)).


## [2025.2.0](https://github.com/aisleron/aisleron/releases/tag/v2025.2.0) - 11 Mar 2025 
* Include an option to add a new product [directly to an aisle](/docs/documentation/manage-aisles#add-a-product-to-an-aisle).

## [2025.1.0](https://github.com/aisleron/aisleron/releases/tag/v2025.1.0) - 03 Mar 2025  
* First Google Play Store release (Closed Testing).

## 0.2.0 - 06 Feb 2025
* Display a Welcome page on initial run.
* Show a snack bar message on product status change. 
* Add an option to load sample items into the database on initial run.

## 0.1.0 - 01 Jan 2025
* Ability to manage Shops, Aisles and Products.
* Organize aisles and products in home and shop lists.
* Display home lists for *In Stock*, *Needed*, and *All Items*.
* Display shop lists with *Needed* products.
* Backup and Restore application data.
* Search for a product on any list.