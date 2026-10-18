# Privacy Policy for Minutely

**Last Updated**: October 18, 2026  
**Published by**: Sanoj Technologies

## Introduction

Welcome to Minutely, developed and published by Sanoj Technologies ("we", "our", or "us"). We respect your privacy and are committed to protecting your personal data. This privacy policy will inform you about how we handle your data when you use our mobile application.

## Information We Collect

### Data Stored Locally
- **Recordings**: Audio you record is saved as files in the app's private documents directory
- **Transcripts**: The text produced from your recordings, including speaker labels you assign
- **Meeting Notes**: Titles, summaries, key points and action items generated from your recordings
- **Session Details**: Timestamps, durations and playback positions stored in a local SQLite database
- **On-device Models**: Speech-to-text, speaker and summarisation models copied to app storage on first launch so they can run offline
- **App Preferences**: Display theme and other app configuration options

### Data We DO NOT Collect
- We do NOT collect any personal information
- We do NOT collect your name, email, or contact information
- We do NOT track your location
- We do NOT access or transmit your recordings, transcripts or summaries to any external servers
- We do NOT share any data with third parties
- We do NOT use analytics or tracking services
- We do NOT use advertising services
- We do NOT use cookies (there is no web version)

## How We Use Your Data

- **Recordings**: Saved locally so you can play them back and re-read their notes
- **Transcripts and Notes**: Generated locally and stored so you can search, review and export them
- **Speaker Labels**: Derived locally from your audio so transcript speakers can be named
- **Preferences**: Saved locally to remember your theme and display settings

## Data Storage

All data is stored locally on your device:
- **Sessions**: SQLite database (titles, transcripts, speaker labels, summaries) in the app's private database directory
- **Audio**: WAV files in the app's private documents directory
- **Models**: Copied from the app package into private app storage on first launch
- **Preferences**: Held by the operating system's app preferences storage

## Data Processing

**Important**: Recording, transcription, speaker identification and summarisation all happen entirely on your device. Minutely declares no network permission and contains no network client: your audio is never uploaded, and neither are your transcripts, notes or any statistics derived from them.

Sharing is something you do yourself: if you use the app's share action, you choose what to send and the receiving app (email, chat, cloud drive) handles it under its own privacy policy.

## Data Retention

- **Sessions and Recordings**: Persist until you:
  - Delete the recording inside the app
  - Clear app data or cache from system settings
  - Uninstall the app
- **On-device Models**: Remain in app storage until you clear app data or uninstall

## Backup

Minutely disables Android auto backup and device-to-device transfer for its app data, so recordings, transcripts and summaries are not copied to cloud backup services or moved to a new device by the system.

## Permissions We Request

- **Microphone**: Required to capture audio when you start a recording. Recording only happens while you have started a session.
- **Notifications**: Used for the ongoing "Recording" notification and its lock-screen Stop action while a session is in progress or being processed.
- **Wake Lock**: Keeps the CPU alive while a recording is processed so transcription is not interrupted by the screen switching off.

## Children's Privacy

Our app is suitable for all ages. We do not knowingly collect any personal information from children or anyone else, and the app does not send any information anywhere.

## Your Rights

You have the right to:
- Delete any recording and its notes at any time from the app
- Delete all your data by clearing app data or uninstalling the app
- Opt-out of any data collection (we don't collect any data anyway!)
- Access your locally stored data through the app's library and export features

## Third-Party Services

We currently do NOT use any third-party services, analytics, or advertising networks. Minutely is built on open-source libraries that run entirely on your device (including whisper.cpp, sherpa-onnx, llama.cpp, ffmpeg and SQLite), with speech, speaker and summarisation models bundled into the app.

## Changes to This Policy

We may update this privacy policy from time to time. We will notify you of any changes by posting the new policy in the app or on our website.

## Data Security

All data is stored locally on your device in the app's private storage and is subject to your device's security measures (screen lock, encryption at rest where your device provides it). Since all processing happens on-device, your recordings and transcripts never leave your device.

## Contact Us

If you have any questions about this Privacy Policy, please contact us at:
- **Company**: Sanoj Technologies
- **Email**: contact@sanojtechnologies.com
- **Website**: https://sanojtechnologies.com

## GDPR Compliance

For users in the European Union:
- We process no personal data
- No data transfers occur (all processing is local)
- No consent is required as no data is collected or transmitted
- All recording and transcription happens on your device

## CCPA Compliance

For California residents:
- We do not sell personal information
- We do not collect personal information
- We do not share personal information with third parties
- No opt-out is necessary

---

**Summary**: Minutely stores your recordings, transcripts and meeting notes locally on your device only. Everything — recording, transcription, speaker labelling and summarisation — happens entirely on your device. Your audio never leaves your phone, and we do not collect, transmit, or share any of your data. Ever.
