# Miscela Facile

[English](README.md) · [Italiano](README.it.md)

**A simple, offline petrol-and-oil mixture calculator for Android.**

Choose how much petrol you want to use, enter the oil percentage specified in your engine manual, and see how many millilitres of oil to add.

## Features

- Petrol presets from **0.5 to 5 litres**, including half-litre quantities.
- Custom petrol quantities and oil percentages.
- Immediate results in millilitres.
- Local history of up to **20 saved calculations**, with reuse and clear-history controls.
- Safety instructions shown before the calculator, including the use of clean petrol.
- A soft, light **orange interface** with matching custom-input fields.
- Device-language detection and an alphabetical language selector with a globe icon.
- English fallback when a translation is unavailable.
- Button sound and haptic feedback on Android, subject to device settings.
- Offline operation, with no accounts or advertising.

## Android download

[Open GitHub Releases](https://github.com/devfaxpro/miscela-facile/releases)

APK downloads will be listed in the **Assets** section of a published release. If no APK is listed, the installation package has not yet been made available there.

**Minimum requirement:** Android 8.0 or later. This project does not provide an iOS app.

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

Italian and English text is available for the new history and clean-petrol features. The existing interface includes **78 base translation dictionaries**, prepared with machine assistance and awaiting independent linguistic review. Other languages currently use English for untranslated new messages.

The project welcomes language contributions from every continent. This is a goal, not a claim that every language is already supported or verified. Native language names remain visible in the selector so users can recover from an accidental choice.

## Privacy

[Read the privacy policy (Italian / English)](https://devfaxpro.github.io/miscela-facile/privacy.html). Version 1.4.1 also includes an offline copy inside the app.

Saved preferences and calculation history stay on the device. The Android app requests no permissions and does not require an account or an internet connection.

## Development and contributions

The prepared project uses JavaScript for the shared interface and a Java Android WebView shell. Its source package includes build scripts, tests and translation contribution instructions.

Translation review, accessibility feedback and reproducible bug reports are welcome. Please include the app version, device and selected language, without passwords or personal data.

Automated checks cover calculations, language selection, history and small-screen layouts. They do not certify translation accuracy or replace testing on a physical Android device.

## License

An application-wide open-source license has **not yet been adopted**. MIT has been proposed but not applied. The bundled Nunito font retains its separate **SIL Open Font License 1.1**.