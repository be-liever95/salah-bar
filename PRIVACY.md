# Salah Bar Privacy Policy

*Last updated: 30 October 2026*

**In short: Salah Bar collects nothing.** There are no accounts, no analytics, no
ads and no tracking. Your settings, your location and your prayer log stay on
your own devices. The developer never receives any of your data. The one
exception, off until you turn it on, is the weather: then your location,
rounded to about 10 km, goes to Open-Meteo (see below).

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
- **Google Drive** (every version, off until you turn it on). *Settings → Sync →
  Sync with Google Drive* lets you sign in with Google instead of choosing a
  file. Salah Bar then asks Google for one permission only, to keep its own file
  in your Google Drive's hidden app folder (the `drive.appdata` scope): it can't
  see, open or change any of your other files in Drive. It keeps the same sync
  file there, "Salah Bar sync.json", sending it straight from your device to
  your own Drive over HTTPS; there is no Salah Bar server in between, and the
  developer never sees the file or your account. The sign-in token is kept in
  your Mac's or iPhone's Keychain, on that device only; Salah Bar also keeps
  your account's email address, to show it. [Google's privacy
  policy](https://policies.google.com/privacy) applies to your Google account
  and Drive. *Sign Out* takes this device's data out of the file and stops
  syncing here; *Remove My Data from Drive* deletes the file (every device's
  data in it) and takes Salah Bar's access away. You can also remove the access
  from your Google Account (Security → Third-party apps) and delete the hidden
  data in Drive → Settings → Manage apps. Salah Bar's use of information
  received from Google APIs adheres to the [Google API Services User Data
  Policy](https://developers.google.com/terms/api-services-user-data-policy),
  including the Limited Use requirements: it only reads and writes its own sync
  file in your Drive, to sync your devices, and never uses it for anything else
  or passes it to anyone.

## What goes over the internet

Salah Bar only connects to the services below, and only to do what you asked.
None of them receives your name, your settings or an account, and only the
three that say so receive a location; like any web request they see your
device's IP address.

| Service | When | What it receives |
|---|---|---|
| **Apple** (location services) | When your location changes | Your coordinates, to turn them into a place name such as "Manisa, TR" ([Apple's privacy policy](https://www.apple.com/legal/privacy/) applies) |
| **Apple Maps** | When you search for a city in Settings, and when you open *Nearby mosques* beside the Qibla | The text you type, or your location, to find the city or the mosques around it (Apple's privacy policy applies) |
| **Open-Meteo** (api.open-meteo.com) | Only with *Show the weather* on (Settings → Appearance): when you turn it on, then at most every 30 minutes while the app is open | Your location rounded to 0.1° (about 10 km), to get the current weather there; nothing else is sent with it |
| **mp3quran.net** | Only when you use the Quran player, the Mushaf or Hifz mode | Requests for the reciters list (at most once a week), for the surahs you play or download, and for the ayah timings that highlight the ayah being recited |
| **EveryAyah.com** | Only in Hifz mode, for reciters that mp3quran.net has no ayah timings for | Requests for the ayahs you repeat, one file per ayah |
| **Quran for Android** (android.quran.com, files.quran.app) | Only when you choose a translation or tafsir in the Mushaf, or a printed page style (Madani, Shamarly, IndoPak) | Requests for that translation's file or those page images, downloaded once |
| **hisnmuslim.com** | Only when you play a dua (the Duas window, the Dhikr tab, *Listen* on a dhikr card, or the morning and evening adhkar) or download the duas for offline use | Requests for the recordings you play or download (Hamad al-Duraihim's, the default reciter) |
| **IslamHouse.com** and **archive.org** | Only when you choose another dua reciter (Sulayman al-Shuwaihi and Walid Abu Ziyad from IslamHouse; Abu Ahmad al-Shaydhmi and the Dua & Zikr app's reciter from archive.org) and play or download their recordings | Requests for the recording files |
| **Wikimedia Commons** (upload.wikimedia.org) | Only when you play a name in the 99 Names (or a name-of-the-day card) or download the names for offline use | Requests for the recordings you play or download |
| **GitHub** | When you add an adhan from the online library; and, in the Mac version downloaded from GitHub, when it checks for updates (every 6 hours, with the Sparkle updater) | Requests for the adhan file (from this project's GitHub releases), or for the update feed |
| **Your mosque's website** (the link you give) or **islamic.app** (api.islamic.app) | Only with *Iqama times from your mosque* on (Settings → Iqama): when you save the link, when you tap *Refresh now*, and once a week | A request for the iqama timetable at that link (or that islamic.app mosque); nothing is sent with it |
| **Google** (accounts.google.com, oauth2.googleapis.com, www.googleapis.com) | Only with *Sync with Google Drive* on: when you sign in, and at each sync | Your sign-in, on Google's own page, and the sync file described above, to and from your own Drive |
| **Your country's religious authority** (dinhizmetleri.diyanet.gov.tr with e-Devlet's copy at www.turkiye.gov.tr, ditib.de, e-khutbah.jais.gov.my) | Only with *This week's khutbah* on (iPhone, iPad and Android): when you open its screen (at most once an hour), and on Thursday and Friday until the week's sermon is in | A request for the authority's list of sermons, and for the PDF or recording you open or download |
| **YouTube** (www.youtube.com) | With Türkiye's (Diyanet's) khutbah list, at the same times | A request for the public feed of Salah Bar's own YouTube channel, to find the week's khutbah video; no account, no key, no cookies |
| **YouTube's player** (www.youtube-nocookie.com) | Only when you tap *Watch* on a week's khutbah | The video plays in YouTube's privacy-enhanced player inside the app; Salah Bar sends nothing about you, and [Google's privacy policy](https://policies.google.com/privacy) applies to the player |

Nothing else is contacted. Tanzil.net (the Quran text), Aladhan and Diyanet
(prayer-time tables used in the app's tests) are credited in the app, but the
app never connects to them: the Quran text ships inside the app, and prayer
times are calculated on your device, not downloaded. Diyanet's list of Friday sermons (*This week's khutbah*, above) is the one exception.

**The weather** (off until you turn it on, on each device). The sky behind
the next prayer and in the widgets is worked out on the device from the prayer
times. If you turn on *Show the weather* (Settings → Appearance), Salah Bar
first says what it will send, then asks Open-Meteo (open-meteo.com) for the
current weather at your location rounded to 0.1° (about 10 km), at most every
30 minutes while the app is open (on the Mac, while it runs), with no account,
key, cookie or identifier. The answer (clouds, rain, snow…) stays on the device
and is shared with its widgets. Turning the switch off stops the requests and
forgets the last answer. Open-Meteo's terms and privacy policy apply to the
request; its weather data is CC BY 4.0.

Pressing **Support Salah Bar** opens Buy Me a Coffee or GitHub Sponsors in
your browser, and the link to Salah Bar for Android opens Google Play. What
you do there is covered by their privacy policies; Salah Bar itself sends
nothing.

## App Store privacy labels

For the App Store's "App Privacy" section: Salah Bar tracks nothing and
collects no data, with one optional exception: with *Show the weather* on, the
location rounded to about 10 km goes to Open-Meteo, declared as Coarse
Location, not linked to you, not used for tracking, for App Functionality.
Location, Health, calendar and photo access are used only on
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
