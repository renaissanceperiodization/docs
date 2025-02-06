---
title:          Getting Started
nav_order:      100
parent:         Diet Coach App 1.22 Beta
---

<details open markdown="block">
  <summary>
    &nbsp;Table of Contents
  </summary>
{: .no_toc }
- TOC
{:toc}
</details>

# Who the Beta is For

You should only sign up to participate in the beta if you're already familiar with the current publicly available RP Diet Coach App and are willing to endure some bugs here and there, even though the beta version is already in a pretty stable, usable state.

Keep in mind that, while the app can be run on tablets and on certain Mac computers, we discourage you from running it on those platforms, as we have not verified compatibility or stability, and so we cannot support you if you run into bugs.

# Active Subscription is Required

The beta version of the RP Diet Coach app is available to users under the same access terms as the production app, which means an active subscription is required. If you're already subscribed to the RP Diet Coach app, you'll be able to use the beta just like you would the regular version--your existing login and subscription will carry over automatically.

If you're not currently subscribed, you'll need to sign up for a subscription to access the beta. The beta isn't a free trial, but rather an early-access version of the app with new features and improvements in development. We greatly appreciate our beta testers' feedback, and your participation helps us make the app even better!

# No Going Back

By enrolling in the beta, you are committing to enduring some amount of instability and potential disruption to being able to run your diet for the remainder of the beta period.

This is because upgrading to this new version fundamentally changes the structure of your diet data, and there is no downgrade path to go back to the previous data structure.

We anticipate that the beta will last no longer than through the end of June 2025, but unforeseen circumstance may require us to run the beta for longer.

Once we have developed a stable version that we are comfortable publishing publicly, your participation in the beta program will end, and you will upgrade to the latest version of the publicly available production app.

# Migration Notes

If you are in in the middle of a diet, most parts of your diet data will carry over seamlessly. However, because we have significantly changed how [checking in meals](/docs/diet-coach-app/1.22-beta/features/checking-in/) works, you should be aware of how that will be migrated over:
* If, before upgrading, you checked in a meal
    * "at macros" or did not check it in at all (and it's before the current time), your meal will be checked in at target macros in the beta version.
    * "below macros", your meal will be checked in at 50% of the target macros.
    * "over macros", your meal will be checked in at 150% of the target macros.
* If, before upgrading, you didn't check in a meal that was scheduled for a time before you upgraded, your meal will be checked in at target macros in the beta version.

# Debugging Information

There are some elements in the app that currently exist primarily to provide you with context and debugging information, specifically to help you to better understand what might be going on "under the hood", so that you can more effectively determine if something is really amiss and to provide better feedback.

Here are a few examples of such debugging information:
* On the "Schedule" tab, each day has some text under the day target calories and macros that shows the wee's "Trending towards" and "Target" calories. These refer to the [average daily calories you're trending toward for the week](/docs/diet-coach-app/1.22-beta/concepts/calories/#trending-toward-average) and the [average daily calories you've selected as your target for the the week](/docs/diet-coach-app/1.22-beta/concepts/calories/#target-average-daily-calories), respectively.
* On the "Schedule" tab, under the "Step Count Target" card, there's a card that indicates a number of meals and a time range. The number of meals represents your preference for how many meals the app should program for you for that day, and the time range is when you want the app to program meals for you each day ([replacing sleep periods](/docs/diet-coach-app/1.22-beta/concepts/sleep/)).

# Feature Incomplete

This beta represents a major change to the RP Diet Coach App, and so we have had to minimize its scope to only those changes and features that are absolutely required to run successful diets.

We are already aware of numerous improvements that we will make after we launch this new version publicly.

If there are features and functionalities you wish the app had, they're probably already on our backlog! But that shouldn't stop you from providing feedback anyway--that will help us to gauge the relative importance of those features.

Of course, depending on what we learn, we may significantly change the functionality of certain features and remove others. The fact that something works a particular way in this beta does not guarantee that it will work the same way when we launch publicly. We may also change the visual look and feel of the app.

# Nondisclosure

With a public beta like this, it's inevitable that some folks will post screenshots and otherwise comment publicly on this new version, whether because they didn't read this section or because, in their excitement, they forgot!

Particularly because there is so much in flux with the app, we request that you try hard to remember to not post anything on social media or on any public forum about this new version and what you learn about it. We know you're excited about it, but the point of this public beta is for you to deliver constructive criticism to us directly and then allow us to make needed app updates. We don't want to get the public's hopes up or otherwise get them worked up about things we'd fix before launching it to them!

# How to Provide Feedback

The best way to deliver feedback and to get help is to tap on the "Me" tab in the app, go to "Help", and then fill out and submit the form on the "Contact Us" page. That will automatically provide useful information about your app and device.

However, if you are unable or you prefer, you can also email us at [diet-app-beta@rpstrength.com](mailto:diet-app-beta@rpstrength.com). If you choose to email us, make sure to provide the device model and OS version and your app version number. One place to find this information is in the app: Navigate to the "Me" tab, then "Help", then "About". Either include those in your email as text or take a screenshot of that page and attach it to your email.

Whichever approach you use, please provide screenshots or a screen recording and as much information about what you were doing, what you expected to happen, what actually happened, and whether you can reliably reproduce the problem. Timely feedback (ie, as soon as the problem occurs) is most helpful, as that allows us to investigate issues that could be connected with your specific account data before you take further action that might wipe out evidence that provides valuable context.

If you submitted the "Contact Us" form in the app, you can send screenshots and screen recordings by replying to the acknowledgement email you receive after submitting the form.

Check out these resources for taking screenshots and recordings:
* iOS
  * [screenshots](https://support.apple.com/guide/iphone/take-a-screenshot-iphc872c0115/ios){:target="&lowbar;blank"}
  * [screen recordings](https://support.apple.com/guide/iphone/take-a-screen-recording-iph52f6e1987/ios){:target="&lowbar;blank"}
    * If you want to narrate your screen recordings, tap and hold the screen recording control form your Control Center, then tap on the microphone icon so that it turns red and is captioned "Microphone On". Then tap the "Start Recording" button.
* [Android](https://support.google.com/android/answer/9075928?hl=en){:target="&lowbar;blank"}

# Enrolling in the Beta

Note that if you cannot join the beta, the testing pool may be full. Don't despair--we will launch publicly as soon as possible!

## iOS

1. If you don't already have it, install the TestFlight app:<br />
Option 1: [Direct Link](https://apps.apple.com/app/testflight/id899247664){:target="&lowbar;blank"} (Make sure to tap on this link from your iPhone!)<br />
Option 2: Manual Search and Installation
    1. Open the App Store on your iPhone.
    2. In the search bar, enter "TestFlight".
    3. Locate the "TestFlight" app in the search results (make sure that "Apple" is the developer of the app) and tap the "Get" or download icon to install it.
2. Join the beta testing program:
    1. After installing TestFlight, [join the "Open External Beta" TestFlight group](https://testflight.apple.com/join/k6rTNPTe){:target="&lowbar;blank"}. (Make sure to tap on this link from your phone!) This link will automatically open the TestFlight app and display the RP Diet Coach app beta invitation.
    2. Tap "Accept" to join the beta testing program.
3. Install the beta version of the app: Within TestFlight, after accepting the invitation, you will see the RP Diet Coach App listed. Tap the "Install" button next to the app to download and install the beta version. (If you already have the RP Diet Coach App installed, this beta version will replace the existing app on your device.)

## Android

1. Install the RP Diet Coach app:<br />
Option 1: [Direct Link](https://play.google.com/store/apps/details?id=com.rp.rpdiet){:target="&lowbar;blank"} (Make sure to tap on this link from your Android phone!)<br />
Option 2: Manual Search and Installation
    1. Open the Google Play Store on your Android device.
    2. In the search bar, type "RP Diet Coach & Macro Planner" and tap the search icon.
    3. Locate the app in the search results and tap "Install" to download and install it on your device.
2. Join the beta testing program:<br />
Option 1: [Direct Link](https://play.google.com/store/apps/details?id=com.rp.rpdiet){:target="&lowbar;blank"} (Make sure to tap on this link from your Android phone!)<br />
Option 2: Manual Enrollment
    1. Open the Google Play Store and navigate to the RP Diet Coach App’s page.
    2. Scroll down to find the "Join the beta" section.
    3. Tap "Join" to enroll in the beta testing program.
    4. A confirmation dialog will appear; tap "Join" again to confirm. (It may take a few minutes for your account to be added to the beta program.)
3. Update to the beta version:
    1. Once you’ve joined the beta program, return to the RP Diet Coach App’s page in the Google Play Store.
    2. If a beta version is available, you’ll see an option to update the app.
    3. Tap "Update" to install the beta version over your existing app.