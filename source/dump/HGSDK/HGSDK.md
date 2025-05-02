# HGSDK

**Namespace:** `HGSDK`


## Fields

- `SDKOptions _sdkOptions`

- `Options _options`

- `SDKLoginPage _loginPrefab`

- `SDKPayPage _payPrefab`

- `HGSDKPopupPage _popupPrefab`

- `HGSettingViewAccount _settingAccountPrefab`

- `TextAsset _stringMap`

- `Urls _urls`

- `String m_token`

- `String m_uid`

- `LoginResult m_loginResult`

- `Boolean m_isGuest`

- `Boolean m_hasLogin`

- `UIManager m_uiManager`

- `PingManager m_pingManager`

- `Int64 m_Ts`

- `U8Plugin m_u8Plugin`


## Properties

- `String lastUsedUid`

- `String lastUsedAccountToken`

- `String lastUsedGuestToken`

- `Boolean lastIdentityVerified`

- `Boolean lastIsMinor`

- `String deviceId`

- `String SDKUrl`

- `Camera sdkCamera`

- `String appCode`

- `String cachedUsername`

- `String sdkUid`

- `String sdkToken`

- `LoginResult loginResult`

- `Boolean isGuest`

- `Boolean hasCachedUser`

- `Urls urls`


## Methods

- `String get_lastUsedUid()`

- `String get_lastUsedAccountToken()`

- `String get_lastUsedGuestToken()`

- `Boolean get_lastIdentityVerified()`

- `Boolean get_lastIsMinor()`

- `String get_deviceId()`

- `String get_SDKUrl()`

- `Camera get_sdkCamera()`

- `String get_appCode()`

- `String get_cachedUsername()`

- `Void set_cachedUsername(String)`

- `String get_sdkUid()`

- `String get_sdkToken()`

- `LoginResult get_loginResult()`

- `Boolean get_isGuest()`

- `Boolean get_hasCachedUser()`

- `Urls get_urls()`

- `Boolean CheckIfGuest()`

- `Void ProcessPaymentState_PayProcess(Action`1)`

- `Void PreventGuestDelete(Action)`

- `Void ConfirmLoginInfo(LoginResult, Boolean, Boolean)`

- `Boolean TryHookDeleteAllPlayerPrefs(Action, Action)`

- `Void TryInjectSettings(InjectSettingOptions)`

- `Void TryInjectCashShop(InjectShopOptions)`

- `Void TryShowGlobalAgreement(Action, Action)`

- `Void ClearLoginInfo()`

- `Void SaveCaptchaTs(String, Int64)`

- `Int64 GetCaptchaTs(String)`

- `Void TryToCallLoginoutWhenLogin()`

- `Void TryToCallLoginoutWhenLogout()`

- `Void Login(Action`1, Action)`

- `Void Logout(Action, Action)`

- `Void Pay(Action`1, Action)`

- `Void OpenChangePhoneSettingView()`

- `Void OpenChagePwdSettingView()`

- `Void OpenAgreementSettingView()`

- `Void OpenUnbindGrantView()`

- `Void CallLoginService(String, String, Action`1, Action)`

- `Void CallAuthService(String, Action`1, Action)`

- `Void CallSendSmsCodeWithType(String, SendSmsCodeType, Action`1, Action)`

- `Void CallRegisterService(String, String, String, Action`1, Action)`

- `Void CallSmsCodeLoginService(String, String, Action`1, Action)`

- `Void CallGuestRegisterCaptcha(Action`1, Action)`

- `GuestLoginHandler CallGuestLoginService(String)`

- `Void CallIdentityVerifyService(String, String, Action`1, Action)`

- `Void CallCheckIdCardServie(String, Action`1, Action)`

- `Void CallGuestUpgradeService(LoginResult, Action, Action)`

- `Void CallUpdateAgreementService(String, Action)`

- `Void CallChangePwdService(ChangePwdRequestParams, Action`1)`

- `Void CallChangePhoneCheckService(String, Action`1)`

- `Void CallChangePhoneService(ChangePhoneRequestParams, Action`1)`

- `Void TestOnlyNotifyEnterGame()`

- `GameRoleInfo GetGameRoleInfo()`

- `String GetString(String)`

- `Void _OnLoginSuc(LoginResult, Boolean, Action`1)`

- `Void _OnAuthOrLoginFail(String, Action)`

- `Void _OnRegisterFailed(String, Action)`

- `Void _OnGuestLoginFailed(Int64, Action, String)`

- `Void _ReloadPingMgrIfNeeded()`

- `String _GetAvailableToken()`

- `Void _CallLoginoutService(Int32)`

- `IEnumerator _InitCloudAuthCoroutine()`

- `Void _SendSDKAPIV2Request(String, RequestType, APIV2RequestCallback`1)`

- `Void _APIV2RequestWithCaptchaImpl(String, RequestType, APIV2RequestCallback`1)`

- `Void _CallNeedCloudAuthService(CloudAuthContext, Action`1)`

- `Void _CallCloudAuthService(CloudAuthContext, Action`1)`

- `Void _CallVerifyCloudAuthService(CloudAuthContext)`

- `Void StartCloudAuth(LoginResult, Action, Action)`

- `Void _FetchCloudAuthInfo(CloudAuthContext)`

- `Void _DoCloudAuthWithSDK(CloudAuthContext)`

- `Void CallSendPhoneCodeWithTypeV2(String, SendPhoneCodeTypeV2, APIV2RequestCallback`1)`

- `Void CallUnbindGrantService(String, String, String, APIV2RequestCallback`1)`

- `Void StartCheckGrantInfo(Action, Action)`

- `Void _OnCheckGrantInfoFailed(APIV2FailResponse, Action, Action)`

- `Void <OpenChangePhoneSettingView>b__100_0(ChangePhoneCheckResponse)`

- `Void <OpenChangePhoneSettingView>b__100_1()`

- `Void <OpenChagePwdSettingView>b__101_0()`

- `Void <OpenUnbindGrantView>b__103_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK
public class HGSDK : SDKBase`1, IMsgHolderInjecter
{
	public const String VERSION; // 0x0
	public const Int32 TYPE_LOGIN; // 0x0
	public const Int32 TYPE_LOGOUT; // 0x0
	private SDKOptions _sdkOptions; // 0x18
	private Options _options; // 0x40
	private SDKLoginPage _loginPrefab; // 0x60
	private SDKPayPage _payPrefab; // 0x68
	private HGSDKPopupPage _popupPrefab; // 0x70
	private HGSettingViewAccount _settingAccountPrefab; // 0x78
	private TextAsset _stringMap; // 0x80
	private Urls _urls; // 0x88
	private String m_token; // 0xa8
	private String m_uid; // 0xb0
	private LoginResult m_loginResult; // 0xb8
	private Boolean m_isGuest; // 0xd0
	private Boolean m_hasLogin; // 0xd1
	private UIManager m_uiManager; // 0xd8
	private PingManager m_pingManager; // 0xe0
	private ListDict`2 m_captchaAllowNextTsMap; // 0xe8
	private Int64 m_Ts; // 0xf0
	private U8Plugin m_u8Plugin; // 0xf8
	private Dictionary`2 m_stringMap; // 0x100
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_Start; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge __Hotfix0_get_lastUsedUid; // 0x18
	private static DelegateBridge __Hotfix0_get_lastUsedAccountToken; // 0x20
	private static DelegateBridge __Hotfix0_GetLastUsedAccountToken; // 0x28
	private static DelegateBridge __Hotfix0_get_lastUsedGuestToken; // 0x30
	private static DelegateBridge __Hotfix0_get_lastIdentityVerified; // 0x38
	private static DelegateBridge __Hotfix0_get_lastIsMinor; // 0x40
	private static DelegateBridge __Hotfix0_get_deviceId; // 0x48
	private static DelegateBridge __Hotfix0_get_SDKUrl; // 0x50
	private static DelegateBridge __Hotfix0_get_sdkCamera; // 0x58
	private static DelegateBridge __Hotfix0_get_appCode; // 0x60
	private static DelegateBridge __Hotfix0_get_cachedUsername; // 0x68
	private static DelegateBridge __Hotfix0_set_cachedUsername; // 0x70
	private static DelegateBridge __Hotfix0_GetCachedUsername; // 0x78
	private static DelegateBridge __Hotfix0_get_sdkUid; // 0x80
	private static DelegateBridge __Hotfix0_get_sdkToken; // 0x88
	private static DelegateBridge __Hotfix0_get_loginResult; // 0x90
	private static DelegateBridge __Hotfix0_get_isGuest; // 0x98
	private static DelegateBridge __Hotfix0_get_hasCachedUser; // 0xa0
	private static DelegateBridge __Hotfix0_get_urls; // 0xa8
	private static DelegateBridge __Hotfix0_CheckIfGuest; // 0xb0
	private static DelegateBridge __Hotfix0_ProcessPaymentState_PayProcess; // 0xb8
	private static DelegateBridge __Hotfix0_get_externalPlugin; // 0xc0
	private static DelegateBridge __Hotfix0_PreventGuestDelete; // 0xc8
	private static DelegateBridge __Hotfix0_ConfirmLoginInfo; // 0xd0
	private static DelegateBridge __Hotfix0_TryHookDeleteAllPlayerPrefs; // 0xd8
	private static DelegateBridge __Hotfix0_TryInjectSettings; // 0xe0
	private static DelegateBridge __Hotfix0_Torappu.SDK.IMsgHolderInjecter.isPopupAgreement; // 0xe8
	private static DelegateBridge __Hotfix0_TryInjectCashShop; // 0xf0
	private static DelegateBridge __Hotfix0_TryShowGlobalAgreement; // 0xf8
	private static DelegateBridge __Hotfix0_ClearLoginInfo; // 0x100
	private static DelegateBridge __Hotfix0_SaveCaptchaTs; // 0x108
	private static DelegateBridge __Hotfix0_GetCaptchaTs; // 0x110
	private static DelegateBridge __Hotfix0_TryToCallLoginoutWhenLogin; // 0x118
	private static DelegateBridge __Hotfix0_TryToCallLoginoutWhenLogout; // 0x120
	private static DelegateBridge __Hotfix0_Login; // 0x128
	private static DelegateBridge __Hotfix0_Logout; // 0x130
	private static DelegateBridge __Hotfix0_Pay; // 0x138
	private static DelegateBridge __Hotfix0_OpenChangePhoneSettingView; // 0x140
	private static DelegateBridge __Hotfix0_OpenChagePwdSettingView; // 0x148
	private static DelegateBridge __Hotfix0_OpenAgreementSettingView; // 0x150
	private static DelegateBridge __Hotfix0_OpenUnbindGrantView; // 0x158
	private static DelegateBridge __Hotfix0_CallLoginService; // 0x160
	private static DelegateBridge __Hotfix0__CallLoginService; // 0x168
	private static DelegateBridge __Hotfix0_CallAuthService; // 0x170
	private static DelegateBridge __Hotfix0_CallSendSmsCodeWithType; // 0x178
	private static DelegateBridge __Hotfix0__CallSendSmsCode; // 0x180
	private static DelegateBridge __Hotfix0_CallRegisterService; // 0x188
	private static DelegateBridge __Hotfix0__CallRegisterService; // 0x190
	private static DelegateBridge __Hotfix0_CallSmsCodeLoginService; // 0x198
	private static DelegateBridge __Hotfix0__CallSmsCodeLoginService; // 0x1a0
	private static DelegateBridge __Hotfix0_CallGuestRegisterCaptcha; // 0x1a8
	private static DelegateBridge __Hotfix0_CallGuestLoginService; // 0x1b0
	private static DelegateBridge __Hotfix0_CallPayCreateOrderAppstore; // 0x1b8
	private static DelegateBridge __Hotfix0_CallLegacyPayConfirmOrderAppstore; // 0x1c0
	private static DelegateBridge __Hotfix0_CallPayConfirmOrderAppstore; // 0x1c8
	private static DelegateBridge __Hotfix0_CallIdentityVerifyService; // 0x1d0
	private static DelegateBridge __Hotfix0__CallIdentityVerifyService; // 0x1d8
	private static DelegateBridge __Hotfix0_CallCheckIdCardServie; // 0x1e0
	private static DelegateBridge __Hotfix0_CallGuestUpgradeService; // 0x1e8
	private static DelegateBridge __Hotfix0_CallUpdateAgreementService; // 0x1f0
	private static DelegateBridge __Hotfix0_CallChangePwdService; // 0x1f8
	private static DelegateBridge __Hotfix0_CallChangePhoneCheckService; // 0x200
	private static DelegateBridge __Hotfix0_CallChangePhoneService; // 0x208
	private static DelegateBridge __Hotfix0_TestOnlyNotifyEnterGame; // 0x210
	private static DelegateBridge __Hotfix0_Alert; // 0x218
	private static DelegateBridge __Hotfix0_Toast; // 0x220
	private static DelegateBridge __Hotfix0_ShowReentrantLoading; // 0x228
	private static DelegateBridge __Hotfix0_HideReentrantLoading; // 0x230
	private static DelegateBridge __Hotfix0_DoLogout; // 0x238
	private static DelegateBridge __Hotfix0__GenRandomString; // 0x240
	private static DelegateBridge __Hotfix0_GetGameRoleInfo; // 0x248
	private static DelegateBridge __Hotfix0_GetString; // 0x250
	private static DelegateBridge __Hotfix0__SendSDKRequest; // 0x258
	private static DelegateBridge __Hotfix0__OnLoginSuc; // 0x260
	private static DelegateBridge __Hotfix0__OnAuthOrLoginFail; // 0x268
	private static DelegateBridge __Hotfix0__OnRegisterFailed; // 0x270
	private static DelegateBridge __Hotfix0__OnGuestLoginFailed; // 0x278
	private static DelegateBridge __Hotfix0__ReloadPingMgrIfNeeded; // 0x280
	private static DelegateBridge __Hotfix0__GetAvailableToken; // 0x288
	private static DelegateBridge __Hotfix0__CallLoginoutService; // 0x290
	private static DelegateBridge __Hotfix0__InitCloudAuthCoroutine; // 0x298
	private static DelegateBridge __Hotfix0__SendSDKAPIV2Request; // 0x2a0
	private static DelegateBridge __Hotfix0__APIV2RequestWithCaptchaImpl; // 0x2a8
	private static DelegateBridge __Hotfix0__CallNeedCloudAuthService; // 0x2b0
	private static DelegateBridge __Hotfix0__CallCloudAuthService; // 0x2b8
	private static DelegateBridge __Hotfix0__CallVerifyCloudAuthService; // 0x2c0
	private static DelegateBridge __Hotfix0_StartCloudAuth; // 0x2c8
	private static DelegateBridge __Hotfix0__FetchCloudAuthInfo; // 0x2d0
	private static DelegateBridge __Hotfix0__DoCloudAuthWithSDK; // 0x2d8
	private static DelegateBridge __Hotfix0_CallSendPhoneCodeWithTypeV2; // 0x2e0
	private static DelegateBridge __Hotfix0_CallUnbindGrantService; // 0x2e8
	private static DelegateBridge __Hotfix0_StartCheckGrantInfo; // 0x2f0
	private static DelegateBridge __Hotfix0__OnCheckGrantInfoFailed; // 0x2f8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x300

	public String lastUsedUid { get; }
	protected String lastUsedAccountToken { get; }
	public String lastUsedGuestToken { get; }
	public Boolean lastIdentityVerified { get; }
	public Boolean lastIsMinor { get; }
	protected String deviceId { get; }
	public String SDKUrl { get; }
	protected Camera sdkCamera { get; }
	protected String appCode { get; }
	public String cachedUsername { get; set; }
	public String sdkUid { get; }
	public String sdkToken { get; }
	public LoginResult loginResult { get; }
	public Boolean isGuest { get; }
	public Boolean hasCachedUser { get; }
	public Urls urls { get; }
	public override IExternalPlugin externalPlugin { get; }

	// RVA: 0x2f1d764 VA: 0x7595535764
	protected override Void OnInit() { }
	// RVA: 0x2f1d84c VA: 0x759553584c
	protected virtual Void Start() { }
	// RVA: 0x2f1d974 VA: 0x7595535974
	protected virtual Void Update() { }
	// RVA: 0x2f1db00 VA: 0x7595535b00
	public String get_lastUsedUid() { }
	// RVA: 0x2f1db80 VA: 0x7595535b80
	protected String get_lastUsedAccountToken() { }
	// RVA: 0x2f1dbe4 VA: 0x7595535be4
	public static String GetLastUsedAccountToken() { }
	// RVA: 0x2f1dc5c VA: 0x7595535c5c
	public String get_lastUsedGuestToken() { }
	// RVA: 0x2f1dcdc VA: 0x7595535cdc
	public Boolean get_lastIdentityVerified() { }
	// RVA: 0x2f1cb04 VA: 0x7595534b04
	public Boolean get_lastIsMinor() { }
	// RVA: 0x2f1dd6c VA: 0x7595535d6c
	protected String get_deviceId() { }
	// RVA: 0x2f1ca60 VA: 0x7595534a60
	public String get_SDKUrl() { }
	// RVA: 0x2f1dea8 VA: 0x7595535ea8
	protected Camera get_sdkCamera() { }
	// RVA: 0x2f1df10 VA: 0x7595535f10
	protected String get_appCode() { }
	// RVA: 0x2f1df78 VA: 0x7595535f78
	public String get_cachedUsername() { }
	// RVA: 0x2f1e054 VA: 0x7595536054
	protected Void set_cachedUsername(String value) { }
	// RVA: 0x2f1dfdc VA: 0x7595535fdc
	public static String GetCachedUsername() { }
	// RVA: 0x2f1bf40 VA: 0x7595533f40
	public String get_sdkUid() { }
	// RVA: 0x2f1bec0 VA: 0x7595533ec0
	public String get_sdkToken() { }
	// RVA: 0x2f1e110 VA: 0x7595536110
	public LoginResult get_loginResult() { }
	// RVA: 0x2f1e1a0 VA: 0x75955361a0
	public Boolean get_isGuest() { }
	// RVA: 0x2f1e208 VA: 0x7595536208
	public Boolean get_hasCachedUser() { }
	// RVA: 0x2f1e284 VA: 0x7595536284
	public Urls get_urls() { }
	// RVA: 0x2f1e310 VA: 0x7595536310
	public Boolean CheckIfGuest() { }
	// RVA: 0x2f1e38c VA: 0x759553638c
	public Void ProcessPaymentState_PayProcess(Action`1 callback) { }
	// RVA: 0x2f1e490 VA: 0x7595536490
	public override IExternalPlugin get_externalPlugin() { }
	// RVA: 0x2f1e630 VA: 0x7595536630
	public Void PreventGuestDelete(Action nextStep) { }
	// RVA: 0x2f1e904 VA: 0x7595536904
	public Void ConfirmLoginInfo(LoginResult result, Boolean isGuest, Boolean isUpgradingDuringPay) { }
	// RVA: 0x2f1eb28 VA: 0x7595536b28
	public Boolean TryHookDeleteAllPlayerPrefs(Action deleteFunc, Action saveFunc) { }
	// RVA: 0x2f1ece0 VA: 0x7595536ce0
	public Void TryInjectSettings(InjectSettingOptions options) { }
	// RVA: 0x2f1ef30 VA: 0x7595536f30
	private Boolean Torappu.SDK.IMsgHolderInjecter.isPopupAgreement() { }
	// RVA: 0x2f1ef94 VA: 0x7595536f94
	public Void TryInjectCashShop(InjectShopOptions options) { }
	// RVA: 0x2f1f00c VA: 0x759553700c
	public Void TryShowGlobalAgreement(Action onAgree, Action backLogin) { }
	// RVA: 0x2f1f08c VA: 0x759553708c
	public Void ClearLoginInfo() { }
	// RVA: 0x2f1f178 VA: 0x7595537178
	public Void SaveCaptchaTs(String key, Int64 timeStamp) { }
	// RVA: 0x2f1f224 VA: 0x7595537224
	public Int64 GetCaptchaTs(String key) { }
	// RVA: 0x2f1f2d0 VA: 0x75955372d0
	public Void TryToCallLoginoutWhenLogin() { }
	// RVA: 0x2f1f618 VA: 0x7595537618
	public Void TryToCallLoginoutWhenLogout() { }
	// RVA: 0x2f1c144 VA: 0x7595534144
	public Void Login(Action`1 onSuc, Action onFail) { }
	// RVA: 0x2f1c468 VA: 0x7595534468
	public Void Logout(Action onSuc, Action onFail) { }
	// RVA: 0x2f1c654 VA: 0x7595534654
	public Void Pay(Action`1 onSuc, Action onFail) { }
	// RVA: 0x2f1f844 VA: 0x7595537844
	public Void OpenChangePhoneSettingView() { }
	// RVA: 0x2f1fbd8 VA: 0x7595537bd8
	public Void OpenChagePwdSettingView() { }
	// RVA: 0x2f1fdac VA: 0x7595537dac
	public Void OpenAgreementSettingView() { }
	// RVA: 0x2f1fef0 VA: 0x7595537ef0
	public Void OpenUnbindGrantView() { }
	// RVA: 0x2f20138 VA: 0x7595538138
	public Void CallLoginService(String username, String password, Action`1 onSuc, Action onFail) { }
	// RVA: 0x2f20308 VA: 0x7595538308
	private RequestWithMessageHandler`1 _CallLoginService(LoginParam param) { }
	// RVA: 0x2f205b8 VA: 0x75955385b8
	public Void CallAuthService(String token, Action`1 onSuc, Action onFail) { }
	// RVA: 0x2f2080c VA: 0x759553880c
	public Void CallSendSmsCodeWithType(String phoneNumber, SendSmsCodeType type, Action`1 onSuc, Action onFail) { }
	// RVA: 0x2f209d4 VA: 0x75955389d4
	private RequestWithMessageHandler`1 _CallSendSmsCode(SendSmsCodeParam param) { }
	// RVA: 0x2f20c48 VA: 0x7595538c48
	public Void CallRegisterService(String account, String pwd, String smsCode, Action`1 onSuc, Action onFail) { }
	// RVA: 0x2f20e3c VA: 0x7595538e3c
	private RequestWithMessageHandler`1 _CallRegisterService(RegisterParam param) { }
	// RVA: 0x2f210fc VA: 0x75955390fc
	public Void CallSmsCodeLoginService(String phoneNum, String smsCode, Action`1 onSuc, Action onFail) { }
	// RVA: 0x2f212cc VA: 0x75955392cc
	private RequestWithMessageHandler`1 _CallSmsCodeLoginService(SmsCodeLoginParam param) { }
	// RVA: 0x2f2157c VA: 0x759553957c
	public Void CallGuestRegisterCaptcha(Action`1 onSuc, Action onFail) { }
	// RVA: 0x2f21834 VA: 0x7595539834
	public GuestLoginHandler CallGuestLoginService(String captcha) { }
	// RVA: 0x2f21ad4 VA: 0x7595539ad4
	public ResultHandler`1 CallPayCreateOrderAppstore(String orderId) { }
	// RVA: 0x2f21c38 VA: 0x7595539c38
	public ResultHandler`1 CallLegacyPayConfirmOrderAppstore(String orderId, String receiptData) { }
	// RVA: 0x2f21d84 VA: 0x7595539d84
	public ResultHandler`1 CallPayConfirmOrderAppstore(String curOrderId, List`1 infoList, String receiptData) { }
	// RVA: 0x2f21f80 VA: 0x7595539f80
	public Void CallIdentityVerifyService(String realName, String cardNum, Action`1 onSuc, Action onFail) { }
	// RVA: 0x2f22144 VA: 0x759553a144
	private RequestWithMessageHandler`1 _CallIdentityVerifyService(UserIdentityAuthParam param) { }
	// RVA: 0x2f223d8 VA: 0x759553a3d8
	public Void CallCheckIdCardServie(String cardNum, Action`1 onSuc, Action onFail) { }
	// RVA: 0x2f22620 VA: 0x759553a620
	public Void CallGuestUpgradeService(LoginResult accountResult, Action onSuc, Action onFail) { }
	// RVA: 0x2f226e4 VA: 0x759553a6e4
	public Void CallUpdateAgreementService(String token, Action onFinal) { }
	// RVA: 0x2f22808 VA: 0x759553a808
	public Void CallChangePwdService(ChangePwdRequestParams changePwdParams, Action`1 onProceed) { }
	// RVA: 0x2f1f9fc VA: 0x75955379fc
	public Void CallChangePhoneCheckService(String token, Action`1 onProceed) { }
	// RVA: 0x2f22a34 VA: 0x759553aa34
	public Void CallChangePhoneService(ChangePhoneRequestParams changePhoneParams, Action`1 onProceed) { }
	// RVA: 0x2f22c60 VA: 0x759553ac60
	public Void TestOnlyNotifyEnterGame() { }
	// RVA: 0x2f1d33c VA: 0x759553533c
	public static Void Alert(String content, Action onConfirm) { }
	// RVA: 0x2f22cec VA: 0x759553acec
	public static Void Toast(String content) { }
	// RVA: 0x2f22d60 VA: 0x759553ad60
	public static Void ShowReentrantLoading() { }
	// RVA: 0x2f22dbc VA: 0x759553adbc
	public static Void HideReentrantLoading() { }
	// RVA: 0x2f22e18 VA: 0x759553ae18
	public static Void DoLogout() { }
	// RVA: 0x2f217a8 VA: 0x75955397a8
	private static String _GenRandomString() { }
	// RVA: 0x2f22e9c VA: 0x759553ae9c
	public GameRoleInfo GetGameRoleInfo() { }
	// RVA: 0x2f23028 VA: 0x759553b028
	public String GetString(String key) { }
	// RVA: 0x VA: 0x0
	private ResultHandler`1 _SendSDKRequest(String serviceCode, RequestType requestContent, Boolean needSign) { }
	// RVA: 0x2f232b0 VA: 0x759553b2b0
	private Void _OnLoginSuc(LoginResult result, Boolean isGuest, Action`1 onSuc) { }
	// RVA: 0x2f23380 VA: 0x759553b380
	private Void _OnAuthOrLoginFail(String alert, Action onFail) { }
	// RVA: 0x2f23468 VA: 0x759553b468
	private Void _OnRegisterFailed(String alert, Action onFail) { }
	// RVA: 0x2f234f0 VA: 0x759553b4f0
	private Void _OnGuestLoginFailed(Int64 errorCode, Action onFail, String errorMsg) { }
	// RVA: 0x2f1f69c VA: 0x759553769c
	private Void _ReloadPingMgrIfNeeded() { }
	// RVA: 0x2f1f944 VA: 0x7595537944
	private String _GetAvailableToken() { }
	// RVA: 0x2f1f350 VA: 0x7595537350
	private Void _CallLoginoutService(Int32 type) { }
	// RVA: 0x2f1d8d8 VA: 0x75955358d8
	private IEnumerator _InitCloudAuthCoroutine() { }
	// RVA: 0x VA: 0x0
	private Void _SendSDKAPIV2Request(String serviceCode, RequestType requestContent, APIV2RequestCallback`1 callback) { }
	// RVA: 0x VA: 0x0
	private Void _APIV2RequestWithCaptchaImpl(String serviceCode, RequestType requestContent, APIV2RequestCallback`1 callback) { }
	// RVA: 0x2f237dc VA: 0x759553b7dc
	private Void _CallNeedCloudAuthService(CloudAuthContext context, Action`1 cloudAuthNextStep) { }
	// RVA: 0x2f23ad4 VA: 0x759553bad4
	private Void _CallCloudAuthService(CloudAuthContext context, Action`1 cloudAuthNextStep) { }
	// RVA: 0x2f23dcc VA: 0x759553bdcc
	private Void _CallVerifyCloudAuthService(CloudAuthContext context) { }
	// RVA: 0x2f2409c VA: 0x759553c09c
	public Void StartCloudAuth(LoginResult loginResult, Action onSuc, Action onFail) { }
	// RVA: 0x2f24228 VA: 0x759553c228
	private Void _FetchCloudAuthInfo(CloudAuthContext context) { }
	// RVA: 0x2f243b8 VA: 0x759553c3b8
	private Void _DoCloudAuthWithSDK(CloudAuthContext context) { }
	// RVA: 0x2f245c0 VA: 0x759553c5c0
	public Void CallSendPhoneCodeWithTypeV2(String phoneNum, SendPhoneCodeTypeV2 type, APIV2RequestCallback`1 callback) { }
	// RVA: 0x2f24710 VA: 0x759553c710
	public Void CallUnbindGrantService(String smsCode, String name, String idCard, APIV2RequestCallback`1 callback) { }
	// RVA: 0x2f248b4 VA: 0x759553c8b4
	public Void StartCheckGrantInfo(Action onProceed, Action onBlock) { }
	// RVA: 0x2f24ba4 VA: 0x759553cba4
	private Void _OnCheckGrantInfoFailed(APIV2FailResponse response, Action onProceed, Action onBlock) { }
	// RVA: 0x2f25264 VA: 0x759553d264
	public Void .ctor() { }
	// RVA: 0x2f25348 VA: 0x759553d348
	private Void <OpenChangePhoneSettingView>b__100_0(ChangePhoneCheckResponse response) { }
	// RVA: 0x2f25638 VA: 0x759553d638
	private Void <OpenChangePhoneSettingView>b__100_1() { }
	// RVA: 0x2f25740 VA: 0x759553d740
	private Void <OpenChagePwdSettingView>b__101_0() { }
	// RVA: 0x2f25848 VA: 0x759553d848
	private Void <OpenUnbindGrantView>b__103_0() { }
}
```