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
* [Android] some sheets would extend into the Android Status Bar, making content unreadable and not tapable (#L3002, #ZD184827, #ZD184985)



# 1.22.5 (2025-02-13)
* iOS build 6679
* Android build 2962

## Fixed
{: .no_toc }

* [Android] some sheets would extend into the Android Status Bar, making content unreadable and not tapable (#L3002)
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