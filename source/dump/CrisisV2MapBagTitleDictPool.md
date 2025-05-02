# CrisisV2MapBagTitleDictPool

**Namespace:** ` `


## Fields

- `CrisisV2SlotDetailMapView m_closure`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CrisisV2MapBagTitleDictPool : GameObjectDictPool`1
{
	private CrisisV2SlotDetailMapView m_closure; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ContainsKey; // 0x8
	private static DelegateBridge __Hotfix0_GetPrefab; // 0x10
	private static DelegateBridge __Hotfix0_Instantiate; // 0x18
	private static DelegateBridge __Hotfix0_IterKeys; // 0x20
	private static DelegateBridge __Hotfix0_OnAllocate; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30


	// RVA: 0x2c17d80 VA: 0x759522fd80
	public Void .ctor(CrisisV2SlotDetailMapView closure) { }
	// RVA: 0x2c19520 VA: 0x7595231520
	protected override Boolean ContainsKey(String key) { }
	// RVA: 0x2c19610 VA: 0x7595231610
	protected override CrisisV2MapBagTitleView GetPrefab(String key) { }
	// RVA: 0x2c19698 VA: 0x7595231698
	protected override CrisisV2MapBagTitleView Instantiate(String key, CrisisV2MapBagTitleView prefab) { }
	// RVA: 0x2c1976c VA: 0x759523176c
	protected override IEnumerable`1 IterKeys() { }
	// RVA: 0x2c1985c VA: 0x759523185c
	protected override Void OnAllocate(String key, CrisisV2MapBagTitleView obj) { }
	// RVA: 0x2c19a3c VA: 0x7595231a3c
	protected override Void Render(String key, CrisisV2MapBagTitleView obj) { }
}
```