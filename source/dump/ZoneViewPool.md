# ZoneViewPool

**Namespace:** ` `


## Fields

- `SandboxV2DungeonMapView m_closure`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ZoneViewPool : GameObjectDictPool`1
{
	private SandboxV2DungeonMapView m_closure; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ContainsKey; // 0x8
	private static DelegateBridge __Hotfix0_IterKeys; // 0x10
	private static DelegateBridge __Hotfix0_GetPrefab; // 0x18
	private static DelegateBridge __Hotfix0_Instantiate; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28


	// RVA: 0x257116c VA: 0x7594b8916c
	public Void .ctor(SandboxV2DungeonMapView closure) { }
	// RVA: 0x257407c VA: 0x7594b8c07c
	protected override Boolean ContainsKey(String key) { }
	// RVA: 0x25741a0 VA: 0x7594b8c1a0
	protected override IEnumerable`1 IterKeys() { }
	// RVA: 0x2574290 VA: 0x7594b8c290
	protected override SandboxV2ZoneView GetPrefab(String key) { }
	// RVA: 0x25743a0 VA: 0x7594b8c3a0
	protected override SandboxV2ZoneView Instantiate(String key, SandboxV2ZoneView prefab) { }
	// RVA: 0x2574454 VA: 0x7594b8c454
	protected override Void Render(String key, SandboxV2ZoneView obj) { }
}
```