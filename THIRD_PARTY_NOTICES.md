# Third-party notices

Salah Bar is "all rights reserved" (see [LICENSE](LICENSE)), except for the
components below, which keep their own licenses and owners.

## Sparkle (auto-updates)
Copyright (c) 2006–2013 Andy Matuschak and the Sparkle Project contributors.
MIT License: https://github.com/sparkle-project/Sparkle/blob/2.x/LICENSE
(version 2.10.0, Mac only).

## libwebp (stickers, iPhone and iPad)
Sticker packs for WhatsApp and Telegram must be WebP images, which Apple's
ImageIO cannot write, so the iPhone app encodes them with **libwebp** 1.6.0,
Copyright (c) 2010 Google Inc., through the
[SDWebImage/libwebp-Xcode](https://github.com/SDWebImage/libwebp-Xcode) Swift
package. libwebp is used under the **BSD 3-Clause License**
(https://chromium.googlesource.com/webm/libwebp/+/HEAD/COPYING):
redistribution with the copyright notice and this disclaimer is permitted;
it is provided "as is" without warranty, and neither Google's name nor its
contributors' may be used to endorse products derived from it.

## AppAuth (Sync with Google Drive)
Signing in with Google for *Sync with Google Drive* (OAuth 2 with PKCE) uses
[AppAuth for iOS and macOS](https://github.com/openid/AppAuth-iOS) 3.0.0,
Copyright 2015 The AppAuth Authors and Google Inc., under the **Apache
License 2.0** (https://www.apache.org/licenses/LICENSE-2.0): it may be used
and redistributed with this notice, and is provided "as is", without
warranties or conditions of any kind.

## Prayer-time calculation
Since 2.8.0 Salah Bar computes the sun's position with its own code, written
from the U.S. Naval Observatory's public-domain "Approximate Solar
Coordinates" (https://aa.usno.navy.mil/faq/sun_approx).

Versions 2.0.0 to 2.7.3 instead used `SolarModel.swift`, a Swift port of the
astronomical algorithm of **PrayTimes.js**, Copyright (c) 2007–2011
PrayTimes.org (Hamid Zarrabi-Zadeh). As a derived work it is licensed under
the **GNU Lesser General Public License v3.0**
(https://www.gnu.org/licenses/lgpl-3.0.html), and its source stays published in
[`third-party/SolarModel-2.0-2.7.3.swift`](third-party/SolarModel-2.0-2.7.3.swift)
for those versions.

## The Quran text
The Arabic of the Quranic quotes added in Salah Bar, and the full Quran text
shown in the Quran player's Hifz (memorisation) mode
(`app/SalahBar/Resources/quran-text.json`, made by `scripts/gen-quran-text.py`),
is from the **Tanzil Quran Text** (quran-simple, version 1.1),
Copyright (c) 2007–2026 Tanzil Project, https://tanzil.net, licensed under
Creative Commons Attribution 3.0 and used verbatim under its terms of use:
the text is not changed, its source is credited with a link to tanzil.net in
the Hifz view ("Text: Tanzil.net"), and Tanzil's copyright notice is kept in
the bundled file. Ayah timings for Hifz mode come from mp3quran.net's API,
and ayah-by-ayah audio from EveryAyah.com (see below).

The floating Mushaf shows the **Tanzil Quran Text** in the Uthmani script
(quran-uthmani, version 1.1; `app/SalahBar/Resources/quran-uthmani.json`, made by
`scripts/gen-quran-text.py --uthmani`) under the same terms: verbatim, with
Tanzil's copyright notice in the file.

The floating Mushaf's printed styles show page images and their ayah positions
from **Quran for Android** (https://github.com/quran/quran_android; files.quran.app):
the **Madani** pages, the **Mushaf al-Shamarly** (contributed to that project by
Waleed Ibrahim) and the **IndoPak** mushaf (which that project uses with permission
of SHL Info Systems). They are downloaded only when a style is used, never bundled,
and not covered by Salah Bar's license. No license is published for these images.

Where each page of the Madani mushaf begins, for the daily wird
(`QuranPagesGenerated.swift`, made by `scripts/gen-quran-pages.py`), is from
Tanzil's **Quran Metadata** (version 1.0), Copyright (C) 2008–2009 Tanzil.info,
licensed under Creative Commons Attribution 3.0.

The **Turkish** text style uses the page breaks of the **Diyanet İşleri Başkanlığı**
mushaf (ayet berkenar, 605 pages), read from https://kuran.diyanet.gov.tr/mushaf:
only which ayah begins each page (`data/turkish-mushaf-pages.json`, made into
`TurkishPagesGenerated.swift` by `scripts/gen-turkish-pages.py`). No text or images
from that mushaf are used; the text is Tanzil's Uthmani text, in Amiri Quran.

## The Amiri font

The hadith on the welcome tour and in Settings is set in
[Amiri](https://github.com/aliftype/amiri) 1.000 by Khaled Hosny, bundled
unmodified (`Amiri-Bold.ttf`, `Amiri-Regular.ttf`, and `AmiriQuran.ttf` for the
floating Mushaf) under the
[SIL Open Font License 1.1](https://openfontlicense.org); its licence text ships
with the app as `Amiri-OFL.txt`.

## Share-card fonts (iPhone, iPad, Android)

Share cards can also set the Arabic in these fonts, bundled unmodified from
[Google Fonts](https://github.com/google/fonts) under the
[SIL Open Font License 1.1](https://openfontlicense.org); each licence text ships
beside its font (`<family>-OFL.txt`):
[Scheherazade New](https://software.sil.org/scheherazade/) (SIL International),
[Noto Naskh Arabic](https://notofonts.github.io/) and
[Noto Nastaliq Urdu](https://notofonts.github.io/) (The Noto Project Authors),
[Aref Ruqaa](https://github.com/aliftype/aref-ruqaa) (Khaled Hosny, Abdullah Aref),
[Reem Kufi](https://github.com/aliftype/reem-kufi) (Khaled Hosny, Santiago Orozco),
[El Messiri](https://github.com/Jovanny-Lemonad/El-Messiri) (Jovanny Lemonad, Mohamed Gaber).

## The Dhikr tab's hands (🤲)

The Dhikr tab's icon is the "palms up together" emoji (U+1F932) from
[Noto Emoji](https://github.com/google/fonts/tree/main/ofl/notoemoji), weight 600,
Copyright 2013 Google LLC, under the
[SIL Open Font License 1.1](https://openfontlicense.org): its outline taken
unchanged from the font, as a vector image (`DuaHands` in the iPhone app: the
Duas section's header, the welcome tour and CarPlay's Duas tab). The Dhikr tab's
own icon, a figure kneeling in dua on a prayer mat, is Salah Bar's own drawing.

## Translations
English quotes use **Sahih International**; Turkish quotes use the
**Diyanet İşleri Başkanlığı** translation. These belong to their publishers.

The Mushaf's **translations and tafsirs** (Settings → Quran → Translations and
Tafsir) come from **Quran for Android**'s list (https://android.quran.com, the
same project as the printed pages): each is a database of one translation or
tafsir, downloaded only when it's chosen, never bundled, and not covered by Salah
Bar's license. They belong to their translators and publishers, whose names are
shown under the text.

## The hadith on the share cards and stickers (iPhone and iPad)
The 45 hadith the share cards offer (`app/Packages/SalahCore/Hadith/catalog.json`,
made into `HadithGenerated.swift` by `scripts/gen-hadith.py`) are the Arabic
texts of **Sahih al-Bukhari** (14), **Sahih Muslim** (30), **Jami' at-Tirmidhi** (9),
**Sunan Abi Dawud** (3), **Sunan Ibn Majah** (2) and **Musnad Ahmad** (1), many of
them in **an-Nawawi's Forty**, checked word for word against the standard
editions (Muslim in Fuad Abd al-Baqi's numbering), each shown with its
collection and number. The hadith texts are in the public domain. Their
meanings in all twelve languages were translated for Salah Bar. The sticker
packs quote the same way: the visit to the sick (al-Bukhari 3616), the farewell
(Ibn Majah 2825), the traveller's provision (at-Tirmidhi 3444) and the wedding
wish (Abu Dawud 2130); the rest are common greetings and dhikr as they are said.

The **For sisters** content (`app/Packages/SalahCore/Sisters/catalog.json`: 20
ayat, 20 hadith and 15 duas) uses the Tanzil Quran Text above, hadith Arabic
checked against the collections (the Arabic editions of
[fawazahmed0/hadith-api](https://github.com/fawazahmed0/hadith-api)) and duas
from Hisn al-Muslim (below), with meanings translated for Salah Bar.

## Share-card photographs (iPhone and iPad)
The 30 nature photographs behind the share cards' *Nature* style
(`app/SalahBar/Resources/CardBackgrounds/card-<name>.jpg`, cropped to 3:4 and
scaled to 1800×2400, with 180×240 swatches) come from Wikimedia Commons and are
each **public domain** (works of the U.S. National Park Service and other U.S.
agencies) or **CC0** (released by their photographers through Unsplash's
former CC0 licence): free to use and modify, no credit required. Their origins,
as kept in `CardBackgrounds/SOURCES.md`:

| File | Source on Wikimedia Commons | Author | Licence |
|---|---|---|---|
| `card-fog-sunrise.jpg` | [Fog Ocean Sunrise (22567407688).jpg](https://commons.wikimedia.org/wiki/File:Fog_Ocean_Sunrise_(22567407688).jpg) | Shenandoah National Park from Virginia | Public domain |
| `card-lake-mountains.jpg` | [Lake McDonald Sunrise 4 12 16 (26171445740).jpg](https://commons.wikimedia.org/wiki/File:Lake_McDonald_Sunrise_4_12_16_(26171445740).jpg) | GlacierNPS | Public domain |
| `card-dunes-sun.jpg` | [Sandscape (Unsplash).jpg](https://commons.wikimedia.org/wiki/File:Sandscape_(Unsplash).jpg) | Fabian Struwe _fabian_ | CC0 |
| `card-calm-sea.jpg` | [Calm-sea-haleiwa (Unsplash).jpg](https://commons.wikimedia.org/wiki/File:Calm-sea-haleiwa_(Unsplash).jpg) | Jeremy Bishop tidesinourveins | CC0 |
| `card-sea-sunset.jpg` | [Blue-Orange Gradient Sunset.jpg](https://commons.wikimedia.org/wiki/File:Blue-Orange_Gradient_Sunset.jpg) | The People's Internet | CC0 |
| `card-misty-pines.jpg` | [Dense fog in the woods (Unsplash).jpg](https://commons.wikimedia.org/wiki/File:Dense_fog_in_the_woods_(Unsplash).jpg) | Kash Goudarzi kash | CC0 |
| `card-milky-way.jpg` | [Magic Hour Milky Way (20555427831).jpg](https://commons.wikimedia.org/wiki/File:Magic_Hour_Milky_Way_(20555427831).jpg) | GlacierNPS | Public domain |
| `card-above-clouds.jpg` | [Summer above the clouds (Unsplash).jpg](https://commons.wikimedia.org/wiki/File:Summer_above_the_clouds_(Unsplash).jpg) | Liane Metzler liane | CC0 |
| `card-blue-clouds.jpg` | [Up in the Clouds (Unsplash).jpg](https://commons.wikimedia.org/wiki/File:Up_in_the_Clouds_(Unsplash).jpg) | Misuni K misuniphoto | CC0 |
| `card-green-meadow.jpg` | [Green Meadow (Unsplash).jpg](https://commons.wikimedia.org/wiki/File:Green_Meadow_(Unsplash).jpg) | Pär Pärsson godofadvertising | CC0 |
| `card-waterfall.jpg` | [Smooth waterfall (Unsplash).jpg](https://commons.wikimedia.org/wiki/File:Smooth_waterfall_(Unsplash).jpg) | Megan Johnston megancorkery | CC0 |
| `card-snowy-peak.jpg` | [Mount McKinley, Sunrise (6473159529).jpg](https://commons.wikimedia.org/wiki/File:Mount_McKinley,_Sunrise_(6473159529).jpg) | Denali National Park and Preserve | Public domain |
| `card-red-dunes.jpg` | [Otherworldly Dunes (53215961524).jpg](https://commons.wikimedia.org/wiki/File:Otherworldly_Dunes_(53215961524).jpg) | Great Sand Dunes National Park and Preserve | Public domain |
| `card-misty-forest.jpg` | [Fog rolls through the trees on the Petrified Forest Interpretive Trail (portrait) (48788931236).jpg](https://commons.wikimedia.org/wiki/File:Fog_rolls_through_the_trees_on_the_Petrified_Forest_Interpretive_Trail_(portrait)_(48788931236).jpg) | Yellowstone National Park | Public domain |
| `card-milky-way-tree.jpg` | [Milky Way From Inferno Cone (4fc3421b-c931-4347-a4f6-7b5806c41456).jpg](https://commons.wikimedia.org/wiki/File:Milky_Way_From_Inferno_Cone_(4fc3421b-c931-4347-a4f6-7b5806c41456).jpg) | Jacob W. Frank | Public domain |
| `card-rapeseed.jpg` | [Rapeseed-blue-sky (Unsplash).jpg](https://commons.wikimedia.org/wiki/File:Rapeseed-blue-sky_(Unsplash).jpg) | Sweet Ice Cream Photography sweeticecreamphotography | CC0 |
| `card-alpine-peaks.jpg` | [Snowy Mountains France (Unsplash).jpg](https://commons.wikimedia.org/wiki/File:Snowy_Mountains_France_(Unsplash).jpg) | Xavi Garcia thexav | CC0 |
| `card-palm-oasis.jpg` | [Lost Palms Oasis (52583481721).jpg](https://commons.wikimedia.org/wiki/File:Lost_Palms_Oasis_(52583481721).jpg) | Joshua Tree National Park | Public domain |
| `card-date-palm-sunset.jpg` | [Sunset palm tree in Goodyear (Unsplash).jpg](https://commons.wikimedia.org/wiki/File:Sunset_palm_tree_in_Goodyear_(Unsplash).jpg) | Brady Cook bradycookphotos | CC0 |
| `card-cloud-sea-dawn.jpg` | [Cloudy sunrise in the mountains (Unsplash).jpg](https://commons.wikimedia.org/wiki/File:Cloudy_sunrise_in_the_mountains_(Unsplash).jpg) | Karsten Würth (@inf1783) inf1783 | CC0 |
| `card-autumn-larches.jpg` | [Autumn woods across the lake (Unsplash).jpg](https://commons.wikimedia.org/wiki/File:Autumn_woods_across_the_lake_(Unsplash).jpg) | Sam Ferrara samferrara | CC0 |
| `card-aurora-birches.jpg` | [Aurora borealis over Lapland (Unsplash).jpg](https://commons.wikimedia.org/wiki/File:Aurora_borealis_over_Lapland_(Unsplash).jpg) | Vincent Guth vingtcent | CC0 |
| `card-dune-stars.jpg` | [Big Dipper Constellation Over Dunes (38836718054).jpg](https://commons.wikimedia.org/wiki/File:Big_Dipper_Constellation_Over_Dunes_(38836718054).jpg) | Great Sand Dunes National Park and Preserve | Public domain |
| `card-blue-hour-lake.jpg` | [Still waters by the mountains (Unsplash).jpg](https://commons.wikimedia.org/wiki/File:Still_waters_by_the_mountains_(Unsplash).jpg) | Paul Summers somonesummers | CC0 |
| `card-leaf-drop.jpg` | [Green Leaf With Water Drop, Frankfurt, Germany (Unsplash).jpg](https://commons.wikimedia.org/wiki/File:Green_Leaf_With_Water_Drop,_Frankfurt,_Germany_(Unsplash).jpg) | Jan northlandscapes | CC0 |
| `card-snow-ghosts.jpg` | [Frozen winter forest (Unsplash).jpg](https://commons.wikimedia.org/wiki/File:Frozen_winter_forest_(Unsplash).jpg) | Les Anderson lesanderson | CC0 |
| `card-river-valley.jpg` | [Wet mountain valley (Unsplash).jpg](https://commons.wikimedia.org/wiki/File:Wet_mountain_valley_(Unsplash).jpg) | Kalen Emsley kalenemsley | CC0 |
| `card-canyon-sunset.jpg` | [Grand Canyon at Sunset (Unsplash).jpg](https://commons.wikimedia.org/wiki/File:Grand_Canyon_at_Sunset_(Unsplash).jpg) | Jad Limcaco jadlimcaco | CC0 |
| `card-dark-waves.jpg` | [Monochrome icelandic waves (Unsplash).jpg](https://commons.wikimedia.org/wiki/File:Monochrome_icelandic_waves_(Unsplash).jpg) | Tobias van Schneider vanschneider | CC0 |
| `card-lavender.jpg` | [Lavender field (Unsplash).jpg](https://commons.wikimedia.org/wiki/File:Lavender_field_(Unsplash).jpg) | Annie Spratt anniespratt | CC0 |

## Quran recitations
The Quran player streams (and, on request, downloads) recitations from
**mp3quran.net**, https://mp3quran.net, using its public API. The reciters
list bundled with the app comes from the same API. mp3quran.net's policy
(https://www.mp3quran.net/eng/privacy, "Copyrights") states: "All rights are
available to everyone, and we allow any visitor or developer to copy any
material or use any link on the websites". The recordings belong to their
reciters and producers and are not covered by Salah Bar's license.

## Duas (Hisn al-Muslim)
The Duas window has the Arabic text and chapters of **Hisn al-Muslim** (Fortress
of the Muslim) by Sa'id ibn Wahf al-Qahtani, as published by
**hisnmuslim.com** (https://www.hisnmuslim.com) through its public API, and
streams (and, on request, downloads) that site's recording of each dua. The
chapter titles and meanings in every language were translated from the Arabic
for Salah Bar. The recordings belong to their producers and are not covered by
Salah Bar's license.

### The other dua reciters
Besides hisnmuslim.com's reciter (Hamad al-Duraihim, the default), *Reading and
voice* can play each dua in the recordings of four other reciters, streamed (and,
on request, downloaded) from where they are published. Each dua was found in the
reciter's own files with speech recognition (`scripts/dua-reciters/`), and where a
reciter has no recording of a dua, al-Duraihim's plays. The recordings are played
unchanged and belong to their reciters and publishers; none of the sources states a
licence, and they are not covered by Salah Bar's license:

- **Sulayman al-Shuwaihi** and **Walid Abu Ziyad**: from
  [IslamHouse.com](https://islamhouse.com) (d1.islamhouse.com).
- **Abu Ahmad al-Shaydhmi**: his own upload on
  [archive.org](https://archive.org/details/shaydzmi19).
- **The Dua & Zikr app's reciter**: the Greentech Apps Foundation's Hisn al-Muslim
  audio on [archive.org](https://archive.org/details/HisnulMuslimAudio_201510).

## The 99 Names of Allah
The names and their order are at-Tirmidhi's list (Jami' at-Tirmidhi 3507), in the
public domain, as are their standard transliterations; their meanings in all twelve
languages and the explanations (English, Turkish, Arabic) were written for Salah Bar
(`app/Packages/SalahCore/Names/names.json`, made into `NamesGenerated.swift` by
`scripts/gen-names.py`). The Quran words shown with each name are the Tanzil Quran
Text above, verbatim.

The recording of each name is by **Mohammed Sadiq** (GraphicJunction.com), published
on [Wikimedia Commons](https://commons.wikimedia.org/wiki/Category:Arabic_pronunciation_of_names_of_God_in_Islam)
(`01-ar-rahman.ogg` … `99-as-sabur.ogg`) under the
[Creative Commons Attribution-ShareAlike 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
licence. The app streams (and, on request, downloads) Commons' MP3 transcode of each
file from upload.wikimedia.org, never bundles them and doesn't change them; the
names screen credits the recordings. They are not covered by Salah Bar's license.

## EveryAyah (Hifz mode)
For recitations that mp3quran.net has no ayah timings for, Hifz
(memorisation) mode downloads the ayahs it repeats, one MP3 per ayah, from
**EveryAyah.com** (formerly VerseByVerseQuran.com), https://everyayah.com,
and keeps them on the Mac (Application Support/Salah Bar/Quran/everyayah).
Which EveryAyah folder belongs to which recitation is listed in
`app/Packages/SalahCore/Sources/SalahCore/Quran/EveryAyah.swift`.
EveryAyah publishes no terms of use on its site today. Its timing files
(https://everyayah.com/data/timings_files/000_disclaimer.txt) ask products
that use them to link back to the site, and its former licence page
(versebyversequran.com/site/license, 2012) pointed to Creative Commons
Attribution-NonCommercial 2.5 Canada. Salah Bar credits it with a link in
the Hifz view ("Audio: EveryAyah.com"), plays the recordings unchanged
(only the files' ID3 tags, and any stray bytes before the audio, are
removed) and is free. The recordings belong to their reciters and producers
and are not covered by Salah Bar's license.

## Adhan recordings
These bundled recordings are used under open licences (Salah Bar trims them,
evens out their volume and converts them; the CC BY-SA ones stay under CC BY-SA):

- "Call to prayer from the Prophet's Mosque" by ejaz215, CC BY 3.0
  (https://creativecommons.org/licenses/by/3.0/), via Wikimedia Commons:
  https://commons.wikimedia.org/wiki/File:33937_ejaz215_call-to-prayer-from-the-prophet-s-mo.ogg
- "AZAAN in Makkah" by Seyfula Islam, CC BY 3.0, via Wikimedia Commons:
  https://commons.wikimedia.org/wiki/File:Adhan,_Great_Mosque_of_Mecca_-_Jan_21,_2013.webm
- "Eid al-Fitr Fajr azan at Malmö Mosque" (muezzin Besim Azemi) by Islamic
  Center Malmö, CC BY 3.0, via Wikimedia Commons:
  https://commons.wikimedia.org/wiki/File:Eid_al-Fitr_Fajr_azan_at_Malmö_Mosque_-_19_August_2012.webm
- "Adhan in Shalqar mosque" by Esetok, CC BY-SA 4.0
  (https://creativecommons.org/licenses/by-sa/4.0/), via Wikimedia Commons:
  https://commons.wikimedia.org/wiki/File:Adhan_in_Shalqar_mosque.webm
- "Islamic Call to Prayer (Dhuhr Adhan Audiophile Field Recording from
  Hamtramck, MI)" by RJStefanski, CC BY 3.0, via Freesound:
  https://freesound.org/people/RJStefanski/sounds/255231/
- "adzan-forest" by bagustris (Bagus Tris Atmaja), CC0, via Freesound:
  https://freesound.org/people/bagustris/sounds/508441/

The other adhan recordings, bundled and in the online library, belong to
their reciters and producers and are not covered by Salah Bar's license.

## Official prayer-time data
Salah Bar's accuracy-test data comes from
Diyanet İşleri Başkanlığı (namazvakitleri.diyanet.gov.tr) and Aladhan
(aladhan.com), and is used only to test accuracy.
