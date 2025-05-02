# InstantActionToOwnerAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `ActionArray _actions`


## Methods

- `Category <>xLuaBaseProxy_get_category()`

- `SelectTargetSource <>xLuaBaseProxy_get_selectTargetSource()`

- `Boolean <>xLuaBaseProxy_get_alwaysIncludeTarget()`

- `Boolean <>xLuaBaseProxy_get_allowNoTarget()`

- `Void <>xLuaBaseProxy_GatherActionNodes(List`1)`

- `Boolean <>xLuaBaseProxy_OnSpellStart()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class InstantActionToOwnerAbility : EmptyAbility, IActionNodeSource
{
	private ActionArray _actions; // 0x108
	private static DelegateBridge __Hotfix0_get_category; // 0x0
	private static DelegateBridge __Hotfix0_get_selectTargetSource; // 0x8
	private static DelegateBridge __Hotfix0_get_alwaysIncludeTarget; // 0x10
	private static DelegateBridge __Hotfix0_get_allowNoTarget; // 0x18
	private static DelegateBridge __Hotfix0_GatherActionNodes; // 0x20
	private static DelegateBridge __Hotfix0_OnSpellStart; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override Category category { get; }
	public override SelectTargetSource selectTargetSource { get; }
	protected override Boolean alwaysIncludeTarget { get; }
	public override Boolean allowNoTarget { get; }

	// RVA: 0x1e02804 VA: 0x759441a804
	public override Category get_category() { }
	// RVA: 0x1e0286c VA: 0x759441a86c
	public override SelectTargetSource get_selectTargetSource() { }
	// RVA: 0x1e028d4 VA: 0x759441a8d4
	protected override Boolean get_alwaysIncludeTarget() { }
	// RVA: 0x1e02938 VA: 0x759441a938
	public override Boolean get_allowNoTarget() { }
	// RVA: 0x1e029a0 VA: 0x759441a9a0
	public override Void GatherActionNodes(List`1 results) { }
	// RVA: 0x1e02a44 VA: 0x759441aa44
	protected override Boolean OnSpellStart() { }
	// RVA: 0x1e02d14 VA: 0x759441ad14
	public Void .ctor() { }
	// RVA: 0x1e02dc4 VA: 0x759441adc4
	private Category <>xLuaBaseProxy_get_category() { }
	// RVA: 0x1e02dcc VA: 0x759441adcc
	private SelectTargetSource <>xLuaBaseProxy_get_selectTargetSource() { }
	// RVA: 0x1e02dd4 VA: 0x759441add4
	private Boolean <>xLuaBaseProxy_get_alwaysIncludeTarget() { }
	// RVA: 0x1e02ddc VA: 0x759441addc
	private Boolean <>xLuaBaseProxy_get_allowNoTarget() { }
	// RVA: 0x1e02de4 VA: 0x759441ade4
	private Void <>xLuaBaseProxy_GatherActionNodes(List`1 P0) { }
	// RVA: 0x1e02dec VA: 0x759441adec
	private Boolean <>xLuaBaseProxy_OnSpellStart() { }
}
```