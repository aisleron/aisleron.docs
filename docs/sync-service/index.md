---
title: Aisleron Sync Service
nav_order: 15
---

# Aisleron Sync Service

The Aisleron Sync service allows you to keep your shopping lists up to date across all your devices.

When connected to a sync service, a sync will be executed:
* Periodically, every 15 minutes.
* On resuming the application main activity.
* Immediately when updating a products [status](../documentation/product-status#product-status) or [quantity](../documentation/product-status#quantity-tracking).
* When manually initiating a sync from [Account Preferences](./account-preferences#sync-settings)

The manual sync will run on any network, regardless of whether *Sync on mobile data* is enabled or not. All other sync jobs will run on unmetered networks (e.g., WiFi), and on mobile data only if *Sync on mobile data* is enabled.

{: .note }
The periodic sync job will also run when *not* connected to a sync service, to perform certain maintenance tasks such as deleting records flagged for removal.
