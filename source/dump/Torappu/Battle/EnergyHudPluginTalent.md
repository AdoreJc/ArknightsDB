# EnergyHudPluginTalent

**Namespace:** `Torappu.Battle`


## Fields

- `EnergyBuffAbility _energyBuffAbility`


## Properties

- `EnergyBuffAbility energyBuffAbility`


## Methods

- `EnergyBuffAbility get_energyBuffAbility()`

- `Void _OnHudCreated(Object)`

- `Void <>xLuaBaseProxy_DoAttach()`

- `Void <>xLuaBaseProxy_DoDetach()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EnergyHudPluginTalent : UIPluginTalent
{
	private EnergyBuffAbility _energyBuffAbility; // 0x60
	private static DelegateBridge __Hotfix0_get_energyBuffAbility; // 0x0
	private static DelegateBridge __Hotfix0_get_type; // 0x8
	private static DelegateBridge __Hotfix0_DoAttach; // 0x10
	private static DelegateBridge __Hotfix0_DoDetach; // 0x18
	private static DelegateBridge __Hotfix0__OnHudCreated; // 0x20
	private static DelegateBridge __Hotfix0_LoadPlugin; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public EnergyBuffAbility energyBuffAbility { get; }
	public override PluginType type { get; }

	// RVA: 0x1b82e60 VA: 0x759419ae60
	public EnergyBuffAbility get_energyBuffAbility() { }
	// RVA: 0x1b82ec8 VA: 0x759419aec8
	public override PluginType get_type() { }
	// RVA: 0x1b82f2c VA: 0x759419af2c
	protected override Void DoAttach() { }
	// RVA: 0x1b830cc VA: 0x759419b0cc
	protected override Void DoDetach() { }
	// RVA: 0x1b831ec VA: 0x759419b1ec
	private Void _OnHudCreated(Object arg) { }
	// RVA: 0x1b83288 VA: 0x759419b288
	protected override UnitTalentUIPlugin LoadPlugin(String pluginName) { }
	// RVA: 0x1b833a4 VA: 0x759419b3a4
	public Void .ctor() { }
	// RVA: 0x1b83414 VA: 0x759419b414
	private Void <>xLuaBaseProxy_DoAttach() { }
	// RVA: 0x1b8341c VA: 0x759419b41c
	private Void <>xLuaBaseProxy_DoDetach() { }
}
```