# OneOfAllBlockedOrAdvancedSelector

**Namespace:** `Torappu.Battle`


## Fields

- `Character <character>k__BackingField`


## Properties

- `Character character`


## Methods

- `Character get_character()`

- `Void set_character(Character)`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class OneOfAllBlockedOrAdvancedSelector : BlockedBaseSelector
{
	private Character <character>k__BackingField; // 0xe8
	private static DelegateBridge __Hotfix0_get_character; // 0x0
	private static DelegateBridge __Hotfix0_set_character; // 0x8
	private static DelegateBridge __Hotfix0_Reset; // 0x10
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected Character character { get; set; }

	// RVA: 0x1bb46cc VA: 0x75941cc6cc
	protected Character get_character() { }
	// RVA: 0x1bb4734 VA: 0x75941cc734
	private Void set_character(Character value) { }
	// RVA: 0x1bb47b8 VA: 0x75941cc7b8
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1bb48b4 VA: 0x75941cc8b4
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1bb4e5c VA: 0x75941cce5c
	public Void .ctor() { }
	// RVA: 0x1bb4ec8 VA: 0x75941ccec8
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1bb4ed0 VA: 0x75941cced0
	private ReusableList`1 <>xLuaBaseProxy_DoFindTargets_DISPOSE(Vector2 P0) { }
}
```