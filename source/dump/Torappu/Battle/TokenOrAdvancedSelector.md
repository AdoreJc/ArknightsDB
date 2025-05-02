# TokenOrAdvancedSelector

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _includeOwner`

- `Character <character>k__BackingField`


## Properties

- `Character character`


## Methods

- `Character get_character()`

- `Void set_character(Character)`

- `Boolean <DoFindTargets_DISPOSE>b__6_0(Entity)`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`

- `Boolean <>xLuaBaseProxy_CheckTargetIn(ILocatable)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class TokenOrAdvancedSelector : AdvancedSelector
{
	private Boolean _includeOwner; // 0xe8
	private Character <character>k__BackingField; // 0xf0
	private static DelegateBridge __Hotfix0_get_character; // 0x0
	private static DelegateBridge __Hotfix0_set_character; // 0x8
	private static DelegateBridge __Hotfix0_Reset; // 0x10
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x18
	private static DelegateBridge __Hotfix0_CheckTargetIn; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected Character character { get; set; }

	// RVA: 0x1bd2bb4 VA: 0x75941eabb4
	protected Character get_character() { }
	// RVA: 0x1bd2c1c VA: 0x75941eac1c
	private Void set_character(Character value) { }
	// RVA: 0x1bd2ca0 VA: 0x75941eaca0
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1bd2d9c VA: 0x75941ead9c
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1bd3574 VA: 0x75941eb574
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1bd3670 VA: 0x75941eb670
	public Void .ctor() { }
	// RVA: 0x1bd36e0 VA: 0x75941eb6e0
	private Boolean <DoFindTargets_DISPOSE>b__6_0(Entity candidate) { }
	// RVA: 0x1bd3700 VA: 0x75941eb700
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1bd3708 VA: 0x75941eb708
	private ReusableList`1 <>xLuaBaseProxy_DoFindTargets_DISPOSE(Vector2 P0) { }
	// RVA: 0x1bd3710 VA: 0x75941eb710
	private Boolean <>xLuaBaseProxy_CheckTargetIn(ILocatable P0) { }
}
```