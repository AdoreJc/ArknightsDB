# SandboxHudPluginTalent

**Namespace:** `Torappu.Battle`


## Methods

- `Void _OnHudCreated(Object)`

- `Void <>xLuaBaseProxy_DoAttach()`

- `Void <>xLuaBaseProxy_DoDetach()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SandboxHudPluginTalent : UIPluginTalent
{
	private static DelegateBridge __Hotfix0_get_type; // 0x0
	private static DelegateBridge __Hotfix0_LoadPlugin; // 0x8
	private static DelegateBridge __Hotfix0_DoAttach; // 0x10
	private static DelegateBridge __Hotfix0_DoDetach; // 0x18
	private static DelegateBridge __Hotfix0__OnHudCreated; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override PluginType type { get; }

	// RVA: 0x1b884a4 VA: 0x75941a04a4
	public override PluginType get_type() { }
	// RVA: 0x1b88508 VA: 0x75941a0508
	protected override UnitTalentUIPlugin LoadPlugin(String pluginName) { }
	// RVA: 0x1b88604 VA: 0x75941a0604
	protected override Void DoAttach() { }
	// RVA: 0x1b88704 VA: 0x75941a0704
	protected override Void DoDetach() { }
	// RVA: 0x1b8881c VA: 0x75941a081c
	private Void _OnHudCreated(Object arg) { }
	// RVA: 0x1b888b8 VA: 0x75941a08b8
	public Void .ctor() { }
	// RVA: 0x1b88924 VA: 0x75941a0924
	private Void <>xLuaBaseProxy_DoAttach() { }
	// RVA: 0x1b88928 VA: 0x75941a0928
	private Void <>xLuaBaseProxy_DoDetach() { }
}
```