---
title:          Day Balance
nav_order:      300
parent:         Features
---

<details open markdown="block">
  <summary>
    &nbsp;Table of Contents
  </summary>
{: .no_toc }
- TOC
{:toc}
</details>

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

# On the Schedule tab
On the Schedule tab, the Day Balance is pinned to the bottom of the screen, and you will see that it has a "Reallocate" button. This functionality allows you to select the remaining meals in the day that you want to add or remove macros from, and the app does its best to zero out your Day Balance.

# On a Meal page
When you're on a meal page, the Day Balance is adaptive: In an empty meal, the Day Balance just shows the Day Balance, but after you start adding foods, the Day Balance shows you a "draft state", what your Day Balance would be if you checked in the meal using the "Allocate difference to Day Macro Balance" option. This can be especially useful if you're adding foods and want to use up your positive Day Balance or if you're already in the hole and need to eat less in remaining meals, but want to try to construct reasonable, modest meals on the fly. If at any point you're happy with the "draft state", but you're not ready to check in the meal, you can commit that intention and quickly adjust your meal targets to reflect only the added foods by using the "Reallocate to day balance" option in the overflow menu.

Alternatively, if you want to try to zero out your Day Balance into the current meal (the same as using the "Reallocate" button from the Schedule tab and selecting only that meal), you can use the "Absorb day balance" option from the overflow menu. This will change the meal's target macros, but note that the Day Balance will still show a draft state based on the added foods.

If you "Save" a meal without checking it in and your added foods' macros don't sum up to the meal's target macros, you'll notice that the Day Balance on the Schedule will not show the draft state you saw in the meal.

# On a Meal Macro Edit sheet
If you're directly editing a meal's macros (eg, by long-pressing a meal on the Schedule and selecting "Edit target macros and time"), the Day Balance will also show a draft state, but this will be a draft state based on your explicit changes to the meal's macro targets, _not_ relative to any added foods. This draft state will be saved when you tap "Save" on this sheet.

In this context, the Day Balance also has two buttons:
1. **Push to Meal**<br />
    This has the same effect as the "Absorb day balance" option from a meal page: It takes the Day Balance and adds any surplus macros to the meal and deducts any deficit from the meal.
2. **Pull**<br />
    This has the same effect as the "Reallocate to day balance" option from a meal page: Even though you don't see the added foods in this context, it takes any leftover macros (relative to the meal targets) and adds them to the Day Balance (or deducts any macro overages from the Day Balance).