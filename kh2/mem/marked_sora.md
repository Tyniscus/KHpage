###### [Kingdom Hearts II](../index.md) / Memory Addresses / [Marked Addresses](marked.md) /

# Sora

This table lists all addresses that pertain to Sora's values.

The offsets may vary between different versions of the game. This table will list offsets in 2.5 ReMIX on PC.

* [Player Stats](#player-stats)
* [HUD Stats](#hud-stats)
* [Equipment](#equipment)
* [Drive Forms](#drive-forms)
* [Summons](#summons)
* [Ability Slots](#ability-slots)

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

<br/>

## Drive Forms

| Offset         | Type   | Notes                                                       |
|----------------|--------|-------------------------------------------------------------|
| 0x009AA770:1>1 | Binary | Valor Form Accessibility
| 0x009AA3A8     | 2 Byte | Valor Form Experience
| 0x009AB086     | 2 Byte | Valor Form, number of times used
|                |        |
| 0x009AA770:2>2 | Binary | Wisdom Form Accessibility
| 0x009AA3E0     | 2 Byte | Wisdom Form Experience
| 0x009AB088     | 2 Byte | Wisdom Form, number of times used
|                |        |
| 0x009AA770:6>6 | Binary | Master Form Accessibility
| 0x009AA450     | 2 Byte | Master Form Experience
| 0x009AB08C     | 2 Byte | Master Form, number of times used
|                |        |
| 0x009AA770:4>4 | Binary | Final Form Accessibility
| 0x009AA488     | 2 Byte | Final Form Experience
| 0x009AB08E     | 2 Byte | Final Form, number of times used
|                |        |
| 0x009AA77A:3>3 | Binary | Limit Form Accessibility
| 0x009AA418     | 2 Byte | Limit Form Experience
| 0x009AB08A     | 2 Byte | Limit Form, number of times used
|                |        |
| 0x009AA770:5>5 | Binary | Antiform Accessibility
| 0x009AA4C0     | 2 Byte | Antiform Points (A higher value means a higher chance of Antiform)
| 0x009AB090     | 2 Byte | Antiform, number of times used

<br/>

## Summons

| Offset         | Type   | Notes |
|----------------|--------|-------|
| 0x009AA794     | Byte   | Summon Experience
|                |        |
| 0x009AA770:0>0 | Binary | Ukulele Charm
| 0x009AA770:3>3 | Binary | Baseball Charm
| 0x009AA774:4>4 | Binary | Lamp Charm
| 0x009AA774:5>5 | Binary | Feather Charm

<br/>

## Ability Slots

| Offset     | Type   | Notes |
|------------|--------|-------|
| 0x009A95F4 | 2 Byte | Ability Slot 1
| 0x009A95F6 | 2 Byte | Ability Slot 2
| 0x009A95F8 | 2 Byte | Ability Slot 3
| 0x009A95FA | 2 Byte | Ability Slot 4
| 0x009A95FC | 2 Byte | Ability Slot 5
| 0x009A95FE | 2 Byte | Ability Slot 6
| 0x009A9600 | 2 Byte | Ability Slot 7
| 0x009A9602 | 2 Byte | Ability Slot 8
| 0x009A9604 | 2 Byte | Ability Slot 9
| 0x009A9606 | 2 Byte | Ability Slot 10
| 0x009A9608 | 2 Byte | Ability Slot 11
| 0x009A960A | 2 Byte | Ability Slot 12
| 0x009A960C | 2 Byte | Ability Slot 13
| 0x009A960E | 2 Byte | Ability Slot 14
| 0x009A9610 | 2 Byte | Ability Slot 15
| 0x009A9612 | 2 Byte | Ability Slot 16
| 0x009A9614 | 2 Byte | Ability Slot 17
| 0x009A9616 | 2 Byte | Ability Slot 18
| 0x009A9618 | 2 Byte | Ability Slot 19
| 0x009A961A | 2 Byte | Ability Slot 20
| 0x009A961C | 2 Byte | Ability Slot 21
| 0x009A961E | 2 Byte | Ability Slot 22
| 0x009A9620 | 2 Byte | Ability Slot 23
| 0x009A9622 | 2 Byte | Ability Slot 24
| 0x009A9624 | 2 Byte | Ability Slot 25
| 0x009A9626 | 2 Byte | Ability Slot 26
| 0x009A9628 | 2 Byte | Ability Slot 27
| 0x009A962A | 2 Byte | Ability Slot 28
| 0x009A962C | 2 Byte | Ability Slot 29
| 0x009A962E | 2 Byte | Ability Slot 30
| 0x009A9630 | 2 Byte | Ability Slot 31
| 0x009A9632 | 2 Byte | Ability Slot 32
| 0x009A9634 | 2 Byte | Ability Slot 33
| 0x009A9636 | 2 Byte | Ability Slot 34
| 0x009A9638 | 2 Byte | Ability Slot 35
| 0x009A963A | 2 Byte | Ability Slot 36
| 0x009A963C | 2 Byte | Ability Slot 37
| 0x009A963E | 2 Byte | Ability Slot 38
| 0x009A9640 | 2 Byte | Ability Slot 39
| 0x009A9642 | 2 Byte | Ability Slot 40
| 0x009A9644 | 2 Byte | Ability Slot 41
| 0x009A9646 | 2 Byte | Ability Slot 42
| 0x009A9648 | 2 Byte | Ability Slot 43
| 0x009A964A | 2 Byte | Ability Slot 44
| 0x009A964C | 2 Byte | Ability Slot 45
| 0x009A964E | 2 Byte | Ability Slot 46
| 0x009A9650 | 2 Byte | Ability Slot 47
| 0x009A9652 | 2 Byte | Ability Slot 48
| 0x009A9654 | 2 Byte | Ability Slot 49
| 0x009A9656 | 2 Byte | Ability Slot 50
| 0x009A9658 | 2 Byte | Ability Slot 51
| 0x009A965A | 2 Byte | Ability Slot 52
| 0x009A965C | 2 Byte | Ability Slot 53
| 0x009A965E | 2 Byte | Ability Slot 54
| 0x009A9660 | 2 Byte | Ability Slot 55
| 0x009A9662 | 2 Byte | Ability Slot 56
| 0x009A9664 | 2 Byte | Ability Slot 57
| 0x009A9666 | 2 Byte | Ability Slot 58
| 0x009A9668 | 2 Byte | Ability Slot 59
| 0x009A966A | 2 Byte | Ability Slot 60
| 0x009A966C | 2 Byte | Ability Slot 61
| 0x009A966E | 2 Byte | Ability Slot 62
| 0x009A9670 | 2 Byte | Ability Slot 63
| 0x009A9672 | 2 Byte | Ability Slot 64
| 0x009A9674 | 2 Byte | Ability Slot 65
| 0x009A9676 | 2 Byte | Ability Slot 66
| 0x009A9678 | 2 Byte | Ability Slot 67
| 0x009A967A | 2 Byte | Ability Slot 68
| 0x009A967C | 2 Byte | Ability Slot 69
| 0x009A967E | 2 Byte | Ability Slot 70; reserved for High Jump
| 0x009A9680 | 2 Byte | Ability Slot 71; reserved for Quick Run
| 0x009A9682 | 2 Byte | Ability Slot 72; reserved for Dodge Roll
| 0x009A9684 | 2 Byte | Ability Slot 73; reserved for Aerial Dodge
| 0x009A9686 | 2 Byte | Ability Slot 74; reserved for Glide
| 0x009A9688 | 2 Byte | Ability Slot 75
| 0x009A968A | 2 Byte | Ability Slot 76
| 0x009A968C | 2 Byte | Ability Slot 77
| 0x009A968E | 2 Byte | Ability Slot 78
| 0x009A9690 | 2 Byte | Ability Slot 79
| 0x009A9692 | 2 Byte | Ability Slot 80
