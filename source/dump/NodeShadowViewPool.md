# NodeShadowViewPool

**Namespace:** ` `


## Fields

- `FifthAnnivExploreMapView m_closure`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class NodeShadowViewPool : GameObjectDictPool`1
{
	private FifthAnnivExploreMapView m_closure; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ContainsKey; // 0x8
	private static DelegateBridge __Hotfix0_IterKeys; // 0x10
	private static DelegateBridge __Hotfix0_GetPrefab; // 0x18
	private static DelegateBridge __Hotfix0_Instantiate; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28


	// RVA: 0x292114c VA: 0x7594f3914c
	public Void .ctor(FifthAnnivExploreMapView closure) { }
	// RVA: 0x2922160 VA: 0x7594f3a160
	protected override Boolean ContainsKey(String key) { }
	// RVA: 0x2922284 VA: 0x7594f3a284
	protected override IEnumerable`1 IterKeys() { }
	// RVA: 0x2922374 VA: 0x7594f3a374
	protected override FifthAnnivExploreNodeShadowView GetPrefab(String key) { }
	// RVA: 0x29225bc VA: 0x7594f3a5bc
	protected override FifthAnnivExploreNodeShadowView Instantiate(String key, FifthAnnivExploreNodeShadowView prefab) { }
	// RVA: 0x2922690 VA: 0x7594f3a690
	protected override Void Render(String key, FifthAnnivExploreNodeShadowView obj) { }
}
```