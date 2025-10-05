# ESPHome Zehnder Comfoair Integration

This project allows you to integrate your **Zehnder Comfoair** ventilation unit with **Home Assistant**.  
It is designed to work with the **M5Stack AtomS3 Lite** equipped with the **Mini CAN Unit (TJA1051T/3)**, powered from the 12V supply of the ventilation unit.

For detailed hardware information and setup, see the original repository:  
[Zehnder Comfoair ESPHome integration by yoziru](https://github.com/yoziru/esphome-zehnder-comfoair/blob/main/docs/m5stack-atoms3.md)

---

## Setup Instructions

1. Get an **M5Stack AtomS3 Lite** with **Mini CAN Unit**.
2. In **Home Assistant ESPHome Builder**, add a **new device**.
3. Choose **empty configuration**.
4. Give your device a descriptive **name**.
5. Copy the contents of `comfoair.yaml` from this repository into your new device configuration.
   **No other files from the GitHub repository need to be copied.**
7. Replace the **API encryption key** with your own.
8. Replace the **OTA password** with your own.

> 💡 Tip: Ensure your `secrets.yaml` is properly configured to avoid compilation errors.

---

## Acknowledgements

This project is **based on the original work by [yoziru](https://github.com/yoziru/esphome-zehnder-comfoair)**.  
Many thanks for sharing the ESPHome Comfoair integration.

