# FocusGuard privacy policy

_Last updated: 15 November 2026_

FocusGuard is built so that **nothing leaves your phone**.

## What the app accesses
FocusGuard uses Android's **Accessibility service** for one purpose: to limit Facebook, X and the other sites and apps you choose to limit or block.
- It checks **which app is open** (the app's package name only).
- In **Chrome only**, it reads the **web address in the address bar** to recognise blocked sites (like facebook.com) and Facebook/X video pages (like Reels), for scrolling breaks.
- It does **not** read messages, passwords, page content or anything typed in other apps.

## What the app stores (on your phone only)
- Minutes of use of your blocked sites and apps per day, and minutes added to your allowed hours by breaks, kept for 7 days.
- The start and end time of the latest scrolling break. Non-stop minutes are only kept in memory.
- Your settings: daily limit, bonus minutes, allowed hours, limited list, scrolling breaks, child mode, its always-blocked list and short parent openings, and your partner's WhatsApp number.
- **Child mode only, activity report for the parent:** website names visited in Chrome (for example youtube.com)
  with minutes, search words from Google, YouTube, Bing and DuckDuckGo searches in Chrome (incognito too), blocked
  attempts, and time per app. Kept for **today and yesterday only**, deleted when child mode is turned off, and only
  viewable with the parent's code. The child's home screen says that this report exists.
- Partner unlock counters (last code used, wrong attempts).
- The partner unlock secret, stored in the **Android Keystore**, where even FocusGuard can't read it back.

Outside the child-mode report, web addresses are checked in memory and **never stored**. Nothing is ever written to
the system log.

## What the app sends
**Nothing.** FocusGuard has no internet permission, no accounts, no ads and no analytics or crash reporting.
When you tap "Ask partner on WhatsApp", WhatsApp opens with a message that **you** choose to send.
It never contains a code. In child mode, "Send to parent on WhatsApp" opens WhatsApp with the day's report summary,
which the parent chooses to send.

## Deleting your data
Uninstalling FocusGuard, or **Settings › Apps › FocusGuard › Storage › Clear data**, deletes everything above.

## Contact
Questions: [open an issue](https://github.com/mumtazmaqsood/focusguard-releases/issues/new/choose).
