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

# I forgot to log a meal and can't remember what I ate. What should I do?

# I did my Weekly Review and Planning before the end of the weekend, but then significantly deviated from my targets over the weekend, and now the app is saying I have an updated recommendation. What should I do?

{% comment %}
THIS DEPENDS ON ENG-3025

# Why can't I configure zero meals for a day?
{% endcomment %}