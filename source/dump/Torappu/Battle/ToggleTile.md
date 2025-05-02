# ToggleTile

**Namespace:** `Torappu.Battle`


## Fields

- `Options _toggleOptions`


## Methods

- `Int32 <>xLuaBaseProxy_get_maxTriggerCnt()`

- `Void <>xLuaBaseProxy_OnTrigger()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ToggleTile : InteractableTile
{
	private Options _toggleOptions; // 0x110
	private static DelegateBridge __Hotfix0_get_maxTriggerCnt; // 0x0
	private static DelegateBridge __Hotfix0_OnTrigger; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	protected override Int32 maxTriggerCnt { get; }

	// RVA: 0x4099a30 VA: 0x75966b1a30
	protected override Int32 get_maxTriggerCnt() { }
	// RVA: 0x4099a98 VA: 0x75966b1a98
	protected override Void OnTrigger() { }
	// RVA: 0x4099b34 VA: 0x75966b1b34
	public Void .ctor() { }
	// RVA: 0x4099ba0 VA: 0x75966b1ba0
	private Int32 <>xLuaBaseProxy_get_maxTriggerCnt() { }
	// RVA: 0x4099ba4 VA: 0x75966b1ba4
	private Void <>xLuaBaseProxy_OnTrigger() { }
}
```