# SDKPopupChangePhoneState

**Namespace:** `HGSDK.UI`


## Fields

- `InputField _newPhoneInput`

- `SDKInputWarning _phoneInputWarning`

- `SDKInputWarning _phoneUsedWarning`

- `InputField _newPhoneCaptchaInput`

- `SDKCaptchaWidget _newCaptchaWidget`

- `InputField _oriPhoneCaptchaInput`

- `SDKCaptchaWidget _oriCaptchaWidget`

- `HGSDKSettingNotifyView _notifyView`

- `Button _closeBtn`


## Methods

- `Void EventOnCloseClicked()`

- `Void EventOnChangePhoneClicked()`

- `Void _OnNewPhoneInvalid()`

- `Void _OnNewCaptchaSendSuc(Int64)`

- `Void _OnOriPhoneInvalid()`

- `Void _OnOriCaptchaSendSuc(Int64)`

- `Void _ShowRemindDialog(String)`

- `Void _CallChangePhone(String)`

- `Void _OnChangePhoneSuccess()`

- `Void _ShowChangePhoneFailToast()`

- `String <OnRegister>b__11_1()`

- `Void <_CallChangePhone>b__20_0(ChangePhoneResponse)`

- `Void <_OnChangePhoneSuccess>b__21_0()`

- `Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1, UIPage)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKPopupChangePhoneState : UIState
{
	private InputField _newPhoneInput; // 0x50
	private SDKInputWarning _phoneInputWarning; // 0x58
	private SDKInputWarning _phoneUsedWarning; // 0x60
	private InputField _newPhoneCaptchaInput; // 0x68
	private SDKCaptchaWidget _newCaptchaWidget; // 0x70
	private InputField _oriPhoneCaptchaInput; // 0x78
	private SDKCaptchaWidget _oriCaptchaWidget; // 0x80
	private HGSDKSettingNotifyView _notifyView; // 0x88
	private Button _closeBtn; // 0x90
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnRegister; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_EventOnCloseClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnChangePhoneClicked; // 0x20
	private static DelegateBridge __Hotfix0__OnNewPhoneInvalid; // 0x28
	private static DelegateBridge __Hotfix0__OnNewCaptchaSendSuc; // 0x30
	private static DelegateBridge __Hotfix0__OnOriPhoneInvalid; // 0x38
	private static DelegateBridge __Hotfix0__OnOriCaptchaSendSuc; // 0x40
	private static DelegateBridge __Hotfix0__ShowRemindDialog; // 0x48
	private static DelegateBridge __Hotfix0__CallChangePhone; // 0x50
	private static DelegateBridge __Hotfix0__OnChangePhoneSuccess; // 0x58
	private static DelegateBridge __Hotfix0__ShowChangePhoneFailToast; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public override PopupState myState { get; }

	// RVA: 0x355f79c VA: 0x7595b7779c
	public override PopupState get_myState() { }
	// RVA: 0x355f804 VA: 0x7595b77804
	public override Void OnRegister(UIStateMachine`1 stateMachine, UIPage page) { }
	// RVA: 0x355fd6c VA: 0x7595b77d6c
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x355ffa4 VA: 0x7595b77fa4
	public Void EventOnCloseClicked() { }
	// RVA: 0x3560030 VA: 0x7595b78030
	public Void EventOnChangePhoneClicked() { }
	// RVA: 0x356027c VA: 0x7595b7827c
	private Void _OnNewPhoneInvalid() { }
	// RVA: 0x35602f0 VA: 0x7595b782f0
	private Void _OnNewCaptchaSendSuc(Int64 timeStamp) { }
	// RVA: 0x35603ac VA: 0x7595b783ac
	private Void _OnOriPhoneInvalid() { }
	// RVA: 0x356041c VA: 0x7595b7841c
	private Void _OnOriCaptchaSendSuc(Int64 timeStamp) { }
	// RVA: 0x35604d8 VA: 0x7595b784d8
	private Void _ShowRemindDialog(String token) { }
	// RVA: 0x35600e8 VA: 0x7595b780e8
	private Void _CallChangePhone(String token) { }
	// RVA: 0x35606a0 VA: 0x7595b786a0
	private Void _OnChangePhoneSuccess() { }
	// RVA: 0x35607a8 VA: 0x7595b787a8
	private Void _ShowChangePhoneFailToast() { }
	// RVA: 0x3560888 VA: 0x7595b78888
	public Void .ctor() { }
	// RVA: 0x35608f4 VA: 0x7595b788f4
	private String <OnRegister>b__11_1() { }
	// RVA: 0x3560910 VA: 0x7595b78910
	private Void <_CallChangePhone>b__20_0(ChangePhoneResponse response) { }
	// RVA: 0x3560a30 VA: 0x7595b78a30
	private Void <_OnChangePhoneSuccess>b__21_0() { }
	// RVA: 0x3560a98 VA: 0x7595b78a98
	private Void <>xLuaBaseProxy_OnRegister(UIStateMachine`1 P0, UIPage P1) { }
	// RVA: 0x3560a9c VA: 0x7595b78a9c
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
}
```