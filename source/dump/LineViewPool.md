# LineViewPool

**Namespace:** ` `


## Fields

- `FifthAnnivExploreMapView m_closure`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class LineViewPool : GameObjectDictPool`1
{
	private FifthAnnivExploreMapView m_closure; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ContainsKey; // 0x8
	private static DelegateBridge __Hotfix0_IterKeys; // 0x10
	private static DelegateBridge __Hotfix0_GetPrefab; // 0x18
	private static DelegateBridge __Hotfix0_Instantiate; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28


	// RVA: 0x29211f4 VA: 0x7594f391f4
	public Void .ctor(FifthAnnivExploreMapView closure) { }
	// RVA: 0x2922f50 VA: 0x7594f3af50
	protected override Boolean ContainsKey(String key) { }
	// RVA: 0x2923074 VA: 0x7594f3b074
	protected override IEnumerable`1 IterKeys() { }
	// RVA: 0x2923164 VA: 0x7594f3b164
	protected override FifthAnnivExploreLineView GetPrefab(String key) { }
	// RVA: 0x2923258 VA: 0x7594f3b258
	protected override FifthAnnivExploreLineView Instantiate(String key, FifthAnnivExploreLineView prefab) { }
	// RVA: 0x292332c VA: 0x7594f3b32c
	protected override Void Render(String key, FifthAnnivExploreLineView obj) { }
}
```