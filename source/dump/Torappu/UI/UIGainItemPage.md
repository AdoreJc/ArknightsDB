# UIGainItemPage

**Namespace:** `Torappu.UI`


## Fields

- `UIGainItemFloatPanel _prefab`

- `RectTransform _itemContainer`

- `UIGainItemFloatPanel m_floatPanel`


## Properties

- `UIGainItemFloatPanel floatPanel`


## Methods

- `UIGainItemFloatPanel get_floatPanel()`

- `Void _HideItemFloat()`

- `Void _OnExit()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(Boolean)`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(Boolean)`

- `Void <>xLuaBaseProxy_OnPageRouted()`

- `Void <>xLuaBaseProxy_OnRecycle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIGainItemPage : UIPage
{
	private UIGainItemFloatPanel _prefab; // 0xd0
	private RectTransform _itemContainer; // 0xd8
	private UIGainItemFloatPanel m_floatPanel; // 0xe0
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x0
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x8
	private static DelegateBridge __Hotfix0_OnPageRouted; // 0x10
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x18
	private static DelegateBridge __Hotfix0_get_floatPanel; // 0x20
	private static DelegateBridge __Hotfix0__HideItemFloat; // 0x28
	private static DelegateBridge __Hotfix0__OnExit; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public UIGainItemFloatPanel floatPanel { get; }

	// RVA: 0x221fc4c VA: 0x7594837c4c
	public override IEnumerator ShowCoroutine(Boolean isFromStack) { }
	// RVA: 0x221fd3c VA: 0x7594837d3c
	protected override IEnumerator HideCoroutine(Boolean isIntoStack) { }
	// RVA: 0x221fe2c VA: 0x7594837e2c
	protected override Void OnPageRouted() { }
	// RVA: 0x221fea0 VA: 0x7594837ea0
	protected override Void OnRecycle() { }
	// RVA: 0x221ffe8 VA: 0x7594837fe8
	public UIGainItemFloatPanel get_floatPanel() { }
	// RVA: 0x2220154 VA: 0x7594838154
	private Void _HideItemFloat() { }
	// RVA: 0x221ff14 VA: 0x7594837f14
	private Void _OnExit() { }
	// RVA: 0x22201c0 VA: 0x75948381c0
	public Void .ctor() { }
	// RVA: 0x2220230 VA: 0x7594838230
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(Boolean P0) { }
	// RVA: 0x222023c VA: 0x759483823c
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(Boolean P0) { }
	// RVA: 0x2220248 VA: 0x7594838248
	private Void <>xLuaBaseProxy_OnPageRouted() { }
	// RVA: 0x2220250 VA: 0x7594838250
	private Void <>xLuaBaseProxy_OnRecycle() { }
}
```