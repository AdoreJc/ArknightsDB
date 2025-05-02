# CrisisV2MapTreasureDictPool

**Namespace:** ` `


## Fields

- `CrisisV2BagDetailMapView m_closure`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CrisisV2MapTreasureDictPool : GameObjectDictPool`1
{
	private CrisisV2BagDetailMapView m_closure; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ContainsKey; // 0x8
	private static DelegateBridge __Hotfix0_GetPrefab; // 0x10
	private static DelegateBridge __Hotfix0_Instantiate; // 0x18
	private static DelegateBridge __Hotfix0_IterKeys; // 0x20
	private static DelegateBridge __Hotfix0_OnAllocate; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30


	// RVA: 0x2bfd93c VA: 0x759521593c
	public Void .ctor(CrisisV2BagDetailMapView closure) { }
	// RVA: 0x2bfdcc4 VA: 0x7595215cc4
	protected override Boolean ContainsKey(String key) { }
	// RVA: 0x2bfddb4 VA: 0x7595215db4
	protected override CrisisV2MapNodeViewHolder GetPrefab(String key) { }
	// RVA: 0x2bfde3c VA: 0x7595215e3c
	protected override CrisisV2MapNodeViewHolder Instantiate(String key, CrisisV2MapNodeViewHolder prefab) { }
	// RVA: 0x2bfdf10 VA: 0x7595215f10
	protected override IEnumerable`1 IterKeys() { }
	// RVA: 0x2bfe000 VA: 0x7595216000
	protected override Void OnAllocate(String key, CrisisV2MapNodeViewHolder obj) { }
	// RVA: 0x2bfe21c VA: 0x759521621c
	protected override Void Render(String key, CrisisV2MapNodeViewHolder obj) { }
}
```