# Act12sideZoneDescViewModel

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `String zoneId`

- `ActZoneClass zoneClass`

- `String zoneName`

- `String unlockText`

- `Int64 startTime`

- `Boolean isStageLocked`

- `Boolean isTimeLocked`

- `Boolean isTimeOut`

- `Boolean isNew`

- `Boolean hasNewStage`


## Properties

- `Boolean isLocked`

- `Boolean isAccessible`

- `Boolean hasNewSign`


## Methods

- `Boolean get_isLocked()`

- `Boolean get_isAccessible()`

- `Boolean get_hasNewSign()`

- `Boolean IsFogUnlockable()`

- `Boolean _StageFogUnlockItemEnough(StageFogInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideZoneDescViewModel : IHotfixable
{
	public String zoneId; // 0x10
	public ActZoneClass zoneClass; // 0x18
	public String zoneName; // 0x20
	public String unlockText; // 0x28
	public Int64 startTime; // 0x30
	public Boolean isStageLocked; // 0x38
	public Boolean isTimeLocked; // 0x39
	public Boolean isTimeOut; // 0x3a
	public ListDict`2 stages; // 0x40
	public Boolean isNew; // 0x48
	public Boolean hasNewStage; // 0x49
	public List`1 stageFogList; // 0x50
	private static DelegateBridge __Hotfix0_get_isLocked; // 0x0
	private static DelegateBridge __Hotfix0_get_isAccessible; // 0x8
	private static DelegateBridge __Hotfix0_get_hasNewSign; // 0x10
	private static DelegateBridge __Hotfix0_IsFogUnlockable; // 0x18
	private static DelegateBridge __Hotfix0__StageFogUnlockItemEnough; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28
	private static DelegateBridge __Hotfix0_Create; // 0x30

	public Boolean isLocked { get; }
	public Boolean isAccessible { get; }
	public Boolean hasNewSign { get; }

	// RVA: 0x3460c80 VA: 0x7595a78c80
	public Boolean get_isLocked() { }
	// RVA: 0x3460d00 VA: 0x7595a78d00
	public Boolean get_isAccessible() { }
	// RVA: 0x3460d84 VA: 0x7595a78d84
	public Boolean get_hasNewSign() { }
	// RVA: 0x3460e04 VA: 0x7595a78e04
	public Boolean IsFogUnlockable() { }
	// RVA: 0x3460f28 VA: 0x7595a78f28
	private Boolean _StageFogUnlockItemEnough(StageFogInfo fogInfo) { }
	// RVA: 0x3460ff0 VA: 0x7595a78ff0
	private Void .ctor() { }
	// RVA: 0x3461060 VA: 0x7595a79060
	public static Act12sideZoneDescViewModel Create(String activityId, ActivityZoneViewModel zoneModel, ZoneAdditionData descInfo, ZoneValidInfo validInfo, Int64 timeStampNow, Int64 activityStartTime) { }
}
```