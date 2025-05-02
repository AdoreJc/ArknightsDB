# ApProtectZoneInfo

**Namespace:** `Torappu`


## Fields

- `String zoneId`


## Methods

- `Void AddTimeRange(Int64, Int64)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ApProtectZoneInfo
{
	public String zoneId; // 0x10
	public List`1 timeRanges; // 0x18


	// RVA: 0x34f6cb0 VA: 0x7595b0ecb0
	public Void .ctor() { }
	// RVA: 0x34f6cb8 VA: 0x7595b0ecb8
	public Void .ctor(String zoneId, Int64 startTs, Int64 endTs) { }
	// RVA: 0x34f6d08 VA: 0x7595b0ed08
	public Void AddTimeRange(Int64 startTs, Int64 endTs) { }
}
```