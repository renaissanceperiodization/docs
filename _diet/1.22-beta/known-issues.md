---
title:          Known Issues
nav_order:      400
parent:         Diet Coach App 1.22 Beta
---

Following are a few known issues in the beta. We are aware of them, so it's not important that you report them to us. Some are bugs, some are performance issues, and some are areas for UI improvement.

# Open Issues

* The app will sometimes flicker between screen transitions.
* Performing certain operations and transitioning between screens can sometimes be sluggish. Please be patient!
* When adding foods to a meal, there are duplicative buttons on each of the three steps: There are buttons that scroll with the food list, and there are buttons that float on top of the food list. These buttons are for adding proteins, fats, carbs, other foods, and accessing the barcode scanner.
* The app will sometimes show target calories rounded to the nearest 5, rather than to the nearest 100. For now, this is provided for debugging purposes.
* In some cases, upgrading from 1.21 to 1.22.x on iOS does not request access to steps from Apple Health.
* There is currently no mechanism to holistically copy over all meals' foods from the week being reviewed to the week being planned. This is a functionality we will be reintroducing in the future. In the meantime, after completing [Weekly Review and Planning](/docs/diet-coach-app/1.22-beta/features/weekly-review-and-weekly-planning/), you can either copy individual meals' foods over into meals in your upcoming week, or you can holistically copy entire days using "Edit schedule" (from the "..." overflow menu on the "Schedule" tab). Just make sure to check the configuration options for the copy operation to make sure you're copying only exactly what you want (eg, not necessarily copy the source day's target macros).
* Copy Day will occasionally fail to copy into certain days.

# Resolved Issues

* Fixed in [1.22.5](/docs/diet-coach-app/1.22-beta/release-notes/#1225-2025-02-13): On Android, sometimes opening the keyboard will slide the sheet "up" out of view and make it not scrollable, rather than covering up the sheet and still alow scrolling of the content behind the keyboard.
* Fixed in [1.22.6](/docs/diet-coach-app/1.22-beta/release-notes/#1226-2025-02-14): Shakes on the "Schedule" tab don't show the foods in the shake, even when "Show foods" is enabled.