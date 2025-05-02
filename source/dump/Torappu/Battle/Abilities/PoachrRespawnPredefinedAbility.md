# PoachrRespawnPredefinedAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `ActionArray _actions`

- `BuffData _huntBuff`


## Methods

- `Void <>xLuaBaseProxy_OnCastOnTile(Tile, IList`1, IList`1, IList`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class PoachrRespawnPredefinedAbility : CastOnTileAbility
{
	private ActionArray _actions; // 0x1f8
	public BuffData _huntBuff; // 0x200
	private static DelegateBridge __Hotfix0_GetEventActions; // 0x0
	private static DelegateBridge __Hotfix0_OnCastOnTile; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1e28320 VA: 0x7594440320
	protected override IList`1 GetEventActions(Event ev) { }
	// RVA: 0x1e283b8 VA: 0x75944403b8
	protected override Void OnCastOnTile(Tile tile, IList`1 actions, IList`1 buffs, IList`1 attachments) { }
	// RVA: 0x1e28824 VA: 0x7594440824
	public Void .ctor() { }
	// RVA: 0x1e288d0 VA: 0x75944408d0
	private Void <>xLuaBaseProxy_OnCastOnTile(Tile P0, IList`1 P1, IList`1 P2, IList`1 P3) { }
}
```