# MhWeaknessHudPluginTalent

**Namespace:** `Torappu.Battle`


## Fields

- `FacePosition _weakness`

- `Boolean <takenDamage>k__BackingField`


## Properties

- `Boolean takenDamage`

- `Int32 weaknessSign`


## Methods

- `Boolean get_takenDamage()`

- `Void set_takenDamage(Boolean)`

- `Int32 get_weaknessSign()`

- `Void _OnHudCreated(Object)`

- `Void _OnApplyedModifier(Object)`

- `Boolean _CheckDirection(Vector2)`

- `Boolean _CheckOwnerValidMode()`

- `Void <>xLuaBaseProxy_DoAttach()`

- `Void <>xLuaBaseProxy_DoDetach()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class MhWeaknessHudPluginTalent : UIPluginTalent
{
	private Int32[] _validModeIndices; // 0x60
	private FacePosition _weakness; // 0x68
	private Boolean <takenDamage>k__BackingField; // 0x6c
	private static DelegateBridge __Hotfix0_get_takenDamage; // 0x0
	private static DelegateBridge __Hotfix0_set_takenDamage; // 0x8
	private static DelegateBridge __Hotfix0_get_type; // 0x10
	private static DelegateBridge __Hotfix0_get_validModeIndices; // 0x18
	private static DelegateBridge __Hotfix0_get_weaknessSign; // 0x20
	private static DelegateBridge __Hotfix0_LoadPlugin; // 0x28
	private static DelegateBridge __Hotfix0_DoAttach; // 0x30
	private static DelegateBridge __Hotfix0_DoDetach; // 0x38
	private static DelegateBridge __Hotfix0__OnHudCreated; // 0x40
	private static DelegateBridge __Hotfix0__OnApplyedModifier; // 0x48
	private static DelegateBridge __Hotfix0__CheckDirection; // 0x50
	private static DelegateBridge __Hotfix0__CheckOwnerValidMode; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public Boolean takenDamage { get; set; }
	public override PluginType type { get; }
	public Int32[] validModeIndices { get; }
	public Int32 weaknessSign { get; }

	// RVA: 0x1b878b0 VA: 0x759419f8b0
	public Boolean get_takenDamage() { }
	// RVA: 0x1b87918 VA: 0x759419f918
	public Void set_takenDamage(Boolean value) { }
	// RVA: 0x1b87998 VA: 0x759419f998
	public override PluginType get_type() { }
	// RVA: 0x1b879fc VA: 0x759419f9fc
	public Int32[] get_validModeIndices() { }
	// RVA: 0x1b87a64 VA: 0x759419fa64
	public Int32 get_weaknessSign() { }
	// RVA: 0x1b87acc VA: 0x759419facc
	protected override UnitTalentUIPlugin LoadPlugin(String pluginName) { }
	// RVA: 0x1b87be8 VA: 0x759419fbe8
	protected override Void DoAttach() { }
	// RVA: 0x1b87d6c VA: 0x759419fd6c
	protected override Void DoDetach() { }
	// RVA: 0x1b87efc VA: 0x759419fefc
	private Void _OnHudCreated(Object arg) { }
	// RVA: 0x1b87f98 VA: 0x759419ff98
	private Void _OnApplyedModifier(Object arg) { }
	// RVA: 0x1b88310 VA: 0x75941a0310
	private Boolean _CheckDirection(Vector2 mapDir) { }
	// RVA: 0x1b8822c VA: 0x75941a022c
	private Boolean _CheckOwnerValidMode() { }
	// RVA: 0x1b88424 VA: 0x75941a0424
	public Void .ctor() { }
	// RVA: 0x1b88498 VA: 0x75941a0498
	private Void <>xLuaBaseProxy_DoAttach() { }
	// RVA: 0x1b8849c VA: 0x75941a049c
	private Void <>xLuaBaseProxy_DoDetach() { }
}
```