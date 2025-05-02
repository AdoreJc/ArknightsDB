# CrisisV2MapBagDictPool

**Namespace:** ` `


## Fields

- `CrisisV2BagDetailMapView m_closure`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CrisisV2MapBagDictPool : GameObjectDictPool`1
{
	private CrisisV2BagDetailMapView m_closure; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ContainsKey; // 0x8
	private static DelegateBridge __Hotfix0_GetPrefab; // 0x10
	private static DelegateBridge __Hotfix0_Instantiate; // 0x18
	private static DelegateBridge __Hotfix0_IterKeys; // 0x20
	private static DelegateBridge __Hotfix0_OnAllocate; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30


	// RVA: 0x2bfd894 VA: 0x7595215894
	public Void .ctor(CrisisV2BagDetailMapView closure) { }
	// RVA: 0x2bfe864 VA: 0x7595216864
	protected override Boolean ContainsKey(String key) { }
	// RVA: 0x2bfe954 VA: 0x7595216954
	protected override CrisisV2MapBagView GetPrefab(String key) { }
	// RVA: 0x2bfe9dc VA: 0x75952169dc
	protected override CrisisV2MapBagView Instantiate(String key, CrisisV2MapBagView prefab) { }
	// RVA: 0x2bfeab0 VA: 0x7595216ab0
	protected override IEnumerable`1 IterKeys() { }
	// RVA: 0x2bfeba0 VA: 0x7595216ba0
	protected override Void OnAllocate(String key, CrisisV2MapBagView obj) { }
	// RVA: 0x2bfeea4 VA: 0x7595216ea4
	protected override Void Render(String key, CrisisV2MapBagView obj) { }
}
```