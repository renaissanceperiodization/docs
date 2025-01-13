---
title:          Features
nav_order:      400
parent:         Diet Coach App 1.22 Beta
has_children:   true
---

<details open markdown="block">
  <summary>
    &nbsp;Table of Contents
  </summary>
{: .no_toc }
- TOC
{:toc}
</details>

# Weekly Review and Weekly Planning

What was previously just called "Weekly Review" is now split up into two, more clearly distinct steps:
1. Weekly Review, in which
    1. you make sure to have given the app all the information you have about your eating and weigh-ins, and
    2. the app provides a review of your progress
2. Weekly Planning, in which 
    1. the app uses your schedule template to program your upcoming week based on the RP-recommended target average daily calories, and
    2. you optionally adjust your upcoming week's target average daily calories and schedule as needed

You are eligible to start Weekly Review and Planning any day Friday through Sunday, to review the week since Monday and to plan the week starting on the upcoming Monday. You can enter Weekly Review and Planning through the banner you'll see at the top of the Schedule tab. (Note that if you started your diet on a Thursday or later and it's your first week, you'll be eligible for your first Weekly Review and Planning starting the following Friday.)

If you haven't checked in all your meals up to the day before you start Weekly Review, you'll be prompted to check in those meals. Similarly, if you haven't provided the app enough weigh-ins, you'll be prompted to provide weigh-in data as well.

After that, the app will summarize your progress for you so that you can see how you're tracking against your diet goal (which you can also modify from this screen).

In the Weekly Planning step, you are essentially editing your schedule, using the same interface that you would use to edit the schedule in the middle of a week. The chief difference is that, during Weekly Planning, your days' target calories must average out to the selected target average daily calories.

Weekly Planning starts with target average daily calories that are recommended by the RP algorithm, which is annotated with the red shield. If you select a different number of average calories, the app will not automatically change the target calories for any of the days. You will need to get these in sync, either by
1. using the Auto-Configure functionality, which can adjust any unlocked days' targets
2. manually adjusting days' targets until the configured average equals the target average daily calories

However, before running Auto-Configure, it's a good idea to review your schedule (number of meals, workouts and their parameters, etc), and only then run Auto-Configure, since that powerful function can dramatically simplify reprogramming based on RP recommended optimizations while respecting your schedule and locked preferences.

When you're satisfied with your schedule, tap "Save". Unlike the current publicly available version of the app, there's never a need to "redo" your Weekly Review or Planning, since at any point, you are able to edit your schedule and make adjustments (including changing your target average daily calories and running or re-running Auto-Configure).

# Checking In Meals

In the new version, there is a major shift in meal checkins: You no longer check in meals, loosely "at macros", "below macros", or "over macros". Instead, you report the macros that you actually consumed.

There are two ways to check in a meal:
1. From the Schedule tab, swipe the meal to the right. If you do a long-swipe, the check-in action sheet will come up. If you do a partial-swipe, you then tap on the green "Check-in" button that's revealed.
2. From a meal page, tap the "Check in" button pinned to the bottom of the page.

There are three forms of checkins:
1. **Manually specify macros**<br />
    If you do not typically interact with foods in the app and just know what macros you've eaten (and they're different from the target macros from the meal), use this option. It will open a sheet that allows you to specify the exact macros that you consumed without needing to specify the foods. If you've already added foods to your meal, they will stay there, but your manually specified macros will override the summation of the foods' macros and create a "Manual Macros" entry in the meal as though it were a food item.
2. **Check in at target macros**<br />
    Use this option in one of two situations:
    1. You've eaten the foods you've added to the meal, and their macros sum up to the meal's targets.
    2. You've know you've eaten the target macros for the meal, but you've only logged some of the foods you ate and don't want to bother with logging the rest.
3. **Allocate difference to Day Macro Balance**<br />
    Use this option if the foods you added to the meal reflect what you actually ate, you're done with that meal, and you've gone over or under on any of the macros. In that case, whatever extent you've gone over or under on any macro will be deducted or added, respectively, to your [Day Balance](/diet/features/#day-balance). This allows you to later reallocate the macros across the remaining meals in the day.

If you've made a mistake, you can go back to the meal page and use the "Remove Check in" button, but keep in mind that it will not revert your meal targets to what they were before the checkin.

# Day Balance

The Day Balance is a feature that addresses a major challenge in the current publicly available app: redistributing macros across meals. It support two main scenarios:
1. As you go through the day, you're eating some amount over and under the target macros for your scheduled meals. If you're checking in using "Allocate difference to Day Macro Balance", your Day Balance will reflect how many macros and calories you have available or how much you've gone over. You can then use various operations to automatically or manually adjust the target macros for remaining meals.
2. You know in advance that you want some macros reserved for more flexible eating (such as supporting a snack). When you configure your schedule, you make sure that the macros for meal targets sum up to less than the day's targets.

Think of the Day Balance as your "swap space", "snack bucket", or "flex macros".

{: .note-title }
> Pro Tip
> 
> Remember that the primary driver of achieving your dietary goals is hitting the right number of calories. And it's also important to make sure that you get at least the minimum amount of protein per day. Because most people don't typically struggle to get the minimum amount of fat required for health, and because (within limits) insufficient carbs doesn't have a disastrous effect on body composition goals, a useful rule of thumb is as follows:
> 
> Get your Day Balance calories as close to 0 as possible, and make sure that your protein number is not positive (meaning that you aren't under-eating protein).

## On the Schedule tab
On the Schedule tab, the Day Balance is pinned to the bottom of the screen, and you will see that it has a "Reallocate" button. This functionality allows you to select the remaining meals in the day that you want to add or remove macros from, and the app does its best to zero out your Day Balance.

## On a Meal page
When you're on a meal page, the Day Balance is adaptive: In an empty meal, the Day Balance just shows the Day Balance, but after you start adding foods, the Day Balance shows you a "draft state", what your Day Balance would be if you checked in the meal using the "Allocate difference to Day Macro Balance" option. This can be especially useful if you're adding foods and want to use up your positive Day Balance or if you're already in the hole and need to eat less in remaining meals, but want to try to construct reasonable, modest meals on the fly. If at any point you're happy with the "draft state", but you're not ready to check in the meal, you can commit that intention and quickly adjust your meal targets to reflect only the added foods by using the "Reallocate to day balance" option in the overflow menu.

Alternatively, if you want to try to zero out your Day Balance into the current meal (the same as using the "Reallocate" button from the Schedule tab and selecting only that meal), you can use the "Absorb day balance" option from the overflow menu. This will change the meal's target macros, but note that the Day Balance will still show a draft state based on the added foods.

If you "Save" a meal without checking it in and your added foods' macros don't sum up to the meal's target macros, you'll notice that the Day Balance on the Schedule will not show the draft state you saw in the meal.

## On a Meal Macro Edit sheet
If you're directly editing a meal's macros (eg, by long-pressing a meal on the Schedule and selecting "Edit target macros and time"), the Day Balance will also show a draft state, but this will be a draft state based on your explicit changes to the meal's macro targets, _not_ relative to any added foods. This draft state will be saved when you tap "Save" on this sheet.

In this context, the Day Balance also has two buttons:
1. **Push to Meal**<br />
    This has the same effect as the "Absorb day balance" option from a meal page: It takes the Day Balance and adds any surplus macros to the meal and deducts any deficit from the meal.
2. **Pull**<br />
    This has the same effect as the "Reallocate to day balance" option from a meal page: Even though you don't see the added foods in this context, it takes any leftover macros (relative to the meal targets) and adds them to the Day Balance (or deducts any macro overages from the Day Balance).

# Auto-Configure

# AI Scanner

# Apple Health for Steps and Weight (iOS only)