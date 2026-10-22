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
- **Ad Frequency History**: A timestamp per recording of when an ad was last shown for it, used for one purpose only — not showing you the same recording's ad again the same day
- **On-device Models**: Speech-to-text, speaker and summarisation models stored in private app storage (downloaded or unpacked on first launch and when you choose higher-tier presets) so they run 100% offline
- **App Preferences**: Display theme, quality presets, and other engine configuration options

### Data We DO NOT Collect
- We do NOT collect any personal information directly
- We do NOT collect your name, email, or contact information
- We do NOT track your location
- We do NOT access or transmit your recordings, transcripts or summaries to any external servers — not even for advertising
- We do NOT use analytics or tracking services of our own
- We do NOT use cookies (there is no web version)
- We do NOT sell your personal information

The only network uses are downloading public open-source AI model weights on demand and the advertising SDK described below; neither ever receives, accesses, or transmits your recordings, transcripts, or personal content.

## How We Use Your Data

- **Recordings**: Saved locally so you can play them back and re-read their notes
- **Transcripts and Notes**: Generated locally and stored so you can search, review and export them
- **Speaker Labels**: Derived locally from your audio so transcript speakers can be named
- **Preferences**: Saved locally to remember your theme, presets, and display settings

## Data Storage

All data is stored locally on your device:
- **Sessions**: SQLite database (titles, transcripts, speaker labels, summaries) in the app's private database directory
- **Audio**: WAV files in the app's private documents directory
- **Models**: Downloaded on first launch (or unpacked from the app package where pre-bundled) into private app storage, with optional higher-tier presets downloaded on demand
- **Preferences**: Held by the operating system's app preferences storage and local settings store

## Data Processing

**Important**: Recording, transcription, speaker identification and summarisation all happen entirely on your device. Your audio is never uploaded, and neither are your transcripts, notes or any statistics derived from them — neither model downloads nor the advertising SDK has access to any of it. The app's only network traffic is:
1. **Model Weights Downloads**: Secure HTTPS requests to public open-source model repositories (such as Hugging Face) to download static model files on first launch or when you select an upgraded quality preset.
2. **Advertising**: Loading the single frequency-capped ad described below (and opening policy links in your browser, which happens outside the app).

Sharing is something you do yourself: if you use the app's share action, you choose what to send and the receiving app (email, chat, cloud drive) handles it under its own privacy policy.

## Advertising

Minutely is free and supported by advertising, shown through **Google AdMob**. Ads appear in exactly one place: when you open a recording's transcript. Never during recording, playback or summaries. The app limits this to one ad per recording per calendar day and stores only the per-recording timestamp needed to enforce that limit.

Google's ad SDK may collect, for advertising, measurement and fraud prevention:
- Your Android Advertising Identifier (or another resettable device identifier), device and OS type, and your approximate region inferred from your IP address
- Ad events — for example that an ad was shown — used for reporting
- With your consent, data used to personalise the ads you see

For users in the EEA and the UK, the app shows Google's standard consent form on first launch, before any ad is requested; ads are only requested once Google records your decision. Where required, the About screen (info button on the home screen) contains an **"Ad privacy settings"** entry that reopens that form so you can change your choice at any time. You can also opt out of personalised advertising system-wide through your device's settings (Android: Settings → Privacy → Ads).

Google's own processing is described in:
- [Google Privacy & Terms](https://policies.google.com/privacy)
- [How Google uses information from sites or apps that use its services](https://policies.google.com/technologies/partner-sites)
- [Google Ads personalisation controls](https://adssettings.google.com)

Your recordings, transcripts and summaries are never transmitted for advertising or any other purpose.

## Data Retention

- **Sessions and Recordings**: Persist until you:
  - Delete the recording inside the app
  - Clear app data or cache from system settings
  - Uninstall the app
- **On-device Models**: Default models remain in app storage until you clear app data or uninstall. Optional quality preset models (such as Whisper Base or LLaMA 3.2 3B) can be deleted directly within the app's settings at any time to free device storage.

## Backup

Minutely disables Android auto backup and device-to-device transfer for its app data, so recordings, transcripts and summaries are not copied to cloud backup services or moved to a new device by the system.

## Permissions We Request

- **Microphone**: Required to capture audio when you start a recording. Recording only happens while you have started a session.
- **Notifications**: Used for the ongoing "Recording" notification and its lock-screen Stop action while a session is in progress or being processed, as well as progress notifications during background AI model downloads and session regenerations.
- **Foreground Services & Wake Lock**: Keeps the CPU alive and maintains network sockets during model downloading and audio processing so tasks are not interrupted when the app is minimized or the screen is turned off.
- **Internet**: Used only to download public open-source model files (on first launch or when you switch quality presets) and to load the one ad described above and its consent and measurement calls. Recording, transcription, diarization and summarisation run strictly on-device and never transmit data.
- **Advertising ID** (`com.google.android.gms.permission.AD_ID`): Lets Google AdMob serve, attribute and measure ads. You can reset or delete this identifier in your device settings.

## Children's Privacy

Our app is suitable for all ages. We do not knowingly collect personal information from children. Advertising is delivered by Google AdMob under Google's own policies, and personalised advertising is not targeted at children.

## Your Rights

You have the right to:
- Delete any recording and its notes at any time from the app
- Delete optional downloaded model weights from the settings screen to reclaim storage
- Delete all your data by clearing app data or uninstalling the app
- Withdraw or change your ad consent via the "Ad privacy settings" entry on the About screen (where shown) or your device's Ads settings
- Access your locally stored data through the app's library and export features

## Third-Party Services

We do not use analytics. Third-party network interactions are strictly limited to:
1. **Model Downloads**: When downloading open-source speech and language models, the app connects directly to public model repositories (Hugging Face) via secure HTTPS to fetch static model files. No user data, device identifiers, audio, transcripts, or usage telemetry are transmitted during this download.
2. **Google AdMob**: Delivers and measures the single frequency-capped ad described above; its SDK runs inside the app.

Everything else — whisper.cpp, sherpa-onnx, llama.cpp, ffmpeg, SQLite and the speech, speaker and summarisation inference engines — runs entirely on your device with no network access.

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

For users in the European Union, United Kingdom and EEA:
- Your recordings, transcripts and summaries are processed only on your device; we never receive a copy of them
- Google processes limited device data in order to show ads; the legal basis for personalised advertising is your consent
- That consent is collected through Google's standard consent form on first launch, before any ad is requested
- You may withdraw it at any time via the "Ad privacy settings" entry on the About screen, or through your device's Ads settings

## CCPA Compliance

For California residents:
- We do not sell personal information
- We do not have access to, and never collect, your recordings, transcripts or notes
- Device data used to serve ads is processed by Google AdMob under Google's own policies
- You can opt out of ad personalisation through your device's Ads settings

---

**Summary**: Minutely stores your recordings, transcripts and meeting notes locally on your device only. Everything — recording, transcription, speaker labelling and summarisation — happens entirely on your device, and your audio never leaves your phone. The app's network use is strictly limited to downloading open-source model weights on demand and the single ad shown when you open a transcript; we do not collect, view, or transmit your content or personal information. Ever.
