# AlecoAir D16 HOME - Home Assistant

## Integration
[LocalTuya](https://github.com/rospogrigio/localtuya)

## Mapping
| ID | HA Type | Status              | Function             | Desc                         |
| -- | ------- | ------------------- | -------------------- | ---------------------------- |
|1   | switch  | Working 			       | Power On/Off         | True: On; False: Off         |
|2   | select  | Working 			       | Mode Auto/Continuous | Auto: 0; Continuous: 1       |
|3   | sensor  | Working 			       | Current Humidity     |                              |
|4   | number  | Working 			       | Set Humidity         | min: 30; max: 80; step: 5    |
|5   |         | Not working 	       | Anion (maybe)        |                              |
|6   | select  | Working 			       | Fan Speed            | 0: High; 1: Low              |
|7   | switch  | Working 			       | Child Lock           | True: Locked; False: Unlocked|
|11  | sensor  |                     | Fault Code           | 4: defrost, 8: full tank     |
|12  | number  | You can't change it | Countdown            | min: 0; max: 24              |
|13  | sensor  | Working             | Countdown Left       | min: 0; max: 1440            |
|101 | switch  | Working             | Indise Drying        | True: On; False: Off         |

Check [floryn08](https://github.com/floryn08/alecoair-d12-home-assistant-integration) for AlecoAir D12 mapping
