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

# Why does the app show calories now? I liked it better when it just showed me macros!

Keep in mind that the app is still primarily a _macro_ planner. The benefits of exposing the calorie information are to help you to calibrate more effectively across days and to build up an intuition around calorie needs for various goals.

At the end of the day, net calories is going to be the chief driver of body composition changes, and we'd gotten a lot of feedback requesting transparency around calories.

Indeed, our hope with how we've restructured the app is to further avoid encouraging an unhealthy relationship with food, by allowing for greater flexibility: For example, instead of obsessing over hitting your macros perfectly, you can now more easily flex between macros and still hit your calorie targets. Or, for instance, if you know you need the psychological relief of a more relaxed eating day each week (or you know you're going to go out to eat on a particular day), the app can help you to readjust your calorie distribution throughout the week, so that you're still hitting your goals.

Exposing calories has been a polarizing issue among our users, but we are betting that it will be better for the vast majority in the long-run. Unfortunately, when you increase flexibility, the tradeoff is often that you do so at the expense of simplicity. We will continue to work on balancing these often-competing interests and make the app as flexible _and_ simple as possible, but even something like creating a different mode in the app that hides calories would be difficult at this stage and is not presently on our roadmap.

And if you're willing to give the beta a shot, you may get a sense for why it can often actually be simpler in a lot of contexts to see a single calorie number represent levels of nutrients, rather than seeing three macros numbers.

We hope this doesn't adversely affect your experience, and we're always open to [your feedback](/docs/diet-coach-app/1.22-beta/getting-started/#how-to-provide-feedback)!

# Why can't I say what days I want to weigh in?

The new version of the diet app now recommends daily [weigh-ins](/docs/diet-coach-app/1.22-beta/concepts/weight/), and while you can configure _when_ each day you would like to weigh in (to encourage consistent conditions each time), there is no option to exclude days.

There are several reasons for this:

Most fundamentally, because the app now better integrates your actual caloric intake, it requires a minimum of 4 weigh-ins from the week to get enough information to extrapolate how to make better recommendations. The more weigh-ins, the better, since the app's algorithm will be able to better understand how your caloric balance is affecting your progress toward your diet goal and overcome statistical noise. (If you don't provide 4 weigh-ins, the app now repeats the [target average daily calories](https://docs.rpstrength.com/docs/diet-coach-app/1.22-beta/concepts/calories/#target-average-daily-calories) recommendation from the previous week, scaled to any difference in activity levels.)

Because that's more than half of the days of a week, recommending daily weigh-ins helps with adherence, by building up a habit that's part of your routine.

We realize that this might be stressful for some folks, especially if you have negative psychological associations with weighing yourself or if seeing your weight daily might subtly encourage you to eat more or less than the app recommends, to try to shift the weight trend in a more favorable direction (or because you think you can get away with it!). While these can be difficult to work through at first, our hope is that, with time and experience, you can overcome some of these challenges, _especially_ when you find that weighing yourself daily ends up being associated with superior dieting results!

If you miss a day, it's really no big deal. Indeed, it's not even a big deal if in one week, you weigh in fewer than 4 times and the app repeats its recommendation. One day or one week isn't going to completely derail your progress, and the app will always do its best to interpret your progress data in a way that allows it to give you better ongoing recommendations.

<a id="i-changed-my-preferred-startend-meal-times-so-why-are-my-meal-times-still-the-same"></a>

# I changed my preferred number of meals or start/end times, so why do I still have the same number of meals and the times are still the same?

A key point to remember is that changing your preferred meal number and [start/end meal times](/docs/diet-coach-app/1.22-beta/concepts/sleep-and-preferred-meal-time-range/) is telling the app when _it_ should automatically program your meals. If you have already-programmed meals on your schedule, changing this preference does _not_ automatically change the number or times of any meals; it only applies to future (re)programming.

This is consistent with a general principle throughout the new version of the app, which is that, while there are many tools to align your schedule with optimal RP recommendations, the app will never override anything that's already programmed without your explicit action.

(A major pain point for many users in the previous, non-beta version of the app was that any time there was any slight change to the schedule, the app would completely reprogram the whole day from scratch, potentially wiping out a significant amount of meal planning and work that the user had already done.)

There are two places where you might change the preferred meal number or start/end times:

1. in the current week's schedule
  * "Schedule" tab → "..." overflow menu → "Edit schedule" → "..." overflow menu for the day → "Set first/last meal times"
  * tapping on the meal number and window [debugging infomation card](/docs/diet-coach-app/1.22-beta/getting-started/#debugging-information:~:text=On%20the%20%E2%80%9CSchedule%E2%80%9D%20tab%2C%20under%20the%20%E2%80%9CStep%20Count%20Target%E2%80%9D%20card%2C%20there%E2%80%99s%20a%20card%20that%20indicates%20a%20number%20of%20meals%20and%20a%20time%20range.) on the "Schedule" tab or in the "Edit schedule" mode
2. in the [schedule template](/docs/diet-coach-app/1.22-beta/concepts/schedule/)

Again, _changes to the preference in the current week's schedule will not automatically change the times or number of any meals that are already on your schedule_. So if you already had a meal on your schedule at 08:00, and you changed your start time to 09:00, that 08:00 meal will stay there. You can, of course, just manually change the time of that and any other meal to meet your needs for the day or add or remove meals directly, but the point of changing the start/end meal time preference would be to later run [Auto-Configure](/docs/diet-coach-app/1.22-beta/features/auto-configure/) to reprogram your schedule. Just be careful to first [lock](/docs/diet-coach-app/1.22-beta/concepts/locks-and-pins/#locks) any meals you don't want Auto-Configure to potentially wipe out, and make sure you set the right [configuration options](/docs/diet-coach-app/1.22-beta/features/auto-configure/#configuration-options).

By contrast, changes to your [schedule template](/docs/diet-coach-app/1.22-beta/concepts/schedule/) will only be used during the next [Weekly Planning](/docs/diet-coach-app/1.22-beta/features/weekly-review-and-weekly-planning/), and they will persist for all subsequent Weekly Plannings. Those changes will _not_ be applied to the current week, even if you run [Auto-Configure](/docs/diet-coach-app/1.22-beta/features/auto-configure/), because the preference lives in your updated template that was not used as a blueprint for the current week's preferences.



# I added/removed/edited a workout, but why didn't the app rearrange my meals or change my meal macros?

This is by design. In previous versions of the app, many users faced the frustration of planning out meals, then making a minor schedule change, only to have those meals wiped out. The app no longer assumes that, just because you're making a particular on-the-fly schedule change, you want it to automatically reprogram the rest of your day's schedule.

So when you add, remove, or modify a workout, you're only touching that one workout, and the app won't do anything automatically. If your change is significant enough, it _will_ prompt you to accept or decline a change to your day calorie/macro targets (which, if you accept, will get applied only to your [Day Balance](/docs/diet-coach-app/1.22-beta/features/day-balance/) for you to deal with later, either manually, through Reallocate, or [Auto-Configure](/docs/diet-coach-app/1.22-beta/features/auto-configure/)). But that won't change the timing or macros of any of your already-programmed meals on that day.

If you _do_ want the app to make those changes for you (including timing optimizations like skewing carbs to your post-workout meal), use [Auto-Configure](/docs/diet-coach-app/1.22-beta/features/auto-configure/) on that day, using the option from the "..." (horizontal kabob) overflow menu from the "Schedule" tab or in "Edit schedule". Make sure you have already [locked](/docs/diet-coach-app/1.22-beta/concepts/locks-and-pins/#locks) any meals you absolutely don't want touched (already checked-in meals are implicitly locked), and make sure you set the [options](/docs/diet-coach-app/1.22-beta/features/auto-configure/#configuration-options) you want. That will give you more control over what the app previously did automatically.

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

<a id="#i-forgot-to-log-a-meal-and-cant-remember-what-i-ate-what-should-i-do"></a>

# I ate a cheat meal or I forgot to log a meal, and I can't remember what or how much I ate. What should I do?

Don't panic! But also don't just delete the meal! The same principle applies if you didn't record what you ate for a whole day or even for a few days.

The updated RP algorithm depends on knowing what you ate to give you accurate week-over-week recommendations. But sometimes, life happens, and you just couldn't log a meal, you forgot, or you just fell off the wagon. No big deal. Here's what to do:

Estimate.

If you can guess at the foods (especially the most caloric ones) that you ate in various meals and make a guess as to how much you ate, just put that in and then [check in using the "Allocate difference to Day Macro Balance" option](/docs/diet-coach-app/1.22-beta/features/checking-in/#:~:text=Allocate%20difference%20to%20Day%20Macro%20Balance). Do this even if you don't plan to interact with the [Day Balance](/docs/diet-coach-app/1.22-beta/features/day-balance/) for that day, since this still tells the app that for that meal, you ate the macros of the added foods.

If you can't really guess at the foods, but you have a sense for the macros, you can always [check in the meal using the "Manually specify macros"](/docs/diet-coach-app/1.22-beta/features/checking-in/#:~:text=Manually%20specify%20macros) option.

And if you really don't know, but you know you ate the meal, just ["Check in at target macros"](/docs/diet-coach-app/1.22-beta/features/checking-in/#:~:text=Check%20in%20at%20target%20macros).

If you've missed a whole day (or multiple days) and can't even remember which meals you ate, ["Check in at target macros"](/docs/diet-coach-app/1.22-beta/features/checking-in/#:~:text=Check%20in%20at%20target%20macros) for all the meals of those days.

Just don't sweat it. Of course, the app will work better for you when you give it accurate information, but as long as you get back on track, by the time of your following [Weekly Review and Planning](/docs/diet-coach-app/1.22-beta/features/weekly-review-and-weekly-planning/), the app will be able to readjust and give you accurate recommendations again.

# I went way off the rails and ate way more or less than the app told me to. What should I do?

Let's say you're on a cut, your [target average daily calories](/docs/diet-coach-app/1.22-beta/concepts/calories/#target-average-daily-calories) is set to the RP-recommended value of 2000, and it's Wednesday evening. Let's say that it was a higher-than normal activity day, so your day target was 2200, but you were so hungry that you ended up eating 3950 instead. Let's say that you otherwise ate exactly according to plan. So now, you're [trending toward](/docs/diet-coach-app/1.22-beta/concepts/calories/#trending-toward-average) a 2250 average, rather than a 2000 average, which would _slow_ your weight loss by roughly 0.5 lbs per week, perhaps even causing you to maintain or gain weight this week.

First things first--

Don’t let this cause you to spin out. It’s normal to feel a bit guilty when you go off track--that just means you care about your goals. But guilt should work for you, not against you. Use it as a reminder to get back on track, not as a reason to dwell on it or beat yourself up.

It is _absolutely_ okay to just write the day off and continue on as planned, without making any adjustments. Indeed, that is the baseline RP recommendation.

However, if this is going to subtly nag at you and lead you to try to get back on track by eyeballing and guessing based on your gut (and perhaps unhealthily starving yourself by overcompensating) or even by trying to pull out pencil and paper and do your own calculations, the app has tools to help you to readjust safely.

After you're done [checking in](/docs/diet-coach-app/1.22-beta/features/checking-in/) your meals on the "problematic" day...
1. Go to "Edit schedule" from the "..." (horizontal kabob) overflow menu on the "Schedule" tab.
2. Make any other adjustments you need to your schedule, including remaining workouts for the week, step count targets, etc.
3. Select the RP-recommended [target average daily calories](/docs/diet-coach-app/1.22-beta/concepts/calories/#target-average-daily-calories) (or a different value if you really know what you're doing).
4. Run [Auto-configure](/docs/diet-coach-app/1.22-beta/features/auto-configure/) on the remaining days of the week.

The RP app will do its best to reprogram the remainder of your week to get you in line with your diet goals as safely as possible--but keep in mind that the remainder of the week may end up being a lot more difficult than you anticipate, and the risk is that, if you struggle to abide by the new recommendations, that can lead to more guilt and frustration. We really only recommend this if you know what you're doing, you won't be thrown for a psychological loop, and you're willing to be flexible and gentle with yourself.


# I started my week by selecting the RP-recommended target average daily calories, but in the middle of the week, it looks like the RP recommendation has changed. What should I do?

It really depends on what will help _you_ to diet more effectively, based on your individual psychological dispositions.

The RP recommendation will typically only change in the middle of a week when you have made significant mid-week changes to your activity levels (adding/removing/modifying workouts or step count targets).

You'll notice that when you make those changes, you're prompted to accept or decline a change to your day macro/calorie targets. If you accept those changes, your average daily calories will _generally_ [trend toward](/docs/diet-coach-app/1.22-beta/concepts/calories/#trending-toward-average) the RP-recommended [target average daily calories](/docs/diet-coach-app/1.22-beta/concepts/calories/#target-average-daily-calories), but it might not be equal to it if you've also veered off course from your day targets. Note that accepting the change to day targets when you change your activity levels does _not_ automatically change your selected [target average daily calories](/docs/diet-coach-app/1.22-beta/concepts/calories/#target-average-daily-calories).

If you decline the change to your day targets when you change your activity levels, the RP recommendation may still change, but neither your day targets nor your [target average daily calories](/docs/diet-coach-app/1.22-beta/concepts/calories/#target-average-daily-calories) will automatically change.

The reason that the app does not make those kinds of changes automatically in the middle of a week and doesn't even encourage you to make them on your own is that _for many people, it's psychologically unhealthy to introduce that amount of disruptive, frequent adjustment and reactive change_. This is equivalent to looking at the scale every day and then trying to change how many calories you eat that day...like if you're on a cut, randomly gain some water weight, and then starve yourself that day because you fear you've actually gained weight. It's not good for you.

While you _can_ up- and down-regulate calories on a particular day to scale with your activity levels, RP recommends that, in most cases, you just continue on with your week as programmed. Remember that [Weekly Review and Planning](/docs/diet-coach-app/1.22-beta/features/weekly-review-and-weekly-planning/) will catch your progress based on your actual eating and make updated recommendations for the following week. It's rarely critical to replan the remainder of the current week because life got a bit messy.

However, if you feel a strong urgency to reprogram the rest of the week and get in line with the optimal RP recommendation, those tools are available to you. The chief reason that you would want to do this is if you know that you will be subconsciously inclined to try to correct for the changes yourself, and you'd rather get safe recommendations from the app than try to eyeball it or go by your gut. In that case, by all means, go to "Edit schedule", make any additional schedule changes you need to (eg, adding/removing/modifying workouts or step count targets), select the RP-recommended [target average daily calories](/docs/diet-coach-app/1.22-beta/concepts/calories/#target-average-daily-calories), and then run [Auto-configure](/docs/diet-coach-app/1.22-beta/features/auto-configure/) on the remaining days this week to help you to get back on track.

# I did my Weekly Review and Planning before the end of the weekend, but then significantly deviated from my targets over the weekend, and now the app is saying I have an updated recommendation. What should I do?

Unlike the guidance for mid-week adjustments in [I went way off the rails and ate way more or less than the app told me to. What should I do?](#i-went-way-off-the-rails-and-ate-way-more-or-less-than-the-app-told-me-to-what-should-i-do) above, in this scenario, it's a good idea to reprogram your week. This is essentially redoing [Weekly Planning](/docs/diet-coach-app/1.22-beta/features/weekly-review-and-weekly-planning/).

However, you may have already done a significant amount of meal planning in the upcoming week, and you don't want to accidentally wipe out all that work.

Here's what to do if there are just a few meals that you've already planned out (ie, added foods to) that you want to preserve:

1. For any meal you definitely don't want reprogrammed (time or foods), go to that meal in the upcoming week on the "Schedule" tab and [lock](/docs/diet-coach-app/1.22-beta/concepts/locks-and-pins/) it. The easiest way to do that is to swipe left on the meal card. Keep in mind that this will prevent the meal's macros from being reprogrammed, so that will limit the algorithm's effectiveness somewhat, but changes can still be applied to your [Day Balance](/docs/diet-coach-app/1.22-beta/features/day-balance/) for you to reallocate manually later.
2. Navigate to a day next week on the "Schedule" tab and go to "Edit schedule" by tapping on the "..." (horizontal kabob) overflow menu.
3. Make whatever other changes you want to make to your schedule next week (eg, any workouts you forgot to add/remove/modify).
4. Select the [target average daily calories](/docs/diet-coach-app/1.22-beta/concepts/calories/#target-average-daily-calories) you want, presumably the RP-recommended value with the red shield.
5. Run [Auto-configure](/docs/diet-coach-app/1.22-beta/features/auto-configure/) using the 🪄 (magic wand) icon on all the days of the week. Keep all the [options](/docs/diet-coach-app/1.22-beta/features/auto-configure/#configuration-options) enabled, since you want the unlocked meals to be reprogrammed, and you _definitely_ want day targets to be adjusted.

Here's what to do if you you have planned nearly all your meals already (and it would be a pain to go through and lock a ton of them):

1. Navigate to a day next week on the "Schedule" tab and go to "Edit schedule" by tapping on the "..." (horizontal kabob) overflow menu.
2. Make whatever other changes you want to make to your schedule next week (eg, any workouts you forgot to add/remove/modify).
3. Select the [target average daily calories](/docs/diet-coach-app/1.22-beta/concepts/calories/#target-average-daily-calories) you want, presumably the RP-recommended value with the red shield.
4. Run [Auto-configure](/docs/diet-coach-app/1.22-beta/features/auto-configure/) using the 🪄 (magic wand) icon on all the days of the week.<br />_**Important:** Set the following [options](/docs/diet-coach-app/1.22-beta/features/auto-configure/#configuration-options):_
  * [Adjust day calories and macros](/docs/diet-coach-app/1.22-beta/features/auto-configure/#adjust-day-calories-and-macros): Keep this ON.
  * [Adjust macros of unlocked meals](/docs/diet-coach-app/1.22-beta/features/auto-configure/#adjust-macros-of-unlocked-meals): Turn this OFF.<br />_This is part of what will tell the RP algorithm to preserve all the meals that you already planned._
  * [Adjust times of unlocked meals](/docs/diet-coach-app/1.22-beta/features/auto-configure/#adjust-times-of-unlocked-meals): Turn this OFF.<br />_This is part of what will tell the RP algorithm to preserve all the meals that you already planned._

# Why does the app round my macros to the nearest 5 grams?

This kind of rounding has been a foundational part of the RP approach since we launched the Diet Coach App, and the chief reason for it is that anything more granular than 5 grams really doesn't matter that much in terms of success with diet goals.

You will find a greater effect from the "statistical noise" introduced by other irregularities in your lifestyle, like subtle differences in activity levels, how much sleep you got, the quality of your sleep, your stress levels, etc.

We don't want to encourage people to obsess over getting things exactly right to the gram! While this can introduce some funny arithmetic in places, we think you'll find that the app does an excellent job of supporting practical success _because_ of this rounding, not despite it.

# I just did my first Weekly Planning, and the app recommended target average daily calories that seem unreasonably high or low, especially when comparing the macros to those recommended by the previous (non-beta) version of the app. What should I do?

When you first update to the beta version of the RP Diet Coach app, the initial [Weekly Planning](/docs/diet-coach-app/1.22-beta/features/weekly-review-and-weekly-planning/) may recommend calorie targets that feel off--either too high or too low--compared to what you were seeing in the previous (non-beta) version. This discrepancy often stems from how the beta app calculates your starting point.

The new version uses the information from your initial setup and your check-in data from the previous week. However, if this is your first time using the beta, the app relies on more generalized estimates of your actual caloric intake based on the at/over/under macros ratings from your previous check-ins. This approach is less precise than what the app will achieve in subsequent weeks when it has more detailed data about your caloric intake and adherence to macros.

If your recommended calories seem off, here's what you should do:
* Manually adjust your [target average daily calories](/docs/diet-coach-app/1.22-beta/concepts/calories/#target-average-daily-calories): If you have a good sense of what works for you (eg, a calorie target that has helped you maintain, gain, or lose weight appropriately), set that as your temporary target.
* Follow your own target for the first week: By hitting this target and [tracking](/docs/diet-coach-app/1.22-beta/features/checking-in/) consistently, you'll provide the app with more accurate data to fine-tune its recommendations.
* Let the app learn: Over time, the app will better align its suggestions with your actual needs, leading to more accurate recommendations during [Weekly Planning](/docs/diet-coach-app/1.22-beta/features/weekly-review-and-weekly-planning/).

If you continue to get recommendations that seem unreasonable, please make sure to [submit feedback](/docs/diet-coach-app/1.22-beta/getting-started/#how-to-provide-feedback)!

{% comment %}
THIS DEPENDS ON ENG-3025

# Why can't I configure zero meals for a day?
{% endcomment %}