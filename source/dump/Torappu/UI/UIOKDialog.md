# UIOKDialog

**Namespace:** `Torappu.UI`


## Fields

- `UITextIconContent _btnConfirm`

- `Text _descText`

- `RectTransform _textContainer`

- `RectTransform _customContainer`

- `ScrollRect _contentScroll`

- `ScrollRect _textScroll`

- `Button _confirmButton`

- `Options m_options`


## Properties

- `Options options`


## Methods

- `Void set_options(Options)`

- `Void OnEnable()`

- `Void _Render()`

- `Void EventOnBackgroundClick()`

- `Void EventOnConfrimBtnClick()`

- `IEnumerator _ResetTextScroll()`

- `Void <>xLuaBaseProxy_Start()`

- `Void <>xLuaBaseProxy_OnDismiss()`

- `Void <>xLuaBaseProxy_OnShow()`

- `String <>xLuaBaseProxy_get_message()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIOKDialog : CommonDialog
{
	private UITextIconContent _btnConfirm; // 0x30
	private Text _descText; // 0x38
	private RectTransform _textContainer; // 0x40
	private RectTransform _customContainer; // 0x48
	private ScrollRect _contentScroll; // 0x50
	private ScrollRect _textScroll; // 0x58
	private Button _confirmButton; // 0x60
	private Options m_options; // 0x68
	private static DelegateBridge __Hotfix0_set_options; // 0x0
	private static DelegateBridge __Hotfix0_Start; // 0x8
	private static DelegateBridge __Hotfix0_OnEnable; // 0x10
	private static DelegateBridge __Hotfix0__Render; // 0x18
	private static DelegateBridge __Hotfix0_OnDismiss; // 0x20
	private static DelegateBridge __Hotfix0_OnShow; // 0x28
	private static DelegateBridge __Hotfix0_OnDialogDeduplicated; // 0x30
	private static DelegateBridge __Hotfix0_get_message; // 0x38
	private static DelegateBridge __Hotfix0_EventOnBackgroundClick; // 0x40
	private static DelegateBridge __Hotfix0_EventOnConfrimBtnClick; // 0x48
	private static DelegateBridge __Hotfix0__ResetTextScroll; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Options options { set; }
	public override String message { get; }

	// RVA: 0x22176a4 VA: 0x759482f6a4
	public Void set_options(Options value) { }
	// RVA: 0x2217968 VA: 0x759482f968
	protected override Void Start() { }
	// RVA: 0x2217a74 VA: 0x759482fa74
	private Void OnEnable() { }
	// RVA: 0x2217764 VA: 0x759482f764
	private Void _Render() { }
	// RVA: 0x2217b98 VA: 0x759482fb98
	protected override Void OnDismiss() { }
	// RVA: 0x2217c34 VA: 0x759482fc34
	protected override Void OnShow() { }
	// RVA: 0x2217d34 VA: 0x759482fd34
	protected override Void OnDialogDeduplicated() { }
	// RVA: 0x2217dac VA: 0x759482fdac
	public override String get_message() { }
	// RVA: 0x2217e14 VA: 0x759482fe14
	public Void EventOnBackgroundClick() { }
	// RVA: 0x2217e84 VA: 0x759482fe84
	public Void EventOnConfrimBtnClick() { }
	// RVA: 0x2217aec VA: 0x759482faec
	private IEnumerator _ResetTextScroll() { }
	// RVA: 0x2217f1c VA: 0x759482ff1c
	public Void .ctor() { }
	// RVA: 0x2217f8c VA: 0x759482ff8c
	private Void <>xLuaBaseProxy_Start() { }
	// RVA: 0x2217f94 VA: 0x759482ff94
	private Void <>xLuaBaseProxy_OnDismiss() { }
	// RVA: 0x2217f9c VA: 0x759482ff9c
	private Void <>xLuaBaseProxy_OnShow() { }
	// RVA: 0x2217fa4 VA: 0x759482ffa4
	private String <>xLuaBaseProxy_get_message() { }
}
```