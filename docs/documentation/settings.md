---
title: Settings
parent: Documentation
nav_order: 30
---

# Aisleron Settings
{: .no_toc }

![Settings Page](/assets/images/screenshots/light-mode/alr-050-settings.png)
{: .mx-auto .float-md-right }

The *Settings* page is used to configure application behavior and perform database backup and restore activities. To access *Settings*, tap the hamburger menu to open the navigation drawer, then tap the *Settings* menu item.

Settings are automatically saved when leaving the *Settings* page.

The following settings are available:

{:toc}
* TOC

---

## Display Options

**Show on lock screen**: By default, your phone needs to be unlocked to use Aisleron. With this setting toggled to *On*, the Aisleron shopping list will be displayed over the lock screen for convenience. Any action outside Aisleron will still require the screen to be unlocked.

**Keep screen on**: When turned on, the phone screen will remain on while viewing a shopping list.

**Theme**: The application's display theme. Available options are *System Theme*, *Light Theme*, or *Dark Theme*.

## Shopping List Options

**Hide status change message**: By default, a notification is displayed whenever a product's status is changed between *Needed* and *In Stock*. With this setting toggled to *On*, the status change notification will be hidden.

**Show empty aisles**: By default, an aisle will be hidden if it currently doesn't have any visible products. Toggle this to *On* to always display all aisles.

**Tracking mode**: Determines how products will be tracked in lists. Available options are:

* *Checkbox*: Show a checkbox on each product to toggle the needed state. Checkbox is the default option.
* *Quantity*: Show a quantity stepper on each product to track the number of needed items. Swipe left or right to toggle the needed status.
* *Checkbox and Quantity*: Display both the checkbox and the quantity stepper.
* *None (swipe only)*: Hide both the checkbox and quantity stepper. Swipe left or right to toggle the needed status.

## Backup/Restore

**Backup folder**: Select the folder where database backups will be saved. This will also be auto-set after executing a backup or restore action.

**Backup database**: Back up a copy of the application database to a selected folder. The initial folder will be the *Backup folder* defined above. 

**Restore database**: Restore a previous database backup from a selected folder. The initial folder will be the *Backup folder* defined above. 

{: .warning }  
When restoring a database, the existing database and all its data will be removed and replaced with the restored database. 