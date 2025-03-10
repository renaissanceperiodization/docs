---
title:          Checking In Meals
nav_order:      200
parent:         Features
---

In the new version, there is a major shift in meal checkins: You no longer check in meals, loosely "at macros", "below macros", or "over macros". Instead, you report the macros that you actually consumed, whether in the form of adding foods to a meal or by attesting to consuming specific macros.

Meal check-ins are now required because the app's algorithm has been significantly upgraded to factor in your actual calorie intake in addition to your weekly weight changes when adjusting your macros.

In previous versions, weekly updates assumed you ate close to your prescribed macros, regardless of how much you actually consumed. Now, the app directly accounts for how much you're eating and how your body responds. This means it can calibrate more precisely to your metabolism and make smarter adjustments.

If you eat over or under your [target average daily calories](/docs/diet-coach-app/1.22-beta/concepts/calories/#target-average-daily-calories) for a given week, the app will factor that into its recommendations--helping you stay on track with better precision. This ensures that your calorie and macro updates align more closely with your actual intake and results, making it easier to dial in your nutrition for optimal progress.

There are two ways to check in a meal:
1. From the "Schedule" tab, swipe the meal to the right. If you do a long-swipe, the check-in action sheet will come up. If you do a partial-swipe, you then tap on the green "Check-in" button that's revealed.
2. From a meal page, tap the "Check in" button pinned to the bottom of the page.

There are three forms of check-ins:
1. **Manually specify macros**<br />
    If you do not typically interact with foods in the app and just know what macros you've eaten (and they're different from the target macros from the meal), use this option. It will open a sheet that allows you to specify the exact macros that you consumed without needing to specify the foods. If you've already added foods to your meal, they will stay there, but your manually specified macros will override the summation of the foods' macros and create a "Manual Macros" entry in the meal as though it were a food item.
2. **Check in at target macros**<br />
    Use this option in one of two situations:
    1. You've eaten the foods you've added to the meal, and their macros sum up to the meal's targets.
    2. You've know you've eaten the target macros for the meal, but you've only logged some of the foods you ate and don't want to bother with logging the rest.
3. **Allocate difference to Day Macro Balance**<br />
    Use this option if the foods you added to the meal reflect what you actually ate, you're done with that meal, and you've gone over or under on any of the macros. In that case, whatever extent you've gone over or under on any macro will be deducted or added, respectively, to your [Day Balance](/docs/diet-coach-app/1.22-beta/features/day-balance/). This allows you to later reallocate the macros across the remaining meals in the day.

If you've made a mistake, you can go back to the meal page and use the "Remove Check in" button, but keep in mind that it will not revert your meal targets to what they were before the check-in.