# UlpiaS3Ability

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _skillProgressBBKey`

- `String _colBBKey`

- `String _rowBBKey`


## Methods

- `Void OnProjectileReached(Object)`

- `Void _AssignSharedData(Character, GridPosition)`

- `Void _ResetSharedData(Character)`

- `Boolean _TryGetTileSecond(Tile, out)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class UlpiaS3Ability : PassiveBuffAbility
{
	private String _skillProgressBBKey; // 0x110
	private String _colBBKey; // 0x118
	private String _rowBBKey; // 0x120
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x0
	private static DelegateBridge __Hotfix0_GetProjectileActions; // 0x8
	private static DelegateBridge __Hotfix0_DoAttach; // 0x10
	private static DelegateBridge __Hotfix0_DoDetach; // 0x18
	private static DelegateBridge __Hotfix0_OnProjectileReached; // 0x20
	private static DelegateBridge __Hotfix0__AssignSharedData; // 0x28
	private static DelegateBridge __Hotfix0__ResetSharedData; // 0x30
	private static DelegateBridge __Hotfix0__TryGetTileSecond; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x1eb60fc VA: 0x75944ce0fc
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1eb6174 VA: 0x75944ce174
	public override IList`1 GetProjectileActions(Event ev, Projectile projectile) { }
	// RVA: 0x1eb61f4 VA: 0x75944ce1f4
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1eb6308 VA: 0x75944ce308
	protected override Void DoDetach() { }
	// RVA: 0x1eb640c VA: 0x75944ce40c
	public Void OnProjectileReached(Object args) { }
	// RVA: 0x1eb69ac VA: 0x75944ce9ac
	private Void _AssignSharedData(Character character, GridPosition gridPosition) { }
	// RVA: 0x1eb6674 VA: 0x75944ce674
	private Void _ResetSharedData(Character character) { }
	// RVA: 0x1eb6768 VA: 0x75944ce768
	private Boolean _TryGetTileSecond(Tile projectileReachedTile, out Tile targetTile) { }
	// RVA: 0x1eb6b1c VA: 0x75944ceb1c
	public Void .ctor() { }
	// RVA: 0x1eb6bf4 VA: 0x75944cebf4
	private IList`1 <>xLuaBaseProxy_GetEventActions(Event P0) { }
	// RVA: 0x1eb6bfc VA: 0x75944cebfc
	private IList`1 <>xLuaBaseProxy_GetProjectileActions(Event P0, Projectile P1) { }
	// RVA: 0x1eb6c04 VA: 0x75944cec04
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1eb6c0c VA: 0x75944cec0c
	private Void <>xLuaBaseProxy_DoDetach() { }
}
```