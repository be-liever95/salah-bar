# Salah Bar Privacy Policy

*Last updated: 28 October 2026*

**In short: Salah Bar collects nothing.** There are no accounts, no analytics, no
ads and no tracking. Your settings, your location and your prayer log stay on
your own devices. The developer never receives any of your data.

This policy covers Salah Bar for Mac, and Salah Bar for iPhone, iPad and
Apple Watch (the same app, coming to the App Store).

English · [Türkçe](PRIVACY.tr.md) · [العربية](PRIVACY.ar.md) · [اردو](PRIVACY.ur.md) · [Bahasa Indonesia](PRIVACY.id.md) · [Bahasa Melayu](PRIVACY.ms.md) · [Français](PRIVACY.fr.md) · [Русский](PRIVACY.ru.md) · [Deutsch](PRIVACY.de.md) · [Español](PRIVACY.es.md) · [فارسی](PRIVACY.fa.md) · [বাংলা](PRIVACY.bn.md)

## What stays on your device

- **Your location.** With your permission, your Mac, iPhone or Apple Watch
  tells Salah Bar where you are, to calculate prayer times and the Qibla
  direction. The calculation happens on the device. Salah Bar keeps your last
  location on the device so the times are right at the next launch. You can
  choose a city instead and never share your location.
- **Your settings**, your own adhan files, your prayer log (including, if you
  turn them on, the jama'ah and masjid marks and the Sunnah prayers), your
  fasts, your Quran favourites, the place where you stopped in each surah, your
  khatma and wird progress, your tasbih counts, and any surahs or duas you
  choose to download.
- **For sisters** (iPhone and iPad). If you choose *Sister* in Settings, the
  excused days you log and the fasts to make up are kept on the device, in the
  same way as the prayer log. Nothing about them is shown in widgets, in the
  Live Activity or on the watch beyond the quiet period itself.
- **Apple Health** (iPhone, For sisters, off until you turn it on). If you turn
  on the Health link, Salah Bar writes a finished excused period to Health's
  cycle tracking (menstrual flow, one entry a day) and reads the cycle days
  other apps logged there, up to 180 days back, so your excused days are
  complete. That is the only Health data it touches. It is read and written
  on the device through Apple's HealthKit and never leaves it; Salah Bar sends
  no Health data anywhere and the developer cannot see it. You can turn the
  link off at any time in Settings or in the Health app.
- **Your calendar** (Mac, iPhone and iPad, off until you turn it on). To warn
  you when a meeting overlaps a prayer, Salah Bar reads the events of the
  calendars you choose, on the device. If you turn on prayer blocks, it adds
  short "Dhuhr", "Asr"… events to a calendar you choose and only ever changes
  the blocks it made. Your events never leave the device.
- **Whether you're busy** (Mac). To stay quiet during calls, Salah Bar checks
  at prayer time whether the microphone or camera is in use, or whether a
  Focus is on. It only checks *whether* they're in use. It never records,
  listens to or sees anything, and stores nothing about it.
- **Notifications, widgets, the Live Activity and the Lock Screen** are
  scheduled and drawn by macOS, iOS and watchOS on the device. The Live
  Activity (iPhone) is updated by the app itself; no push server is involved.
- **CarPlay** (iPhone) shows the app's own prayer times, Quran and duas on
  the car's screen. Nothing is sent to the car beyond what is drawn and played.
- **The duas read aloud** (iPhone and iPad). "Reading and voice" reads a dua's
  meaning with the voices built into the device (Apple's speech synthesis).
  The text is spoken on the device, not sent anywhere.
- **Share cards, stickers and photos** (iPhone and iPad). A card or a sticker
  you make is an image created on the device. If you save a card, Salah Bar
  only *adds* it to your photo library; it never reads your photos. If you
  add a sticker pack to WhatsApp, Telegram or Messages, the images are handed
  to that app, and that app's own privacy policy applies to what happens next.
- **Siri, Shortcuts and controls** run on the device with the app's own data.
  What you say to Siri is handled by Apple under Apple's privacy policy.
- **Diagnostics** (Settings → Advanced on the iPhone) make a text report
  (the app version, your settings without your cities, and the app's log) only
  when you ask, and it goes only where you choose to share it.

## Your devices talking to each other

- **Apple Watch.** The iPhone sends the watch your settings, your city (or
  your last location), your prayer log and fasts around today, through
  Apple's WatchConnectivity; the watch sends back what you mark on the wrist.
  This goes between your own two devices, never through the developer. When
  your iPhone follows your location, the watch may use its own location for
  the times when it is far from the phone.
- **iCloud** (the Mac App Store version and the iPhone/iPad app only). If you
  turn on *Sync with iCloud*, your settings, prayer log, fasts, Quran progress
  (favourites, where you stopped, the khatma) and, for sisters, the cycle log
  are stored in your own iCloud account (Apple's key-value store) so your Mac,
  iPhone and iPad share them. They go to Apple's servers under your Apple
  Account and [Apple's privacy policy](https://www.apple.com/legal/privacy/);
  the developer has no access to them. The version downloaded from GitHub has
  no iCloud.
- **The sync file** (every version, off until you turn it on). *Settings →
  Sync file* lets you keep a file named "Salah Bar sync.json" in a cloud
  drive of your choice (iCloud Drive, Google Drive, OneDrive, Dropbox,
  Nextcloud…) so Salah Bar on Windows, Android, another Mac or an iPhone can
  share the same data. The file holds, for each of your devices, its name and
  platform and the same data as iCloud sync: settings (without device-only
  things such as the flash warning), prayer log, fasts, Quran progress, the
  khatma log and, for sisters, the cycle log. Salah Bar only reads and writes
  that one file. Where it goes is between you and the drive you chose, under
  that service's privacy policy; the developer never sees it.

## What goes over the internet

Salah Bar only connects to the services below, and only to do what you asked.
None of them receives your name, your settings, your location or an account,
but like any web request they see your device's IP address.

| Service | When | What it receives |
|---|---|---|
| **Apple** (location services) | When your location changes | Your coordinates, to turn them into a place name such as "Manisa, TR" ([Apple's privacy policy](https://www.apple.com/legal/privacy/) applies) |
| **Apple Maps** | When you search for a city in Settings, and when you open *Nearby mosques* beside the Qibla | The text you type, or your location, to find the city or the mosques around it (Apple's privacy policy applies) |
| **mp3quran.net** | Only when you use the Quran player, the Mushaf or Hifz mode | Requests for the reciters list (at most once a week), for the surahs you play or download, and for the ayah timings that highlight the ayah being recited |
| **EveryAyah.com** | Only in Hifz mode, for reciters that mp3quran.net has no ayah timings for | Requests for the ayahs you repeat, one file per ayah |
| **Quran for Android** (android.quran.com, files.quran.app) | Only when you choose a translation or tafsir in the Mushaf, or a printed page style (Madani, Shamarly, IndoPak) | Requests for that translation's file or those page images, downloaded once |
| **hisnmuslim.com** | Only when you play a dua (the Duas window, the Dhikr tab, *Listen* on a dhikr card, or the morning and evening adhkar) or download the duas for offline use | Requests for the recordings you play or download (Hamad al-Duraihim's, the default reciter) |
| **IslamHouse.com** and **archive.org** | Only when you choose another dua reciter (Sulayman al-Shuwaihi and Walid Abu Ziyad from IslamHouse; Abu Ahmad al-Shaydhmi and the Dua & Zikr app's reciter from archive.org) and play or download their recordings | Requests for the recording files |
| **Wikimedia Commons** (upload.wikimedia.org) | Only when you play a name in the 99 Names (or a name-of-the-day card) or download the names for offline use | Requests for the recordings you play or download |
| **GitHub** | When you add an adhan from the online library; and, in the Mac version downloaded from GitHub, when it checks for updates (every 6 hours, with the Sparkle updater) | Requests for the adhan file (from this project's GitHub releases), or for the update feed |
| **Your mosque's website** (the link you give) or **islamic.app** (api.islamic.app) | Only with *Iqama times from your mosque* on (Settings → Iqama): when you save the link, when you tap *Refresh now*, and once a week | A request for the iqama timetable at that link (or that islamic.app mosque); nothing is sent with it |

Nothing else is contacted. Tanzil.net (the Quran text), Aladhan and Diyanet
(prayer-time tables used in the app's tests) are credited in the app, but the
app never connects to them: the Quran text ships inside the app, and prayer
times are calculated on your device, not downloaded.

Pressing **Support Salah Bar** opens Buy Me a Coffee or GitHub Sponsors in
your browser, and the link to Salah Bar for Android opens Google Play. What
you do there is covered by their privacy policies; Salah Bar itself sends
nothing.

## App Store privacy labels

For the App Store's "App Privacy" section: Salah Bar collects no data and
tracks nothing. Location, Health, calendar and photo access are used only on
the device, as described above, and are never linked to you or sent to the
developer.

## Children

Salah Bar collects no data from anyone, including children.

## Changes

If this policy changes, the new version will be published on this page with
a new date.

## Contact

Questions about privacy: open an issue at
https://github.com/be-liever95/salah-bar/issues.
