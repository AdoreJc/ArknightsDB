# ClickGuardModule

**Namespace:** ` `


## Fields

- `ClickGuardEnum guardMask`

- `Boolean cooldown`

- `Single seconds`

- `Double m_lastClickTs`


## Properties

- `Boolean enableClickGuard`


## Methods

- `Boolean get_enableClickGuard()`

- `Void set_enableClickGuard(Boolean)`

- `Void set_selfDefineClickCheck(Func`1)`

- `Boolean IsInCooldown()`

- `Void ConfirmClick()`

- `Boolean CheckSelfDefineFuncClick()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
private class ClickGuardModule
{
	public ClickGuardEnum guardMask; // 0x10
	public Boolean cooldown; // 0x14
	public Single seconds; // 0x18
	private Double m_lastClickTs; // 0x20
	private Func`1 <selfDefineClickCheck>k__BackingField; // 0x28

	public Boolean enableClickGuard { get; set; }
	private Func`1 selfDefineClickCheck { get; set; }

	// RVA: 0x677da64 VA: 0x7598d95a64
	public Boolean get_enableClickGuard() { }
	// RVA: 0x677da74 VA: 0x7598d95a74
	public Void set_enableClickGuard(Boolean value) { }
	// RVA: 0x677da98 VA: 0x7598d95a98
	private Func`1 get_selfDefineClickCheck() { }
	// RVA: 0x677daa0 VA: 0x7598d95aa0
	public Void set_selfDefineClickCheck(Func`1 value) { }
	// RVA: 0x677bc40 VA: 0x7598d93c40
	public Boolean IsInCooldown() { }
	// RVA: 0x677cc28 VA: 0x7598d94c28
	public Void ConfirmClick() { }
	// RVA: 0x677baa4 VA: 0x7598d93aa4
	public Boolean CheckSelfDefineFuncClick() { }
	// RVA: 0x677cf4c VA: 0x7598d94f4c
	public Void .ctor() { }
}
```