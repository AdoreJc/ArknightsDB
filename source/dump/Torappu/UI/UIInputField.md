# UIInputField

**Namespace:** `Torappu.UI`


## Methods

- `Boolean _MayDrag(PointerEventData)`

- `Void <>xLuaBaseProxy_OnPointerDown(PointerEventData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIInputField : InputField, IHotfixable
{
	private static DelegateBridge __Hotfix0_OnPointerDown; // 0x0
	private static DelegateBridge __Hotfix0__MayDrag; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x21ed0b8 VA: 0x75948050b8
	public override Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x21ed2c4 VA: 0x75948052c4
	private Boolean _MayDrag(PointerEventData eventData) { }
	// RVA: 0x21ed3c0 VA: 0x75948053c0
	public Void .ctor() { }
	// RVA: 0x21ed454 VA: 0x7594805454
	private Void <>xLuaBaseProxy_OnPointerDown(PointerEventData P0) { }
}
```