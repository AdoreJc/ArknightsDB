# BuffToCharacterTileListener

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `TargetValidator _targetValidator`

- `Boolean _clearBuffWhenAbilityDetached`

- `Blackboard m_blackboard`


## Methods

- `Void _BuffToCharacter(BuffData[], Character)`

- `Void <>xLuaBaseProxy_DoSetData(Options)`

- `Void <>xLuaBaseProxy_OnDetached()`

- `Void <>xLuaBaseProxy_OnCasted(Tile, Int32)`

- `Void <>xLuaBaseProxy_OnLocatedCharacterUpdate(Character)`

- `Void <>xLuaBaseProxy_OnRefresh(Tile)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class BuffToCharacterTileListener : AttachableTileListener
{
	private TargetValidator _targetValidator; // 0x20
	private BuffData[] _buffs; // 0x28
	private BuffData[] _buffsWhenCasted; // 0x30
	private Boolean _clearBuffWhenAbilityDetached; // 0x38
	private const String CASTED_TIMES; // 0x0
	private Blackboard m_blackboard; // 0x40
	private List`1 m_buffs; // 0x48
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_OnDetached; // 0x8
	private static DelegateBridge __Hotfix0_OnCasted; // 0x10
	private static DelegateBridge __Hotfix0_OnLocatedCharacterUpdate; // 0x18
	private static DelegateBridge __Hotfix0_OnRefresh; // 0x20
	private static DelegateBridge __Hotfix0__BuffToCharacter; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1ed61b0 VA: 0x75944ee1b0
	public override Void DoSetData(Options options) { }
	// RVA: 0x1ed62b0 VA: 0x75944ee2b0
	public override Void OnDetached() { }
	// RVA: 0x1ed64cc VA: 0x75944ee4cc
	public override Void OnCasted(Tile tile, Int32 times) { }
	// RVA: 0x1ed688c VA: 0x75944ee88c
	public override Void OnLocatedCharacterUpdate(Character character) { }
	// RVA: 0x1ed6910 VA: 0x75944ee910
	public override Void OnRefresh(Tile tile) { }
	// RVA: 0x1ed6570 VA: 0x75944ee570
	private Void _BuffToCharacter(BuffData[] buffs, Character character) { }
	// RVA: 0x1ed69ac VA: 0x75944ee9ac
	public Void .ctor() { }
	// RVA: 0x1ed6b04 VA: 0x75944eeb04
	private Void <>xLuaBaseProxy_DoSetData(Options P0) { }
	// RVA: 0x1ed6b2c VA: 0x75944eeb2c
	private Void <>xLuaBaseProxy_OnDetached() { }
	// RVA: 0x1ed6b34 VA: 0x75944eeb34
	private Void <>xLuaBaseProxy_OnCasted(Tile P0, Int32 P1) { }
	// RVA: 0x1ed6b3c VA: 0x75944eeb3c
	private Void <>xLuaBaseProxy_OnLocatedCharacterUpdate(Character P0) { }
	// RVA: 0x1ed6b44 VA: 0x75944eeb44
	private Void <>xLuaBaseProxy_OnRefresh(Tile P0) { }
}
```