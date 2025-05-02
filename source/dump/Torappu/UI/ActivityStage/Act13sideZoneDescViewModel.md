# Act13sideZoneDescViewModel

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `String zoneId`

- `ActZoneClass zoneClass`

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
// Namespace : Torappu.UI.ActivityStage
public class Act13sideZoneDescViewModel : IHotfixable
{
	public String zoneId; // 0x10
	public ActZoneClass zoneClass; // 0x18
	public String unlockText; // 0x20
	public Int64 startTime; // 0x28
	public Boolean isStageLocked; // 0x30
	public Boolean isTimeLocked; // 0x31
	public Boolean isTimeOut; // 0x32
	public ListDict`2 stages; // 0x38
	public Boolean isNew; // 0x40
	public Boolean hasNewStage; // 0x41
	public List`1 stageFogList; // 0x48
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

	// RVA: 0x30930a8 VA: 0x75956ab0a8
	public Boolean get_isLocked() { }
	// RVA: 0x3093128 VA: 0x75956ab128
	public Boolean get_isAccessible() { }
	// RVA: 0x30931ac VA: 0x75956ab1ac
	public Boolean get_hasNewSign() { }
	// RVA: 0x309322c VA: 0x75956ab22c
	public Boolean IsFogUnlockable() { }
	// RVA: 0x3093348 VA: 0x75956ab348
	private Boolean _StageFogUnlockItemEnough(StageFogInfo fogInfo) { }
	// RVA: 0x3093410 VA: 0x75956ab410
	private Void .ctor() { }
	// RVA: 0x3093480 VA: 0x75956ab480
	public static Act13sideZoneDescViewModel Create(String activityId, ActivityZoneViewModel zoneModel, ZoneAdditionData descInfo, ZoneValidInfo validInfo, Int64 timeStampNow, Int64 activityStartTime) { }
}
```