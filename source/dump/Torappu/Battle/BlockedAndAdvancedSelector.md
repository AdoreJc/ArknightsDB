# BlockedAndAdvancedSelector

**Namespace:** `Torappu.Battle`


## Fields

- `Character <character>k__BackingField`


## Properties

- `Character character`


## Methods

- `Character get_character()`

- `Void set_character(Character)`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`

- `Boolean <>xLuaBaseProxy_ValidateTarget(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BlockedAndAdvancedSelector : BlockedBaseSelector
{
	protected List`1 m_tmpList; // 0xe8
	private Character <character>k__BackingField; // 0xf0
	private static DelegateBridge __Hotfix0_get_character; // 0x0
	private static DelegateBridge __Hotfix0_set_character; // 0x8
	private static DelegateBridge __Hotfix0_Reset; // 0x10
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x18
	private static DelegateBridge __Hotfix0_ValidateTarget; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected Character character { get; set; }

	// RVA: 0x1ba268c VA: 0x75941ba68c
	protected Character get_character() { }
	// RVA: 0x1ba26f4 VA: 0x75941ba6f4
	private Void set_character(Character value) { }
	// RVA: 0x1ba2778 VA: 0x75941ba778
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1ba2874 VA: 0x75941ba874
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1ba2ea0 VA: 0x75941baea0
	protected override Boolean ValidateTarget(Entity target) { }
	// RVA: 0x1ba3004 VA: 0x75941bb004
	public Void .ctor() { }
	// RVA: 0x1ba3070 VA: 0x75941bb070
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1ba3078 VA: 0x75941bb078
	private ReusableList`1 <>xLuaBaseProxy_DoFindTargets_DISPOSE(Vector2 P0) { }
	// RVA: 0x1ba3080 VA: 0x75941bb080
	private Boolean <>xLuaBaseProxy_ValidateTarget(Entity P0) { }
}
```