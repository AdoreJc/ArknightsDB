# UIItemDescDialog

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform _floatHolder`

- `RectTransform _descBound`

- `CanvasGroup _alphaHandler`

- `UIItemDescViewModel m_viewModel`

- `UIItemDescFloat m_floatInst`

- `DefaultDialogSwitchTween m_switchTween`


## Methods

- `Void _InitIfNot()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnCloseFloatPanel(ClosePanelRequest)`

- `Void _OnFloatRouteToItemDropInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIItemDescDialog : UICustomDialog`1, IValueMsgReceiver
{
	public const Int32 MSG_CLOSE; // 0x0
	private RectTransform _floatHolder; // 0x50
	private RectTransform _descBound; // 0x58
	private CanvasGroup _alphaHandler; // 0x60
	private UIItemDescViewModel m_viewModel; // 0x68
	private UIItemDescFloat m_floatInst; // 0x70
	private DefaultDialogSwitchTween m_switchTween; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GenerateShowTween; // 0x8
	private static DelegateBridge __Hotfix0_OnRender; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0__OnCloseFloatPanel; // 0x20
	private static DelegateBridge __Hotfix0__OnFloatRouteToItemDropInfo; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x218c090 VA: 0x75947a4090
	private Void _InitIfNot() { }
	// RVA: 0x218c450 VA: 0x75947a4450
	protected override UISwitchTween GenerateShowTween() { }
	// RVA: 0x218c614 VA: 0x75947a4614
	protected override Void OnRender(Options options) { }
	// RVA: 0x218c8d0 VA: 0x75947a48d0
	public Void OnMessage(Int32 msg, ValueBundle param) { }
	// RVA: 0x218c994 VA: 0x75947a4994
	private Void _OnCloseFloatPanel(ClosePanelRequest request) { }
	// RVA: 0x218ca60 VA: 0x75947a4a60
	private Void _OnFloatRouteToItemDropInfo() { }
	// RVA: 0x218cae4 VA: 0x75947a4ae4
	public Void .ctor() { }
}
```