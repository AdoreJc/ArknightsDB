# LpeoplFearHudPluginTalent

**Namespace:** `Torappu.Battle`


## Properties

- `FP fearRatio`


## Methods

- `FP get_fearRatio()`

- `Void _OnHudCreated(Object)`

- `Void <>xLuaBaseProxy_DoAttach()`

- `Void <>xLuaBaseProxy_DoDetach()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class LpeoplFearHudPluginTalent : UIPluginTalent
{
	private static DelegateBridge __Hotfix0_get_fearRatio; // 0x0
	private static DelegateBridge __Hotfix0_get_type; // 0x8
	private static DelegateBridge __Hotfix0_DoAttach; // 0x10
	private static DelegateBridge __Hotfix0_DoDetach; // 0x18
	private static DelegateBridge __Hotfix0__OnHudCreated; // 0x20
	private static DelegateBridge __Hotfix0_LoadPlugin; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public FP fearRatio { get; }
	public override PluginType type { get; }

	// RVA: 0x1b86108 VA: 0x759419e108
	public FP get_fearRatio() { }
	// RVA: 0x1b86184 VA: 0x759419e184
	public override PluginType get_type() { }
	// RVA: 0x1b861e8 VA: 0x759419e1e8
	protected override Void DoAttach() { }
	// RVA: 0x1b862e8 VA: 0x759419e2e8
	protected override Void DoDetach() { }
	// RVA: 0x1b86400 VA: 0x759419e400
	private Void _OnHudCreated(Object arg) { }
	// RVA: 0x1b8649c VA: 0x759419e49c
	protected override UnitTalentUIPlugin LoadPlugin(String pluginName) { }
	// RVA: 0x1b865b8 VA: 0x759419e5b8
	public Void .ctor() { }
	// RVA: 0x1b86624 VA: 0x759419e624
	private Void <>xLuaBaseProxy_DoAttach() { }
	// RVA: 0x1b86628 VA: 0x759419e628
	private Void <>xLuaBaseProxy_DoDetach() { }
}
```