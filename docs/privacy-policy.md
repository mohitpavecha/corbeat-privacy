---
layout: default
title: Corbeat Privacy Policy
---

# Corbeat Privacy Policy

**Effective date:** October 17, 2026
**App:** Corbeat (Android, package `app.corbeat`)
**Developer:** Mohit Pavecha
**Contact:** jain98mohit@gmail.com

Corbeat is a personal recovery, strain and sleep app. It reads health and fitness data that you choose to share from your phone and your wearable, and turns it into scores and guidance. This policy explains what data the app uses, where it goes, and the choices you have.

**The short version:** Corbeat has no account and no servers. Your health data is processed and stored on your phone. We do not receive it, sell it, share it for advertising, or use it to track you. The app contacts only Google (to read the health data you allow) and OpenStreetMap (to draw workout maps).

## 1. What Corbeat uses

### Health and fitness data you allow

When you connect a data source, Corbeat reads, with your permission:

| Data | Used for |
|---|---|
| Heart rate | Strain, heart rate zones, workout and sleep charts |
| Resting heart rate | Recovery, Physical Age |
| Heart rate variability (HRV) | Recovery |
| Sleep sessions and stages | Sleep Score, sleep coach, Recovery |
| Steps | Daily steps, Physical Age |
| Exercise sessions (workouts) | Activities, Strain, training load |
| Weight | Weight history |
| Respiratory rate, skin temperature and blood oxygen (SpO₂) | Detecting signs of illness for Recovery, and the Health tab |
| Body fat, lean mass, bone mass and blood pressure (only if you allow them) | The Health tab: your latest value, history and range |
| Blood glucose and body temperature (only if you allow them) | The Health tab history |
| Active and total calories, resting energy, distance and floors climbed (only if you allow them) | The Health data list in Profile |
| Water and calories eaten (only if you allow them) | The Health data list in Profile |
| VO₂ max | Physical Age and the Health tab |
| Workout routes and exercise location (only if you grant the separate location permission) | The route map and pace, elevation and split charts |
| Health history older than 30 days and background access (only if you grant them) | Building your personal baselines and keeping scores up to date |

The extra items marked "only if you allow them" are optional: Health Connect asks for them on a separate screen, Corbeat works without them, and anything you do not allow is never read. Corbeat keeps up to a year of history on your phone for these readings, and a month of per-minute heart rate.

This data comes from two places, both of which ask for your permission first:

- **Android Health Connect**, using the Health Connect permissions you grant in the system permission screen.
- **The Google Health API**, a Google service that gives access to Fitbit and Google health data. Corbeat asks you to sign in with Google and approve read-only access to sleep, activity and fitness, health metrics and measurements, and (optionally) location data. Corbeat never writes to your health data.

### Information you give the app

- Your name (used for the greeting), date of birth, and optionally your sex, used for the Physical Age estimate.
- Your preferences: units, theme, sleep goal, steps goal, usual wake-up time, reminder time, and notification and backup choices.
- Journal entries you log for a night (for example alcohol, a late meal or high stress), including when you answer the daily "How was last night?" prompt, and manual log entries such as a weight or a workout.

### Information the app creates

Recovery, Strain, Sleep and Physical Age scores, your personal baselines, charts and sleep plans are calculated on your phone from the data above.

### What Corbeat does not collect

Corbeat does not use your phone's location (GPS), contacts, photos, microphone, camera or advertising ID. It has no analytics, advertising or crash-reporting libraries.

## 2. Where your data is stored

Everything is stored on your phone, in the app's private storage:

- Your scores, baselines, journal, manual entries and profile are in a local database.
- Raw readings pulled from your health sources are kept in a separate local cache that the app can rebuild by syncing again.
- Your Google sign-in tokens are encrypted using the Android Keystore.
- Map tiles you have viewed are cached on your phone so a route can reopen without another request.

Corbeat does not send this data to the developer or to any server we operate, because we do not operate one.

## 3. Who else sees data

Corbeat makes network requests only in these cases, always over HTTPS:

- **Google.** To sign you in and read the data you approved from the Google Health API. Google handles that data under its own privacy policy: <https://policies.google.com/privacy>. Health Connect itself works on your phone.
- **OpenStreetMap.** When you open the route map of a workout, the app downloads the map squares (tiles) that cover the route from `tile.openstreetmap.org`. This tells the tile server which map areas were requested, so roughly where the workout happened, along with your IP address. No account, name or workout data is sent. Map data is from OpenStreetMap contributors (<https://www.openstreetmap.org/copyright>), and the tile service's privacy policy is at <https://wiki.osmfoundation.org/wiki/Privacy_Policy>.

We do not sell your data, share it with advertisers or data brokers, or use it for advertising, credit decisions or insurance.

**Google API Services User Data Policy.** Corbeat's use and transfer to any other app of information received from Google APIs will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements. Health Connect data is used only to provide the features described in this policy.

## 4. Backups and exports

- **Android Auto Backup.** Auto Backup is on by default and can be switched off in Profile. When it is on, Android may back up your Corbeat database (scores, baselines, journal and profile) to your own Google account, under Google's backup terms. The raw cache and your sign-in tokens are never included.
- **Export file.** In Profile you can export your data to a file protected with a passphrase you choose (AES-256 encryption). Only that passphrase opens it, and there is no way to recover a forgotten one. Where the file is saved and who you give it to is up to you.

## 5. Notifications and widgets

- **Notifications** (a daily Recovery reminder, a weekly Physical Age update and an optional bedtime nudge) are created on your phone. They need the notification permission and can be turned off in the app or in Android settings.
- **Home-screen widgets** show today's Recovery, Strain and Sleep scores. They read from your phone and never connect to the internet. Anyone who can see your home screen can see them, so remove the widgets if you prefer.

## 6. Keeping your data safe

Data stays in the app's private storage, sign-in tokens are encrypted with the Android Keystore, and all network traffic uses HTTPS. No method of storage is perfectly secure, so keep your phone locked and your Android version up to date.

## 7. How long data is kept, and deleting it

Your data stays on your phone until you delete it. You can remove it at any time:

- **Delete all data in the app.** Profile has a Delete all data option. It erases your scores, baselines, journal and profile, the cache of synced readings, your Google sign-in, the saved map tiles and the app's settings from your phone, cancels its scheduled reminders, and returns the app to setup.
- **Stop sharing from Health Connect or Google.** Corbeat's permission in Health Connect is controlled by Android, so remove it in Android's Health Connect settings. You can also revoke Corbeat's access to your Google data at <https://myaccount.google.com/permissions>.
- **Disconnect an account without deleting.** In Profile you can disconnect Google or Health Connect on its own to stop Corbeat reading from it, and keep your history.
- **Uninstall the app.** This removes everything Corbeat stored on the phone.
- **Backups.** If Auto Backup was on, Google may keep a copy in your Google account. Switch Auto Backup off in Profile, and remove the backup from your Google account's backup settings, if you want it gone.

Because Corbeat has no server, we have no copy of your data to delete or hand over on request. You hold the only copy, and the steps above give you full control of it.

## 8. Not medical advice

Corbeat gives wellness estimates, not medical advice, diagnosis or treatment, and is not a medical device. Do not use it to decide on medical care. See a health professional with any health concern.

## 9. Children

Corbeat is not directed to children under 13, and we do not knowingly collect data from them. If you believe a child has used the app, delete the data using the steps above.

## 10. Your rights

Depending on where you live, you may have rights to access, correct, delete, export or restrict the use of your personal data. In Corbeat you can view your data in the app, correct your profile in Profile, export it with the encrypted export, and delete it with Delete all data. For anything else, contact us at the address above.

## 11. Changes to this policy

If this policy changes, we will update the date at the top and describe the change in the app's release notes. Material changes will be shown in the app before they take effect.

## 12. Contact

Questions about this policy or your data: **jain98mohit@gmail.com**
