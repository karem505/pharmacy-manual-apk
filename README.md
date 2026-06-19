# Pharmacy Manual: APK downloads

An Arabic-first, offline Egyptian drug index and price checker for Android.

## Download

- **[pharmacy-manual-v0.2.1.apk](https://github.com/karem505/pharmacy-manual-apk/raw/main/pharmacy-manual-v0.2.1.apk)** (about 62 MB)

To install: download the APK, enable "install from unknown sources" on your Android device, then open the file. This build is signed with a debug key, intended for testing and sideloading.

## What's new in 0.2.1

- Fixes the "check for updates" button — release builds were missing the INTERNET permission, so the database update could not reach GitHub. Updates now pull the latest data correctly.

## What's new in 0.2.0

- A complete visual redesign — the "Clinical Field Guide" look: calm Ink-Blue brand, reserved red/amber/green safety colours, serif drug names with tabular-figure prices, and class-coded chips.
- New branded app icon and an Arabic app name (دليل الأدوية).
- Browse now shows therapeutic classes with live counts, manufacturers, and routes — each drills into a filtered list.
- A clearer drug-detail price checker that highlights the current drug and badges cheaper same-ingredient alternatives.

## What it does

- Bilingual, diacritic-insensitive search across 24,868+ medicines (Arabic alias, English name, active ingredient)
- Drug detail with a cheapest same-ingredient price comparison (find a cheaper equivalent)
- Browse by drug class, manufacturer, and route
- Light and dark themes, Arabic-first RTL throughout
- An embedded database that updates itself when the source data changes

## Data and disclaimer

Drug data is released under CC0 from [egyptian-drug-database](https://github.com/karem505/egyptian-drug-database). Prices and availability change constantly. This app is for information only: always verify with the Egyptian Drug Authority and a licensed pharmacist before any clinical use.

The application source code is maintained in a separate private repository.
