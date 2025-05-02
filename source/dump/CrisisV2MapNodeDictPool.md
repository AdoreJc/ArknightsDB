# CrisisV2MapNodeDictPool

**Namespace:** ` `


## Fields

- `CrisisV2SlotDetailMapView m_closure`

- `RectTransform m_container`

- `Boolean m_canCoverRoad`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CrisisV2MapNodeDictPool : GameObjectDictPool`1
{
	private CrisisV2SlotDetailMapView m_closure; // 0x20
	private RectTransform m_container; // 0x28
	private Boolean m_canCoverRoad; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ContainsKey; // 0x8
	private static DelegateBridge __Hotfix0_GetPrefab; // 0x10
	private static DelegateBridge __Hotfix0_Instantiate; // 0x18
	private static DelegateBridge __Hotfix0_IterKeys; // 0x20
	private static DelegateBridge __Hotfix0_OnAllocate; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30


	// RVA: 0x2c17c94 VA: 0x759522fc94
	public Void .ctor(CrisisV2SlotDetailMapView closure, RectTransform container, Boolean canCoverRoad) { }
	// RVA: 0x2c19f60 VA: 0x7595231f60
	protected override Boolean ContainsKey(String key) { }
	// RVA: 0x2c1a050 VA: 0x7595232050
	protected override CrisisV2MapNodeViewHolder GetPrefab(String key) { }
	// RVA: 0x2c1a0d8 VA: 0x75952320d8
	protected override CrisisV2MapNodeViewHolder Instantiate(String key, CrisisV2MapNodeViewHolder prefab) { }
	// RVA: 0x2c1a1a0 VA: 0x75952321a0
	protected override IEnumerable`1 IterKeys() { }
	// RVA: 0x2c1a290 VA: 0x7595232290
	protected override Void OnAllocate(String key, CrisisV2MapNodeViewHolder obj) { }
	// RVA: 0x2c1a424 VA: 0x7595232424
	protected override Void Render(String key, CrisisV2MapNodeViewHolder obj) { }
}
```