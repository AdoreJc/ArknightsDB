# AdjacentTileToggleChecker

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _isLocalPosition`

- `TileCondition _condition`

- `Int32 m_minCnt`


## Methods

- `Boolean _CheckCondition(GridPosition, TileCondition)`

- `GridPosition _ObjectToWorldPosition(Entity, GridPosition)`

- `Void <>xLuaBaseProxy_OnDetached()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AdjacentTileToggleChecker : Checker
{
	private GridPosition[] posList; // 0x20
	private Boolean _isLocalPosition; // 0x28
	private TileCondition _condition; // 0x2c
	private Int32 m_minCnt; // 0x34
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_OnDetached; // 0x8
	private static DelegateBridge __Hotfix0_CheckInitialToggled; // 0x10
	private static DelegateBridge __Hotfix0__CheckCondition; // 0x18
	private static DelegateBridge __Hotfix0__ObjectToWorldPosition; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1e57b24 VA: 0x759446fb24
	protected override Void LoadData(Blackboard blackboard) { }
	// RVA: 0x1e57bd8 VA: 0x759446fbd8
	public override Void OnDetached() { }
	// RVA: 0x1e57c44 VA: 0x759446fc44
	public override Boolean CheckInitialToggled() { }
	// RVA: 0x1e57f34 VA: 0x759446ff34
	private Boolean _CheckCondition(GridPosition pos, TileCondition cond) { }
	// RVA: 0x1e57e04 VA: 0x759446fe04
	private GridPosition _ObjectToWorldPosition(Entity obj, GridPosition pos) { }
	// RVA: 0x1e58060 VA: 0x7594470060
	public Void .ctor() { }
	// RVA: 0x1e58108 VA: 0x7594470108
	private Void <>xLuaBaseProxy_OnDetached() { }
}
```