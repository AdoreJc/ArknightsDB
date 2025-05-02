# CrisisV2MapExclusionDictPool

**Namespace:** ` `


## Fields

- `CrisisV2SlotDetailMapView m_closure`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CrisisV2MapExclusionDictPool : GameObjectDictPool`1
{
	private CrisisV2SlotDetailMapView m_closure; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ContainsKey; // 0x8
	private static DelegateBridge __Hotfix0_GetPrefab; // 0x10
	private static DelegateBridge __Hotfix0_Instantiate; // 0x18
	private static DelegateBridge __Hotfix0_IterKeys; // 0x20
	private static DelegateBridge __Hotfix0_OnAllocate; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30


	// RVA: 0x2c17ed0 VA: 0x759522fed0
	public Void .ctor(CrisisV2SlotDetailMapView closure) { }
	// RVA: 0x2c181cc VA: 0x75952301cc
	protected override Boolean ContainsKey(String key) { }
	// RVA: 0x2c182bc VA: 0x75952302bc
	protected override CrisisV2MapExclusionGroupView GetPrefab(String key) { }
	// RVA: 0x2c18344 VA: 0x7595230344
	protected override CrisisV2MapExclusionGroupView Instantiate(String key, CrisisV2MapExclusionGroupView prefab) { }
	// RVA: 0x2c18418 VA: 0x7595230418
	protected override IEnumerable`1 IterKeys() { }
	// RVA: 0x2c18508 VA: 0x7595230508
	protected override Void OnAllocate(String key, CrisisV2MapExclusionGroupView obj) { }
	// RVA: 0x2c186e8 VA: 0x75952306e8
	protected override Void Render(String key, CrisisV2MapExclusionGroupView obj) { }
}
```