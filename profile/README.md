# [Crimpdeq](https://crimpdeq.com/)

Meet [Crimpdeq](https://crimpdeq.com/), a portable digital force sensor designed for climbers, coaches, and therapists to measure and train finger strength, pulling power, and endurance. It was inspired by [Tindeq Progressor](https://tindeq.com/product/progressor/), and designed to work seamlessly with both [Tindeq](https://tindeq.com/) and [Frez](https://www.frez.app/) apps. Read more on the [Crimpdeq book](https://book.crimpdeq.com).

> [!NOTE]
> If you're interested in reproducing this project or giving it a try, please, reach out! You can contact me via email (sergio.gasquez@gmail.com), [Twitter](https://x.com/Sergio_Gasquez) or [Bluesky](https://bsky.app/profile/sergiogasquez.bsky.social).

## Specs

- Rechargeable battery with USB‑C charging
- Communicates via Bluetooth Low Energy (BLE)
- Open-source firmware written in Rust
- Open-source PCB design
- Automatic sleep when inactive
- Compatible with Tindeq Progressor app ([Android](https://play.google.com/store/apps/details?id=com.progressor&hl=es_419) | [iOS](https://apps.apple.com/es/app/tindeq-progressor/id1380412428))
- Compatible with Frez app (formerly ClimbHarder) ([Android](https://play.google.com/store/apps/details?id=com.holdtight.climbharder&pcampaignid=web_share) | [iOS](https://apps.apple.com/us/app/climbharder-no-hang-training/id6730120024))
- Sampling frequency: 80 Hz
- Design load: 1500 N (≈150 kg), full scale
- Precision:
    - 0.05 kg between 0 and 99 kg
    - 0.1 kg between 100 and 150 kg
- Operating temperature: 0–40 °C
- Dimensions: 80 × 90 × 35 mm
- Uses the [Tindeq Progressor API](https://tindeq.com/progressor_api/)

## [Book](https://book.crimpdeq.com)

The book includes everything you need to build and use your own Crimpdeq. It covers assembly, calibration, firmware, charging, and PCB details.

## [App](https://app.crimpdeq.com)

The Crimpdeq App lets you connect to, test, and calibrate your Crimpdeq. It is not intended for training. For training sessions, use the Tindeq Progressor or Frez apps.

See the [Calibration section in the Book](https://book.crimpdeq.com/calibration). The app is available on Windows, macOS, Linux, Android, and the web.
