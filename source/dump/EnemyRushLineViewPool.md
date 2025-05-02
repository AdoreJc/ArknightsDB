# EnemyRushLineViewPool

**Namespace:** ` `


## Fields

- `SandboxV2DungeonMapView m_closure`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class EnemyRushLineViewPool : AsyncGameObjectDictPool`2
{
	private const UInt32 PER_OBJ_COST; // 0x0
	private SandboxV2DungeonMapView m_closure; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ContainsKey; // 0x8
	private static DelegateBridge __Hotfix0_IterKeys; // 0x10
	private static DelegateBridge __Hotfix0_GetPrefab; // 0x18
	private static DelegateBridge __Hotfix0_Instantiate; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28


	// RVA: 0x25712bc VA: 0x7594b892bc
	public Void .ctor(SandboxV2DungeonMapView closure) { }
	// RVA: 0x2574948 VA: 0x7594b8c948
	protected override Boolean ContainsKey(String key) { }
	// RVA: 0x2574a6c VA: 0x7594b8ca6c
	protected override IEnumerable`1 IterKeys() { }
	// RVA: 0x2574b5c VA: 0x7594b8cb5c
	protected override SandboxV2EnemyRushLineView GetPrefab(String key) { }
	// RVA: 0x2574c6c VA: 0x7594b8cc6c
	protected override AsyncDataViewHandler`2 Instantiate(String key, SandboxV2EnemyRushLineView prefab) { }
	// RVA: 0x2574d84 VA: 0x7594b8cd84
	protected override Void Render(String key, AsyncDataViewHandler`2 obj) { }
}
```