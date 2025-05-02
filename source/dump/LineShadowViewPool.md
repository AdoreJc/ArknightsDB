# LineShadowViewPool

**Namespace:** ` `


## Fields

- `FifthAnnivExploreMapView m_closure`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class LineShadowViewPool : GameObjectDictPool`1
{
	private FifthAnnivExploreMapView m_closure; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ContainsKey; // 0x8
	private static DelegateBridge __Hotfix0_IterKeys; // 0x10
	private static DelegateBridge __Hotfix0_GetPrefab; // 0x18
	private static DelegateBridge __Hotfix0_Instantiate; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28


	// RVA: 0x292129c VA: 0x7594f3929c
	public Void .ctor(FifthAnnivExploreMapView closure) { }
	// RVA: 0x2923d8c VA: 0x7594f3bd8c
	protected override Boolean ContainsKey(String key) { }
	// RVA: 0x2923eb0 VA: 0x7594f3beb0
	protected override IEnumerable`1 IterKeys() { }
	// RVA: 0x2923fa0 VA: 0x7594f3bfa0
	protected override FifthAnnivExploreLineView GetPrefab(String key) { }
	// RVA: 0x292402c VA: 0x7594f3c02c
	protected override FifthAnnivExploreLineView Instantiate(String key, FifthAnnivExploreLineView prefab) { }
	// RVA: 0x2924100 VA: 0x7594f3c100
	protected override Void Render(String key, FifthAnnivExploreLineView obj) { }
}
```