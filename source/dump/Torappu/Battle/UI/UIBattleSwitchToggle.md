# UIBattleSwitchToggle

**Namespace:** `Torappu.Battle.UI`


## Methods

- `Boolean _IsFunctionDisabled()`

- `Boolean <>xLuaBaseProxy_get_isOn()`

- `Void <>xLuaBaseProxy_set_isOn(Boolean)`

- `Boolean <>xLuaBaseProxy_get_interactable()`

- `Void <>xLuaBaseProxy_SetInteractable(Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIBattleSwitchToggle : UISwitchToggle, IHotfixable
{
	private static DelegateBridge __Hotfix0_get_isOn; // 0x0
	private static DelegateBridge __Hotfix0_set_isOn; // 0x8
	private static DelegateBridge __Hotfix0_get_interactable; // 0x10
	private static DelegateBridge __Hotfix0_SetInteractable; // 0x18
	private static DelegateBridge __Hotfix0__IsFunctionDisabled; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override Boolean isOn { get; set; }
	public override Boolean interactable { get; }

	// RVA: 0x207bb20 VA: 0x7594693b20
	public override Boolean get_isOn() { }
	// RVA: 0x207bb9c VA: 0x7594693b9c
	public override Void set_isOn(Boolean value) { }
	// RVA: 0x207bc70 VA: 0x7594693c70
	public override Boolean get_interactable() { }
	// RVA: 0x207bda4 VA: 0x7594693da4
	public override Void SetInteractable(Boolean val, Boolean force) { }
	// RVA: 0x207bd08 VA: 0x7594693d08
	private Boolean _IsFunctionDisabled() { }
	// RVA: 0x207be54 VA: 0x7594693e54
	public Void .ctor() { }
	// RVA: 0x207bec4 VA: 0x7594693ec4
	private Boolean <>xLuaBaseProxy_get_isOn() { }
	// RVA: 0x207becc VA: 0x7594693ecc
	private Void <>xLuaBaseProxy_set_isOn(Boolean P0) { }
	// RVA: 0x207bed8 VA: 0x7594693ed8
	private Boolean <>xLuaBaseProxy_get_interactable() { }
	// RVA: 0x207bee0 VA: 0x7594693ee0
	private Void <>xLuaBaseProxy_SetInteractable(Boolean P0, Boolean P1) { }
}
```