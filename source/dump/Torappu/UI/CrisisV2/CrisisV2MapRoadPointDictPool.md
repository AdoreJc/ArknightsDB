# CrisisV2MapRoadPointDictPool

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisV2MapModel m_mapModel`

- `RectTransform m_selectContainer`

- `RectTransform m_unselectContainer`

- `CrisisV2MapRoadPointView m_pointPrefab`

- `ViewType m_viewType`


## Methods

- `Void UpdateModel(CrisisV2MapModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapRoadPointDictPool : GameObjectDictPool`1
{
	private CrisisV2MapModel m_mapModel; // 0x20
	private RectTransform m_selectContainer; // 0x28
	private RectTransform m_unselectContainer; // 0x30
	private CrisisV2MapRoadPointView m_pointPrefab; // 0x38
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


	// RVA: 0x2c0abac VA: 0x7595222bac
	public Void .ctor(Input input) { }
	// RVA: 0x2c0ad00 VA: 0x7595222d00
	public Void UpdateModel(CrisisV2MapModel mapModel) { }
	// RVA: 0x2c0ad84 VA: 0x7595222d84
	private Dictionary`2 _GetRoadPosMap() { }
	// RVA: 0x2c0ae6c VA: 0x7595222e6c
	protected override Void OnAllocate(String key, CrisisV2MapRoadPointView obj) { }
	// RVA: 0x2c0b094 VA: 0x7595223094
	protected override Void OnRecycle(String key, CrisisV2MapRoadPointView obj) { }
	// RVA: 0x2c0b150 VA: 0x7595223150
	protected override Boolean ContainsKey(String key) { }
	// RVA: 0x2c0b200 VA: 0x7595223200
	protected override CrisisV2MapRoadPointView GetPrefab(String key) { }
	// RVA: 0x2c0b27c VA: 0x759522327c
	protected override CrisisV2MapRoadPointView Instantiate(String key, CrisisV2MapRoadPointView prefab) { }
	// RVA: 0x2c0b344 VA: 0x7595223344
	protected override IEnumerable`1 IterKeys() { }
	// RVA: 0x2c0b434 VA: 0x7595223434
	protected override Void Render(String key, CrisisV2MapRoadPointView obj) { }
}
```