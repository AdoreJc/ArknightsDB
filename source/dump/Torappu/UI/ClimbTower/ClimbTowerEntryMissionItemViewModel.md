# ClimbTowerEntryMissionItemViewModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `String id`

- `String desc`

- `Int32 sortId`

- `String seasonName`

- `Int32 seasonNum`

- `Int32 progressCurr`

- `Int32 progressTarget`

- `Single progress`

- `String bindTowerId`

- `String bindGodCardId`

- `Boolean isReceived`

- `Boolean isComplete`


## Properties

- `Boolean needReceive`


## Methods

- `Boolean get_needReceive()`

- `Int32 CompareTo(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryMissionItemViewModel : IHotfixable, IComparable
{
	public String id; // 0x10
	public String desc; // 0x18
	public Int32 sortId; // 0x20
	public String seasonName; // 0x28
	public Int32 seasonNum; // 0x30
	public Int32 progressCurr; // 0x34
	public Int32 progressTarget; // 0x38
	public Single progress; // 0x3c
	public String bindTowerId; // 0x40
	public String bindGodCardId; // 0x48
	public List`1 rewards; // 0x50
	public Boolean isReceived; // 0x58
	public Boolean isComplete; // 0x59
	private static DelegateBridge __Hotfix0_get_needReceive; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_CompareTo; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean needReceive { get; }

	// RVA: 0x2cd8560 VA: 0x75952f0560
	public Boolean get_needReceive() { }
	// RVA: 0x2cd8080 VA: 0x75952f0080
	public static ClimbTowerEntryMissionItemViewModel LoadData(String missionId, ClimbTowerSeasonInfoData seasonInfoData) { }
	// RVA: 0x2cd8650 VA: 0x75952f0650
	public Int32 CompareTo(Object obj) { }
	// RVA: 0x2cd85e0 VA: 0x75952f05e0
	public Void .ctor() { }
}
```