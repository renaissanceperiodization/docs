---
title:          Auto-Configure
nav_order:      400
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

# Overview

Auto-configure is a powerful feature that allows you to have the RP algorithm reprogram various aspects of your schedule, including adjusting days' target calories and macros, the calories and macros of meals, and the times of meals.

This is especially useful in a number of cases:
1. Your average daily calories are trending away from your target, and you want to adjust the rest of your week to get back on track.
2. You have added, removed, or modified numerous meals--or you have added, removed, or modified workouts or activity levels--and you want to reprogram your meals with optimized macros and timing.
3. You have been checking in your meals over or under their original targets--or you have configured future days' meals over or under--and you're left with a Day Balance that you want to have optimally and holistically redistributed.

In the previous version of the RP Diet Coach app, when you made modifications to your meals, it was up to you to manually adjust the rest of your meals to get ideal timing and get your macros to add up to the day targets.

With Auto-configure, you get any of the benefits of RP programming that you want on demand, rather than only once at Weekly Review.


# Accessing Auto-Configure

1. From the "Schedule" tab, tap on the "..." overflow menu, and select "Auto-configure". (This version preselects only the day you were on, but you can always include any other days in this week.)
2. From the "Edit schedule" or "Weekly Planning" page, tap on the magic wand icon (🪄). (This version preselects all the days of the week, but you can exclude any days you don't want adjusted.)

# Configuration Options

You can choose which parts of the RP algorithm will be used to reprogram your schedule, and you get to select the days you want Auto-configure to run on.

For context, you are presented with the target average daily calories you committed to for the week, the target or actual calories for each day of the week, and what average daily calories you're trending toward.

## Adjust day calories and macros

This option allows the algorithm to adjust the target macros and calories of the selected days to help try to get you to trend toward your target average daily calories for the week. When multiple days are selected, it will scale the allocation of calories between days to your scheduled activities (target steps and workouts).

This can be especially useful if you've eaten way over or under for a day or two and want to get back on track the rest of the week. Or perhaps you want to budget some extra calories for a weekend day, so you want to adjust the previous days to have a lower target.

Another time you will find this option very helpful will be when you're in Weekly Planning. Remember that in Weekly Planning, all your days' target calories _must_ equal your selected target average daily calories. If you're making changes to individual days' targets (including by making adjustments to activity levels or workouts and accepting recommended calorie target changes for those days), it's easy to get your [configured average](/docs/diet-coach-app/1.22-beta/concepts/calories/#configured-average) out of sync with your [target average daily calories](/docs/diet-coach-app/1.22-beta/concepts/calories/#target-average-daily-calories), and "Adjust day calories and macros" will do its best to get them equal, within the bounds of safety and arithmetic possibility!

On its own, this only adjusts the selected days' targets, and if you do not have any unlocked meals on those days (or you have not selected [Adjust macros of unlocked meals](#adjust-macros-of-unlocked-meals)), the difference will be applied to your Day Balance, for you to deal with later.

## Adjust macros of unlocked meals

This option allows the algorithm to adjust the target macros and calories of unlocked meals.

On its own, this is like running "Reallocate" from [Day Balance on the "Schedule" tab](/docs/diet-coach-app/1.22-beta/features/day-balance/#on-the-schedule-tab), but with a few caveats:
* In Reallocate, you can individually specify what meals to reallocate the Day Balance to, including locked meals, but with the Auto-configure option, the only way to exclude a meal from being reprogrammed is by locking it.
* In Reallocate, you can reallocate the Day Balance to any meals in a day that have not been checked in, but with the Auto-configure option, any meals scheduled before the current time (ie, in the past) are not reprogrammed.

As a result, this option is most useful when Auto-configure is run on multiple days at once, and especially in combination with the [Adjust day calories and macros](#adjust-day-calories-and-macros) option, since that can help get day targets and meal targets in alignment with your week's [target average daily calories](/docs/diet-coach-app/1.22-beta/concepts/calories/#target-average-daily-calories).

The main context in which you will find this useful is when you have made multiple edits to multiple days, including adding, removing, and modifying meals and workouts, and you want the RP algorithm to essentially "reset" your target calories and macros to the optimal values in your modified schedule.

## Adjust times of unlocked meals

This option allows the algorithm to adjust the times of unlocked meals.

While it can be run without also selecting [Adjust macros of unlocked meals](#adjust-macros-of-unlocked-meals), it is typically helpful in conjunction with that option, because it allows the algorithm to recommend optimal timing of your nutrients.

However, it can still be valuable on its own: For instance, if you know that you want to exercise more manual control over your meals' calories and macros, and you've added or removed meals to get the right _number_ of meals that you plan to eat (without regard to their times), this option can help recommend times to more evenly space out your meals, avoiding workouts and staying within your specified meal time range.

Note that, like [Adjust macros of unlocked meals](#adjust-macros-of-unlocked-meals), this option will not reschedule meals before the current time (ie, in the past).


# Additional Notes on Behavior and Settings

## Assumptions

When Auto-configure reprograms the remainder of today, any meals that have not been checked in yet but are past their scheduled time will be assumed to have been eaten at the target macros. Therefore, it's a great idea to make sure that all of today's meals that you've already consumed are checked in accurately.

## Meal Preservation and Scheduling Settings

Under the "Me" tab, tap into the "Settings" option, and under "Schedule Edits", you will see two more settings that constrain the Auto-configure algorithm, each of which provides a time offset in half-hour increments before and after the current time:

### Preserve meals older than

This tells Auto-configure which unlocked, un-checked-in meals are eligible for being reprogrammed.

For example, if it's 12:00, and this setting is "-2 hrs", then any meals before 10:00 will not be reprogrammed (deleted or modified) by Auto-configure, regardless of their lock or checked-in status. But if you have a meal at 11:00 that's unlocked and not checked in, Auto-configure will attempt to move it to later in the day, on the assumption that you didn't eat that meal.

### Soonest to schedule new meals

This tells Auto-configure how soon it can start programming new meals.

For example, if it's 10:00, and this setting is "+1 hr", then Auto-configure will only reprogram meals at 11:00 or later.