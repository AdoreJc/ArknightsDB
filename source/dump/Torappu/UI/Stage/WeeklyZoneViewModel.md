# WeeklyZoneViewModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Boolean isFuncUnLocked`

- `ZoneOpenDetailState todayOpenState`

- `WeeklyType weeklyType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class WeeklyZoneViewModel : ZoneViewModel
{
	public Boolean isFuncUnLocked; // 0x90
	public ZoneOpenDetailState todayOpenState; // 0x98
	public WeekStruct`1 weekOpenInfo; // 0xa0
	public WeeklyType weeklyType; // 0xd8


	// RVA: 0x2fcaa2c VA: 0x75955e2a2c
	public override Int32 CompareTo(ZoneViewModel otherModel) { }
	// RVA: 0x2fcab00 VA: 0x75955e2b00
	public override Void LoadExtraData(String zoneId) { }
	// RVA: 0x2fcac74 VA: 0x75955e2c74
	public Void .ctor() { }
}
```