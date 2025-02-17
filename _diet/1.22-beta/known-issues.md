---
title:          Known Issues
nav_order:      400
parent:         Diet Coach App 1.22 Beta
description:    "Known issues in the RP Diet Coach App 1.22 beta: Some are bugs, some are performance issues, and some are areas for UI improvement."
---

Following are a few known issues in the beta. We are aware of them, so it's not important that you report them to us. Some are bugs, some are performance issues, and some are areas for UI improvement.

# Open Issues

* The app will sometimes flicker between screen transitions.
* Performing certain operations and transitioning between screens can sometimes be sluggish. Please be patient!
* When adding foods to a meal, there are duplicative buttons on each of the three steps: There are buttons that scroll with the food list, and there are buttons that float on top of the food list. These buttons are for adding proteins, fats, carbs, other foods, and accessing the barcode scanner.
* The app will sometimes show target calories rounded to the nearest 5, rather than to the nearest 100. For now, this is provided for debugging purposes.
* In some cases, upgrading from 1.21 to 1.22.x on iOS does not request access to steps from Apple Health.
* There is currently no mechanism to holistically copy over all meals' foods from the week being reviewed to the week being planned. This is a functionality we will be reintroducing in the future. In the meantime, after completing [Weekly Review and Planning](/docs/diet-coach-app/1.22-beta/features/weekly-review-and-weekly-planning/), you can either [copy individual meals' foods](/docs/diet-coach-app/1.22-beta/features/copy-foods/) over into meals in your upcoming week, or you can holistically copy entire days using "Edit schedule" (from the "..." overflow menu on the "Schedule" tab). [Just make sure to check the configuration options for the copy operation to make sure you're copying only exactly what you want (eg, not necessarily copy the source day's target macros).](/docs/diet-coach-app/1.22-beta/features/copy-day/#copy-foods-in-meals:~:text=If%20you%20want%20to%20copy%20over%20meals%20from%20a%20previous%20week%20to%20the%20current%20week%20while%20preserving%20the%20RP%20algorithm%E2%80%99s%20calorie%20and%20macro%20recommendations)
* "Schedule Template" on the "Me" tab may occasionally become unresponsive and do nothing. Current workaround is to force quit the app and restart it. (#ZD185211)
* Certain days sometimes can't be navigated to on the "Schedule" tab. Current workaround is to force quit the app and restart it. Or, if possible, swipe the day carousel to another week, select the same day of the week for the day that's not navigable to, then swipe back, and the day should be selected. (#ZD185234, #ZD185240, #ZD185471, #L2936)
* Despite our efforts in [1.22.5](/docs/diet-coach-app/1.22-beta/release-notes/#1225-2025-02-13) and [1.22.6](/docs/diet-coach-app/1.22-beta/release-notes/#1226-2025-02-14), which did make some improvements, some sheets continue to extend into the Android Status Bar on some devices, making content unreadable and not tappable. (#ZD185476, #L3002)
* The calendar icon at the top of the "Schedule" tab currently doesn't do anything. This is a functionality we'll be reevaluating as part of a coming visual redesign.
* The info button next to [Day Balance](https://docs.rpstrength.com/docs/diet-coach-app/1.22-beta/features/day-balance/) on the "Add workout" and "Edit workout" sheets shows placeholder text instead of any actual helpful text! (#ZD185477, #L2974)
* Meals will sometimes get automatically programmed outside the [specified range](https://docs.rpstrength.com/docs/diet-coach-app/1.22-beta/concepts/sleep-and-preferred-meal-time-range/). (#ZD185485, #L3026)
* User can schedule overlapping workouts during the diet start wizard. (#ZD185488, #L3027)


# Resolved Issues

* Fixed in [1.22.5](/docs/diet-coach-app/1.22-beta/release-notes/#1225-2025-02-13): On Android, sometimes opening the keyboard will slide the sheet "up" out of view and make it not scrollable, rather than covering up the sheet and still alow scrolling of the content behind the keyboard.
* Fixed in [1.22.6](/docs/diet-coach-app/1.22-beta/release-notes/#1226-2025-02-14): Shakes on the "Schedule" tab don't show the foods in the shake, even when "Show foods" is enabled.
* Fixed in [1.22.6](/docs/diet-coach-app/1.22-beta/release-notes/#1226-2025-02-14): Copy Day will occasionally fail to copy into certain days.