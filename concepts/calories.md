---
title:          Calorie Orientation
nav_order:      200
parent:         Concepts
---

<details open markdown="block">
  <summary>
    &nbsp;Table of Contents
  </summary>
{: .no_toc }
- TOC
{:toc}
</details>

You will notice that calorie counts are now all over the app. Our goal in exposing this information to you directly is to help you to build up your intuition around your caloric needs in achieving your body morphology (or maintenance) goals.

As before, macros are always rounded to the nearest 5 grams. However, with calories, _target_ calories at the week and day levels are rounded to the nearest 100, but when a day is completed (all its meals are checked in), the "actual" calories are rounded to the nearest 5. For purposes of calculating your average calorie consumption trends, the app also rounds to the nearest 100 (so, for instance, if you're only trending away from your targets by an average of 20 calories, it will not tell you that you're off-course).

# Week-Level Calories

Assuming you generally stay within daily macro recommendations (especially protein minima), these numbers are going to be the chief drivers of your diet progress. Note that the app does not specifically deal with week-level aggregates or averages of your macros.

## Target Average Daily Calories

Your "Target Average Daily Calories" is the number of calories you're targeting to consume on an average day for a given week. Whether you accept RP's recommendation (annotated with a red badge in the dropdown when you're editing your programmed schedule, either during a week or during Weekly Planning) or select your own value, this number sets the context or goal for the week.

## Trending-Toward Average

As you go through the week and check in meals, the app is keeping track of whether you're actually trending toward your target average daily calories or away from it. When you finish checking in meals for a day, the app will use the calories you reported consuming that day, along with the _target_ calories of other "unfinished" days in the week, to calculate the average daily calories you're _trending toward_. If you're trending away from your target average daily calories, the app will signal that to you on the Coaching tab, providing you with options on addressing that (eg, adjusting the target calories for other days in the week or changing your target average daily calories at the week level).

When you're editing your schedule mid-week (that is, outside of Weekly Planning), you are provided with information about both your target average daily calories (which you can select directly) and also the average that you're trending toward. If these numbers are not equal, that's where you can make adjustments to the calorie targets of the remaining days in the week to get your "trending-toward average" to equal your selected target average daily calories.

{: .note-title }
> How the "Trending-Toward Average" is Calculated
> 
> TL;DR: The app averages all of your days' target calories, but will replace a day's targets in the calculation with the sum of the day's checked-in meals, once all meals for the day have been checked in.
> 
> At the start of a week, just after you complete Weekly Planning, all of your days' targets average out to your target average daily calories. (See [Configured Average](#configured-average) below.) So the app regards you as trending toward your target, assuming you're going to live up to your daily calorie intentions.
> 
> When you check in all the meals for a day, when computing the average that you're trending toward, the RP algorithm uses the actual sum of the calories of the checked-in meals for that day instead of the day's explicitly configured targets. If you do a good job of following the app's recommendations, these numbers will be close to the same, but if you've veered off course (reflected in finishing a day with a significant [Day Balance](/diet/features/#day-balance)), this can cause you to trend away from your target average daily calories.
>
> Let's use a simple concrete example: You started the week with target average daily calories at 2000, and every day's targets is similarly at 2000. You've finished checking in your meals on Monday, and let's say that you ate 1995 calories. The app will average your actual calories from Monday (1995) with the target calories of the remaining days (all of which are 2000). That means that you're now trending toward a 1999 average, but that's within 100 calories of your selected 2000 target average daily calories, so the app will not report that you are trending away from your target.
>
> Now, let's say that you overate on Tuesday, eating 2700 calories instead of Tuesday's 2000 target. After checking in all of Tuesday's meals, the app will now average the actually consumed 1995 from Monday and 2700 from Tuesday with the remaining 2000 per day for the remaining 5 days of the week, and it will report that you are now trending toward 2100 calories (2099 rounded to the nearest 100). Since that's 100 or more away from your target average daily calories, the app will let you know that you're trending off course.

## Configured Average

When you're in Weekly Planning, however, the targets that you configure for individual days (the "configured average") must average out to your selected target average daily calories--in other words, your target has to be your target! You cannot save and continue past Weekly Planning if your days' targets don't average out to your target average daily calories. You can make sure that they're equal, either by changing your days' targets (which can also be achieved through the Auto-Configure feature) or by changing your target average daily calories.

# Day-Level Calories and Macros

An individual day has both calorie and macro targets. These are typically programmed by the RP algorithm at the time of Weekly Planning, but they can be overridden in advance in the schedule template (preventing the RP algorithm from automatically programming values) or after they've been programmed, by editing the schedule, either during Weekly Planning or during the week itself.

When the RP algorithm programs your day targets, it attempts to take into account any overrides you've specified in your schedule template to program the rest of the days in a way that (1) hits your target average daily calories for the week and (2) scales calories and macros on the basis of each day's activity levels (target step count and scheduled workouts).

A feature you will likely be interacting with a significant amount is your [Day Balance](/diet/features/#day-balance). This represents the difference between a day's target calories/macros and the sum of all the meals' target calories/macros. Essentially, this tells you how much your planned meals, taken all together, are over or under, relative to your day's targets, and it allows you to more flexibly reallocate calories/macros between meals on the same day. Note that the Day Balance does _not_ carry over to another day--if you have eaten significantly over or under on a particular day, that is reflected in a change to your "trending-toward average", once you've checked in all the day's meals.

Note that unlike the current publicly available version of the RP Diet Coach app, you no longer need to painstakingly align all your meals' targets so that they sum up to your day targets.

# Meal-Level Calories and Macros

Individual meals also have their own calorie and macro targets. These are also typically programmed by the RP algorithm at the time of Weekly Planning, but they can be overridden in advance in the schedule template by creating a "manually specified meal" or after they've been programmed, by editing the schedule, either during Weekly Planning or during the week itself. Unlike day targets, meal calorie and macro targets can be be edited from the schedule directly (without going into schedule editing mode) or from inside the meal.

When you edit the target calories and macros for a meal, your change will also be reflected in your [Day Balance](/diet/features/#day-balance). For example, if you increase your protein for a meal by 10 grams (reflecting a corresponding increase by 40 calories), your [Day Balance](/diet/features/#day-balance) will decrease by 10 grams of protein and 40 calories.

Note that when you start adding foods to a meal, you will also see what would happen to your [Day Balance](/diet/features/#day-balance) if you were to check in the meal with those added foods.

Before a meal is checked in, it has separate values for the added foods (the numerators) and the targets (denominators). After checking in, the numerator and denominators are equalized, either by implicitly adding unspecified "manual macros" (most useful for folks who don't always interact with foods directly) or by adjusting the targets to reflect the added foods and allocation the over/under to the [Day Balance](/diet/features/#day-balance). In a way, this parallels how a day's calories and macros are treated: As soon as a day's meals are all checked in, the sum of the checked in meals is what matters to comparing to the week-level target (the target average daily calories), not what the day's targets were previously configured to be.

# Calorie-Impacting Changes

As you go about running your diet, _life happens_, and you may need to make adjustments to your schedule. Or perhaps that workout was longer or shorter or more difficult or easier than you expected. Maybe you got more or fewer steps than you anticipated. No problem. When you make certain kinds of changes, if the RP algorithm believes you should have more or fewer calories, you'll be prompted with the option of adjusting your day's target calories and macros. If you accept the adjustment, the difference will be applied to your [Day Balance](/diet/features/#day-balance); or if that would be too disruptive for you (for instance, all your meals are already prepped!), you can decline the adjustment.

Here are the changes to which this might apply:
* increasing or decreasing your target step count
* adding or removing a workout
* changing the duration of a workout
* changing the intensity of a workout

Note that if the magnitude of the change is small enough and depending on how numbers average and round, the RP algorithm may not recommend any adjustment.