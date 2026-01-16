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

**Pure Black style**: There are four levels of Pure Black styling to choose from, which will apply cumulatively:
* *Theme Default*: Standard theme colors will apply.
* *Economy*: The application background will be black.
* *Business Class*: EThe title bar will be black.
* *First Class*: The navigation drawer will be black.

{: .note }  
On devices running Android 9 and below, Pure Black will only apply to the application background for all levels.

**Starting list**: The list that the application will show when opened. Available options are *Home Stock*, *Needed*, *All Items*, or one of the shops pinned to the navigation bar. 

**Language**: Select a display language from the list of supported languages

## Shopping List Options

**Hide status change message**: By default, a notification is displayed whenever a product's status is changed between *Needed* and *In Stock*. With this setting toggled to *On*, the status change notification will be hidden.

**Show empty aisles**: By default, an aisle will be hidden if it currently doesn't have any visible products. Toggle this to *On* to always display all aisles.

**Tracking mode**: Determines how products will be tracked in lists. Available options are:

* *Checkbox*: Show a checkbox on each product to toggle the needed state. Checkbox is the default option.
* *Quantity*: Show a quantity stepper on each product to track the number of needed items. Swipe left or right to toggle the needed status.
* *Checkbox and Quantity*: Display both the checkbox and the quantity stepper.
* *None (swipe only)*: Hide both the checkbox and quantity stepper. Swipe left or right to toggle the needed status.

**Note hint**: Sets the hint that will be displayed on hte shopping list when an item has a note associated:

* *Button*: Show a button on the item that will open the [Note Dialog](/docs/documentation/notes#note-dialog) when clicked.
* *Summary*: Show the first line of the note below the item name, and will open the [Note Dialog](/docs/documentation/notes#note-dialog) when clicked.
* *Indicator (\*)*: Show an asterisk next to the item name to indicate it has a note.
* *None*: Don't show any hint if the item has a note. This is the default option.

## Backup/Restore

**Backup folder**: Select the folder where database backups will be saved. This will also be auto-set after executing a backup or restore action.

**Backup database**: Back up a copy of the application database to a selected folder. The initial folder will be the *Backup folder* defined above. 

**Restore database**: Restore a previous database backup from a selected folder. The initial folder will be the *Backup folder* defined above. 

{: .warning }  
When restoring a database, the existing database and all its data will be removed and replaced with the restored database. 