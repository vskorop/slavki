---
title: Slavki Privacy Policy
permalink: /privacy/
---

<!--
Source of https://vskorop.github.io/slavki/privacy/ (TD-052).
Before publishing, replace the two [placeholders] below.
Publish: copy this file to privacy.md in the public `slavki` repository and enable
GitHub Pages (Settings → Pages → Deploy from branch → main, root). Jekyll uses the
permalink above.
-->

# Slavki Privacy Policy

Effective: 26 November 2026

Slavki is an ebook reader that helps you learn the words you meet while reading. This
policy explains what the app stores, what leaves your device, and why.

## Short version

- Your books stay on your device. We never upload book files.
- Without an account, everything stays on your device.
- With an account and Slavki Plus, your vocabulary and progress sync through our server
  so they're on all your devices.
- When you look up a word online, the word and its sentence are sent to translate it.
- Usage statistics are anonymous, never include your words or books, and can be turned
  off.
- We don't sell your data and don't show ads.

## What stays on your device

Books you import, your vocabulary, study progress, reading positions, bookmarks and
settings are stored on your device. Reminders are scheduled on your device.

## Your account

You can use Slavki without an account. If you sign in, we store your **email address**
to send you sign-in links and to identify your account.

## Sync (Slavki Plus)

With Slavki Plus, the app copies the following to our server so your other devices get
them:

- your vocabulary: words, translations, definitions, the sentences you saved them from;
- folders, sets and study history (answers and review dates);
- the titles, authors and chapter names of your books, and your reading positions and
  bookmarks (not the book files);
- your reminders and app settings.

The server is run by Supabase ([region placeholder]). Only your account can read this
data.

## Word lookups

When you look up a word and it isn't in a dictionary downloaded on your device, the app
sends **the word and the sentence it appears in** to our server, which asks a
translation service and returns the answer. The services are DeepL and Anthropic
(Claude). They receive the word and sentence only, not your email or account. Results
are saved on your device so the same lookup isn't sent twice. To prevent abuse, our
server counts lookups per IP address for up to a day; it doesn't keep the words or
sentences.

Offline dictionaries work without sending anything.

## Purchases

Subscriptions are processed by Apple (App Store) or Google (Google Play); we never see
your payment details. RevenueCat manages subscription status and receives a random
account identifier and your purchase history for Slavki.

## Usage statistics

If allowed, the app sends anonymous usage events to PostHog, such as "a word was saved"
or "a study session finished, 12 words". They contain no words, sentences, book titles
or email, and use a random identifier for your installation. Turn this off any time in
**Profile → Privacy → Share anonymous usage**; then nothing is sent.

## Crash reports

If the app crashes, a technical report (device model, system version, the error) is
sent to Sentry so we can fix it. Book text, words and your email are removed before
it's sent.

## Sharing vocabulary

When you share a folder or set, the app creates a file with those words and sentences
and hands it to the app you choose. We don't receive it.

## Keeping and deleting data

Delete your account in **Profile → Account → Delete account**. This removes your account
and everything synced to our server. Data on your device is removed when you delete the
app.

## Children

Slavki is not directed at children under 13, and we don't knowingly collect their data.

## Your rights

You can ask to see, correct, export or delete your data. Write to [contact email].

## Changes

If this policy changes, we'll update this page and its date; significant changes will
be shown in the app.

## Contact

[contact email]
