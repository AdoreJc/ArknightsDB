# Act12sideMissionViewModel

**Namespace:** `Torappu.Activity.Act12side`


## Fields

- `Int32 completedCount`

- `Boolean m_filterListInit`

- `ActZoneClass m_filterClass`


## Properties

- `ActZoneClass filterClass`


## Methods

- `ActZoneClass get_filterClass()`

- `Void set_filterClass(ActZoneClass)`

- `Void _FilterList(ActZoneClass)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side
public class Act12sideMissionViewModel : IHotfixable
{
	public List`1 missionItemList; // 0x10
	public Int32 completedCount; // 0x18
	private Boolean m_filterListInit; // 0x1c
	private ActZoneClass m_filterClass; // 0x20
	private List`1 m_filterItemList; // 0x28
	private List`1 m_unlockNewMissionIdList; // 0x30
	private static DelegateBridge __Hotfix0_get_unlockNewMissionIdList; // 0x0
	private static DelegateBridge __Hotfix0_get_filterClass; // 0x8
	private static DelegateBridge __Hotfix0_set_filterClass; // 0x10
	private static DelegateBridge __Hotfix0_get_filterItemList; // 0x18
	private static DelegateBridge __Hotfix0__FilterList; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public List`1 unlockNewMissionIdList { get; }
	public ActZoneClass filterClass { get; set; }
	public List`1 filterItemList { get; }

	// RVA: 0x344b034 VA: 0x7595a63034
	public List`1 get_unlockNewMissionIdList() { }
	// RVA: 0x344b1dc VA: 0x7595a631dc
	public ActZoneClass get_filterClass() { }
	// RVA: 0x344b244 VA: 0x7595a63244
	public Void set_filterClass(ActZoneClass value) { }
	// RVA: 0x344b578 VA: 0x7595a63578
	public List`1 get_filterItemList() { }
	// RVA: 0x344b2e4 VA: 0x7595a632e4
	private Void _FilterList(ActZoneClass zoneClass) { }
	// RVA: 0x344b5fc VA: 0x7595a635fc
	public Void .ctor() { }
}
```