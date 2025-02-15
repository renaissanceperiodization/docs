---
title:          Copy Day
nav_order:      600
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

"Copy Day" is a powerful feature that allows you to more holistically copy days, either in their entirety or only certain aspects of them.

It can be accessed from the "..." (horizontal kabob) on the "Schedule" tab or using the copy icon from the "Edit schedule" mode.

By default, it copies everything from the "source" day to the selected "destination" day(s).

# Advanced Options

Tap on the "Advanced options" card to configure what things you want to get copied. By default, all options are selected, reflecting that the day should be duplicated exactly.

## Copy macros and calories

This option copies over the target macros and calories from the source day to the destination day(s).

After completing the copy day operation, keep an eye on what [calorie average you're now trending toward](/docs/diet-coach-app/1.22-beta/concepts/calories/#trending-toward-average) and whether that is consistent with your selected [target average daily calories](/docs/diet-coach-app/1.22-beta/concepts/calories/#target-average-daily-calories) for the week. You may consider running [Auto-configure](/docs/diet-coach-app/1.22-beta/features/auto-configure/) if you need to realign these numbers.

## Copy target activity levels

This option copies over your step count target from the source day to the destination day(s). Remember that your step count target factors into how the app calculates how many calories you should be consuming, so if you later run [Auto-configure](/docs/diet-coach-app/1.22-beta/features/auto-configure/) on any of the destination days you selected, it will factor in this step count target.

## Copy first/last available meal times

This option copies over [your preference for the time range](/docs/diet-coach-app/1.22-beta/concepts/sleep-and-preferred-meal-time-range/) in which you would want [Auto-configure](/docs/diet-coach-app/1.22-beta/features/auto-configure/) to reschedule meals.

## Copy meals

This option copies over your meals. At a minimum, it makes sure that the destination days have the same number of meals, times, and lock states. But it can also [copy meal macro targets](#copy-meal-macro-targets) and [copy meals' foods](#copy-foods-in-meals).

## Copy meal macro targets

If you enable this option, it will make the meals on the destination day(s) have the same macro targets as the meals on the source day.

If you don't enable this option, but [Copy meals](#copy-meals) is enabled, then the app will attempt to program macros for the meals on the destination day(s) using the same macro allocation algorithm as [Auto-configure](/docs/diet-coach-app/1.22-beta/features/auto-configure/) uses.

## Copy foods in meals

If you enable this option, all the foods in the source days' meals will get copied over into the meals on the destination day(s).

{: .note-title }
> Pro Tip
> 
> If you want to copy over meals from a previous week to the current week while preserving the RP algorithm's calorie and macro recommendations, copy a day from the previous week into the current week, enable this option, but _disable_ all of the other options:
> * [Copy macros and calories](#copy-macros-and-calories)
> * [Copy target activity levels](#copy-target-activity-levels)
> * [Copy first/last available meal times](#copy-firstlast-available-meal-times) (though this is safe to leave enabled, if you wish)
> * [Copy meal macro targets](#copy-meal-macro-targets)
> * [Copy workouts](#copy-workouts)
> 
> You will have to do this for each day for which you had a distinct meal plan, and unless your calorie and macro recommendations happened to be identical to the previous week's, you'll want to adjust the quantity of the foods in each meal, possibly leveraging the "Rebalance" feature.

## Copy workouts

This option copies over all workouts on the day, including the workout type, time, duration, intensity, and whether it has a shake. Note that shakes that are copied over as part of copying workouts will follow the copy rules for meals that you selected in the options above.