# HomeMainWidgetHolderBase

**Namespace:** `Torappu.UI.Home`


## Fields

- `WidgetType _defaultWidget`

- `WidgetType m_currWidget`


## Properties

- `WidgetType currWidget`


## Methods

- `Void ChangeWidget(WidgetType)`

- `WidgetType get_currWidget()`

- `Void _CheckIfDefault()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMainWidgetHolderBase`1 : HomeMainWidgetHolder
{
	private WidgetType _defaultWidget; // 0x0
	private WidgetType m_currWidget; // 0x0
	private static DelegateBridge __Hotfix0_ChangeWidget; // 0x0
	private static DelegateBridge __Hotfix1_ChangeWidget; // 0x0
	private static DelegateBridge __Hotfix0_get_currWidget; // 0x0
	private static DelegateBridge __Hotfix0__CheckIfDefault; // 0x0
	private static DelegateBridge __Hotfix0_OnWidgetChanged; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0

	public WidgetType currWidget { get; }

	// RVA: 0x VA: 0x0
	public override Void ChangeWidget(GameObject widgetGO) { }
	// RVA: 0x VA: 0x0
	public Void ChangeWidget(WidgetType widget) { }
	// RVA: 0x VA: 0x0
	public WidgetType get_currWidget() { }
	// RVA: 0x VA: 0x0
	private Void _CheckIfDefault() { }
	// RVA: 0x VA: 0x0
	protected virtual Void OnWidgetChanged(WidgetType newWidget) { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```