# Act9D0ZoneDescViewModel

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `String zoneId`

- `String zoneName`

- `String iconId`

- `String unlockText`

- `Int64 startTime`

- `Boolean isStageLocked`

- `Boolean isTimeLocked`

- `Boolean isTimeout`

- `Boolean isNew`


## Properties

- `Boolean isLocked`

- `Boolean isAccessible`


## Methods

- `Boolean get_isLocked()`

- `Boolean get_isAccessible()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0ZoneDescViewModel : IHotfixable
{
	public String zoneId; // 0x10
	public String zoneName; // 0x18
	public String iconId; // 0x20
	public String unlockText; // 0x28
	public Int64 startTime; // 0x30
	public Boolean isStageLocked; // 0x38
	public Boolean isTimeLocked; // 0x39
	public Boolean isTimeout; // 0x3a
	public Boolean isNew; // 0x3b
	private static DelegateBridge __Hotfix0_get_isLocked; // 0x0
	private static DelegateBridge __Hotfix0_get_isAccessible; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_Create; // 0x18

	public Boolean isLocked { get; }
	public Boolean isAccessible { get; }

	// RVA: 0x31ae43c VA: 0x75957c643c
	public Boolean get_isLocked() { }
	// RVA: 0x31ae4bc VA: 0x75957c64bc
	public Boolean get_isAccessible() { }
	// RVA: 0x31ae540 VA: 0x75957c6540
	private Void .ctor() { }
	// RVA: 0x31ae5b0 VA: 0x75957c65b0
	public static Act9D0ZoneDescViewModel Create(ActivityZoneViewModel zoneModel, ZoneDescInfo descInfo, ZoneValidInfo validInfo, Int64 timeStampNow, Int64 activityStartTime) { }
}
```