---
title:          Copy Foods
nav_order:      500
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

"Copy Foods" is the new name for the "copy meal" functionality in the previous versions of the app. The previous name connoted actually duplicating the meal itself, but "copy foods" gets at the fact that we're primarily oriented around copying the foods in the meal to another preexisting meal.

The easiest way to copy foods from one meal to another is to long-press the meal from the "Schedule" tab and select "Copy foods" from the menu that comes up.

The UI is relatively straightforward, with the "source" meal and its foods displayed at the top. You then tap the "destination" meals that you want to copy the foods to. Remember that you can also copy to meals on other days.

For now, this overwrites all foods in a destination meal, so if you already had foods in a meal that you select, they will be deleted.

# Advanced Options

Tap on the gear icon next to "Save" at the top right of the "Copy foods" sheet to access the "Advanced options" sheet. These are all off by default, and each time you use "Copy foods", they will start off as off, even if you used them the last time you copied foods from one meal to another.

## Update destination target macros

This is especially useful if your source meal's targets (denominators)already match the sum of its foods' macros (numerators), and you expect your destination meal to have the same targets. (Any change in the destination meals' target macros will be reflected in a reallocation to the [Day Balance](/docs/diet-coach-app/1.22-beta/features/day-balance/).)

Of course, even if your source meal's numerators aren't equal to its denominators, the denominators (targets) will still be copied along with the foods, and the destination meal(s) will have unequal numerators and denominators.

## Update destination meal times

If you're also happy with the source meal's time and want that to get copied along to the destination meals you select, use this option. This is especially helpful if you have a specific meal that you want to eat at a specific time on multiple days in a week, and it's a deviation from the time that was already programmed.

## Copy source meal locked state

Especially if you locked your source meal and don't want other functions like [Auto-configure](/docs/diet-coach-app/1.22-beta/features/auto-configure/) to make any changes to the destination meals after you copied foods to them, use this option. That way, if you run [Auto-configure](/docs/diet-coach-app/1.22-beta/features/auto-configure/) later, these meals that you already configured won't be affected.