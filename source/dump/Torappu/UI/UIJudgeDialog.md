# UIJudgeDialog

**Namespace:** `Torappu.UI`


## Fields

- `Text _descText`

- `UITextIconContent _positiveText`

- `UITextIconContent _negativeText`

- `Button _btnNegative`

- `GameObject _panelRedBtn`

- `GameObject _panelBlueBtn`

- `GameObject _panelCheckbox`

- `Text _textCheckbox`

- `TwoStateToggle _toggleCheckbox`

- `Options m_options`

- `JudgeResult m_judgeResult`

- `CheckboxController m_checkboxImpl`


## Properties

- `CheckboxController checkbox`

- `Options options`


## Methods

- `CheckboxController get_checkbox()`

- `Void set_options(Options)`

- `Void _Render()`

- `Void ClearOption()`

- `Void EventOnPositive()`

- `Void EventOnNegative()`

- `Void EventOnCheckboxClicked()`

- `Void _RenderStyle(StyleMask)`

- `Void _OverrideLineSpacing(Nullable`1)`

- `Void _OnBackPressed()`

- `Void <>xLuaBaseProxy_Start()`

- `Void <>xLuaBaseProxy_OnDismiss()`

- `Void <>xLuaBaseProxy_OnShow()`

- `String <>xLuaBaseProxy_get_message()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIJudgeDialog : CommonDialog
{
	private Text _descText; // 0x30
	private UITextIconContent _positiveText; // 0x38
	private UITextIconContent _negativeText; // 0x40
	private Button _btnNegative; // 0x48
	private GameObject _panelRedBtn; // 0x50
	private GameObject _panelBlueBtn; // 0x58
	private GameObject _panelCheckbox; // 0x60
	private Text _textCheckbox; // 0x68
	private TwoStateToggle _toggleCheckbox; // 0x70
	private Options m_options; // 0x78
	private Nullable`1 m_cachedLineSpacing; // 0xf8
	private JudgeResult m_judgeResult; // 0x100
	private CheckboxController m_checkboxImpl; // 0x108
	private static DelegateBridge __Hotfix0_get_checkbox; // 0x0
	private static DelegateBridge __Hotfix0_set_options; // 0x8
	private static DelegateBridge __Hotfix0_Start; // 0x10
	private static DelegateBridge __Hotfix0__Render; // 0x18
	private static DelegateBridge __Hotfix0_OnDismiss; // 0x20
	private static DelegateBridge __Hotfix0_OnShow; // 0x28
	private static DelegateBridge __Hotfix0_OnDialogDeduplicated; // 0x30
	private static DelegateBridge __Hotfix0_get_message; // 0x38
	private static DelegateBridge __Hotfix0_ClearOption; // 0x40
	private static DelegateBridge __Hotfix0_EventOnPositive; // 0x48
	private static DelegateBridge __Hotfix0_EventOnNegative; // 0x50
	private static DelegateBridge __Hotfix0_EventOnCheckboxClicked; // 0x58
	private static DelegateBridge __Hotfix0__RenderStyle; // 0x60
	private static DelegateBridge __Hotfix0__OverrideLineSpacing; // 0x68
	private static DelegateBridge __Hotfix0__OnBackPressed; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	protected CheckboxController checkbox { get; }
	public Options options { set; }
	public override String message { get; }

	// RVA: 0x22155a8 VA: 0x759482d5a8
	protected CheckboxController get_checkbox() { }
	// RVA: 0x22156c0 VA: 0x759482d6c0
	public Void set_options(Options value) { }
	// RVA: 0x22158a8 VA: 0x759482d8a8
	protected override Void Start() { }
	// RVA: 0x221577c VA: 0x759482d77c
	private Void _Render() { }
	// RVA: 0x2215b64 VA: 0x759482db64
	protected override Void OnDismiss() { }
	// RVA: 0x2215cd8 VA: 0x759482dcd8
	protected override Void OnShow() { }
	// RVA: 0x2215dd4 VA: 0x759482ddd4
	protected override Void OnDialogDeduplicated() { }
	// RVA: 0x2215e3c VA: 0x759482de3c
	public override String get_message() { }
	// RVA: 0x2215c64 VA: 0x759482dc64
	public Void ClearOption() { }
	// RVA: 0x2215ea8 VA: 0x759482dea8
	public Void EventOnPositive() { }
	// RVA: 0x2215f34 VA: 0x759482df34
	public Void EventOnNegative() { }
	// RVA: 0x2215fc0 VA: 0x759482dfc0
	public Void EventOnCheckboxClicked() { }
	// RVA: 0x2215acc VA: 0x759482dacc
	private Void _RenderStyle(StyleMask styleMask) { }
	// RVA: 0x22159b0 VA: 0x759482d9b0
	private Void _OverrideLineSpacing(Nullable`1 value) { }
	// RVA: 0x2216050 VA: 0x759482e050
	private Void _OnBackPressed() { }
	// RVA: 0x22160d0 VA: 0x759482e0d0
	public Void .ctor() { }
	// RVA: 0x221613c VA: 0x759482e13c
	private Void <>xLuaBaseProxy_Start() { }
	// RVA: 0x2216140 VA: 0x759482e140
	private Void <>xLuaBaseProxy_OnDismiss() { }
	// RVA: 0x2216144 VA: 0x759482e144
	private Void <>xLuaBaseProxy_OnShow() { }
	// RVA: 0x2216148 VA: 0x759482e148
	private String <>xLuaBaseProxy_get_message() { }
}
```