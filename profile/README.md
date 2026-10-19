# [Crimpdeq](https://crimpdeq.com/)

Meet [Crimpdeq](https://crimpdeq.com/), a portable digital force sensor designed for climbers, coaches, and therapists to measure and train finger strength, pulling power, and endurance. It was inspired by [Tindeq Progressor](https://tindeq.com/product/progressor/), and designed to work seamlessly with both [Tindeq](https://tindeq.com/) and [Frez](https://www.frez.app/) apps. Read more on the [Crimpdeq book](https://book.crimpdeq.com).

> [!NOTE]
> If you're interested in reproducing this project or giving it a try, please, reach out! You can contact me via email (sergio.gasquez@gmail.com), [Twitter](https://x.com/Sergio_Gasquez) or [Bluesky](https://bsky.app/profile/sergiogasquez.bsky.social).

> [!NOTE]
> If you want a Crimpdeq but don't have the materials or skills to build your own, feel free to email me at sergio.gasquez@gmail.com and we can discuss other options.

## Specs

- Rechargeable battery with USB‑C charging, also while switched off
- Battery level reporting with a MAX17048 fuel gauge
- RGB status LED for connection and low-battery status
- ADS1220 24-bit load-cell ADC
- Communicates via Bluetooth Low Energy (BLE)
- Open-source firmware written in Rust
- Open-source PCB design
- Open-source 3D-printable case design
- Automatic sleep when inactive
- Compatible with Tindeq Progressor app ([Android](https://play.google.com/store/apps/details?id=com.progressor&hl=es_419) | [iOS](https://apps.apple.com/es/app/tindeq-progressor/id1380412428))
- Compatible with Frez app (formerly ClimbHarder) ([Android](https://play.google.com/store/apps/details?id=com.holdtight.climbharder&pcampaignid=web_share) | [iOS](https://apps.apple.com/us/app/climbharder-no-hang-training/id6730120024))
- Sampling frequency: 175 Hz by default, selectable from 20 to 1000 Hz with the Crimpdeq App
- Design load: 1500 N (≈150 kg), full scale
- Precision:
    - 0.05 kg between 0 and 99 kg
    - 0.1 kg between 100 and 150 kg
- Operating temperature: 0–40 °C
- Dimensions: 97 × 77 × 31 mm
- Uses the [Tindeq Progressor API](https://tindeq.com/progressor_api/)

## [Book](https://book.crimpdeq.com)

The book includes everything you need to build and use your own Crimpdeq. It covers assembly, calibration, firmware, charging, and the PCB and 3D-printable case design.

## [App](https://app.crimpdeq.com)

The Crimpdeq App lets you connect to, test, and calibrate your Crimpdeq. It is not intended for training. For training sessions, use the Tindeq Progressor or Frez apps.

See the [Calibration section in the Book](https://book.crimpdeq.com/calibration). The app is available on Windows, macOS, Linux, Android, and the web.

## [Platform](https://platform.crimpdeq.com)

A 3D-printable platform that turns Crimpdeq into an isometric finger dynamometer, with adjustable edge depths, a palm rest, and a phone stand. It prints entirely in plastic, with no hardware to buy.

## [Grips](https://grips.crimpdeq.com)

3D-printed grips for isolated finger training, where each finger rests on its own roller: Photon targets the deep flexor (FDP) and Spark the superficial flexor (FDS). Both are fitted to your hand from a photo.

## Repositories

- [crimpdeq-firmware](https://github.com/crimpdeq/crimpdeq-firmware): Rust firmware
- [crimpdeq-pcb](https://github.com/crimpdeq/crimpdeq-pcb): KiCad PCB design
- [crimpdeq-case](https://github.com/crimpdeq/crimpdeq-case): OpenSCAD 3D-printable case
- [crimpdeq-app](https://github.com/crimpdeq/crimpdeq-app): Flutter app for testing and calibration
- [crimpdeq-book](https://github.com/crimpdeq/crimpdeq-book): Crimpdeq book
- [crimpdeq-platform](https://github.com/crimpdeq/crimpdeq-platform): OpenSCAD finger dynamometer platform
- [crimpdeq-grips](https://github.com/crimpdeq/crimpdeq-grips): OpenSCAD finger training grips

> [!IMPORTANT]
> The PCB, firmware and case are only compatible within the same major version; for example, `crimpdeq-pcb@v3.x` pairs with `crimpdeq-firmware@v3.x` and `crimpdeq-case@v3.x`.
