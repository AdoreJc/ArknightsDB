# CrisisV2MapRoadModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `String m_roadId`

- `CrisisV2MapRoadRelationData m_relationData`


## Properties

- `String roadId`

- `CrisisV2MapRoadPointData startTargetData`

- `CrisisV2MapRoadPointData endTargetData`


## Methods

- `String get_roadId()`

- `CrisisV2MapRoadPointData get_startTargetData()`

- `CrisisV2MapRoadPointData get_endTargetData()`

- `Void Load(String, CrisisV2MapRoadRelationData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapRoadModel : IHotfixable
{
	private String m_roadId; // 0x10
	private CrisisV2MapRoadRelationData m_relationData; // 0x18
	private static DelegateBridge __Hotfix0_get_roadId; // 0x0
	private static DelegateBridge __Hotfix0_get_startTargetData; // 0x8
	private static DelegateBridge __Hotfix0_get_endTargetData; // 0x10
	private static DelegateBridge __Hotfix0_Load; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String roadId { get; }
	public CrisisV2MapRoadPointData startTargetData { get; }
	public CrisisV2MapRoadPointData endTargetData { get; }

	// RVA: 0x2bf3424 VA: 0x759520b424
	public String get_roadId() { }
	// RVA: 0x2bef460 VA: 0x7595207460
	public CrisisV2MapRoadPointData get_startTargetData() { }
	// RVA: 0x2bef4d8 VA: 0x75952074d8
	public CrisisV2MapRoadPointData get_endTargetData() { }
	// RVA: 0x2bf1ac0 VA: 0x7595209ac0
	public Void Load(String roadId, CrisisV2MapRoadRelationData roadRelationData) { }
	// RVA: 0x2bf1a50 VA: 0x7595209a50
	public Void .ctor() { }
}
```