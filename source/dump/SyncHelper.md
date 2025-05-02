# SyncHelper

**Namespace:** ` `


## Fields

- `ConstructLandManager m_manager`


## Methods

- `Void DoSync(Boolean, Boolean)`

- `Void _RefreshMap(NodeStage, Boolean)`

- `Void _RefreshTile(Building, GridPosition, Character, Boolean)`

- `Void _RefreshDeck(Boolean)`

- `Void _RefreshRes(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class SyncHelper : IHotfixable
{
	private Dictionary`2 m_buildingCache; // 0x10
	private Dictionary`2 m_statusCache; // 0x18
	private ConstructLandManager m_manager; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_DoSync; // 0x8
	private static DelegateBridge __Hotfix0__RefreshMap; // 0x10
	private static DelegateBridge __Hotfix0__RefreshTile; // 0x18
	private static DelegateBridge __Hotfix0__RefreshHp; // 0x20
	private static DelegateBridge __Hotfix0__RefreshDeck; // 0x28
	private static DelegateBridge __Hotfix0__RefreshRes; // 0x30


	// RVA: 0x4044d50 VA: 0x759665cd50
	public Void .ctor(ConstructLandManager manager) { }
	// RVA: 0x4044f30 VA: 0x759665cf30
	public Void DoSync(Boolean isMapNeedCheck, Boolean isDeckAndResNeedCheck) { }
	// RVA: 0x4046490 VA: 0x759665e490
	private Void _RefreshMap(NodeStage nodeStage, Boolean needCheck) { }
	// RVA: 0x404751c VA: 0x759665f51c
	private Void _RefreshTile(Building building, GridPosition gridPosition, Character character, Boolean needCheck) { }
	// RVA: 0x404786c VA: 0x759665f86c
	private static Void _RefreshHp(Single targetHpRatio, GridPosition gridPosition, Character character, Boolean needCheck) { }
	// RVA: 0x4046184 VA: 0x759665e184
	private Void _RefreshDeck(Boolean needCheck) { }
	// RVA: 0x4047278 VA: 0x759665f278
	private Void _RefreshRes(Boolean needCheck) { }
}
```