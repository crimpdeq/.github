# Crimpdeq

Meet Crimpdeq, a portable digital force sensor designed for climbers, coaches, and therapists to measure and train finger strength, pulling power, and endurance. It was inspired by [Tindeq Progressor](https://tindeq.com/product/progressor/), and designed to work seamlessly with both [Tindeq](https://tindeq.com/) and [Frez](https://www.frez.app/) apps. Read more on the [Crimpdeq book](https://crimpdeq.github.io/book/).

> [!NOTE]
> If you're interested in reproducing this project or giving it a try, please, reach out! You can contact me via email (sergio.gasquez@gmail.com), [Twitter](https://x.com/Sergio_Gasquez) or [Bluesky](https://bsky.app/profile/sergiogasquez.bsky.social).

## Specs

- Rechargeable battery with USB‑C charging
- Communicates via Bluetooth Low Energy (BLE)
- Open-source firmware written in Rust
- Open-source PCB design
- Automatic sleep when inactive
- Compatible with Tindeq Progressor app ([Android](https://play.google.com/store/apps/details?id=com.progressor&hl=es_419) | [iOS](https://apps.apple.com/es/app/tindeq-progressor/id1380412428))
- Compatible with Frez app (formerly ClimbHarder) app ([Android](https://play.google.com/store/apps/details?id=com.holdtight.climbharder&pcampaignid=web_share) | [iOS](https://apps.apple.com/us/app/climbharder-no-hang-training/id6730120024))
- Sampling frequency: 80 Hz
- Design load: 1500 N (≈150 kg), full scale
- Precision:
    - 0.05 kg between 0 and 99 kg
    - 0.1 kg between 100 and 150 kg
- Operating temperature: 0–40 °C
- Dimensions: 80 × 90 × 35 mm
- Uses the [Tindeq Progressor API](https://tindeq.com/progressor_api/)

## [Book](https://crimpdeq.github.io/book/)
For detailed guidance on assembly, calibration, charging, and usage, see the [Crimpdeq book](https://crimpdeq.github.io/book/).

The documentation covers everything from building your own Crimpdeq to firmware installation and PCB details. Available sections include:

- [Introduction](https://crimpdeq.github.io/book/introduction.html)
- [Making your own Crimpdeq](https://crimpdeq.github.io/book/assembly.html)
- [Calibration](https://crimpdeq.github.io/book/calibration.html)
- [Charging the Battery](https://crimpdeq.github.io/book/battery.html)
- [Firmware](https://crimpdeq.github.io/book/firmware.html)
- [PCB](https://crimpdeq.github.io/book/pcb.html)

