# Activity Report — Privacy Policy

*Last updated: October 28, 2026* · [Version française](privacy-policy.fr.md)

Activity Report is a macOS app that writes your daily stand-up from your GitHub activity, your meetings, your reminders and your own notes. It is built so that your data stays on your Mac.

**In short: the developer collects no data. There is no account, no analytics, no advertising and no tracking. The app only talks to GitHub, with your own token, to read your activity.**

## What the app reads, and where it goes

| Data | Why | Where it goes |
|---|---|---|
| Your GitHub personal access token | To read your GitHub activity | Stored in your macOS keychain. Sent only to GitHub (`api.github.com`), over HTTPS. |
| Your GitHub activity: events, pull requests, reviews, team memberships | To write the report and list your pull requests | Requested from GitHub with your token, shown in the app. Never sent anywhere else. |
| Your calendar events of the reported day | To list your meetings | Read on your Mac through the macOS Calendar (EventKit). Never sent anywhere. |
| Your reminders | To list what you completed and what is due | Read on your Mac through the macOS Reminders (EventKit). Never sent anywhere. |
| Your notes (*Next*, *Blockers*) and the stand-up texts you copy | To keep them for a year, and to write recaps | Stored in the app's folder on your Mac, deleted after a year. |
| Your pull requests over a period of up to a year | To write a recap, when you ask for one | Requested from GitHub with your token, then summarized on your Mac by Apple Intelligence (Apple's on-device model). Never sent anywhere else. |
| Your settings (language, organizations, ticket links, formats) | To remember your choices | Stored in the app's preferences on your Mac. |

Calendar and reminders access is asked by macOS the first time; you can turn it off at any time in System Settings › Privacy & Security.

When you copy the stand-up text, it is put on the clipboard so that you can paste it, in Slack or Google Chat for example. What happens to it there is up to you and to those services.

## What the developer receives

Nothing. The app contains no analytics, crash-reporting or advertising code, and it sends nothing to the developer. If you choose to share crash reports and analytics with app developers in macOS settings, Apple may share anonymous crash reports with the developer, under [Apple's privacy policy](https://www.apple.com/legal/privacy/).

## Third parties

- **GitHub** receives the requests the app makes with your token, as with any GitHub client. See the [GitHub Privacy Statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).
- **Apple** distributes the app and handles any purchase made through the App Store. See the [Apple Privacy Policy](https://www.apple.com/legal/privacy/).

## Keeping and deleting your data

- Notes and copied stand-up texts are deleted automatically after a year; you can also delete a copy from the History screen.
- Your token can be replaced in Settings › GitHub, or removed with the Keychain Access app (item "ActivityReport.GitHubToken").
- Deleting the app and its folder (`~/Library/Containers/com.benjdum59.ActivityReport`) removes everything it stored. You can also revoke the token on GitHub at any time, in Settings › Developer settings › Personal access tokens.

## Children

The app is a work tool and is not directed at children.

## Changes

If this policy changes, the new version will be published at this address, with its date.

## Contact

Questions about this policy: benjamin.dumont.pro@gmail.com
