# BackgroundViewPool

**Namespace:** ` `


## Fields

- `SandboxV2DungeonMapView m_closure`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class BackgroundViewPool : GameObjectDictPool`1
{
	private SandboxV2DungeonMapView m_closure; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ContainsKey; // 0x8
	private static DelegateBridge __Hotfix0_IterKeys; // 0x10
	private static DelegateBridge __Hotfix0_GetPrefab; // 0x18
	private static DelegateBridge __Hotfix0_Instantiate; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28


	// RVA: 0x2571214 VA: 0x7594b89214
	public Void .ctor(SandboxV2DungeonMapView closure) { }
	// RVA: 0x2571ba0 VA: 0x7594b89ba0
	protected override Boolean ContainsKey(String key) { }
	// RVA: 0x2571cc4 VA: 0x7594b89cc4
	protected override IEnumerable`1 IterKeys() { }
	// RVA: 0x2571db4 VA: 0x7594b89db4
	protected override SandboxV2AbstractBackgroundView GetPrefab(String key) { }
	// RVA: 0x2571eac VA: 0x7594b89eac
	protected override SandboxV2AbstractBackgroundView Instantiate(String key, SandboxV2AbstractBackgroundView prefab) { }
	// RVA: 0x2571f74 VA: 0x7594b89f74
	protected override Void Render(String key, SandboxV2AbstractBackgroundView obj) { }
}
```