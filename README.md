# Crystal
A Garmin Connect IQ watch face.

## Description
A crystal clear watch face, with LCD-like goal meter segments, written while snow crystals were falling during an unusually cold spell of weather here in England.

Features (watch-dependent):
- Big time digits right in the middle, with hours in bold.
- 3 customisable data fields: HR history, battery, notifications, calories, distance.
- 2 customisable goal meters: steps, floors climbed, active minutes (weekly). The meters have auto-scaling segments and current/target value display.
- Move bar.
- 8 colour themes.

The techie bit: to save your watch battery, the goal meters and move bar are drawn from a palette-restricted back buffer, for improved drawing performance, with minimal memory penalty.

This is my first ever Connect IQ watch face (please be kind!), so I look forward to your feedback, improving the watch face, and bringing it to more devices.

## What's New

### 1.4.3
- Meters can now show a custom calories goal, specified in settings.
- Fixed issue with wrong strings or crash when changing settings via Garmin Express in non-English locales (thanks to Ezio Pillan for reporting this bug).
- Added app version to settings page.

### 1.4.2
- Allow hiding of seconds.

### 1.4.1
- Reduce battery drain, part 2: optimise per-minute updates (cache drawable references).
- Allow meters to display battery level.

### 1.4.0
- Reduce battery drain, part 1: reduce per-second update time from ~13ms to ~5ms (measured on Approach® S60, simulator).
- Added Red (Dark) and Mono (Dark) themes.
- Added support for vívoactive® HR.

### 1.3.0
- Added support for fēnix® 5S, fēnix® Chronos, Forerunner® 735XT.
- Added Dayglo Orange theme.

### 1.2.1 
- Fixed issue with distance value being too low (thanks to catana.remulus for reporting and assisting with this bug). 

### 1.2.0
- Added support for Approach® S60, D2™ Charlie, Descent™ Mk1, Forerunner® 645, Forerunner® 645 Music, Forerunner® 935, fēnix® 5, fēnix® 5X.
- Added Cornflower Blue and Lemon Cream themes for better visibility.

**N.B. Due to a vívoactive® 3 firmware bug, this watch face will be stuck on the language that was active at the time of the 3.30-3.40 firmware upgrade. Hopefully Garmin will fix this in a future firmware.**

### 1.1.0
- Internationalisation: added support for Chinese (Simplified/Traditional), Czech, Danish, Dutch, Finnish, French, German, Hungarian, Italian, Norwegian, Polish, Portugese, Slovak, Slovenian, Spanish, Swedish.
- Force language to English for unsupported locales, to prevent garbled characters.
- Fixed issue with battery meter not showing low/critical warning colours soon enough.

### 1.0.1
- Fixed issue with showing noon as AM, rather than PM (with thanks to JACalvo for reporting this bug).
- Fixed issue with move bar not updating correctly.

### 1.0.0
- Initial public release for vívoactive® 3 only.

## Credits
Icons:
- "[Distance](https://thenounproject.com/term/distance/1514833/)" icon by Becris from [the Noun Project](https://thenounproject.com).
- "[Fire](https://thenounproject.com/term/fire/24187/)" icon by Jenny Amer from [the Noun Project](https://thenounproject.com).
- "[Steps](https://thenounproject.com/term/steps/87667/)" icon by Eugen Belyakoff from [the Noun Project](https://thenounproject.com).
- "[Upstairs](https://thenounproject.com/term/upstairs/304907/)" icon by Arthur Shlain from [the Noun Project](https://thenounproject.com).
- "[Stopwatch](https://thenounproject.com/term/stopwatch/319102/)" icon by Rohith M S from [the Noun Project](https://thenounproject.com).
