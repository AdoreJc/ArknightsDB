# TimelyDropTimeInfo

**Namespace:** `Torappu`


## Fields

- `Int64 startTs`

- `Int64 endTs`

- `String stagePic`

- `String dropPicId`

- `String stageUnlock`

- `String entranceDownPicId`

- `String entranceUpPicId`

- `String timelyGroupId`

- `String weeklyPicId`

- `Boolean isReplace`


## Methods

- `Int64 GetStartTs()`

- `Int64 GetEndTs()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class TimelyDropTimeInfo : ITimeValidInfo
{
	public Int64 startTs; // 0x10
	public Int64 endTs; // 0x18
	public String stagePic; // 0x20
	public String dropPicId; // 0x28
	public String stageUnlock; // 0x30
	public String entranceDownPicId; // 0x38
	public String entranceUpPicId; // 0x40
	public String timelyGroupId; // 0x48
	public String weeklyPicId; // 0x50
	public Boolean isReplace; // 0x58
	public Dictionary`2 apSupplyOutOfDateDict; // 0x60


	// RVA: 0x34f6a70 VA: 0x7595b0ea70
	public Int64 GetStartTs() { }
	// RVA: 0x34f6a78 VA: 0x7595b0ea78
	public Int64 GetEndTs() { }
	// RVA: 0x34f6a80 VA: 0x7595b0ea80
	public Void .ctor() { }
}
```