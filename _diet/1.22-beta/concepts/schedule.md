---
title:          Programmed Schedule and the Schedule Template
nav_order:      100
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

{: .note-title }
> Summary of Key Points
> - The schedule template is your “idealized” Monday through Sunday and serves as a blueprint for the RP Diet Coach app to program your actual schedule, including target daily macros and meals for each week.
> - You can manually specify target macros for any day or meal within the schedule template, which the RP algorithm will then incorporate into its programming during Weekly Planning.
> - Changes made to the schedule template won't affect any already-programmed weeks, but will be used for the next Weekly Planning session.
> - The schedule template can be edited at any time during your diet, but it's best used for changes expected to apply to most or all future weeks.
> - One-off changes for a specific week should be made directly in your schedule during the current week or during the Weekly Planning for the upcoming week.

# Overview
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
    
# FAQs
    
## Can I schedule a manual meal outside of the first/last meal range?

Yes. You can always manually schedule or reschedule any meal outside the range you specified for the algorithm’s automatic programming. This applies to manual meals in the schedule template, as well as to any meals you edit in your schedule during Weekly Planning or when you’re running your diet.

## If I manually specify a meal on a particular day, does that count as one of however many meals I said I wanted to eat that day?
    
Yes, and this is true regardless of whether you scheduled that manual meal inside the first/last meal range. For example, if you said that you want to eat 4 meals on Wednesdays, to be programmed between 9am and 10pm, and you manually specified 2 meals with particular macros, one at 1pm and another at 11pm, when you go through Weekly Planning, the RP algorithm will schedule only 2 additional meals for you, and they will be constrained to the 9am to 10pm window you specified.

## What rules does the RP algorithm use to program the times of my meals?
* A meal is implicitly considered to be a 30-minute event.
* Therefore, a meal will be scheduled no closer than 30 minutes before the start of a workout.
* A post-workout meal will be scheduled immediately after your workout ends.
* Your last meal will be scheduled no later than 30 minutes before the end of the time range you specified for your meals.
* Meals are otherwise spread out as evenly as possible throughout your specified meal window.

## Can I manually specify macros for workout shakes?
    
Yes. Because shakes are tightly coupled with workouts, you can accomplish this through the workout editor, and if you do specify those macros manually, they will appear on the shake card that’s attached to your workout, rather than in the “Meals” section of the schedule template editor. Note that, unlike other meals, shakes do _not_ count against the total number of meals you set for a day.

## Why can’t I edit my weigh-in times in the schedule template editor?
    
While weigh-ins show up on your schedule as you’re running your diet, they do not appear in the schedule editor, in Weekly Review, or in the template editor. It is crucial that you are extremely consistent about weighing yourself under conditions that are as close to identical to one another as possible; as a result, the app discourages rescheduling your weigh-in times in the middle of your diet. If you must change your weigh-in times, you can find that in the app settings.

## I manually specified target macros and calories for a particular day, but I want to clear those values. How do I do that?
    
Unlike manually added meals (which you can delete using the “Delete meal” option under its vertical kabob overflow menu), to clear the manually specified target macros and calories at the day level, you use the horizontal kabob overflow menu at the top of the day and select “Clear day target macros”.

## Can I specify just the target calories for a day without specifying the target macros?
    
No. If you specify target calories, the RP algorithm will pre-populate recommended macros in the respective fields, but you cannot leave those fields blank. The app will also not allow you to select values for any macros that are below safety limits. If you do not set values for all macros, no macros will be saved into your template for that day, and all macro and calorie values will be cleared when you tap into a different element on the screen.

## Can I specify only some of the macros for a meal?
    
No. As with day targets, you must specify all macros to save a manual meal into your template, but unlike day targets, if you leave any meal macro empty, it will be set to 0.

## What happens if I start my diet on a day other than Monday?
    
If you start your diet on any day other than Monday, your first Weekly Planning will include the remaining days of the week through Sunday, plus the full next week of Monday through Sunday. For example, if you start your diet on a Thursday, your first Weekly Planning will include Thursday to Sunday of the current week, as well as the full Monday through Sunday of the following week, for a total of 11 days, which you would scroll through in the day carousel at the top of various views, including your main schedule view as you’re running your diet. Note that your schedule template will be used as the blueprint for both Thursdays, both Fridays, both Saturdays, and both Sundays of this first 11-day cycle.

## How do I edit my schedule template in the middle of my diet?

Find the "Schedule Template" option on the "Me" tab. This is the current location of this functionality, so as to not be confused with making schedule edits to the current week from the Schedule tab.

## What happens if I edit my schedule template in the middle of my diet?
    
Any already-programmed weeks are not affected: The current week (what you see in your Schedule tab) is never affected. If you have _not_ yet done Weekly Planning for the following week, then schedule template edits _will_ be used as the baseline for that week’s planning. Conversely, if you _have_ already completed Weekly Planning for the next week, then any schedule template edits will _not_ affect next week’s schedule, but they _will_ apply to Weekly Planning for the following week.
    
For example, let’s say that today is Friday, January 5 for the week of January 1-7. If you have _not_ yet done Weekly Planning for January 8-14 and you make changes to your schedule template, then your edits _will_ be used to program that upcoming week. But if you _have_ already done your Weekly Planning for January 8-14 and you make changes to your schedule template, then your edits will only be used as the blueprint for Weekly Planning for January 15-21.

## When should I edit my schedule, and when should I edit my schedule template?
    
This is really a judgement call for you to make. Individual meals, workouts, and other aspects of your schedule don’t have “recurrence” settings the way that events in most calendaring applications do; instead, you use the schedule template to convey roughly the same idea, and that template is applied to each future week that you plan with the help of the RP algorithm’s programming.
    
If you want to make edits that you expect to apply to most or all future weeks, editing your schedule template is probably a better bet, so that you don’t have to repeatedly make the same changes in each future Weekly Planning.
    
By contrast, if you have one-off changes that apply to only the current or upcoming week (or to only a few upcoming weeks), then you might prefer to make such changes in your schedule while running your diet for the current week (if it’s a change you couldn’t anticipate, such as suddenly getting sick) or during Weekly Review for the upcoming week (if it’s a change you planned for, such as travel or working around an appointment).