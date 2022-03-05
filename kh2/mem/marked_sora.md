###### [Kingdom Hearts II](../index.md) / Memory Addresses / [Marked Addresses](marked.md) /

# Sora

This table lists all addresses that pertain to Sora's stats.

The offsets may vary between different versions of the game. This table will list offsets in 2.5 ReMIX on PC.

* [Player Stats](#player-stats)
* [HUD Stats](#hud-stats)
* [Equipment](#equipment)

<br/>

## Player Stats

| Offset     | Type   | Notes                                                       |
|------------|--------|-------------------------------------------------------------|
| 0x009A95AF | Byte   | Player level
| 0x009AA790 | 4 Byte | Experience points; this is shared between all party members
| 0x009AA7B0 | Byte   | Bonus level
|            |        |
| 0x02A20E28 | 2 Byte | Base Strength stat; cannot be edited
| 0x009A95A9 | Byte   | Number of Power Boosts used
| 0x02A20E20 | 2 Byte | Total Strength stat; cannot be edited
|            |        |
| 0x02A20E2A | 2 Byte | Base Magic stat; cannot be edited
| 0x009A95AA | Byte   | Number of Magic Boosts used
| 0x02A20E22 | 2 Byte | Total Magic stat; cannot be edited
|            |        |
| 0x02A20E2C | 2 Byte | Base Defense stat; cannot be edited
| 0x009A95AB | Byte   | Number of Defense Boosts used
| 0x02A20E24 | 2 Byte | Total Defense stat; cannot be edited
|            |        |
| 0x02A20E26 | 2 Byte | Maximum AP
| 0x009A95A8 | Byte   | Number of AP Boosts used

<br/>

## HUD Stats

| Offset     | Type   | Notes                                                       |
|------------|--------|-------------------------------------------------------------|
| 0x02A20C98 | 2 Byte | Current HP (Health)
| 0x02A20C9C | 2 Byte | Maximum HP (Health)
|            |        |
| 0x02A20E18 | 2 Byte | Current MP (Magic)
| 0x02A20E18 | 2 Byte | Maximum MP (Magic)
| 0x02A20E18 | 2 Byte | MP Charge Timer
|            |        |
| 0x02A20E49 | Byte   | Current Drive Gauge
| 0x02A20E4A | Byte   | Maximum Drive Gauge
| 0x02A20E48 | 2 Byte | Current Drive Meter
| 0x02A20E4E | 2 Byte | Current Form Drive Timer

<br/>

## Equipment

| Offset     | Type   | Notes                                                       |
|------------|--------|-------------------------------------------------------------|
| 0x009A95A0 | 2 Byte | Base Weapon Slot
| 0x009AA3A4 | 2 Byte | Valor Weapon Slot
| 0x009AA44C | 2 Byte | Master Weapon Slot
| 0x009AA484 | 2 Byte | Final Weapon Slot
|            |        |
| 0x009A95B0 | Byte   | Number of available Armor slots
| 0x009A95B4 | 2 Byte | Armor Slot 1
| 0x009A95B6 | 2 Byte | Armor Slot 2
| 0x009A95B8 | 2 Byte | Armor Slot 3
| 0x009A95BA | 2 Byte | Armor Slot 4
| 0x009A95BC | 2 Byte | Armor Slot 5
| 0x009A95BE | 2 Byte | Armor Slot 6
| 0x009A95C0 | 2 Byte | Armor Slot 7
| 0x009A95C2 | 2 Byte | Armor Slot 8
|            |        |
| 0x009A95B1 | Byte   | Number of available Accessory slots
| 0x009A95C4 | 2 Byte | Player accessory slot 1
| 0x009A95C6 | 2 Byte | Player accessory slot 2
| 0x009A95C8 | 2 Byte | Player accessory slot 3
| 0x009A95CA | 2 Byte | Player accessory slot 4
| 0x009A95CC | 2 Byte | Player accessory slot 5
| 0x009A95CE | 2 Byte | Player accessory slot 6
| 0x009A95D0 | 2 Byte | Player accessory slot 7
| 0x009A95D2 | 2 Byte | Player accessory slot 8
|            |        |
| 0x009A95B2 | Byte   | Player number of available item slots
| 0x009A95D4 | 2 Byte | Player item slot 1
| 0x009A95D6 | 2 Byte | Player item slot 2
| 0x009A95D8 | 2 Byte | Player item slot 3
| 0x009A95DA | 2 Byte | Player item slot 4
| 0x009A95DC | 2 Byte | Player item slot 5
| 0x009A95DE | 2 Byte | Player item slot 6
| 0x009A95E0 | 2 Byte | Player item slot 7
| 0x009A95E2 | 2 Byte | Player item slot 8
