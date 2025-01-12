---
title:          Concepts
nav_order:      300
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

# Programmed Schedule and the Schedule Template

{: .note-title }
> Summary of Key Points
> - The schedule template is your “idealized” Monday through Sunday and serves as a blueprint for the RP Diet Coach app to program your actual schedule, including target daily macros and meals for each week.
> - You can manually specify target macros for any day or meal within the schedule template, which the RP algorithm will then incorporate into its programming during Weekly Planning.
> - Changes made to the schedule template won't affect any already-programmed weeks, but will be used for the next Weekly Planning session.
> - The schedule template can be edited at any time during your diet, but it's best used for changes expected to apply to most or all future weeks.
> - One-off changes for a specific week should be made directly in your schedule during the current week or during the Weekly Planning for the upcoming week.
    
When you start a diet, you will be asked a series of questions about your lifestyle and typical schedule for each day of the week, including when you work out, how many steps you plan to take, how many meals you want to eat, and within what time range you want the app to automatically program meals for you.
    
This process creates a schedule template that's saved and then used as a blueprint for planning your actual schedule for any upcoming week during Weekly Planning.
    
The schedule template reflects your idealized schedule, so its days, Monday through Sunday, are not attached to specific calendar days. Moreover, by default, the schedule template does not have target macros at the week, day, or meal levels, nor does it have information about specific meal times. These values are programmed by the RP algorithm during Weekly Planning, based on your progress and what is recommended by the best scientific literature available.
    
However, to accommodate varying lifestyles and individualized needs, you can use the schedule template editor to manually specify the target total macros for any given day of the week, as well as any meals that you want to have at particular times with particular macros. When you go through Weekly Planning, whether at the start of your diet or between weeks, the RP algorithm will program the rest of your days’ target macros and remaining meals around the constraints you've specified in your schedule template.
    
For example, if you’re running a fat-loss diet and you know that you are most successful with adherence if you can eat 4000 calories on Saturdays, you can specify that in the template.
    
Or perhaps you know that you always need to have the same pre-bed meal Monday through Friday with specific macros at a specific time: You can add a manual meal that has 25 grams of protein, 0 grams of carbs, and 0 grams of fat, scheduled for 9pm. This will create a “locked” meal in your template that the algorithm will not modify when your schedule is programmed or during automatic configuration.
    
The schedule template editor is powerful, so you must be careful about adding too many days with manual macro targets or too many manually specified meals. Doing so will limit the RP algorithm's ability to program the rest of your days and meals to allow you to achieve your diet goals.
    
During initial diet setup and every weekend, you will go through Weekly Planning, in which the RP algorithm takes your schedule template and then programs your days’ calorie targets and meals based on the RP-recommended target average daily calories that will help you reach your diet goal.
    
In Weekly Planning, you can edit the fully programmed schedule for only the upcoming week. Any changes you make to your schedule in Weekly Planning are _not_ saved to your schedule template.
    
Similarly, once you’re running your diet, you can make schedule edits on the fly (eg, add, remove, or modify meals or workouts), and these changes also do _not_ affect your template. When you get to Weekly Planning for the upcoming week, the schedule for that next week will start off with a freshly programmed version of your schedule template.
    
## FAQs
{: .no_toc }
    
### Can I schedule a manual meal outside of the first/last meal range?

Yes. You can always manually schedule or reschedule any meal outside the range you specified for the algorithm’s automatic programming. This applies to manual meals in the schedule template, as well as to any meals you edit in your schedule during Weekly Planning or when you’re running your diet.

### If I manually specify a meal on a particular day, does that count as one of however many meals I said I wanted to eat that day?
    
Yes, and this is true regardless of whether you scheduled that manual meal inside the first/last meal range. For example, if you said that you want to eat 4 meals on Wednesdays, to be programmed between 9am and 10pm, and you manually specified 2 meals with particular macros, one at 1pm and another at 11pm, when you go through Weekly Planning, the RP algorithm will schedule only 2 additional meals for you, and they will be constrained to the 9am to 10pm window you specified.

### Can I manually specify macros for workout shakes?
    
Yes. Because shakes are tightly coupled with workouts, you can accomplish this through the workout editor, and if you do specify those macros manually, they will appear on the shake card that’s attached to your workout, rather than in the “Meals” section of the schedule template editor. Note that, unlike other meals, shakes do _not_ count against the total number of meals you set for a day.

### Why can’t I edit my weigh-in times in the schedule template editor?
    
While weigh-ins show up on your schedule as you’re running your diet, they do not appear in the schedule editor, in Weekly Review, or in the template editor. It is crucial that you are extremely consistent about weighing yourself under conditions that are as close to identical to one another as possible; as a result, the app discourages rescheduling your weigh-in times in the middle of your diet. If you must change your weigh-in times, you can find that in the app settings.

### I manually specified target macros and calories for a particular day, but I want to clear those values. How do I do that?
    
Unlike manually added meals (which you can delete using the “Delete meal” option under its vertical kabob overflow menu), to clear the manually specified target macros and calories at the day level, you use the horizontal kabob overflow menu at the top of the day and select “Clear day target macros”.

### Can I specify just the target calories for a day without specifying the target macros?
    
No. If you specify target calories, the RP algorithm will pre-populate recommended macros in the respective fields, but you cannot leave those fields blank. The app will also not allow you to select values for any macros that are below safety limits. If you do not set values for all macros, no macros will be saved into your template for that day, and all macro and calorie values will be cleared when you tap into a different element on the screen.

### Can I specify only some of the macros for a meal?
    
No. As with day targets, you must specify all macros to save a manual meal into your template, but unlike day targets, if you leave any meal macro empty, it will be set to 0.

### What happens if I start my diet on a day other than Monday?
    
If you start your diet on any day other than Monday, your first Weekly Planning will include the remaining days of the week through Sunday, plus the full next week of Monday through Sunday. For example, if you start your diet on a Thursday, your first Weekly Planning will include Thursday to Sunday of the current week, as well as the full Monday through Sunday of the following week, for a total of 11 days, which you would scroll through in the day carousel at the top of various views, including your main schedule view as you’re running your diet. Note that your schedule template will be used as the blueprint for both Thursdays, both Fridays, both Saturdays, and both Sundays of this first 11-day cycle.

### How do I edit my schedule template in the middle of my diet?
    
Find the "Edit Schedule Template" option on the "Me" tab. This is the current location of this functionality, so as to not be confused with making schedule edits to the current week from the Schedule tab.

### What happens if I edit my schedule template in the middle of my diet?
    
Any already-programmed weeks are not affected: The current week (what you see in your Schedule tab) is never affected. If you have _not_ yet done Weekly Planning for the following week, then schedule template edits _will_ be used as the baseline for that week’s planning. Conversely, if you _have_ already completed Weekly Planning for the next week, then any schedule template edits will _not_ affect next week’s schedule, but they _will_ apply to Weekly Planning for the following week.
    
For example, let’s say that today is Friday, January 5 for the week of January 1-7. If you have _not_ yet done Weekly Planning for January 8-14 and you make changes to your schedule template, then your edits _will_ be used to program that upcoming week. But if you _have_ already done your Weekly Planning for January 8-14 and you make changes to your schedule template, then your edits will only be used as the blueprint for Weekly Planning for January 15-21.

### When should I edit my schedule, and when should I edit my schedule template?
    
This is really a judgement call for you to make. Individual meals, workouts, and other aspects of your schedule don’t have “recurrence” settings the way that events in most calendaring applications do; instead, you use the schedule template to convey roughly the same idea, and that template is applied to each future week that you plan with the help of the RP algorithm’s programming.
    
If you want to make edits that you expect to apply to most or all future weeks, editing your schedule template is probably a better bet, so that you don’t have to repeatedly make the same changes in each future Weekly Planning.
    
By contrast, if you have one-off changes that apply to only the current or upcoming week (or to only a few upcoming weeks), then you might prefer to make such changes in your schedule while running your diet for the current week (if it’s a change you couldn’t anticipate, such as suddenly getting sick) or during Weekly Review for the upcoming week (if it’s a change you planned for, such as travel or working around an appointment).

# Calorie Orientation

You will notice that calorie counts are now all over the app. Our goal in exposing this information to you directly is to help you to build up your intuition around your caloric needs in achieving your body morphology (or maintenance) goals.

As before, macros are always rounded to the nearest 5 grams. However, with calories, _target_ calories at the week and day levels are rounded to the nearest 100, but when a day is completed (all its meals are checked in), the "actual" calories are rounded to the nearest 5. For purposes of calculating your average calorie consumption trends, the app also rounds to the nearest 100 (so, for instance, if you're only trending away from your targets by an average of 20 calories, it will not tell you that you're off-course).

## Week-Level Calories

Assuming you generally stay within daily macro recommendations (especially protein minima), these numbers are going to be the chief drivers of your diet progress. Note that the app does not specifically deal with week-level aggregates or averages of your macros.

### Target Average Daily Calories

Your "Target Average Daily Calories" is the number of calories you're targeting to consume on an average day for a given week. Whether you accept RP's recommendation (annotated with a red badge in the dropdown when you're editing your programmed schedule, either during a week or during Weekly Planning) or select your own value, this number sets the context or goal for the week.

### Trending-Toward Average

As you go through the week and check in meals, the app is keeping track of whether you're actually trending toward your target average daily calories or away from it. When you finish checking in meals for a day, the app will use the calories you reported consuming that day, along with the _target_ calories of other "unfinished" days in the week, to calculate the average daily calories you're _trending toward_. If you're trending away from your target average daily calories, the app will signal that to you on the Coaching tab, providing you with options on addressing that (eg, adjusting the target calories for other days in the week or changing your target average daily calories at the week level).

When you're editing your schedule mid-week (that is, outside of Weekly Planning), you are provided with information about both your target average daily calories (which you can select directly) and also the average that you're trending toward. If these numbers are not equal, that's where you can make adjustments to the calorie targets of the remaining days in the week to get your "trending-toward average" to equal your selected target average daily calories.

{: .note-title }
> How the "Trending-Toward Average" is Calculated
> 
> TL;DR: The app averages all of your days' target calories, but will replace a day's targets in the calculation with the sum of the day's checked-in meals, once all meals for the day have been checked in.
> 
> At the start of a week, just after you complete Weekly Planning, you're trending toward your target average daily calories. This is because, to save your programmed schedule in Weekly Planning, it doesn't make sense to have day targets that don't equal your week targets. (See [Configured Average](#configured-average) below.)
> 
> When you check in all the meals for the day, when computing the average that you're trending toward, the RP algorithm uses the actual sum of the calories of the checked-in meals for that day instead of the day's explicitly configured targets. If you do a good job of following the app's recommendations, these numbers will be close to the same, but if you've veered off course (reflected in finishing a day with a significant [Day Balance](/diet/features/#day-balance)), this can cause you to trend away from your target average daily calories.
>
> Let's use a simple concrete example: You started the week with target average daily calories at 2000, and every day's targets is similarly at 2000. You've finished checking in your meals on Monday, and let's say that you ate 1995 calories. The app will average your actual calories from Monday (1995) with the target calories of the remaining days (all of which are 2000). That means that you're now trending toward a 1999 average, but that's within 100 calories of your selected 2000 target average daily calories, so the app will not report that you are trending away from your target.
>
> Now, let's say that you overate on Tuesday, eating 2700 calories instead of Tuesday's 2000 target. After checking in all of Tuesday's meals, the app will now average the actually consumed 1995 from Monday and 2700 from Tuesday with the remaining 2000 per day for the remaining 5 days of the week, and it will report that you are now trending toward 2100 calories (2099 rounded to the nearest 100). Since that's 100 or more away from your target average daily calories, the app will let you know that you're trending off course.

### Configured Average

When you're in Weekly Planning, however, the targets that you configure for individual days (the "configured average") must average out to your selected target average daily calories--in other words, your target has to be your target! You cannot save and continue past Weekly Planning if your days' targets don't average out to your target average daily calories. You can make sure that they're equal, either by changing your days' targets (which can also be achieved through the Auto-Configure feature) or by changing your target average daily calories.

## Day-Level Calories and Macros

An individual day has both calorie and macro targets. These are typically programmed by the RP algorithm at the time of Weekly Planning, but they can be overridden in advance in the schedule template (preventing the RP algorithm from automatically programming values) or after they've been programmed, by editing the schedule, either during Weekly Planning or during the week itself.

When the RP algorithm programs your day targets, it attempts to take into account any overrides you've specified in your schedule template to program the rest of the days in a way that (1) hits your target average daily calories for the week and (2) scales calories and macros on the basis of each day's activity levels (target step count and scheduled workouts).

A feature you will likely be interacting with a significant amount is your [Day Balance](/diet/features/#day-balance). This represents the difference between a day's target calories/macros and the sum of all the meals' target calories/macros. Essentially, this tells you how much your planned meals, taken all together, are over or under, relative to your day's targets, and it allows you to more flexibly reallocate calories/macros between meals on the same day. Note that the Day Balance does _not_ carry over to another day--if you have eaten significantly over or under on a particular day, that is reflected in a change to your "trending-toward average", once you've checked in all the day's meals.

Note that unlike the current publicly available version of the RP Diet Coach app, you no longer need to painstakingly align all your meals' targets so that they sum up to your day targets.

## Meal-Level Calories and Macros

Individual meals also have their own calorie and macro targets. These are also typically programmed by the RP algorithm at the time of Weekly Planning, but they can be overridden in advance in the schedule template by creating a "manually specified meal" or after they've been programmed, by editing the schedule, either during Weekly Planning or during the week itself. Unlike day targets, meal calorie and macro targets can be be edited from the schedule directly (without going into schedule editing mode) or from inside the meal.

When you edit the target calories and macros for a meal, your change will also be reflected in your [Day Balance](/diet/features/#day-balance). For example, if you increase your protein for a meal by 10 grams (reflecting a corresponding increase by 40 calories), your [Day Balance](/diet/features/#day-balance) will decrease by 10 grams of protein and 40 calories.

Note that when you start adding foods to a meal, you will also see what would happen to your [Day Balance](/diet/features/#day-balance) if you were to check in the meal with those added foods.

Before a meal is checked in, it has separate values for the added foods (the numerators) and the targets (denominators). After checking in, the numerator and denominators are equalized, either by implicitly adding unspecified "manual macros" (most useful for folks who don't always interact with foods directly) or by adjusting the targets to reflect the added foods and allocation the over/under to the [Day Balance](/diet/features/#day-balance). In a way, this parallels how a day's calories and macros are treated: As soon as a day's meals are all checked in, the sum of the checked in meals is what matters to comparing to the week-level target (the target average daily calories), not what the day's targets were previously configured to be.

## Calorie-Impacting Changes

As you go about running your diet, _life happens_, and you may need to make adjustments to your schedule. Or perhaps that workout was longer or shorter or more difficult or easier than you expected. Maybe you got more or fewer steps than you anticipated. No problem. When you make certain kinds of changes, if the RP algorithm believes you should have more or fewer calories, you'll be prompted with the option of adjusting your day's target calories and macros. If you accept the adjustment, the difference will be applied to your [Day Balance](/diet/features/#day-balance); or if that would be too disruptive for you (for instance, all your meals are already prepped!), you can decline the adjustment.

Here are the changes to which this might apply:
* increasing or decreasing your target step count
* adding or removing a workout
* changing the duration of a workout
* changing the intensity of a workout

Note that if the magnitude of the change is small enough and depending on how numbers average and round, the RP algorithm may not recommend any adjustment.

# Weight Logging

The RP Diet Coach app now recommends daily weigh-ins. During setup, you will specify what time of day you plan to weigh in (which will be the same time every day), but you can always change that by going to the "Me" tab → "Settings" → "Weigh Ins" → "Weigh In Time".

In order for the app to be able to recommend any change in calories from one week to the next, you must log your weight on at least 4 different days during the week. Otherwise, during Weekly Planning, the RP algorithm will recommend the same target average daily calories that it did the previous week.

# Locks and Pins

Locks are persistent, and pins are ephemeral: When you lock a value, it persists until you explicitly unlock it. By contrast, pins persist only as long as a given editing session.

## Locks

The fundamental purpose of locks is for you, the user, to prohibit any automatic programming or other "automagical" functions of the app from changing values that you set. You are always able to override your own locks.

You can lock the following items:
* day calorie/macro targets (either in your programmed schedule or in the schedule template)
* meals, which locks its calorie/macro targets (either in your programmed schedule or in the schedule template by creating a "manually specified meal")
* foods (in meals)

Locking day or meal targets prevents them from being touched by the RP algorithm, including when you use the Auto-Configure feature.

However, when you use the Reallocate or Copy Foods features, you can modify locked meals, since you are permitted to take explicit actions to override your own locks.

In the context of a meal, locking a food works the same as it does in the current publicly available version of the app: It prevents the Rebalance feature from changing the food's quantity.

## Pins

When you're editing the target calories and macros for either a day or a meal, you will be presented with a view that shows sliders for each value, with a pin next to it. The pin allows you to hold that value constant, as you vary the other values. For instance, for a given day or meal, you might want to hold total calories and protein fixed, but easily "flex" between carbs and fat. You would pin calories and protein, and then use the slider to adjust your carbs or fat, and then the value for the other of carbs or fat would change accordingly, to keep you at the same number of total calories.

As soon as you save, the pins are cleared.