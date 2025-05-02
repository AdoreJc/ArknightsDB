# BuffTemplateDBData

**Namespace:** `Torappu`


## Fields

- `String templateKey`

- `String effectKey`

- `OnEventPriority onEventPriority`


## Methods

- `String <>xLuaBaseProxy_ToString()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class BuffTemplateDBData : IHotfixable
{
	public String templateKey; // 0x10
	public String effectKey; // 0x18
	public OnEventPriority onEventPriority; // 0x20
	public Dictionary`2 eventToActions; // 0x28
	private static DelegateBridge __Hotfix0_ToString; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x33c6680 VA: 0x75959de680
	public override String ToString() { }
	// RVA: 0x33c66e8 VA: 0x75959de6e8
	public Void .ctor() { }
	// RVA: 0x33c6790 VA: 0x75959de790
	private String <>xLuaBaseProxy_ToString() { }
}
```