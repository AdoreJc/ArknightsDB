# CrisisV2MapRoadDictPool

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisV2MapModel m_mapModel`

- `RectTransform m_selectContainer`

- `RectTransform m_unselectContainer`

- `CrisisV2MapRoadView m_roadPrefab`

- `ViewType m_viewType`


## Methods

- `Void UpdateModel(CrisisV2MapModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapRoadDictPool : GameObjectDictPool`1
{
	private CrisisV2MapModel m_mapModel; // 0x20
	private RectTransform m_selectContainer; // 0x28
	private RectTransform m_unselectContainer; // 0x30
	private CrisisV2MapRoadView m_roadPrefab; // 0x38
	private ViewType m_viewType; // 0x40
	private HashSet`1 m_unselectRoadSet; // 0x48
	private HashSet`1 m_selectRoadSet; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_UpdateModel; // 0x8
	private static DelegateBridge __Hotfix0__GetRoadPosMap; // 0x10
	private static DelegateBridge __Hotfix0_OnAllocate; // 0x18
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x20
	private static DelegateBridge __Hotfix0_ContainsKey; // 0x28
	private static DelegateBridge __Hotfix0_GetPrefab; // 0x30
	private static DelegateBridge __Hotfix0_Instantiate; // 0x38
	private static DelegateBridge __Hotfix0_IterKeys; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x48


	// RVA: 0x2bfd740 VA: 0x7595215740
	public Void .ctor(Input input) { }
	// RVA: 0x2bfd3a8 VA: 0x75952153a8
	public Void UpdateModel(CrisisV2MapModel mapModel) { }
	// RVA: 0x2c09fe0 VA: 0x7595221fe0
	private Dictionary`2 _GetRoadPosMap() { }
	// RVA: 0x2c0a0c8 VA: 0x75952220c8
	protected override Void OnAllocate(String key, CrisisV2MapRoadView obj) { }
	// RVA: 0x2c0a260 VA: 0x7595222260
	protected override Void OnRecycle(String key, CrisisV2MapRoadView obj) { }
	// RVA: 0x2c0a31c VA: 0x759522231c
	protected override Boolean ContainsKey(String key) { }
	// RVA: 0x2c0a3cc VA: 0x75952223cc
	protected override CrisisV2MapRoadView GetPrefab(String key) { }
	// RVA: 0x2c0a448 VA: 0x7595222448
	protected override CrisisV2MapRoadView Instantiate(String key, CrisisV2MapRoadView prefab) { }
	// RVA: 0x2c0a510 VA: 0x7595222510
	protected override IEnumerable`1 IterKeys() { }
	// RVA: 0x2c0a5bc VA: 0x75952225bc
	protected override Void Render(String key, CrisisV2MapRoadView obj) { }
}
```