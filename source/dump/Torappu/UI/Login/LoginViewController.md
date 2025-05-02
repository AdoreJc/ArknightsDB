# LoginViewController

**Namespace:** `Torappu.UI.Login`


## Fields

- `String testUid`

- `StateEngine _stateEngine`

- `Text _uidText`

- `Text _versionText`

- `Text _devInfoText`

- `Boolean _debugNamingState`

- `Text _hintConnectingText`

- `Text _hintNicknameText`

- `Text _hintNicknameRuleText`

- `Coroutine m_nextStateCoroutine`

- `LoginListener m_loginListener`

- `Coroutine m_loginFinishCoroutine`

- `InvokeWhenUnlock m_loginLatch`

- `Boolean <isSdkControlled>k__BackingField`


## Properties

- `Boolean isSdkControlled`


## Methods

- `Boolean get_isSdkControlled()`

- `Void set_isSdkControlled(Boolean)`

- `Void AlertResourceVersionError()`

- `Void DoSDKLogin(Action)`

- `Void StartMainLoginProcess(LoginListener)`

- `Void EventOnLoginFinished()`

- `Void EventOnNamed(String)`

- `Void EventOnServiceLicenseAgreed()`

- `Void SDKSwitchToPhase1()`

- `Void SDKSwitchToPhase2()`

- `Void OnSDKLoginFinished()`

- `Void SDKClearAccount()`

- `Void SDKExitGameDialog(Action)`

- `Void Start()`

- `IEnumerator _OnStartCoroutine()`

- `Boolean _PredicateExitGameBackPressEvent()`

- `Void _OnLoginProcessInterrupted()`

- `Void _OnResourceOrClientVersionError()`

- `Void _OnNetworkConfigVersionError()`

- `Void _UpdateSDKIdAndLogin(String, String)`

- `Void _LoginServiceSuccess(LoginResponse)`

- `Void _SyncDataServiceSuccess(SyncDataResponse)`

- `Void _BindNickNameServiceSuccess(BindNickNameResponse)`

- `Void _OnBindNickNameSucc()`

- `Void _UpdateSDKUID(String)`

- `Void _OnPlayerInfoReadyToEnterGame(Boolean)`

- `Void _InitPlayerVoiceLangPrefs(Action)`

- `Void _GoToHomeScene()`

- `Void _EnsureNextState(Boolean)`

- `IEnumerator _DoEnsureNextState(Boolean)`

- `Void _InvokeU8Auth(String)`

- `Void _OnU8AuthRejected(Object)`

- `Void _InvokeCaptchaForU8Auth(U8LoginRejectInfo)`

- `Void _OnU8AuthCaptchaFetched(GT3Message)`

- `Void _FetchExtraDataAfterAuth(Action)`

- `Void _OnNativeLicenseFailed(Failure)`

- `IEnumerator _LoginFinishCoroutine()`

- `Void _SDKLoginImpl(Action)`

- `IEnumerator _PreparePlayerInfoToEnterGame()`

- `Boolean _TryToShowInGameLicense()`

- `Void _LoginTrace()`

- `Void <_UpdateSDKIdAndLogin>b__36_0(LoginResponse)`

- `Boolean <_UpdateSDKIdAndLogin>b__36_1(ResponseError)`

- `Boolean <_LoginServiceSuccess>b__38_0(ResponseError)`

- `Void <_SyncDataServiceSuccess>b__39_0()`

- `Void <_InvokeU8Auth>b__48_0(U8LoginResult)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Login
public class LoginViewController : SingletonMonoBehaviour`1, ISingletonNotAutoCreate, IHotfixable
{
	public String testUid; // 0x18
	private StateEngine _stateEngine; // 0x20
	private Text _uidText; // 0x28
	private Text _versionText; // 0x30
	private Text _devInfoText; // 0x38
	private Boolean _debugNamingState; // 0x40
	private Text _hintConnectingText; // 0x48
	private Text _hintNicknameText; // 0x50
	private Text _hintNicknameRuleText; // 0x58
	private Coroutine m_nextStateCoroutine; // 0x60
	private LoginListener m_loginListener; // 0x68
	private Coroutine m_loginFinishCoroutine; // 0x70
	private InvokeWhenUnlock m_loginLatch; // 0x78
	private Boolean <isSdkControlled>k__BackingField; // 0x80
	private static DelegateBridge __Hotfix0_get_isSdkControlled; // 0x0
	private static DelegateBridge __Hotfix0_set_isSdkControlled; // 0x8
	private static DelegateBridge __Hotfix0_AlertResourceVersionError; // 0x10
	private static DelegateBridge __Hotfix0_DoSDKLogin; // 0x18
	private static DelegateBridge __Hotfix0_StartMainLoginProcess; // 0x20
	private static DelegateBridge __Hotfix0_EventOnLoginFinished; // 0x28
	private static DelegateBridge __Hotfix0_EventOnNamed; // 0x30
	private static DelegateBridge __Hotfix0_EventOnServiceLicenseAgreed; // 0x38
	private static DelegateBridge __Hotfix0_SDKSwitchToPhase1; // 0x40
	private static DelegateBridge __Hotfix0_SDKSwitchToPhase2; // 0x48
	private static DelegateBridge __Hotfix0_OnSDKLoginFinished; // 0x50
	private static DelegateBridge __Hotfix0_SDKClearAccount; // 0x58
	private static DelegateBridge __Hotfix0_SDKExitGameDialog; // 0x60
	private static DelegateBridge __Hotfix0_Start; // 0x68
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x70
	private static DelegateBridge __Hotfix0__OnStartCoroutine; // 0x78
	private static DelegateBridge __Hotfix0__PredicateExitGameBackPressEvent; // 0x80
	private static DelegateBridge __Hotfix0__OnLoginProcessInterrupted; // 0x88
	private static DelegateBridge __Hotfix0__OnResourceOrClientVersionError; // 0x90
	private static DelegateBridge __Hotfix0__OnNetworkConfigVersionError; // 0x98
	private static DelegateBridge __Hotfix0__UpdateSDKIdAndLogin; // 0xa0
	private static DelegateBridge __Hotfix0__PostProcessLoginRequest; // 0xa8
	private static DelegateBridge __Hotfix0__LoginServiceSuccess; // 0xb0
	private static DelegateBridge __Hotfix0__SyncDataServiceSuccess; // 0xb8
	private static DelegateBridge __Hotfix0__BindNickNameServiceSuccess; // 0xc0
	private static DelegateBridge __Hotfix0__OnBindNickNameSucc; // 0xc8
	private static DelegateBridge __Hotfix0__UpdateSDKUID; // 0xd0
	private static DelegateBridge __Hotfix0__OnPlayerInfoReadyToEnterGame; // 0xd8
	private static DelegateBridge __Hotfix0__InitPlayerVoiceLangPrefs; // 0xe0
	private static DelegateBridge __Hotfix0__GoToHomeScene; // 0xe8
	private static DelegateBridge __Hotfix0__EnsureNextState; // 0xf0
	private static DelegateBridge __Hotfix0__DoEnsureNextState; // 0xf8
	private static DelegateBridge __Hotfix0__InvokeU8Auth; // 0x100
	private static DelegateBridge __Hotfix0__OnU8AuthRejected; // 0x108
	private static DelegateBridge __Hotfix0__InvokeCaptchaForU8Auth; // 0x110
	private static DelegateBridge __Hotfix0__OnU8AuthCaptchaFetched; // 0x118
	private static DelegateBridge __Hotfix0__FetchExtraDataAfterAuth; // 0x120
	private static DelegateBridge __Hotfix0__OnNativeLicenseFailed; // 0x128
	private static DelegateBridge __Hotfix0__LoginFinishCoroutine; // 0x130
	private static DelegateBridge __Hotfix0__SDKLoginImpl; // 0x138
	private static DelegateBridge __Hotfix0__PreparePlayerInfoToEnterGame; // 0x140
	private static DelegateBridge __Hotfix0__TryToShowInGameLicense; // 0x148
	private static DelegateBridge __Hotfix0__LoginTrace; // 0x150
	private static DelegateBridge __Hotfix0__ShowExitGameDialog; // 0x158
	private static DelegateBridge __Hotfix0__ProcessDataBeforeEnteringMainGame; // 0x160
	private static DelegateBridge _c__Hotfix0_ctor; // 0x168

	public Boolean isSdkControlled { get; set; }

	// RVA: 0x27b4148 VA: 0x7594dcc148
	public Boolean get_isSdkControlled() { }
	// RVA: 0x27b41b0 VA: 0x7594dcc1b0
	private Void set_isSdkControlled(Boolean value) { }
	// RVA: 0x27b4230 VA: 0x7594dcc230
	public Void AlertResourceVersionError() { }
	// RVA: 0x27b01b0 VA: 0x7594dc81b0
	public Void DoSDKLogin(Action nextStep) { }
	// RVA: 0x27b1214 VA: 0x7594dc9214
	public Void StartMainLoginProcess(LoginListener listener) { }
	// RVA: 0x27b4468 VA: 0x7594dcc468
	public Void EventOnLoginFinished() { }
	// RVA: 0x27b18a0 VA: 0x7594dc98a0
	public Void EventOnNamed(String nickname) { }
	// RVA: 0x27b07b8 VA: 0x7594dc87b8
	public Void EventOnServiceLicenseAgreed() { }
	// RVA: 0x27b47fc VA: 0x7594dcc7fc
	public Void SDKSwitchToPhase1() { }
	// RVA: 0x27b4898 VA: 0x7594dcc898
	public Void SDKSwitchToPhase2() { }
	// RVA: 0x27b4934 VA: 0x7594dcc934
	public Void OnSDKLoginFinished() { }
	// RVA: 0x27b49f4 VA: 0x7594dcc9f4
	public Void SDKClearAccount() { }
	// RVA: 0x27b4b6c VA: 0x7594dccb6c
	public Void SDKExitGameDialog(Action onDismiss) { }
	// RVA: 0x27b4ed0 VA: 0x7594dcced0
	private Void Start() { }
	// RVA: 0x27b5008 VA: 0x7594dcd008
	protected override Void OnDestroy() { }
	// RVA: 0x27b4f5c VA: 0x7594dccf5c
	private IEnumerator _OnStartCoroutine() { }
	// RVA: 0x27b5088 VA: 0x7594dcd088
	private Boolean _PredicateExitGameBackPressEvent() { }
	// RVA: 0x27b5134 VA: 0x7594dcd134
	private Void _OnLoginProcessInterrupted() { }
	// RVA: 0x27b51e4 VA: 0x7594dcd1e4
	private Void _OnResourceOrClientVersionError() { }
	// RVA: 0x27b5264 VA: 0x7594dcd264
	private Void _OnNetworkConfigVersionError() { }
	// RVA: 0x27b52e4 VA: 0x7594dcd2e4
	private Void _UpdateSDKIdAndLogin(String uid, String token) { }
	// RVA: 0x27b5cd8 VA: 0x7594dcdcd8
	private static Void _PostProcessLoginRequest(LoginRequest loginRequest) { }
	// RVA: 0x27b5d78 VA: 0x7594dcdd78
	private Void _LoginServiceSuccess(LoginResponse resBody) { }
	// RVA: 0x27b6244 VA: 0x7594dce244
	private Void _SyncDataServiceSuccess(SyncDataResponse response) { }
	// RVA: 0x27b6528 VA: 0x7594dce528
	private Void _BindNickNameServiceSuccess(BindNickNameResponse response) { }
	// RVA: 0x27b65f8 VA: 0x7594dce5f8
	private Void _OnBindNickNameSucc() { }
	// RVA: 0x27b4a60 VA: 0x7594dcca60
	private Void _UpdateSDKUID(String uid) { }
	// RVA: 0x27b45b4 VA: 0x7594dcc5b4
	private Void _OnPlayerInfoReadyToEnterGame(Boolean isCreateRoleProcess) { }
	// RVA: 0x27b68e4 VA: 0x7594dce8e4
	private Void _InitPlayerVoiceLangPrefs(Action nextStep) { }
	// RVA: 0x27b6bc0 VA: 0x7594dcebc0
	private Void _GoToHomeScene() { }
	// RVA: 0x VA: 0x0
	private Void _EnsureNextState(Boolean isReplaceTop) { }
	// RVA: 0x VA: 0x0
	private IEnumerator _DoEnsureNextState(Boolean isReplaceTop) { }
	// RVA: 0x27b4320 VA: 0x7594dcc320
	private Void _InvokeU8Auth(String captcha) { }
	// RVA: 0x27b6e60 VA: 0x7594dcee60
	private Void _OnU8AuthRejected(Object rawRejectInfo) { }
	// RVA: 0x27b6ff4 VA: 0x7594dceff4
	private Void _InvokeCaptchaForU8Auth(U8LoginRejectInfo rejectInfo) { }
	// RVA: 0x27b715c VA: 0x7594dcf15c
	private Void _OnU8AuthCaptchaFetched(GT3Message message) { }
	// RVA: 0x27b71f8 VA: 0x7594dcf1f8
	private Void _FetchExtraDataAfterAuth(Action nextStep) { }
	// RVA: 0x27b73d8 VA: 0x7594dcf3d8
	private Void _OnNativeLicenseFailed(Failure reason) { }
	// RVA: 0x27b4508 VA: 0x7594dcc508
	private IEnumerator _LoginFinishCoroutine() { }
	// RVA: 0x27b7530 VA: 0x7594dcf530
	private Void _SDKLoginImpl(Action nextStep) { }
	// RVA: 0x27b76d0 VA: 0x7594dcf6d0
	private IEnumerator _PreparePlayerInfoToEnterGame() { }
	// RVA: 0x27b777c VA: 0x7594dcf77c
	private Boolean _TryToShowInGameLicense() { }
	// RVA: 0x27b78d0 VA: 0x7594dcf8d0
	private Void _LoginTrace() { }
	// RVA: 0x27b4c84 VA: 0x7594dccc84
	private static Void _ShowExitGameDialog(Action onDismiss) { }
	// RVA: 0x27b6dd4 VA: 0x7594dcedd4
	private static Void _ProcessDataBeforeEnteringMainGame() { }
	// RVA: 0x27b7998 VA: 0x7594dcf998
	public Void .ctor() { }
	// RVA: 0x27b7a8c VA: 0x7594dcfa8c
	private Void <_UpdateSDKIdAndLogin>b__36_0(LoginResponse response) { }
	// RVA: 0x27b7a90 VA: 0x7594dcfa90
	private Boolean <_UpdateSDKIdAndLogin>b__36_1(ResponseError error) { }
	// RVA: 0x27b7ba0 VA: 0x7594dcfba0
	private Boolean <_LoginServiceSuccess>b__38_0(ResponseError error) { }
	// RVA: 0x27b7cb0 VA: 0x7594dcfcb0
	private Void <_SyncDataServiceSuccess>b__39_0() { }
	// RVA: 0x27b7cc0 VA: 0x7594dcfcc0
	private Void <_InvokeU8Auth>b__48_0(U8LoginResult authResult) { }
}
```