# SDKUnbindEditInfoState

**Namespace:** `HGSDK.UI`


## Fields

- `SDKCaptchaWidget _captchaWidget`

- `GameObject _idNameWarning`

- `GameObject _captchaWarning`

- `InputField _inputId`

- `InputField _inputName`

- `InputField _inputCaptcha`

- `Button _btnNextStep`

- `Text _textGameAccount`

- `String m_phoneNumber`


## Methods

- `Void _InitViewStatus()`

- `Void _OnCurrentAccountInvalid()`

- `Void _UpdateViewStatusByInput(InputSource)`

- `Boolean _CheckIfAllInputValid()`

- `Void _BindCommonInputEvent(InputField, InputSource)`

- `Void _EventOnCloseClicked()`

- `Void _EventOnBackClicked()`

- `Void EventOnNextStepClicked()`

- `String <_InitViewStatus>b__15_0()`

- `Void <_OnCurrentAccountInvalid>b__16_0()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `FloatV2Handler <>xLuaBaseProxy_GetFloatV2Handler()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKUnbindEditInfoState : UIState
{
	private SDKCaptchaWidget _captchaWidget; // 0x50
	private GameObject _idNameWarning; // 0x58
	private GameObject _captchaWarning; // 0x60
	private InputField _inputId; // 0x68
	private InputField _inputName; // 0x70
	private InputField _inputCaptcha; // 0x78
	private Button _btnNextStep; // 0x80
	private Text _textGameAccount; // 0x88
	private String m_phoneNumber; // 0x90
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_GetFloatV2Handler; // 0x10
	private static DelegateBridge __Hotfix0__InitViewStatus; // 0x18
	private static DelegateBridge __Hotfix0__OnCurrentAccountInvalid; // 0x20
	private static DelegateBridge __Hotfix0__UpdateViewStatusByInput; // 0x28
	private static DelegateBridge __Hotfix0__CheckIfAllInputValid; // 0x30
	private static DelegateBridge __Hotfix0__BindCommonInputEvent; // 0x38
	private static DelegateBridge __Hotfix0__EventOnCloseClicked; // 0x40
	private static DelegateBridge __Hotfix0__EventOnBackClicked; // 0x48
	private static DelegateBridge __Hotfix0_EventOnNextStepClicked; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public override PopupState myState { get; }

	// RVA: 0x356268c VA: 0x7595b7a68c
	public override PopupState get_myState() { }
	// RVA: 0x35626f4 VA: 0x7595b7a6f4
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x3562bf4 VA: 0x7595b7abf4
	public override FloatV2Handler GetFloatV2Handler() { }
	// RVA: 0x356277c VA: 0x7595b7a77c
	private Void _InitViewStatus() { }
	// RVA: 0x3563080 VA: 0x7595b7b080
	private Void _OnCurrentAccountInvalid() { }
	// RVA: 0x3562f58 VA: 0x7595b7af58
	private Void _UpdateViewStatusByInput(InputSource source) { }
	// RVA: 0x3563148 VA: 0x7595b7b148
	private Boolean _CheckIfAllInputValid() { }
	// RVA: 0x3562d5c VA: 0x7595b7ad5c
	private Void _BindCommonInputEvent(InputField input, InputSource tag) { }
	// RVA: 0x356320c VA: 0x7595b7b20c
	private Void _EventOnCloseClicked() { }
	// RVA: 0x3563280 VA: 0x7595b7b280
	private Void _EventOnBackClicked() { }
	// RVA: 0x3563328 VA: 0x7595b7b328
	public Void EventOnNextStepClicked() { }
	// RVA: 0x35634cc VA: 0x7595b7b4cc
	public Void .ctor() { }
	// RVA: 0x3563570 VA: 0x7595b7b570
	private String <_InitViewStatus>b__15_0() { }
	// RVA: 0x3563578 VA: 0x7595b7b578
	private Void <_OnCurrentAccountInvalid>b__16_0() { }
	// RVA: 0x3563590 VA: 0x7595b7b590
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x3563594 VA: 0x7595b7b594
	private FloatV2Handler <>xLuaBaseProxy_GetFloatV2Handler() { }
}
```