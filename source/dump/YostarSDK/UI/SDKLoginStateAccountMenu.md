# SDKLoginStateAccountMenu

**Namespace:** `YostarSDK.UI`


## Fields

- `GameObject _btnGoogle`

- `GameObject _btnGuest`

- `GameObject _btnTwitter`

- `GameObject _btnFacebook`

- `GameObject _panelApple`

- `StyleConfig _krConfig`

- `StyleConfig _enConfig`

- `Image _imgYostar`

- `Image _imgGoogle`

- `Image _imgTW`

- `Image _imgFB`

- `Image _imgGuest`

- `Image _imgApple`

- `CurStatus m_curStatus`

- `Action m_latestLoginAction`


## Methods

- `Void _UpdateStyleConfig(StyleConfig)`

- `Void OnDeviceLoginClick()`

- `Void OnTwitterLoginClick()`

- `Void OnFacebookLoginClick()`

- `Void OnYostarLoginClick()`

- `Void OnGoogleLoginClick()`

- `Void OnAppleLoginClicked()`

- `Void _LoginPreventAccountDeleted(Action)`

- `Void _OnAiriSDKLogin(LoginRet)`

- `Void _ProtectedBeforeNewDeviceAccount(Action)`

- `Void _OnLoginWithOtherMethods(Action)`

- `Void <OnDeviceLoginClick>b__21_0()`

- `Void <OnDeviceLoginClick>b__21_1()`

- `Void <OnDeviceLoginClick>b__21_2()`

- `Void <OnTwitterLoginClick>b__22_0()`

- `Void <OnTwitterLoginClick>b__22_1()`

- `Void <OnFacebookLoginClick>b__23_0()`

- `Void <OnFacebookLoginClick>b__23_1()`

- `Void <OnYostarLoginClick>b__24_0()`

- `Void <OnGoogleLoginClick>b__25_0()`

- `Void <OnGoogleLoginClick>b__25_1()`

- `Void <OnAppleLoginClicked>b__26_0()`

- `Void <OnAppleLoginClicked>b__26_1()`

- `Void <_OnAiriSDKLogin>b__28_0()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class SDKLoginStateAccountMenu : UIState
{
	private GameObject _btnGoogle; // 0x50
	private GameObject _btnGuest; // 0x58
	private GameObject _btnTwitter; // 0x60
	private GameObject _btnFacebook; // 0x68
	private GameObject _panelApple; // 0x70
	private StyleConfig _krConfig; // 0x78
	private StyleConfig _enConfig; // 0xa8
	private Image _imgYostar; // 0xd8
	private Image _imgGoogle; // 0xe0
	private Image _imgTW; // 0xe8
	private Image _imgFB; // 0xf0
	private Image _imgGuest; // 0xf8
	private Image _imgApple; // 0x100
	private CurStatus m_curStatus; // 0x108
	private Action m_latestLoginAction; // 0x110
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__UpdateStyleConfig; // 0x10
	private static DelegateBridge __Hotfix0_OnDeviceLoginClick; // 0x18
	private static DelegateBridge __Hotfix0_OnTwitterLoginClick; // 0x20
	private static DelegateBridge __Hotfix0_OnFacebookLoginClick; // 0x28
	private static DelegateBridge __Hotfix0_OnYostarLoginClick; // 0x30
	private static DelegateBridge __Hotfix0_OnGoogleLoginClick; // 0x38
	private static DelegateBridge __Hotfix0_OnAppleLoginClicked; // 0x40
	private static DelegateBridge __Hotfix0__LoginPreventAccountDeleted; // 0x48
	private static DelegateBridge __Hotfix0__OnAiriSDKLogin; // 0x50
	private static DelegateBridge __Hotfix0__ProtectedBeforeNewDeviceAccount; // 0x58
	private static DelegateBridge __Hotfix0__OnLoginWithOtherMethods; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public override LoginState myState { get; }

	// RVA: 0x1b444bc VA: 0x759415c4bc
	public override LoginState get_myState() { }
	// RVA: 0x1b44524 VA: 0x759415c524
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1b448d8 VA: 0x759415c8d8
	private Void _UpdateStyleConfig(StyleConfig styleConfig) { }
	// RVA: 0x1b44a58 VA: 0x759415ca58
	public Void OnDeviceLoginClick() { }
	// RVA: 0x1b44c00 VA: 0x759415cc00
	public Void OnTwitterLoginClick() { }
	// RVA: 0x1b44cd0 VA: 0x759415ccd0
	public Void OnFacebookLoginClick() { }
	// RVA: 0x1b44da0 VA: 0x759415cda0
	public Void OnYostarLoginClick() { }
	// RVA: 0x1b44e70 VA: 0x759415ce70
	public Void OnGoogleLoginClick() { }
	// RVA: 0x1b44f40 VA: 0x759415cf40
	public Void OnAppleLoginClicked() { }
	// RVA: 0x1b45010 VA: 0x759415d010
	private Void _LoginPreventAccountDeleted(Action loginAction) { }
	// RVA: 0x1b450bc VA: 0x759415d0bc
	private Void _OnAiriSDKLogin(LoginRet ret) { }
	// RVA: 0x1b456d8 VA: 0x759415d6d8
	private Void _ProtectedBeforeNewDeviceAccount(Action nextStep) { }
	// RVA: 0x1b44b28 VA: 0x759415cb28
	private Void _OnLoginWithOtherMethods(Action nextStep) { }
	// RVA: 0x1b4575c VA: 0x759415d75c
	public Void .ctor() { }
	// RVA: 0x1b458b4 VA: 0x759415d8b4
	private Void <OnDeviceLoginClick>b__21_0() { }
	// RVA: 0x1b45934 VA: 0x759415d934
	private Void <OnDeviceLoginClick>b__21_1() { }
	// RVA: 0x1b459b4 VA: 0x759415d9b4
	private Void <OnDeviceLoginClick>b__21_2() { }
	// RVA: 0x1b45a68 VA: 0x759415da68
	private Void <OnTwitterLoginClick>b__22_0() { }
	// RVA: 0x1b45ae8 VA: 0x759415dae8
	private Void <OnTwitterLoginClick>b__22_1() { }
	// RVA: 0x1b45b9c VA: 0x759415db9c
	private Void <OnFacebookLoginClick>b__23_0() { }
	// RVA: 0x1b45c1c VA: 0x759415dc1c
	private Void <OnFacebookLoginClick>b__23_1() { }
	// RVA: 0x1b45cd0 VA: 0x759415dcd0
	private Void <OnYostarLoginClick>b__24_0() { }
	// RVA: 0x1b45d64 VA: 0x759415dd64
	private Void <OnGoogleLoginClick>b__25_0() { }
	// RVA: 0x1b45de4 VA: 0x759415dde4
	private Void <OnGoogleLoginClick>b__25_1() { }
	// RVA: 0x1b45e98 VA: 0x759415de98
	private Void <OnAppleLoginClicked>b__26_0() { }
	// RVA: 0x1b45f18 VA: 0x759415df18
	private Void <OnAppleLoginClicked>b__26_1() { }
	// RVA: 0x1b45fcc VA: 0x759415dfcc
	private Void <_OnAiriSDKLogin>b__28_0() { }
	// RVA: 0x1b45fe8 VA: 0x759415dfe8
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
}
```