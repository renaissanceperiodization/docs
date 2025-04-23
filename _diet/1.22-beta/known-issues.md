---
title:          Known Issues
nav_order:      400
parent:         Diet Coach App 1.22 Beta
description:    "Known issues in the RP Diet Coach App 1.22 beta: Some are bugs, some are performance issues, and some are areas for UI improvement."
---

Following are a few known issues in the beta. We are aware of them, so it's not important that you report them to us. Some are bugs, some are performance issues, and some are areas for UI improvement.

# Open Issues

* Performing certain operations and transitioning between screens can sometimes be sluggish. Please be patient!
* When adding foods to a meal, there are duplicative buttons on each of the three steps: There are buttons that scroll with the food list, and there are buttons that float on top of the food list. These buttons are for adding proteins, fats, carbs, other foods, and accessing the barcode scanner.
* The app will sometimes show target calories rounded to the nearest 5, rather than to the nearest 100. For now, this is provided for debugging purposes.
* In some cases, upgrading from 1.21 to 1.22.x on iOS does not request access to steps from Apple Health. (#L2918)
* There is currently no mechanism to holistically copy over all meals' foods from the week being reviewed to the week being planned. This is a functionality we will be reintroducing in the future. In the meantime, after completing [Weekly Review and Planning](/docs/diet-coach-app/1.22-beta/features/weekly-review-and-weekly-planning/), you can either [copy individual meals' foods](/docs/diet-coach-app/1.22-beta/features/copy-foods/) over into meals in your upcoming week, or you can holistically copy entire days using "Edit schedule" (from the "..." overflow menu on the "Schedule" tab). [Just make sure to check the configuration options for the copy operation to make sure you're copying only exactly what you want (eg, not necessarily copy the source day's target macros).](/docs/diet-coach-app/1.22-beta/features/copy-day/#copy-foods-in-meals:~:text=If%20you%20want%20to%20copy%20over%20meals%20from%20a%20previous%20week%20to%20the%20current%20week%20while%20preserving%20the%20RP%20algorithm%E2%80%99s%20calorie%20and%20macro%20recommendations)
* "Schedule Template" on the "Me" tab may occasionally become unresponsive and do nothing. Current workaround is to force quit the app and restart it. (#ZD185211)
* When typing fast on Android, the app would sometimes fail to register keystrokes. (#ZD185901, #ZD186122, #ZD186092, #ZD186173, #ZD186065, #L3042)
* Sometimes tapping into a numeric field wouldn't automatically highlight the whole value. (#ZD185720, #ZD186097, #ZD186291, #L3056)
* Sometimes the trailing digit of a number in a macro pill or numeric input field is truncated. (#ZD185514, #ZD185731, #ZD185814, #ZD185722, #L3028)
* Unable to tap "Save" on weigh-in sheet when manually syncing weight from Apple Health because manual entry field is blank. (#ZD186410)
* Diet difficulty messaging when configuring a new diet doesn't accurately reflect actual difficulty of goals. (#ZD186816, #L3074)
* Some sheets extend into the Android Status Bar on some devices, making content unreadable and not tappable. (#ZD185476, #ZD186481, #L3002, #L3075)
* Sometimes launching the Android app would freeze on the RP logo splash screen. (#ZD186481, #ZD186936, #L3076)
* Numeric notification badges on iOS app icon not clearly correlated with in-app actions. (#ZD185277, #ZD186228, #ZD185772, #L3085)


# Resolved Issues

* Fixed in [1.22.5](/docs/diet-coach-app/1.22-beta/release-notes/#1225-2025-02-13): On Android, sometimes opening the keyboard will slide the sheet "up" out of view and make it not scrollable, rather than covering up the sheet and still alow scrolling of the content behind the keyboard.
* Fixed in [1.22.6](/docs/diet-coach-app/1.22-beta/release-notes/#1226-2025-02-14): Shakes on the "Schedule" tab don't show the foods in the shake, even when "Show foods" is enabled.
* Fixed in [1.22.6](/docs/diet-coach-app/1.22-beta/release-notes/#1226-2025-02-14): Copy Day will occasionally fail to copy into certain days.
* Added in [1.22.8](/docs/diet-coach-app/1.22-beta/release-notes/#1228-2025-02-17): The info button next to [Day Balance](https://docs.rpstrength.com/docs/diet-coach-app/1.22-beta/features/day-balance/) on the "Add workout" and "Edit workout" sheets shows placeholder text instead of any actual helpful text! (#ZD185477, #L2974)
* Fixed in [1.22.8](/docs/diet-coach-app/1.22-beta/release-notes/#1228-2025-02-17): User can schedule overlapping workouts during the diet start wizard. (#ZD185488, #L3027)
* Fixed in [1.22.8](/docs/diet-coach-app/1.22-beta/release-notes/#1228-2025-02-17): Certain days sometimes can't be navigated to on the "Schedule" tab. Current workaround is to force quit the app and restart it. Or, if possible, swipe the day carousel to another week, select the same day of the week for the day that's not navigable to, then swipe back, and the day should be selected. (#ZD185234, #ZD185240, #ZD185471, #L2936)
* Fixed in [1.22.10](/docs/diet-coach-app/1.22-beta/release-notes/#12210-2025-02-19): Sometimes can't add "other foods" to a meal. (#ZD185509, #ZD185684, #ZD185308, #L3029)
* Fixed in [1.22.10](/docs/diet-coach-app/1.22-beta/release-notes/#12210-2025-02-19): Sometimes [Copy Day](/docs/diet-coach-app/1.22-beta/features/copy-day/) focuses the previous week instead of the current week in the day carousel. (#ZD185752, #L3036)
* Fixed in [1.22.10](/docs/diet-coach-app/1.22-beta/release-notes/#12210-2025-02-19): On Android, sometimes the step count target card on the "Schedule" tab doesn't show the step count target. (#ZD185749, #ZD185640, #ZD185581, #L3035)
* Fixed in [1.22.12](/docs/diet-coach-app/1.22-beta/release-notes/#12212-2025-02-22): Diet share image incorrectly shows meal adherence stats and has misaligned graph elements. (#ZD186050, #L3053)
* Fixed in [1.22.12](/docs/diet-coach-app/1.22-beta/release-notes/#12212-2025-02-22): Sometimes the camera won't be detected or open automatically for UPC scanning. (#ZD185308, #ZD185928, #ZD185914, #ZD186112, #ZD186149, #ZD186235, #ZD186246, #ZD186269, #ZD185772, #ZD186301, #L3040)
* Fixed in [1.22.13](/docs/diet-coach-app/1.22-beta/release-notes/#12213-2025-02-22): Sometimes schedule changes result in foods being duplicated across meals. (#ZD185772, #ZD186138, #ZD186228, #L3058)
* Fixed in [1.22.13](/docs/diet-coach-app/1.22-beta/release-notes/#12213-2025-02-22): Can't exit out of the Custom Foods sheet when entering it from the "Me" tab. (#ZD186221, #ZD186247, #ZD186111, #L3066)
* Fixed in [1.22.15](/docs/diet-coach-app/1.22-beta/release-notes/#12215-2025-02-28): Changing the [start/end meal times](/docs/diet-coach-app/1.22-beta/concepts/sleep-and-preferred-meal-time-range/) for one day on the [schedule template](/docs/diet-coach-app/1.22-beta/concepts/schedule/) changes it for all days. (#ZD186766, #ZD186936, #L3077)
* Fixed in [1.22.15](/docs/diet-coach-app/1.22-beta/release-notes/#12215-2025-02-28): Sometimes tapping on a meal in the Schedule will open a different meal. (#ZD185772, #L3078)
* Fixed in [1.22.18](/docs/diet-coach-app/1.22-beta/release-notes/#12218-2025-03-06): Foods cannot be deleted from meals. (#ZD187481, #ZD187548, #ZD187616, #L3087)
* Fixed in [1.22.18](/docs/diet-coach-app/1.22-beta/release-notes/#12218-2025-03-06): The calendar icon at the top of the "Schedule" tab currently doesn't do anything. (#ZD185445, #ZD185470, #ZD185723, #L3092)
* Fixed in [1.22.19](/docs/diet-coach-app/1.22-beta/release-notes/#12219-2025-03-07): Keyboard sometimes covers text input fields. (#ZD185772, #ZD187521, #L3088)
* Fixed in [1.22.20](/docs/diet-coach-app/1.22-beta/release-notes/#12220-2025-04-23): The app will sometimes flicker between screen transitions.
