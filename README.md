# Miscela Facile

**Available for Android.**

This repository contains information about the app. Application source code and APK files are not distributed in the current version of this repository.

[English](README.md) · [Italiano](README.it.md)

**A simple, offline petrol-and-oil mixture calculator for Android.**

Choose how much petrol you want to use, enter the oil percentage specified in your engine manual, and see how much oil to add in your chosen unit.

## Features

- Independent fuel/oil units: L, mL, US or imperial gallons and fluid ounces. Automatic locale presets, remembered manual choices and a reset to language defaults.

- Petrol presets from **0.5 to 5 litres**, including half-litre quantities.
- Custom petrol quantities and oil percentages.
- Immediate results in your selected oil unit.
- Local history of up to **20 saved calculations**, with reuse and clear-history controls.
- Safety instructions shown before the calculator, including the use of clean petrol.
- A soft, light **orange interface** with matching custom-input fields.
- Device-language detection and an alphabetical language selector with a globe icon.
- English fallback when a translation is unavailable.
- Button sound and haptic feedback on Android, subject to device settings.
- Offline operation, with no accounts or advertising.

## Android availability

Miscela Facile is available for **Android 8.0 or later**. Version **1.5.0**.

APK downloads are no longer provided through this repository.

## How to use it

1. Read the safety instructions.
2. Select a petrol quantity or enter your own.
3. Enter the oil percentage required by your engine.
4. Read the amount of oil to add.
5. Optionally save the calculation to history.

**Example:** 2.5 L of petrol at 2% requires **50 mL of oil**.

```text
Oil in mL = petrol in litres × oil percentage × 10
```

The petrol quantity is measured before adding oil. There is no universal oil percentage for every engine: follow the manufacturer's instructions.

## Safety

Use clean petrol, free from water and dirt, and a clean container suitable for fuel. Work outdoors, away from flames and cigarettes. Refuel only when the engine is switched off and cool.

**Chainsaw chain oil is not mixing oil.** Use the oil type and ratio prescribed for your engine.

## Languages

The existing interface includes **78 base translation dictionaries**, prepared with machine assistance and awaiting independent linguistic review. New unit controls include texts for Italian, English, Spanish, Brazilian Portuguese, French, German, Simplified Chinese, Japanese, Korean and Russian. Translation coverage varies by feature; untranslated messages fall back to English. This does not certify complete or independently reviewed translations.

The project welcomes language contributions from every continent. This is a goal, not a claim that every language is already supported or verified. Native language names remain visible in the selector so users can recover from an accidental choice.

## Privacy

[Read the privacy policy (Italian / English)](https://devfaxpro.github.io/miscela-facile/privacy.html). Version 1.5.0 includes an offline copy inside the app.

Saved preferences and calculation history stay on the device. The Android app requests no permissions and does not require an account or an internet connection.

## Feedback

For bug reports or translation corrections, open an [issue](https://github.com/devfaxpro/miscela-facile/issues). Include the app version, device and selected language, without passwords or personal data.
