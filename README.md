# CorsairLink plugin for FanControl

The unofficial CorsairLink plugin for [FanControl](https://github.com/Rem0o/FanControl.Releases).

## Device Support

| Device                         | Status       | Read Fan RPM | Set Fan Power | Read Temp Sensor |
| ------------------------------ | ------------ | ------------ | ------------- | ---------------- |
| Commander PRO                  | Full Support | ✔            | ✔             | ✔                |
| Commander PRO (Obsidian 1000D) | Full Support | ✔            | ✔             | ✔                |
| Commander CORE                 | Planned      |              |               |
| Commander CORE XT              | Planned      |              |               |

## Installation

1. Unblock the downloaded ZIP file. (Right-click, Properties, check Unblock, OK)
2. Exit FanControl.
3. Copy `FanControl.CorsairLink.dll` to the FanControl `Plugins` directory.
4. Start FanControl.
5. Run assisted setup or sensor detection.

## Notes

⚠ This plugin will not function correctly if Corsair iCUE (specifically, the "Corsair Service" service) is running. This service should be stopped before running FanControl.
