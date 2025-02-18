---
title: Settings
parent: Documentation
nav_order: 30
---

# Aisleron Settings
{: .no_toc }

![Settings Page](/assets/images/screenshots/alr-050-settings.png)
{: .mx-auto .float-md-right }

The *Settings* page is used to configure application behavior and perform database backup and restore activities. To access *Settings*, tap the hamburger menu to open the navigation drawer, then tap the *Settings* menu item.

Settings are automatically saved when leaving the *Settings* page.

The following settings are available:

{:toc}
* TOC

---

## Display Options

**Show on lock screen**: By default, your phone needs to be unlocked to use Aisleron. With this setting toggled to *On*, the Aisleron shopping list will be displayed over the lock screen for convenience. Any action outside Aisleron will still require the screen to be unlocked.

**Theme**: The application's display theme. Available options are *System Theme*, *Light Theme*, or *Dark Theme*.

## Shopping List Options

**Hide status change message**: By default, a notification is displayed whenever a product's status is changed between *Needed* and *In Stock*. With this setting toggled to *On*, the status change notification will be hidden.

## Backup/Restore

**Backup folder**: Select the folder where database backups will be saved. This will also be auto-set after executing a backup or restore action.

**Backup database**: Back up a copy of the application database to a selected folder. The initial folder will be the *Backup folder* defined above. 

**Restore database**: Restore a previous database backup from a selected folder. The initial folder will be the *Backup folder* defined above. 

{: .warning }  
When restoring a database, the existing database and all its data will be removed and replaced with the restored database. 