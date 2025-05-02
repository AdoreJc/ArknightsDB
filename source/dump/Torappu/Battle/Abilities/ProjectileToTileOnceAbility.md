# ProjectileToTileOnceAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `TileSelector _subTileSelector`

- `Boolean _useSubSelector`


## Methods

- `Void CastOnTileBySubSelector()`

- `TargetSelector <>xLuaBaseProxy_get_selector()`

- `Void <>xLuaBaseProxy_OnCastOnTile(Tile, IList`1, IList`1, IList`1)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_Reset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ProjectileToTileOnceAbility : ProjectileToTileAbility
{
	private TileSelector _subTileSelector; // 0x250
	private List`1 m_cachedTiles; // 0x258
	private Boolean _useSubSelector; // 0x260
	private static DelegateBridge __Hotfix0_get_selector; // 0x0
	private static DelegateBridge __Hotfix0_OnCastOnTile; // 0x8
	private static DelegateBridge __Hotfix0_DoSetData; // 0x10
	private static DelegateBridge __Hotfix0_Reset; // 0x18
	private static DelegateBridge __Hotfix0_CastOnTileBySubSelector; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override TargetSelector selector { get; }

	// RVA: 0x1e2b200 VA: 0x7594443200
	public override TargetSelector get_selector() { }
	// RVA: 0x1e2b284 VA: 0x7594443284
	protected override Void OnCastOnTile(Tile tile, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e2b400 VA: 0x7594443400
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e2b51c VA: 0x759444351c
	protected override Void Reset() { }
	// RVA: 0x1e2b600 VA: 0x7594443600
	public Void CastOnTileBySubSelector() { }
	// RVA: 0x1e2b68c VA: 0x759444368c
	public Void .ctor() { }
	// RVA: 0x1e2b74c VA: 0x759444374c
	private TargetSelector <>xLuaBaseProxy_get_selector() { }
	// RVA: 0x1e2b754 VA: 0x7594443754
	private Void <>xLuaBaseProxy_OnCastOnTile(Tile P0, IList`1 P1, IList`1 P2, IList`1 P3) { }
	// RVA: 0x1e2b758 VA: 0x7594443758
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e2b77c VA: 0x759444377c
	private Void <>xLuaBaseProxy_Reset() { }
}
```