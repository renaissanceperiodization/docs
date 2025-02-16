---
title:          Frequently Asked Questions
nav_order:      500
parent:         Diet Coach App 1.22 Beta
---

As the beta progresses, we'll supplement the documentation and add more frequently asked questions here!

<details open markdown="block">
  <summary>
    &nbsp;Table of Contents
  </summary>
{: .no_toc }
- TOC
{:toc}
</details>

# Why didn't the app program as many meals as I requested?

For example, you may have asked the app to program 6 meals for you, but it only programmed 5.

You may even notice that the debugging information card on the "Schedule" tab shows the number of meals that you requested, but fewer meals are actually scheduled that day.

This can happen if the app is unable to squeeze in a reasonable amount of meals within the constraints you provided, such as too short a time window that you plan to eat meals or too many workouts that are too long. (While _you_ can always manually schedule or reschedule meals outside your preferred time range or during workouts, the app will respect your stated preferences and avoid overlapping meals and workouts when it does automatic programming.)

Note that this can also come up if you run [Auto-configure](/docs/diet-coach-app/1.22-beta/features/auto-configure/) on today, in the middle of the day. If, for example, you said you wanted 6 meals, but you've only checked in 2 meals, it's already 7pm, and you told the app that you only want to have meals scheduled until 8pm, the app will not be able to schedule 4 meals in the next hour, but it will do its best to allocate your remaining macros into however many meals it _can_ schedule for you.

# I'm on a cut. Why did the app increase my calories for next week?

At present, when you're on a cut, if all else is equal, the app will never increase its recommendation for your target average daily calories from one week to the next. That's true even if you're losing weight much faster than projected, and in that case, the app would keep you at the same calories.

However, _all else is not always equal_! There are a number of factors that can cause the app to increase its calorie recommendation from one week to the next when you're on a cut.

One possibility is that it may _seem_ as though the app is increasing your calories, but in reality, it's keeping them the same. Let's say that you did your [Weekly Planning](/docs/diet-coach-app/1.22-beta/features/weekly-review-and-weekly-planning/) and accepted the RP-recommended [target average daily calories](/docs/diet-coach-app/1.22-beta/concepts/calories/#target-average-daily-calories) without making any changes to your schedule (meaning it was direct programming of your [schedule template](/docs/diet-coach-app/1.22-beta/concepts/schedule/)).

Then, as the week went on,you removed workouts or decreased their duration or intensity. Or perhaps you reduced your step count goals on some days. These kinds of changes would cause the algorithm to recognize that, to hit your diet goal, you actually need to be eating fewer calories than what you had previously accepted as your [target average daily calories](/docs/diet-coach-app/1.22-beta/concepts/calories/#target-average-daily-calories) during [Weekly Planning](/docs/diet-coach-app/1.22-beta/features/weekly-review-and-weekly-planning/).

Even though the RP algorithm updates its recommendation and prompts you to change day targets (if you want to), _it doesn't automatically change your selected [target average daily calories](/docs/diet-coach-app/1.22-beta/concepts/calories/#target-average-daily-calories)_; that's up to you to do, again, only if you want to. (It's not important that you do that!)

So your next [Weekly Review and Planning](/docs/diet-coach-app/1.22-beta/features/weekly-review-and-weekly-planning/) comes up, but if you're still basically on track, when it programs your next week based on your [schedule template](/docs/diet-coach-app/1.22-beta/concepts/schedule/), it will repeat the same recommendation that it made the previous week, before you reduced your activity levels, giving the appearance of increasing your [target average daily calories](/docs/diet-coach-app/1.22-beta/concepts/calories/#target-average-daily-calories) when you compare it to what you [actually averaged](/docs/diet-coach-app/1.22-beta/concepts/calories/#trending-toward-average) for that week.

Another possibility, closely related, is that you may have selected a lower [target average daily calories](/docs/diet-coach-app/1.22-beta/concepts/calories/#target-average-daily-calories) than the RP recommendation, so when you get to [Weekly Planning](/docs/diet-coach-app/1.22-beta/features/weekly-review-and-weekly-planning/) and see the RP-recommended value pre-selected, it seems to you that the app is increasing your calories.

And, of course, perhaps during [Weekly Planning](/docs/diet-coach-app/1.22-beta/features/weekly-review-and-weekly-planning/), you've configured your schedule to include a lot more activity (workout number, duration, or intensity or step counts) than the previous week, so the RP algorithm realizes that you need more calories to lose weight at the target rate to hit your diet goal--but this increase in calories from the previous week's recommendation is proportional to the difference in activity levels.

# I skipped a meal. What should I do?

If you actually didn't eat the prescribed meal, delete it in the app. We recommend _against_ [checking it in](/docs/diet-coach-app/1.22-beta/features/checking-in/) at 0 macros/calories (or worse, at some positive number of macros/calories!), because that can interfere with [Auto-configure](/docs/diet-coach-app/1.22-beta/features/auto-configure/)'s scheduling algorithm if you choose to use it.

If, by contrast, you're actually just going to eat the meal at another time during the day (whether you already ate it earlier or plan to eat it later), feel free to just change its time and then [check it in](/docs/diet-coach-app/1.22-beta/features/checking-in/) accordingly.

# I forgot to log a meal and can't remember what I ate. What should I do?

Don't panic! But also don't just delete the meal! The same principle applies if you didn't record what you ate for a whole day or even for a few days.

The updated RP algorithm depends on knowing what you ate to give you accurate week-over-week recommendations. But sometimes, life happens, and you just couldn't log a meal, you forgot, or you just fell off the wagon. No big deal. Here's what to do:

Estimate.

If you can guess at the foods (especially the most caloric ones) that you ate in various meals and make a guess as to how much you ate, just put that in and then [check in using the "Allocate difference to Day Macro Balance" option](/docs/diet-coach-app/1.22-beta/features/checking-in/#:~:text=Allocate%20difference%20to%20Day%20Macro%20Balance). Do this even if you don't plan to interact with the [Day Balance](/docs/diet-coach-app/1.22-beta/features/day-balance/) for that day, since this still tells the app that for that meal, you ate the macros of the added foods.

If you can't really guess at the foods, but you have a sense for the macros, you can always [check in the meal using the "Manually specify macros"](/docs/diet-coach-app/1.22-beta/features/checking-in/#:~:text=Manually%20specify%20macros) option.

And if you really don't know, but you know you ate the meal, just ["Check in at target macros"](/docs/diet-coach-app/1.22-beta/features/checking-in/#:~:text=Check%20in%20at%20target%20macros).

If you've missed a whole day (or multiple days) and can't even remember which meals you ate, ["Check in at target macros"](/docs/diet-coach-app/1.22-beta/features/checking-in/#:~:text=Check%20in%20at%20target%20macros) for all the meals of those days.

Just don't sweat it. Of course, the app will work better for you when you give it accurate information, but as long as you get back on track, by the time of your following [Weekly Review and Planning](/docs/diet-coach-app/1.22-beta/features/weekly-review-and-weekly-planning/), the app will be able to readjust and give you accurate recommendations again.

# I did my Weekly Review and Planning before the end of the weekend, but then significantly deviated from my targets over the weekend, and now the app is saying I have an updated recommendation. What should I do?

{% comment %}
THIS DEPENDS ON ENG-3025

# Why can't I configure zero meals for a day?
{% endcomment %}