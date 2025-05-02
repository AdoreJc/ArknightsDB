# AdvancedSelectorTokenOrHost

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _checkBuff`

- `String _buffKey`

- `Boolean _isExcluded`

- `Character <character>k__BackingField`


## Properties

- `Boolean checkBuff`

- `Character character`


## Methods

- `Boolean get_checkBuff()`

- `Character get_character()`

- `Void set_character(Character)`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`

- `Boolean <>xLuaBaseProxy_CheckTargetIn(ILocatable)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AdvancedSelectorTokenOrHost : AdvancedSelector
{
	private Boolean _checkBuff; // 0xe8
	private String _buffKey; // 0xf0
	private Boolean _isExcluded; // 0xf8
	private Character <character>k__BackingField; // 0x100
	private static DelegateBridge __Hotfix0_get_checkBuff; // 0x0
	private static DelegateBridge __Hotfix0_get_character; // 0x8
	private static DelegateBridge __Hotfix0_set_character; // 0x10
	private static DelegateBridge __Hotfix0_Reset; // 0x18
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x20
	private static DelegateBridge __Hotfix0_FindTiles; // 0x28
	private static DelegateBridge __Hotfix0_CheckTargetIn; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Boolean checkBuff { get; }
	protected Character character { get; set; }

	// RVA: 0x1b99770 VA: 0x75941b1770
	private Boolean get_checkBuff() { }
	// RVA: 0x1b997d8 VA: 0x75941b17d8
	protected Character get_character() { }
	// RVA: 0x1b99840 VA: 0x75941b1840
	private Void set_character(Character value) { }
	// RVA: 0x1b998c4 VA: 0x75941b18c4
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1b999bc VA: 0x75941b19bc
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1b99ba8 VA: 0x75941b1ba8
	public override List`1 FindTiles(Vector2 pos) { }
	// RVA: 0x1b99c28 VA: 0x75941b1c28
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1b99cfc VA: 0x75941b1cfc
	public Void .ctor() { }
	// RVA: 0x1b99d68 VA: 0x75941b1d68
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1b99d6c VA: 0x75941b1d6c
	private ReusableList`1 <>xLuaBaseProxy_DoFindTargets_DISPOSE(Vector2 P0) { }
	// RVA: 0x1b99d74 VA: 0x75941b1d74
	private List`1 <>xLuaBaseProxy_FindTiles(Vector2 P0) { }
	// RVA: 0x1b99d7c VA: 0x75941b1d7c
	private Boolean <>xLuaBaseProxy_CheckTargetIn(ILocatable P0) { }
}
```