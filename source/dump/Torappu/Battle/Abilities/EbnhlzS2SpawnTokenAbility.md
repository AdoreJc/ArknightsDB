# EbnhlzS2SpawnTokenAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _abilityName`

- `Int32 m_castCounter`


## Methods

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_DoSpawnOnTile(Tile)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class EbnhlzS2SpawnTokenAbility : SpawnTokenOnTileByIDAbility
{
	private String _abilityName; // 0x238
	private Int32 m_castCounter; // 0x240
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x8
	private static DelegateBridge __Hotfix0_DoSpawnOnTile; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1e2a6c4 VA: 0x75944426c4
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e2a76c VA: 0x759444276c
	protected override Void OnCastStart() { }
	// RVA: 0x1e2a7dc VA: 0x75944427dc
	protected override Void DoSpawnOnTile(Tile tile) { }
	// RVA: 0x1e2a930 VA: 0x7594442930
	public Void .ctor() { }
	// RVA: 0x1e2a99c VA: 0x759444299c
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e2a9c4 VA: 0x75944429c4
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1e2a9c8 VA: 0x75944429c8
	private Void <>xLuaBaseProxy_DoSpawnOnTile(Tile P0) { }
}
```