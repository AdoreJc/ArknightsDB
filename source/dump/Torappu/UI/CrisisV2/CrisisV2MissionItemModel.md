# CrisisV2MissionItemModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisV2MissionInfo missionInfo`

- `Int32 sortId`

- `String title`

- `String desc`

- `MissionSortType missionSortType`

- `SortState missionState`


## Methods

- `Int32 CompareTo(CrisisV2MissionItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MissionItemModel : IHotfixable, IComparable`1
{
	public CrisisV2MissionInfo missionInfo; // 0x10
	public Int32 sortId; // 0x18
	public String title; // 0x20
	public String desc; // 0x28
	public List`1 rewardList; // 0x30
	public MissionSortType missionSortType; // 0x38
	public SortState missionState; // 0x3c
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_CompareTo; // 0x8


	// RVA: 0x2bf348c VA: 0x759520b48c
	public Void .ctor(String id, CrisisV2MissionType type) { }
	// RVA: 0x2bf35d8 VA: 0x759520b5d8
	public Int32 CompareTo(CrisisV2MissionItemModel obj) { }
}
```