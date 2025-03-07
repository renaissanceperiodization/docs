---
title:          Release Notes
nav_order:      600
parent:         Diet Coach App 1.22 Beta
---

As the beta progresses, release notes for each new version will be posted here.

<details open markdown="block">
  <summary>
    &nbsp;Table of Contents
  </summary>
{: .no_toc }
- TOC
{:toc}
</details>

# 1.22.18 (2025-03-06)
* iOS build 6699
* Android build 2980

## Added
{: .no_toc }
* new settings to toggle debugging information display for
  * [preferred meal count and start/end (from/until) time](/docs/diet-coach-app/1.22-beta/concepts/sleep-and-preferred-meal-time-range/)
  * [target average daily calories](/docs/diet-coach-app/1.22-beta/concepts/calories/#target-average-daily-calories) and [trending-toward average](/docs/diet-coach-app/1.22-beta/concepts/calories/#trending-toward-average) on "Schedule" tab
* calorie information for meals
* more robust information and guidance on "Coaching" tab around calorie averages and trends

## Changed
{: .no_toc }
* days must have at least one non-shake meal; when deleting meals, the last remaining meal on a day cannot be deleted

## Fixed
{: .no_toc }
* calendar icon on "Schedule" tab brings focus to today
* day target numeric input fields would sometimes show "NaN" when editing
* day target calorie/macro sliders would stay open when switching between days in [schedule template](/docs/diet-coach-app/1.22-beta/concepts/schedule/)
* adjusting schedule of future days would sometimes clear foods from meals
* missing remove icon (⛔) when trying to delete a food from a meal


# 1.22.17 (2025-03-04)
* iOS build 6697
* Android build 2978

## Fixed
{: .no_toc }
* sometimes "Rebalance" would need to be tapped twice in a meal before the sliders and food quantities would update (#ZD187007, #L3084)


# 1.22.16 (2025-02-28)
* iOS build 6696
* Android build 2977

## Fixed
{: .no_toc }
* crash on trying to change [start/end (from/until) meal time range](/docs/diet-coach-app/1.22-beta/concepts/sleep-and-preferred-meal-time-range/) during new diet start wizard (#ZD186908, #L3082)
* initial weight values and graph would sometimes be inconsistent if the weight was changed during new diet start wizard

# 1.22.15 (2025-02-28)
* iOS build 6695
* Android build 2976

## Fixed
{: .no_toc }
* [Weekly Planning](/docs/diet-coach-app/1.22-beta/features/weekly-review-and-weekly-planning/) calorie-recommendation algorithm didn't factor in enough days when computing recent average caloric intake (#ZD186965)
* initial calorie recommendation for new diets used sometimes unreliable data from diet history in its "metabolic learning" (#ZD186489, #L3081)
* end/until time for [preferred meal time range](/docs/diet-coach-app/1.22-beta/concepts/sleep-and-preferred-meal-time-range/) was allowed to be before start/from time, resulting in empty programming (#ZD186908, #L3079)
* changing the [start/end (from/until) meal times](/docs/diet-coach-app/1.22-beta/concepts/sleep-and-preferred-meal-time-range/) in the [schedule template](/docs/diet-coach-app/1.22-beta/concepts/schedule/) for one day would always affect all days (#ZD186766, #ZD186936, #L3077)
* changes to diet goal in [Weekly Review](/docs/diet-coach-app/1.22-beta/features/weekly-review-and-weekly-planning/) did not always reliably save
* sometimes tapping on a meal in the Schedule will open a different meal (#ZD185772, #L3078)


# 1.22.14 (2025-02-24)
* iOS build 6693
* Android build 2974

## Added
{: .no_toc }
* icon on "Schedule" tab that indicates day macro and calorie targets are [locked](/docs/diet-coach-app/1.22-beta/concepts/locks-and-pins/#locks)

## Removed
{: .no_toc }
* prompt to rate app on Apple App Store and Google Play (because it was crashing)

## Fixed
{: .no_toc }
* missing diet end date during diet start flow when using kg as weight units


# 1.22.13 (2025-02-22)
* iOS build 6692
* Android build 2973

## Added
{: .no_toc }
* better instructions and links on "Contact Us" screen (#GH1215)

## Fixed
{: .no_toc }
* sometimes schedule changes result in foods being duplicated across meals (#ZD185772, #ZD186138, #ZD186228, #L3058)
* some screen flickering when opening food lists / search results
* missing "Cancel" button when Custom Foods accessed from "Me" tab (#ZD186221, #ZD186247, #ZD186111, #L3066)

## Removed
{: .no_toc }
* "Redo weekly review" button on "Me" tab (#ZD186052, #L3062)


# 1.22.12 (2025-02-22)
* iOS build 6689
* Android build 2971

## Fixed
{: .no_toc }

* sometimes the camera won't be detected or open automatically for UPC scanning (#ZD185308, #ZD185928, #ZD185914, #ZD186112, #ZD186149, #L3040)
* diet share image incorrectly shows meal adherence stats and has misaligned graph elements (#ZD186050, #L3053)
* sometimes the food quantity slider would stutter (#ZD185585, #L3054)


# 1.22.11 (2025-02-20)
* iOS build 6688
* Android build 2970

## Fixed
{: .no_toc }

* sometimes the trailing digit of a number in a macro pill or numeric input field is truncated (#ZD185514, #ZD185731, #ZD185814, #ZD185722, #L3028)
* sometimes the food quantity slider wouldn't update after typing in the value (#ZD186009)
* [Android] sometimes the camera won't open automatically for UPC scanning (#ZD185308, #ZD185928, #ZD185914, #L3040)

# 1.22.10 (2025-02-19)
* iOS build 6685
* Android build 2968

## Changed
{: .no_toc }

* disabled font scaling

## Fixed
{: .no_toc }

* sometimes [Copy Day](/docs/diet-coach-app/1.22-beta/features/copy-day/) focuses the previous week instead of the current week in the day carousel (#ZD185752, #L3036)
* [Android] app would sometimes become unresponsive after using back button/gesture (#ZD185585)
* [Android] sometimes "Other Foods" couldn't be added to a meal (#ZD185509, #ZD185684, #ZD185308, #L3029)
* [Android] time units on adding workouts during diet start flow would be missing
* [Android] sometimes the step count target card on the "Schedule" tab doesn't show the step count target (#ZD185749, #ZD185640, #L3035)


# 1.22.9 (2025-02-18)
* iOS build 6684
* Android build 2967

## Fixed
{: .no_toc }
* [Auto-Configure](/docs/diet-coach-app/1.22-beta/features/auto-configure/) would sometimes duplicate checked-in meals (#ZD185593, #L3030)


# 1.22.8 (2025-02-17)
* iOS build 6683
* Android build 2966

## Added
{: .no_toc }

* help text to some info buttons (#ZD185477, #L2974)

## Fixed
{: .no_toc }

* the selected date on the schedule sometimes wasn't focused (#ZD184646, #L3012)
* certain days sometimes can’t be navigated to on the “Schedule” tab (#ZD185234, #ZD185240, #ZD185471, #L2936)
* overlapping workouts could be added during diet start wizard (#ZD185488, #L3027)
* crash on [Copy Day](/docs/diet-coach-app/1.22-beta/features/copy-day/) when there are no valid destination days (#L3024)
* macro pills in meals were sometimes truncated (#ZD185514, #L3028)



# 1.22.7 (2025-02-17)
* iOS build 6682
* Android build 2965

## Fixed
{: .no_toc }

* [Android] some sheets would extend into the Android Status Bar, making content unreadable and not tappable (#L3002, #ZD184827, #ZD184985)



# 1.22.6 (2025-02-14)
* iOS build 6681
* Android build 2964

## Changed
{: .no_toc }
* diet end flow now parallels Weekly Review's new check-in paradigm (#L2873)

## Fixed
{: .no_toc }

* occasional failure to copy day (#L3022, #ZD185080)
* day target macros could go negative (#L2019, #ZD184916)
* shake cards on Schedule didn't show foods (#L3009, #ZD184617, #ZD184847)
* occasional missing weigh-in list in Weekly Review
* meal count debug information card sometimes showing up in incorrect order (#L3023, #ZD184983)
* adding/deleting/editing workout sometimes empties meals on future days (#L3021)
* [Android] some sheets would extend into the Android Status Bar, making content unreadable and not tappable (#L3002, #ZD184827, #ZD184985)



# 1.22.5 (2025-02-13)
* iOS build 6679
* Android build 2962

## Fixed
{: .no_toc }

* [Android] some sheets would extend into the Android Status Bar, making content unreadable and not tappable (#L3002)
* [Android] keyboard would sometimes slide screens up out of view (#L3014)



# 1.22.3 (2025-02-11)
* iOS build 6677
* Android build 2960

## Fixed
{: .no_toc }

* [iOS] occasional account migration failure causing crash on login (#ZD184616, #ZD184620)



# 1.22.2 (2025-02-10)
* iOS build 6675
* Android build 2958

## Fixed
{: .no_toc }

* [Android] crash when loading a screen with a picker/dropdown (#ZD184617)



# 1.22.1 (2025-02-10)
* iOS build 6673
* Android build 2956

## Fixed
{: .no_toc }

* [Android] broken raw/cooked toggle (#L3006)