# CrisisV2MapBagBgDictPool

**Namespace:** ` `


## Fields

- `CrisisV2SlotDetailMapView m_closure`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CrisisV2MapBagBgDictPool : GameObjectDictPool`1
{
	private CrisisV2SlotDetailMapView m_closure; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ContainsKey; // 0x8
	private static DelegateBridge __Hotfix0_GetPrefab; // 0x10
	private static DelegateBridge __Hotfix0_Instantiate; // 0x18
	private static DelegateBridge __Hotfix0_IterKeys; // 0x20
	private static DelegateBridge __Hotfix0_OnAllocate; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30


	// RVA: 0x2c17e28 VA: 0x759522fe28
	public Void .ctor(CrisisV2SlotDetailMapView closure) { }
	// RVA: 0x2c18b04 VA: 0x7595230b04
	protected override Boolean ContainsKey(String key) { }
	// RVA: 0x2c18bf4 VA: 0x7595230bf4
	protected override CrisisV2MapBagBgView GetPrefab(String key) { }
	// RVA: 0x2c18c7c VA: 0x7595230c7c
	protected override CrisisV2MapBagBgView Instantiate(String key, CrisisV2MapBagBgView prefab) { }
	// RVA: 0x2c18d50 VA: 0x7595230d50
	protected override IEnumerable`1 IterKeys() { }
	// RVA: 0x2c18e40 VA: 0x7595230e40
	protected override Void OnAllocate(String key, CrisisV2MapBagBgView obj) { }
	// RVA: 0x2c19020 VA: 0x7595231020
	protected override Void Render(String key, CrisisV2MapBagBgView obj) { }
}
```