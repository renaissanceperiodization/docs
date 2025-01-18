---
title:          Locks and Pins
nav_order:      400
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

Locks are persistent, and pins are ephemeral: When you lock a value, it persists until you explicitly unlock it. By contrast, pins persist only as long as a given editing session.

# Locks

The fundamental purpose of locks is for you, the user, to prohibit any automatic programming or other "automagical" functions of the app from changing values that you set. You are always able to override your own locks.

You can lock the following items:
* day calorie/macro targets (either in your programmed schedule or in the schedule template)
* meals, which locks its calorie/macro targets (either in your programmed schedule or in the schedule template by creating a "manually specified meal")
* foods (in meals)

Locking day or meal targets prevents them from being touched by the RP algorithm, including when you use the Auto-Configure feature.

However, when you use the Reallocate or Copy Foods features, you can modify locked meals, since you are permitted to take explicit actions to override your own locks.

In the context of a meal, locking a food works the same as it does in the current publicly available version of the app: It prevents the Rebalance feature from changing the food's quantity.

# Pins

When you're editing the target calories and macros for either a day or a meal, you will be presented with a view that shows sliders for each value, with a pin next to it. The pin allows you to hold that value constant, as you vary the other values. For instance, for a given day or meal, you might want to hold total calories and protein fixed, but easily "flex" between carbs and fat. You would pin calories and protein, and then use the slider to adjust your carbs or fat, and then the value for the other of carbs or fat would change accordingly, to keep you at the same number of total calories.

As soon as you save, the pins are cleared.