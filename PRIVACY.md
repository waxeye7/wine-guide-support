# Wine Guide: Cellar & Pairings, Privacy Policy

Effective date: 15 October 2026

This policy covers the Wine Guide: Cellar & Pairings app for iPhone (iOS) and Android. The developer is Merlin Robin Stemmer. Contact details are at the end.

## The short version

- Your cellar, tasting notes, quiz answers and reminders stay on your device. We have no servers that receive them.
- There is no account, no ads, no advertising identifier and no analytics.
- Two features do send data off your device: the live wine catalog search (to VinoFYI) and the app update check (to Expo). Both are explained below.
- On iPhone only, Wine Guide Pro subscriptions are handled by Apple and RevenueCat. Android has no purchases.

## What stays on your device

Your cellar, tasting notes, own bottles, drink-by reminders, quiz answers and fridge selections are stored on your device only. The app does not upload them to the developer or to anyone else. The developer holds no account data about you, because there are no accounts.

Some features depend on the platform:

- Fridge mode and Pro features such as tasting notes and drink-by reminders are part of Wine Guide Pro, which is available on iPhone only for now.
- If you tap Export in Settings, the app builds a CSV file on your device and hands it to your phone's share sheet. Where it goes is your choice. The app sends it nowhere itself.

## Catalog search and wine pages (VinoFYI)

Wine reference content that is not built into the app comes from the VinoFYI wine encyclopedia (vinofyi.com), a third-party service that we do not run. VinoFYI's own terms and practices apply to what it receives. We did not find a privacy policy published by VinoFYI, so we cannot tell you how long it keeps requests.

What the app sends:

- **Catalog search.** When you type 3 or more characters in the catalog search box, the app sends the text you typed to VinoFYI after a short pause. This is not limited to wine names. Whatever you type is sent, so do not type anything you want to keep private.
- **Opening a page.** When you open a grape, region or wine page that is not built into the app, the app requests that page from VinoFYI, so VinoFYI can see which page you opened.
- **Normal request data.** Like any internet request, these requests expose your device's IP address and a standard user agent to VinoFYI. The app does not add cookies, an account ID, a device ID or custom identifiers.

What the app does not send: your cellar, notes, quiz answers, reminders, purchase information or any identifier of yours.

The app also keeps a copy of recent results on your device so they load faster. That copy stays on your device.

If you do not want to send anything to VinoFYI, do not use the live catalog search or open pages that are not built in. The rest of the app works from its built-in catalog. When live search is unavailable, the app shows the built-in catalog.

Links to VinoFYI pages, GitHub and Apple's terms open in your phone's own browser. The app sends nothing when you tap them, but the site you visit then applies its own policy.

## App update check (Expo)

The app checks for updates to its own code through Expo's update service (u.expo.dev, with downloads from Expo's asset hosts). The check happens when the app starts and again when you return to it, at most about once an hour. The request includes a random install identifier created by Expo's update library, the platform (iOS or Android) and the app's runtime version, and it exposes your IP address. The identifier is not your name, your email or your advertising ID. We do not add a user ID or any of your data. The check is used only to deliver app updates, never for advertising. Expo's own privacy policy applies to its handling of these requests.

## Purchases (iPhone only)

Wine Guide Pro is a subscription available on iPhone only. Apple takes the payment. RevenueCat (react-native-purchases) processes the subscription so we can unlock Pro features. RevenueCat receives an anonymous app user ID and your purchase history. It is not linked to your name, email or any account we hold. See https://www.revenuecat.com/privacy.

On Android, Pro cannot be bought, and the app does not contact RevenueCat or use Google Play Billing for purchases.

## Notifications

Reminders and the optional Friday bottle pick are local notifications scheduled on your device. The decant timer works the same way. No push notification server is used, no push token is created, and nothing about them leaves the phone.

## Android backup

On Android, your phone's own backup feature may include the app's data, such as your cellar, notes and quiz answers, in your Google account backup and restore it on a new phone. That backup is controlled by you through your phone and Google account settings. It is not sent to the developer. You can turn it off in your phone's settings.

## What we don't do

- No ads and no advertising identifiers
- No account or sign-in
- No analytics. This release does not send crash reports or usage data to anyone.
- No sale of data. We do not sell your information and we do not share it for advertising.
- No location access

## Who data goes to

- **VinoFYI:** catalog search text, the pages you open, and normal request data (see above).
- **Expo:** update check request data (see above).
- **Apple and RevenueCat (iPhone only):** subscription and purchase data (see above).

Apart from these, we do not share data with anyone. Apple and Google run the app stores and have their own policies for downloads and billing.

## Keeping and deleting your data

- Data on your device stays there until you remove it. Uninstalling the app or clearing its data deletes it. In the app you can also use Settings and choose "Erase all my data", which wipes the app's local data.
- On Android, a copy in your phone's backup is kept by your Google account until you delete the backup.
- The developer holds no account data about you, so there is nothing to delete on our side. We cannot delete requests held by VinoFYI, Expo, Apple or RevenueCat. Each has its own process, and you can ask us to point you to it.
- To ask a question or make a request about your data, write to the contact below.

## Age

Wine Guide is about wine and is for adults of legal drinking age. It is not directed at children, and we do not knowingly collect personal information from anyone under 18. If you believe a child has given us information, contact us and we will help.

## Changes

If this policy changes, the new version will be published at the same address with a new effective date.

## Contact

Developer: Merlin Robin Stemmer

Email: stemmermerlin@gmail.com

Issues: https://github.com/waxeye7/wine-guide-support
