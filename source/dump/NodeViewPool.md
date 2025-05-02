# NodeViewPool

**Namespace:** ` `


## Fields

- `FifthAnnivExploreMapView m_closure`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class NodeViewPool : GameObjectDictPool`1
{
	private FifthAnnivExploreMapView m_closure; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ContainsKey; // 0x8
	private static DelegateBridge __Hotfix0_IterKeys; // 0x10
	private static DelegateBridge __Hotfix0_GetPrefab; // 0x18
	private static DelegateBridge __Hotfix0_Instantiate; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28


	// RVA: 0x29210a4 VA: 0x7594f390a4
	public Void .ctor(FifthAnnivExploreMapView closure) { }
	// RVA: 0x29213d4 VA: 0x7594f393d4
	protected override Boolean ContainsKey(String key) { }
	// RVA: 0x29214f8 VA: 0x7594f394f8
	protected override IEnumerable`1 IterKeys() { }
	// RVA: 0x29215e8 VA: 0x7594f395e8
	protected override FifthAnnivExploreNodeGroup GetPrefab(String key) { }
	// RVA: 0x2921720 VA: 0x7594f39720
	protected override FifthAnnivExploreNodeGroup Instantiate(String key, FifthAnnivExploreNodeGroup prefab) { }
	// RVA: 0x29217f4 VA: 0x7594f397f4
	protected override Void Render(String key, FifthAnnivExploreNodeGroup obj) { }
}
```