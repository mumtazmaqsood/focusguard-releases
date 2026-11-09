# FocusGuard

**Spend less time on Facebook and X.** FocusGuard gives Facebook and X (Twitter) one shared daily allowance
(60 minutes by default), whether you use them in **Chrome** or in their **apps**. When the time is used up,
they're blocked until midnight. They're also only allowed during your **allowed hours** (14:00–19:00 by default). You can
add more **websites and apps** to the block list. Need more time? Only your **partner** can give it, with a one-time code from
their Google Authenticator that you ask for on WhatsApp.

> 🧪 **Early test version.** Please [send feedback](../../issues/new/choose): bugs, ideas, anything that confused you.

## Download
➡️ **[Latest release](../../releases/latest)** › under *Assets*, tap **`FocusGuard-<version>.apk`**.

Requires Android 8.0 or newer. Tested on a Samsung Galaxy A51 (Android 13).

## Install (about 2 minutes)
1. Open the release page **on your phone** and tap the `.apk` file to download it.
2. Open the downloaded file. Android asks to **allow installing from this source** (Chrome or My Files).
   Allow it, go back and tap **Install**.
   - Google Play Protect may say it doesn't recognise the app. Tap **More details › Install anyway**.
     This is normal for apps that aren't from the Play Store.
3. Open **FocusGuard** and tap **Turn on blocker**. Read the explanation and tap **Agree and continue**.
4. In Accessibility settings, tap **Installed apps › FocusGuard blocker › On › Allow**.
   - ⚠️ **"Restricted setting" message?** Android 13+ does this for apps installed from a file. Fix it:
     **Settings › Apps › FocusGuard › ⋮ (top right) › Allow restricted settings**, then repeat step 4.
5. In FocusGuard, open **Settings**: set your daily limit and your partner's **WhatsApp number**
   (with country code, e.g. `+923001234567`).
6. **Set up with partner** (do this together): your partner installs **Google Authenticator**, taps
   **+ › Scan a QR code**, scans the code on your screen, and you type in the 6-digit code their app shows.

**Samsung tip:** so the blocker keeps running, go to **Settings › Battery › Background usage limits ›
Never sleeping apps** and add FocusGuard.

## How to use it
- The home screen shows how many minutes are left today.
- At the limit, blocked sites and apps show a **"Time's up"** screen. Outside your allowed hours, they show
  **"Not allowed right now"**. In Chrome, **Keep browsing other sites** takes you out (other websites keep
  working). In the apps, **Go to home screen** does.
- **More time:** tap **Ask partner on WhatsApp**. Your partner replies with the current code from Google
  Authenticator, you enter it, and you get bonus minutes (15 by default). Each code works once.
- **Settings** lets you change the allowed hours and add websites (e.g. instagram.com) or apps to the block list.
  Everything on the list shares the daily limit and the hours.
- Raising your limit or bonus, widening the hours, removing something from the block list, or changing your partner
  also needs a partner code. Making the rules stricter
  doesn't.

## Update
Download the newer `.apk` from [Releases](../../releases) and install it over the old one.
Your settings and partner setup are kept.

## Uninstall
Long-press the FocusGuard icon › **Uninstall** (or **Settings › Apps › FocusGuard › Uninstall**).
This deletes all usage data, settings and the partner secret. Ask your partner to delete the
**FocusGuard (Partner unlock)** entry in Google Authenticator. Codes from it can never work again.

## Privacy
FocusGuard has **no internet permission** and no ads or analytics. Nothing leaves your phone.
See [PRIVACY.md](PRIVACY.md).

## Known limitations (test version)
- Only **Chrome** is checked. Other browsers (Samsung Internet, Firefox) aren't blocked yet.
- The blocker can still be switched off in Accessibility settings, or the app uninstalled. Stronger protection
  is planned.
- Changing the phone's date *and then restarting the phone* can start a new day early.

## Feedback
[Open an issue](../../issues/new/choose) → **Bug report** or **Idea**. A free GitHub account is needed.
Screenshots help a lot (but the partner setup screen can't be screenshotted, on purpose).
