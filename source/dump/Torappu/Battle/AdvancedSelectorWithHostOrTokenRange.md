# AdvancedSelectorWithHostOrTokenRange

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _fetchHost`

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
public class AdvancedSelectorWithHostOrTokenRange : SecondaryFilterAdvancedSelector
{
	private Boolean _fetchHost; // 0x118
	private Character <character>k__BackingField; // 0x120
	private List`1 m_entities; // 0x128
	private List`1 m_extraTargets; // 0x130
	private static DelegateBridge __Hotfix0_get_character; // 0x0
	private static DelegateBridge __Hotfix0_set_character; // 0x8
	private static DelegateBridge __Hotfix0_Reset; // 0x10
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x18
	private static DelegateBridge __Hotfix0_DoFindTargetsInHostOrTokenRange; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected Character character { get; set; }

	// RVA: 0x1b9b94c VA: 0x75941b394c
	protected Character get_character() { }
	// RVA: 0x1b9b9b4 VA: 0x75941b39b4
	private Void set_character(Character value) { }
	// RVA: 0x1b9ba38 VA: 0x75941b3a38
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1b9bb98 VA: 0x75941b3b98
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1b9bf3c VA: 0x75941b3f3c
	protected virtual Void DoFindTargetsInHostOrTokenRange() { }
	// RVA: 0x1b9c62c VA: 0x75941b462c
	public Void .ctor() { }
	// RVA: 0x1b9c724 VA: 0x75941b4724
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1b9c728 VA: 0x75941b4728
	private ReusableList`1 <>xLuaBaseProxy_DoFindTargets_DISPOSE(Vector2 P0) { }
}
```