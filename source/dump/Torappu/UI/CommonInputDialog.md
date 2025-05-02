# CommonInputDialog

**Namespace:** `Torappu.UI`


## Fields

- `InputField _inputName`

- `Text _placeHolder`

- `GameObject _confirmBtnBlue`

- `GameObject _confirmBtnRed`

- `RectTransform _backRt`

- `UIRenderTextureImage _blurBkg`

- `Boolean m_isInited`

- `ICommonInputDialogConfirmConfig m_confirmConfig`

- `Action m_onSuccess`

- `String m_emptyToast`

- `ValueBundle m_param`

- `Int32 m_inputLimitCount`

- `Boolean m_checkCrossDay`

- `StringBuilder m_sharedBuilder`


## Methods

- `Void _InitIfNot()`

- `Void _OnInputFieldValueChange(String)`

- `Void _OnInputFieldEndEdit(String)`

- `String _BlockLength(String)`

- `Void ClosePanel()`

- `Void OnSubmitInputClicked()`

- `Void <OnSubmitInputClicked>b__22_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CommonInputDialog : UICustomDialog`1
{
	private InputField _inputName; // 0x90
	private Text _placeHolder; // 0x98
	private GameObject _confirmBtnBlue; // 0xa0
	private GameObject _confirmBtnRed; // 0xa8
	private RectTransform _backRt; // 0xb0
	private UIRenderTextureImage _blurBkg; // 0xb8
	private Boolean m_isInited; // 0xc0
	private ICommonInputDialogConfirmConfig m_confirmConfig; // 0xc8
	private Action m_onSuccess; // 0xd0
	private String m_emptyToast; // 0xd8
	private ValueBundle m_param; // 0xe0
	private Int32 m_inputLimitCount; // 0x100
	private Boolean m_checkCrossDay; // 0x104
	private StringBuilder m_sharedBuilder; // 0x108
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0__OnInputFieldValueChange; // 0x10
	private static DelegateBridge __Hotfix0__OnInputFieldEndEdit; // 0x18
	private static DelegateBridge __Hotfix0__BlockLength; // 0x20
	private static DelegateBridge __Hotfix0__CalcCharCount; // 0x28
	private static DelegateBridge __Hotfix0_ClosePanel; // 0x30
	private static DelegateBridge __Hotfix0_OnSubmitInputClicked; // 0x38
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x21394b0 VA: 0x75947514b0
	private Void _InitIfNot() { }
	// RVA: 0x2139690 VA: 0x7594751690
	protected override Void OnRender(Options options) { }
	// RVA: 0x2139858 VA: 0x7594751858
	private Void _OnInputFieldValueChange(String input) { }
	// RVA: 0x2139b40 VA: 0x7594751b40
	private Void _OnInputFieldEndEdit(String input) { }
	// RVA: 0x2139990 VA: 0x7594751990
	private String _BlockLength(String input) { }
	// RVA: 0x2139c78 VA: 0x7594751c78
	private static Int32 _CalcCharCount(Char c) { }
	// RVA: 0x2139d24 VA: 0x7594751d24
	public Void ClosePanel() { }
	// RVA: 0x2139dd8 VA: 0x7594751dd8
	public Void OnSubmitInputClicked() { }
	// RVA: 0x2139ff4 VA: 0x7594751ff4
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x213a05c VA: 0x759475205c
	public Void .ctor() { }
	// RVA: 0x213a12c VA: 0x759475212c
	private Void <OnSubmitInputClicked>b__22_0() { }
}
```