# Act10D5ZoneDescViewModel

**Namespace:** `Torappu.Activity.Act10D5`


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
// Namespace : Torappu.Activity.Act10D5
public class Act10D5ZoneDescViewModel : IHotfixable
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

	// RVA: 0x3486a38 VA: 0x7595a9ea38
	public Boolean get_isLocked() { }
	// RVA: 0x34869b4 VA: 0x7595a9e9b4
	public Boolean get_isAccessible() { }
	// RVA: 0x3489384 VA: 0x7595aa1384
	private Void .ctor() { }
	// RVA: 0x34893f4 VA: 0x7595aa13f4
	public static Act10D5ZoneDescViewModel Create(ActivityZoneViewModel zoneModel, ZoneDescInfo descInfo, ZoneValidInfo validInfo, Int64 timeStampNow, Int64 activityStartTime) { }
}
```