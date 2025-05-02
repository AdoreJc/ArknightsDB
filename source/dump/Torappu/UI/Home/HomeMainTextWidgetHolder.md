# HomeMainTextWidgetHolder

**Namespace:** `Torappu.UI.Home`


## Fields

- `String m_cachedText`


## Properties

- `String text`


## Methods

- `String get_text()`

- `Void set_text(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMainTextWidgetHolder : HomeMainWidgetHolderBase`1
{
	private String m_cachedText; // 0x28
	private static DelegateBridge __Hotfix0_get_text; // 0x0
	private static DelegateBridge __Hotfix0_set_text; // 0x8
	private static DelegateBridge __Hotfix0_OnWidgetChanged; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public String text { get; set; }

	// RVA: 0x2849690 VA: 0x7594e61690
	public String get_text() { }
	// RVA: 0x28496f8 VA: 0x7594e616f8
	public Void set_text(String value) { }
	// RVA: 0x2849808 VA: 0x7594e61808
	protected override Void OnWidgetChanged(HomeMainTextWidget newWidget) { }
	// RVA: 0x28498d4 VA: 0x7594e618d4
	public Void .ctor() { }
}
```