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