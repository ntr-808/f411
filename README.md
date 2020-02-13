# `f411`
Support crate for the [STM32F411E-DISCO](https://www.st.com/en/evaluation-tools/32f411ediscovery.html).

[Reference Manual (EN)](https://www.st.com/content/ccc/resource/technical/document/reference_manual/9b/53/39/1c/f7/01/4a/79/DM00119316.pdf/files/DM00119316.pdf/jcr:content/translations/en.DM00119316.pdf)

## Board Features
- `STM32F411VET6` microcontroller (Cortex-M4F) featuring 512 KiB of Flash memory
- `LQFP100` 128 KiB of RAM
- `L3GD20`: ST MEMS motion sensor 3-axis digital output gyroscope
- `LSM303DLHC`: ST MEMS system-in-package featuring a 3D digital linear acceleration sensor and a 3D digital magnetic sensor
- `MP45DT02`: ST MEMS audio sensor, omnidirectional digital microphone
- `CS43L22`: audio DAC with integrated class D speaker driver
- 8 LEDs:
    - `LD1` red/green - USB communication
    - `LD2` red - 3.3V power on
    - 4 user LEDs
        - `LD3` orange
        - `LD4` green
        - `LD5` red
        - `LD6` blue
    - 2 USB OTG LEDs
        - `LD7` green - VBus
        - `LD8` red - over-current
- 2 buttons (user and reset)
- USB OTG with micro-AB connector

- ST-LINK/V2
- Board power supply: through USB bus or from an external 5V supply voltage
- External application power supply: 3V and 5V

<!-- ## [Documentation](https://docs.rs/f4) -->

## [Change log](CHANGELOG.md)

## License
- MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)