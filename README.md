# 🤖 Gemini and Your Android Messages: What Google Can See, and How to Limit It

![Android](https://img.shields.io/badge/Android-Gemini-3DDC84?logo=android&logoColor=white)
![Type: privacy guide](https://img.shields.io/badge/Type-privacy%20guide-d73a49)
![Apps: Messages, Phone, WhatsApp](https://img.shields.io/badge/Apps-Messages%20%7C%20Phone%20%7C%20WhatsApp-5c2d91)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey)](LICENSE)

**📄 [Download the PDF](Android-Gemini-Messages-Privacy.pdf)**

## 📖 Overview
In mid-2025, Google emailed some Android users to say that from **July 7, 2025**, Gemini would be able to help with Phone, Messages and WhatsApp **whether or not Gemini Apps Activity was on**. That wording alarmed people, and videos like **Useful Things'** [Now GOOGLE SEES YOUR MESSAGES on YOUR PHONE. Turn This Off](https://www.youtube.com/watch?v=Ee3UIVDkWNM) (July 2025) showed how to turn Gemini Apps Activity off.

The catch is that, according to Google's own help pages, **turning that setting off doesn't stop Gemini using those apps**. This guide explains what Gemini can and can't do with your messages, which settings actually control it, and which of your conversations are end-to-end encrypted.

## ⚠️ Important Notes
* **Turning off Keep Activity (formerly Gemini Apps Activity) doesn't disconnect Gemini from your apps.** Google's pages say Phone, Messages and WhatsApp still work with it off. To stop that, disconnect the apps (Section 3).
* **Turning it off doesn't stop all human review either.** Google says reviewers may still see chats to keep its services safe (Section 4).
* **Menus change often.** Google renames Gemini's settings regularly. If a label doesn't match, look for the nearest equivalent, and check Google's linked pages.

## 🚀 How to Use
Download the PDF above, or read on below. **The Short Version** gives the key settings. Section 3 is the one that actually disconnects Gemini from your messages.

Using an iPhone too, or texting people who do? See the companion guide, [iPhone Messages and AI Privacy](https://github.com/ImmuneMoon/iPhone-Messages-AI-Privacy).

---

<!-- guide:start -->

*Checked against Google's own help pages in November 2026. Each section says whether it comes from the video or from added research.*

**Source video:** [Now GOOGLE SEES YOUR MESSAGES on YOUR PHONE. Turn This Off](https://www.youtube.com/watch?v=Ee3UIVDkWNM) by Useful Things. Sections marked **Added** come from Google's documentation and other research, listed in Sources.

## The Short Version

- **To stop Gemini using Messages, Phone and WhatsApp:** in the Gemini app, go to **Menu** ▸ **Customize** ▸ **Connectors**, and disconnect each app (Section 3).
- **To stop your Gemini chats being saved and used to improve Google's AI:** turn off **Keep Activity**, as the video shows (Section 4). It doesn't disconnect your apps.
- **To delete what's already saved:** use **Gemini Apps Activity** ▸ **Delete** (Section 5).
- **To hide Gemini inside Google Messages:** turn off **Show Gemini button** in Messages settings (Section 6).
- **To keep conversations private in transit:** use RCS chats with end-to-end encryption, shown by a lock icon. SMS isn't encrypted (Section 7).

## Contents

1. [What Changed in July 2025](#1-what-changed-in-july-2025)
2. [What Gemini Can and Can't Do With Your Messages](#2-what-gemini-can-and-cant-do-with-your-messages)
3. [Disconnect Gemini From Your Apps](#3-disconnect-gemini-from-your-apps)
4. [Turn Off Keep Activity](#4-turn-off-keep-activity)
5. [Delete What's Already Saved](#5-delete-whats-already-saved)
6. [Gemini Inside Google Messages](#6-gemini-inside-google-messages)
7. [Which of Your Messages Are Encrypted](#7-which-of-your-messages-are-encrypted)
8. [Texting People With iPhones](#8-texting-people-with-iphones)
9. [Quick Checklist](#9-quick-checklist)
10. [Sources](#10-sources)

---

## 1. What Changed in July 2025

*From the video, with added detail from Google and news reports.*

The video explains that some users, but not all, got an email from Google about a change starting **July 7, 2025**. Gemini would gain access to apps on your phone, such as Messages and WhatsApp. The email also mentioned that some data may be reviewed to improve quality and safety, which the video points out means real people might see it.

News coverage of the email quoted its key line: Gemini would help with Phone, Messages, WhatsApp and Utilities **whether your Gemini Apps Activity is on or off**. Google later explained that the change lets you send messages, make calls and set timers with Gemini even with that setting off. It added that chats with the setting off aren't reviewed or used to improve its AI models, and that you can disconnect apps at any time.

The setting the video talks about, **Gemini Apps Activity**, is now usually labelled **Keep Activity** in Google's help pages. The activity page itself is still called **Gemini Apps Activity**.

---

## 2. What Gemini Can and Can't Do With Your Messages

*Added research, from Google's help pages.*

Google's help pages list what Gemini can do with your messaging apps:

| Gemini can | Gemini can't |
|---|---|
| Send messages and make calls through Messages, Phone and WhatsApp | Read or summarize messages directly inside your messaging apps |
| Read and reply to messages that appear in your **notifications**, through its **Device assistance** app, including WhatsApp notifications | Use these apps on its own, without you asking |

Google also says that even if you disconnect Messages, Gemini can still reach:
- **your contacts,** if the Google app has Contacts permission;
- **your notifications,** if the Device assistance app is connected.

Gemini's Messages feature also needs the **SMS** permission given to the Google app.

---

## 3. Disconnect Gemini From Your Apps

*Added research. This is the step the video doesn't cover.*

Google says Phone, Messages and WhatsApp keep working with Gemini **even when Keep Activity is off**. With Keep Activity off on Android, those apps and **Device assistance** are the only connected apps still available. So to stop Gemini using them, disconnect them.

In the Gemini app:

1. At the top, tap **Menu**, then **Customize**. If you don't see **Customize**, tap **More** first.
2. At the top, tap **Connectors**.
3. Tap the app you want to stop, such as **Messages**, **Phone** or **WhatsApp**.
4. Tap **More options**, then **Disconnect**.
5. Repeat for **Device assistance** if you don't want Gemini reading or replying to your notifications.

You can also manage connected apps from a computer at [gemini.google.com/apps](https://gemini.google.com/apps), as Google told reporters.

To go further, open your phone's **Settings** ▸ **Apps** ▸ **Google** ▸ **Permissions**. Remove **SMS** or **Contacts** access if you don't use Gemini for messages. Removing permissions can affect other Google features, so check anything you rely on afterward.

---

## 4. Turn Off Keep Activity

*From the video, with corrections and added detail from Google.*

This is the setting the video shows how to turn off. It controls whether your **chats with Gemini** are saved to your account and used to improve Google's AI. It doesn't disconnect your apps (Section 3).

**In the Gemini app** (the video's first method):

1. Open the Gemini app, tap **Menu** at the left, then your **profile picture** or initial.
2. Tap **Gemini Apps Activity**.
3. Near the top, tap **On**, then choose **Turn off**, or **Turn off and delete activity** to also clear what's saved.

**Through your Google Account** (the video's second method, if you can't find the Gemini app):

1. Open your phone's **Settings** ▸ **Google** ▸ **Google Account**.
2. Search for **Gemini Apps Activity** and open it.
3. Tap **Turn off**, and confirm.

### What turning it off changes, according to Google

| | With Keep Activity off |
|---|---|
| **Your future chats** | Not shown in your activity, and not used to train Google's AI, unless you send feedback |
| **How long chats are kept** | Still kept with your account for **72 hours**, so Gemini can respond and process feedback, and for safety |
| **Human review** | Turning it off stops your future chats being reviewed to **improve** Google's services. Google says it still uses chats, including with human reviewers, to protect its services and users |
| **Connected apps** | Phone, Messages, WhatsApp and Device assistance **still work** on Android |

### About human review

The video's warning that real people might see your data is right. Google says a **subset of chats** is reviewed by people, including trained service providers, to improve its services. Before review, chats are disconnected from your account. Reviewed chats are kept for **up to three years**, and **deleting your activity doesn't delete chats already reviewed**.

---

## 5. Delete What's Already Saved

*Added research.*

1. In the Gemini app, tap **Menu**, then your **profile picture** or initial, then **Gemini Apps Activity**.
2. Tap **Delete**, and choose a range, from **Last hour** to **All time**. You can also delete single items.

Two more things worth setting:
- **Auto-delete.** Google keeps activity for **18 months** by default. On the same page, you can change that to 3 or 36 months, or turn it off.
- **Other places stay untouched.** Deleting Gemini activity doesn't delete data in other Google services, or Gemini chats you had inside Google Messages (Section 6).

---

## 6. Gemini Inside Google Messages

*Added research.*

Google Messages can have a built-in Gemini chat, separate from the Gemini app.

- **Chats with Gemini in Messages aren't end-to-end encrypted,** unlike RCS chats with other people (Section 7).
- **It doesn't use connected apps,** and doesn't get your precise location.

To turn it off, open **Google Messages** settings ▸ **Gemini in Messages**, and turn off **Show Gemini button**. To delete a Gemini chat in Messages, open it and choose **More** ▸ **Delete conversation**.

---

## 7. Which of Your Messages Are Encrypted

*Added research, from Google's Messages help.*

**End-to-end encryption** means only you and the person you're messaging can read a message, not Google or your carrier.

| Message type | End-to-end encrypted? |
|---|---|
| **RCS chat between Google Messages users** | **Yes, by default,** if both have RCS chats turned on and use data or Wi-Fi |
| **SMS and MMS** | **No** |
| **Your chats with Gemini** | **No** |

**How to tell:** in an encrypted chat, a **lock icon** appears on the send button and next to each message's timestamp. Google's help describes RCS messages in dark blue bubbles and SMS in light blue, though colors can vary by theme.

**Two things that weaken encryption:**
- **Losing data or Wi-Fi** makes the conversation fall back to SMS, which isn't encrypted.
- **Once messages arrive on your phone,** Google says they're included in your **Android backup** and readable by **any app you've given SMS or notification permission**. End-to-end encryption protects messages in transit, not on your phone. That's one more reason to check which apps have those permissions (Section 3).

---

## 8. Texting People With iPhones

*Added research.*

Conversations between Android and iPhone use **RCS** or **SMS**:

- **SMS is never end-to-end encrypted.**
- **RCS can now be.** Google's help page says only Google Messages supports encrypted RCS. Apple's newer guidance says that from **iOS 26.5**, iPhones support end-to-end encrypted RCS as a beta, where carriers support it. That page shows **Encrypted** with a lock icon at the top of the conversation. So cross-platform encryption depends on both people's carriers. **Look for the lock icon** rather than assuming.

The companion guide, [iPhone Messages and AI Privacy](https://github.com/ImmuneMoon/iPhone-Messages-AI-Privacy), covers the iPhone side, including Siri, Apple Intelligence and iCloud backups.

---

## 9. Quick Checklist

- [ ] Disconnected Messages, Phone and WhatsApp from Gemini, if I don't use them with it
- [ ] Disconnected Device assistance, if I don't want Gemini reading notifications
- [ ] Turned off Keep Activity, if I don't want my chats saved or used to improve Google's AI
- [ ] Deleted past Gemini activity, and set auto-delete to 3 months
- [ ] Turned off the Gemini button in Google Messages, if I don't use it
- [ ] Checked which apps have SMS and notification access
- [ ] Look for the lock icon before sending anything sensitive

---

## 10. Sources

Checked in November 2026.

**Video**
- [Now GOOGLE SEES YOUR MESSAGES on YOUR PHONE. Turn This Off](https://www.youtube.com/watch?v=Ee3UIVDkWNM) by Useful Things

**Google**
- [Gemini Apps Privacy Hub](https://support.google.com/gemini/answer/13594961)
- [Use & manage Connected Apps in Gemini (Android)](https://support.google.com/gemini/answer/13695044?co=GENIE.Platform%3DAndroid)
- [Manage & delete your Gemini Apps activity (Android)](https://support.google.com/gemini/answer/13278892?co=GENIE.Platform%3DAndroid)
- [Send messages with Gemini on Android](https://support.google.com/gemini/answer/15574940)
- [Use WhatsApp with Gemini](https://support.google.com/gemini/answer/15574928)
- [Use Gemini in Google Messages](https://support.google.com/gemini/answer/14599070)
- [End-to-end encryption in Google Messages](https://support.google.com/messages/answer/10262381)

**News coverage of the July 2025 change**
- [Android Authority: Gemini Apps Activity email](https://www.androidauthority.com/gemini-apps-activity-email-july-7-3570651)
- [Gizmodo: Google's email about Gemini and your texts](https://gizmodo.com/google-to-gemini-users-were-going-to-look-at-your-texts-2000620141)

**Apple (for mixed conversations)**
- [Apple: iMessage, RCS and SMS/MMS](https://support.apple.com/en-us/104972)

<!-- guide:end -->

## ☕ Support the Project

If you find this project helpful and want to support further development by Fulllion Creative Works, consider leaving a tip!

* [Donate via PayPal](https://www.paypal.com/donate/?hosted_button_id=LCDZX75HR4CLC)
* [Support on Ko-fi](https://ko-fi.com/fulllion)

---
© 2026 Fulllion Creative Works. All rights reserved.
