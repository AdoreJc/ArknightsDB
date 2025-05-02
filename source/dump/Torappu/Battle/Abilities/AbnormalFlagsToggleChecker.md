# AbnormalFlagsToggleChecker

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _disableWhenAbnormalFlag`


## Methods

- `Void _OnAbnormalFlagDirty(Object)`

- `Void _OnAbnormalComboDirty(AbnormalCombo)`

- `Boolean _CheckToggled()`

- `Void <>xLuaBaseProxy_OnAttached()`

- `Void <>xLuaBaseProxy_OnDetached()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AbnormalFlagsToggleChecker : Checker
{
	private List`1 _abnormalFlags; // 0x20
	private List`1 _abnormalCombos; // 0x28
	private Boolean _disableWhenAbnormalFlag; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_OnAttached; // 0x8
	private static DelegateBridge __Hotfix0_OnDetached; // 0x10
	private static DelegateBridge __Hotfix0_CheckInitialToggled; // 0x18
	private static DelegateBridge __Hotfix0__OnAbnormalFlagDirty; // 0x20
	private static DelegateBridge __Hotfix0__OnAbnormalComboDirty; // 0x28
	private static DelegateBridge __Hotfix0__CheckToggled; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x1e55a08 VA: 0x759446da08
	protected override Void LoadData(Blackboard blackboard) { }
	// RVA: 0x1e55a80 VA: 0x759446da80
	public override Void OnAttached() { }
	// RVA: 0x1e55dc8 VA: 0x759446ddc8
	public override Void OnDetached() { }
	// RVA: 0x1e55fe8 VA: 0x759446dfe8
	public override Boolean CheckInitialToggled() { }
	// RVA: 0x1e56240 VA: 0x759446e240
	private Void _OnAbnormalFlagDirty(Object arg) { }
	// RVA: 0x1e56388 VA: 0x759446e388
	private Void _OnAbnormalComboDirty(AbnormalCombo combo) { }
	// RVA: 0x1e56050 VA: 0x759446e050
	private Boolean _CheckToggled() { }
	// RVA: 0x1e56444 VA: 0x759446e444
	public Void .ctor() { }
	// RVA: 0x1e56520 VA: 0x759446e520
	private Void <>xLuaBaseProxy_OnAttached() { }
	// RVA: 0x1e56588 VA: 0x759446e588
	private Void <>xLuaBaseProxy_OnDetached() { }
}
```