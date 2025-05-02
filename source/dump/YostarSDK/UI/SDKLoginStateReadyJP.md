# SDKLoginStateReadyJP

**Namespace:** `YostarSDK.UI`


## Fields

- `GameObject _panelPlatform`

- `GameObject _btnTwitter`

- `GameObject _panelApple`

- `Text _textPlatform`

- `Animator _tapToLoginAnim`

- `Text _textOtherMethodsTitle`

- `LogicModel m_curStatus`


## Methods

- `Void _UpdateStatus()`

- `Void EventOnTapToLogin()`

- `Void EventOnLoginYostar()`

- `Void EventOnLoginTw()`

- `Void EventOnLoginMigrate()`

- `Void EventOnLoginApple()`

- `IEnumerator _PerformTapToLoginClicked()`

- `IEnumerator _QuickLoginCoroutine()`

- `Void _AiriSDKLoginCallback(LoginRet)`

- `Void _OnLoginSuc(LoginRet)`

- `Void _OnLoginFailed(LoginRet)`

- `Void _ResetAnimStateOnFail()`

- `Void _OnLoginWithOtherMethods(Action)`

- `Void <EventOnLoginYostar>b__15_0()`

- `Void <EventOnLoginTw>b__16_0()`

- `Void <EventOnLoginMigrate>b__17_0()`

- `Void <EventOnLoginApple>b__18_0()`

- `Void <_OnLoginSuc>b__22_0()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class SDKLoginStateReadyJP : UIState
{
	private const String ANIM_KEY_CLICKED; // 0x0
	private const Single TAP_TO_LOGIN_DELAY; // 0x0
	private GameObject _panelPlatform; // 0x50
	private GameObject _btnTwitter; // 0x58
	private GameObject _panelApple; // 0x60
	private Text _textPlatform; // 0x68
	private Animator _tapToLoginAnim; // 0x70
	private Text _textOtherMethodsTitle; // 0x78
	private LogicModel m_curStatus; // 0x80
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__UpdateStatus; // 0x10
	private static DelegateBridge __Hotfix0_EventOnTapToLogin; // 0x18
	private static DelegateBridge __Hotfix0_EventOnLoginYostar; // 0x20
	private static DelegateBridge __Hotfix0_EventOnLoginTw; // 0x28
	private static DelegateBridge __Hotfix0_EventOnLoginMigrate; // 0x30
	private static DelegateBridge __Hotfix0_EventOnLoginApple; // 0x38
	private static DelegateBridge __Hotfix0__PerformTapToLoginClicked; // 0x40
	private static DelegateBridge __Hotfix0__QuickLoginCoroutine; // 0x48
	private static DelegateBridge __Hotfix0__AiriSDKLoginCallback; // 0x50
	private static DelegateBridge __Hotfix0__OnLoginSuc; // 0x58
	private static DelegateBridge __Hotfix0__OnLoginFailed; // 0x60
	private static DelegateBridge __Hotfix0__ResetAnimStateOnFail; // 0x68
	private static DelegateBridge __Hotfix0__OnLoginWithOtherMethods; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public override LoginState myState { get; }

	// RVA: 0x1b47768 VA: 0x759415f768
	public override LoginState get_myState() { }
	// RVA: 0x1b477d0 VA: 0x759415f7d0
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1b47858 VA: 0x759415f858
	private Void _UpdateStatus() { }
	// RVA: 0x1b47b00 VA: 0x759415fb00
	public Void EventOnTapToLogin() { }
	// RVA: 0x1b47c3c VA: 0x759415fc3c
	public Void EventOnLoginYostar() { }
	// RVA: 0x1b47de4 VA: 0x759415fde4
	public Void EventOnLoginTw() { }
	// RVA: 0x1b47eb4 VA: 0x759415feb4
	public Void EventOnLoginMigrate() { }
	// RVA: 0x1b47f84 VA: 0x759415ff84
	public Void EventOnLoginApple() { }
	// RVA: 0x1b47b90 VA: 0x759415fb90
	private IEnumerator _PerformTapToLoginClicked() { }
	// RVA: 0x1b4807c VA: 0x759416007c
	private IEnumerator _QuickLoginCoroutine() { }
	// RVA: 0x1b48150 VA: 0x7594160150
	private Void _AiriSDKLoginCallback(LoginRet loginRet) { }
	// RVA: 0x1b481f4 VA: 0x75941601f4
	private Void _OnLoginSuc(LoginRet ret) { }
	// RVA: 0x1b482d8 VA: 0x75941602d8
	private Void _OnLoginFailed(LoginRet ret) { }
	// RVA: 0x1b48554 VA: 0x7594160554
	private Void _ResetAnimStateOnFail() { }
	// RVA: 0x1b47d0c VA: 0x759415fd0c
	private Void _OnLoginWithOtherMethods(Action nextStep) { }
	// RVA: 0x1b485e4 VA: 0x75941605e4
	public Void .ctor() { }
	// RVA: 0x1b48650 VA: 0x7594160650
	private Void <EventOnLoginYostar>b__15_0() { }
	// RVA: 0x1b48658 VA: 0x7594160658
	private Void <EventOnLoginTw>b__16_0() { }
	// RVA: 0x1b4870c VA: 0x759416070c
	private Void <EventOnLoginMigrate>b__17_0() { }
	// RVA: 0x1b48714 VA: 0x7594160714
	private Void <EventOnLoginApple>b__18_0() { }
	// RVA: 0x1b487c8 VA: 0x75941607c8
	private Void <_OnLoginSuc>b__22_0() { }
	// RVA: 0x1b487e0 VA: 0x75941607e0
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
}
```