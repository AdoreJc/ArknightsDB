# YostarSDKAgreement

**Namespace:** `YostarSDK.UI.Agreement`


## Fields

- `CanvasGroup _contentPart`

- `RectTransform _agreeItemRoot`

- `YostarSDKAgreementItem _agreeItemPrefab`

- `TwoStateToggle _toggleAgreeAll`

- `Button _btnAgree`

- `Button _btnCancel`

- `Button _btnOK`

- `Button _btnOKCancel`

- `Button _btnOKAgree`

- `Text _textConfirm`

- `Text _textCancel`

- `Text _textOK`

- `Text _textOKCancel`

- `Text _textOKAgree`

- `Text _textAgreeAll`

- `AgreementOptions m_options`

- `AgreementViewModel m_viewModel`

- `UIManager m_uiMgr`

- `FadeSwitchTween m_fadeTween`


## Methods

- `Void _InitFadeTweenIfNot()`

- `Void Start()`

- `Void EventOnAgreeClicked()`

- `Void EventOnOKClicked()`

- `Void EventOnRejectClicked()`

- `Void EventOnSingleToggleClicked()`

- `Void Open(UIManager, AgreementOptions)`

- `IEnumerator Close()`

- `Void _OnItemToggleClicked(Int32)`

- `Void _InitAgreeItems()`

- `Void _InitConstTexts()`

- `Void _UpdateStatus()`

- `Void _OnBusinessFinished()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI.Agreement
public class YostarSDKAgreement : MonoBehaviour, IHotfixable
{
	private CanvasGroup _contentPart; // 0x18
	private RectTransform _agreeItemRoot; // 0x20
	private YostarSDKAgreementItem _agreeItemPrefab; // 0x28
	private TwoStateToggle _toggleAgreeAll; // 0x30
	private Button _btnAgree; // 0x38
	private Button _btnCancel; // 0x40
	private Button _btnOK; // 0x48
	private Button _btnOKCancel; // 0x50
	private Button _btnOKAgree; // 0x58
	private Text _textConfirm; // 0x60
	private Text _textCancel; // 0x68
	private Text _textOK; // 0x70
	private Text _textOKCancel; // 0x78
	private Text _textOKAgree; // 0x80
	private Text _textAgreeAll; // 0x88
	private AgreementOptions m_options; // 0x90
	private AgreementViewModel m_viewModel; // 0xc0
	private List`1 m_agreeItems; // 0xc8
	private UIManager m_uiMgr; // 0xd0
	private FadeSwitchTween m_fadeTween; // 0xd8
	private static DelegateBridge __Hotfix0__InitFadeTweenIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Start; // 0x8
	private static DelegateBridge __Hotfix0_EventOnAgreeClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnOKClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnRejectClicked; // 0x20
	private static DelegateBridge __Hotfix0_EventOnSingleToggleClicked; // 0x28
	private static DelegateBridge __Hotfix0_Open; // 0x30
	private static DelegateBridge __Hotfix0_Close; // 0x38
	private static DelegateBridge __Hotfix0__OnItemToggleClicked; // 0x40
	private static DelegateBridge __Hotfix0__InitAgreeItems; // 0x48
	private static DelegateBridge __Hotfix0__InitConstTexts; // 0x50
	private static DelegateBridge __Hotfix0__UpdateStatus; // 0x58
	private static DelegateBridge __Hotfix0__OnBusinessFinished; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x258074c VA: 0x7594b9874c
	private Void _InitFadeTweenIfNot() { }
	// RVA: 0x258082c VA: 0x7594b9882c
	private Void Start() { }
	// RVA: 0x2580894 VA: 0x7594b98894
	public Void EventOnAgreeClicked() { }
	// RVA: 0x2580afc VA: 0x7594b98afc
	public Void EventOnOKClicked() { }
	// RVA: 0x2580b94 VA: 0x7594b98b94
	public Void EventOnRejectClicked() { }
	// RVA: 0x2580c2c VA: 0x7594b98c2c
	public Void EventOnSingleToggleClicked() { }
	// RVA: 0x257fd54 VA: 0x7594b97d54
	public Void Open(UIManager uiMgr, AgreementOptions options) { }
	// RVA: 0x2580650 VA: 0x7594b98650
	public IEnumerator Close() { }
	// RVA: 0x2581634 VA: 0x7594b99634
	private Void _OnItemToggleClicked(Int32 index) { }
	// RVA: 0x25811ec VA: 0x7594b991ec
	private Void _InitAgreeItems() { }
	// RVA: 0x25814bc VA: 0x7594b994bc
	private Void _InitConstTexts() { }
	// RVA: 0x2580cac VA: 0x7594b98cac
	private Void _UpdateStatus() { }
	// RVA: 0x2580a84 VA: 0x7594b98a84
	private Void _OnBusinessFinished() { }
	// RVA: 0x25818fc VA: 0x7594b998fc
	public Void .ctor() { }
}
```