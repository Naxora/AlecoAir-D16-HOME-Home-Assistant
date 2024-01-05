# AlecoAir D16 HOME - Home Assistant

## Integration
[LocalTuya](https://github.com/rospogrigio/localtuya)

[Get Tuya Local Key](https://github.com/Naxora/Get-Tuya-Local-Key/blob/main/README.md)

Hint: Use `Smart Life` [IOS](https://apps.apple.com/us/app/smart-life-smart-living/id1115101477) [Android](https://play.google.com/store/apps/details?id=com.tuya.smartlife&hl=en&gl=US) instead of `AlecoAir` app to scan QR code.

## Mapping
| ID | HA Type | Status              | Function             | Desc                         |
| -- | ------- | ------------------- | -------------------- | ---------------------------- |
|1   | switch  | Working 			       | Power On/Off         | True: On; False: Off         |
|2   | select  | Working 			       | Mode Auto/Continuous | Auto: 0; Continuous: 1       |
|3   | sensor  | Working 			       | Current Humidity     |                              |
|4   | number  | Working 			       | Set Humidity         | Min: 30; Max: 80; Step: 5    |
|5   |         | Not working 	       | Anion (maybe)        |                              |
|6   | select  | Working 			       | Fan Speed            | 0: High; 1: Low              |
|7   | switch  | Working 			       | Child Lock           | True: Locked; False: Unlocked|
|11  | sensor  | Working             | Fault Code           | 4: Defrost, 8: Full tank     |
|12  | number  | You can't change it | Countdown            | Min: 0; Max: 24              |
|13  | sensor  | Working             | Countdown Left       | Min: 0; Max: 1440            |
|101 | switch  | Working             | Indise Drying        | True: On; False: Off         |

Check [floryn08](https://github.com/floryn08/alecoair-d12-home-assistant-integration) for AlecoAir D12 mapping
