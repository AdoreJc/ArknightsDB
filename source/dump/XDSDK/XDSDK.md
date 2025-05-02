# XDSDK

**Namespace:** `XDSDK`


## Fields

- `SDKOptions _sdkOptions`

- `XDLoginSwitchAccountPlugin _switchAccountPrefab`

- `XDAccountSetting _accountSettingPrefab`

- `String m_token`

- `String m_uid`

- `U8Plugin m_u8Plugin`


## Properties

- `String lastUsedUid`

- `String lastUsedAccountToken`

- `String lastUsedGuestToken`

- `Boolean lastIdentityVerified`

- `Boolean lastIsMinor`

- `String deviceId`

- `String SDKUrl`

- `String cachedUsername`

- `String sdkUid`

- `String sdkToken`

- `Boolean hasCachedUser`


## Methods

- `String get_lastUsedUid()`

- `String get_lastUsedAccountToken()`

- `String get_lastUsedGuestToken()`

- `Boolean get_lastIdentityVerified()`

- `Boolean get_lastIsMinor()`

- `String get_deviceId()`

- `String get_SDKUrl()`

- `String get_cachedUsername()`

- `Void set_cachedUsername(String)`

- `String get_sdkUid()`

- `String get_sdkToken()`

- `Boolean get_hasCachedUser()`

- `Boolean CheckIfGuest()`

- `Void ProcessPaymentState_PayProcess(Action`1)`

- `Void TryInjectSwitchAccount(InjectSwitchAccountOptions)`

- `Void PreventGuestDelete(Action)`

- `Void TryInjectCashShop(InjectShopOptions)`

- `Void TryShowGlobalAgreement(Action, Action)`

- `Void TryInjectSettings(InjectSettingOptions)`

- `Void ConfirmLoginInfo(LoginResult, Boolean, Boolean)`

- `Void Login(Action`1, Action)`

- `Void Logout(Action, Action)`

- `Void Pay(Action`1, Action)`

- `Void TryFetchCashProductInfo(Action`1, Action`1)`

- `Void _QuerySkuDetailsCallBack(JObject)`

- `Void CallLoginService(String, String, Action`1, Action)`

- `Void CallAuthService(String, Action`1, Action)`

- `Void CallSendSmsCodeForLogin(String, Action`1, Action)`

- `Void CallSendSmsCodeForRegister(String, Action`1, Action)`

- `Void _CallSendSmsCode(String, Int32, Action`1, Action)`

- `Void CallRegisterService(String, String, String, Action`1, Action)`

- `Void CallSmsCodeLoginService(String, String, Action`1, Action)`

- `Void CallGuestRegisterCaptcha(Action`1, Action)`

- `Void CallGuestLoginService(String, Action`1, Action)`

- `Void CallIdentityVerifyService(String, String, Action`1, Action)`

- `Void _OnLoginSuc(LoginResult, Boolean, Action`1)`

- `Void _OnAuthOrLoginFail(String, Action)`

- `Void _OnRegisterFailed(String, Action)`

- `Void _OnGuestLoginFailed(Int64, Action)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : XDSDK
public class XDSDK : SDKBase`1, IMsgHolderInjecter
{
	public const String VERSION; // 0x0
	private static readonly Char[] RANDOM_CHAR_MAP; // 0x0
	public Action`1 QuerySkuDetailsEvent; // 0x18
	public Action`1 QuerySkuDetailsOnSuc; // 0x20
	private SDKOptions _sdkOptions; // 0x28
	private XDLoginSwitchAccountPlugin _switchAccountPrefab; // 0x48
	private XDAccountSetting _accountSettingPrefab; // 0x50
	private String m_token; // 0x58
	private String m_uid; // 0x60
	private U8Plugin m_u8Plugin; // 0x68
	private Action`1 m_editorLoginCallback; // 0x70
	private static DelegateBridge __Hotfix0_get_lastUsedUid; // 0x8
	private static DelegateBridge __Hotfix0_get_lastUsedAccountToken; // 0x10
	private static DelegateBridge __Hotfix0_get_lastUsedGuestToken; // 0x18
	private static DelegateBridge __Hotfix0_get_lastIdentityVerified; // 0x20
	private static DelegateBridge __Hotfix0_get_lastIsMinor; // 0x28
	private static DelegateBridge __Hotfix0_get_deviceId; // 0x30
	private static DelegateBridge __Hotfix0_get_SDKUrl; // 0x38
	private static DelegateBridge __Hotfix0_get_cachedUsername; // 0x40
	private static DelegateBridge __Hotfix0_set_cachedUsername; // 0x48
	private static DelegateBridge __Hotfix0_get_sdkUid; // 0x50
	private static DelegateBridge __Hotfix0_get_sdkToken; // 0x58
	private static DelegateBridge __Hotfix0_get_hasCachedUser; // 0x60
	private static DelegateBridge __Hotfix0_CheckIfGuest; // 0x68
	private static DelegateBridge __Hotfix0_ProcessPaymentState_PayProcess; // 0x70
	private static DelegateBridge __Hotfix0_get_externalPlugin; // 0x78
	private static DelegateBridge __Hotfix0_TryInjectSwitchAccount; // 0x80
	private static DelegateBridge __Hotfix0_PreventGuestDelete; // 0x88
	private static DelegateBridge __Hotfix0_Torappu.SDK.IMsgHolderInjecter.isPopupAgreement; // 0x90
	private static DelegateBridge __Hotfix0_TryInjectCashShop; // 0x98
	private static DelegateBridge __Hotfix0_TryShowGlobalAgreement; // 0xa0
	private static DelegateBridge __Hotfix0_TryInjectSettings; // 0xa8
	private static DelegateBridge __Hotfix0_ConfirmLoginInfo; // 0xb0
	private static DelegateBridge __Hotfix0_Login; // 0xb8
	private static DelegateBridge __Hotfix0_Logout; // 0xc0
	private static DelegateBridge __Hotfix0_Pay; // 0xc8
	private static DelegateBridge __Hotfix0_TryFetchCashProductInfo; // 0xd0
	private static DelegateBridge __Hotfix0__QuerySkuDetailsCallBack; // 0xd8
	private static DelegateBridge __Hotfix0_CallLoginService; // 0xe0
	private static DelegateBridge __Hotfix0_CallAuthService; // 0xe8
	private static DelegateBridge __Hotfix0_CallSendSmsCodeForLogin; // 0xf0
	private static DelegateBridge __Hotfix0_CallSendSmsCodeForRegister; // 0xf8
	private static DelegateBridge __Hotfix0__CallSendSmsCode; // 0x100
	private static DelegateBridge __Hotfix0_CallRegisterService; // 0x108
	private static DelegateBridge __Hotfix0_CallSmsCodeLoginService; // 0x110
	private static DelegateBridge __Hotfix0_CallGuestRegisterCaptcha; // 0x118
	private static DelegateBridge __Hotfix0_CallGuestLoginService; // 0x120
	private static DelegateBridge __Hotfix0_CallPayCreateOrderAppstore; // 0x128
	private static DelegateBridge __Hotfix0_CallLegacyPayConfirmOrderAppstore; // 0x130
	private static DelegateBridge __Hotfix0_CallPayConfirmOrderAppstore; // 0x138
	private static DelegateBridge __Hotfix0_CallIdentityVerifyService; // 0x140
	private static DelegateBridge __Hotfix0_Alert; // 0x148
	private static DelegateBridge __Hotfix0_Toast; // 0x150
	private static DelegateBridge __Hotfix0_ShowReentrantLoading; // 0x158
	private static DelegateBridge __Hotfix0_HideReentrantLoading; // 0x160
	private static DelegateBridge __Hotfix0__GenRandomString; // 0x168
	private static DelegateBridge __Hotfix0__SendSDKRequest; // 0x170
	private static DelegateBridge __Hotfix0__OnLoginSuc; // 0x178
	private static DelegateBridge __Hotfix0__OnAuthOrLoginFail; // 0x180
	private static DelegateBridge __Hotfix0__OnRegisterFailed; // 0x188
	private static DelegateBridge __Hotfix0__OnGuestLoginFailed; // 0x190
	private static DelegateBridge _c__Hotfix0_ctor; // 0x198

	public String lastUsedUid { get; }
	protected String lastUsedAccountToken { get; }
	public String lastUsedGuestToken { get; }
	public Boolean lastIdentityVerified { get; }
	public Boolean lastIsMinor { get; }
	protected String deviceId { get; }
	public String SDKUrl { get; }
	public String cachedUsername { get; set; }
	public String sdkUid { get; }
	public String sdkToken { get; }
	public Boolean hasCachedUser { get; }
	public override IExternalPlugin externalPlugin { get; }

	// RVA: 0x25844c4 VA: 0x7594b9c4c4
	public String get_lastUsedUid() { }
	// RVA: 0x2584554 VA: 0x7594b9c554
	protected String get_lastUsedAccountToken() { }
	// RVA: 0x25845e4 VA: 0x7594b9c5e4
	public String get_lastUsedGuestToken() { }
	// RVA: 0x2584674 VA: 0x7594b9c674
	public Boolean get_lastIdentityVerified() { }
	// RVA: 0x25836f8 VA: 0x7594b9b6f8
	public Boolean get_lastIsMinor() { }
	// RVA: 0x2584714 VA: 0x7594b9c714
	protected String get_deviceId() { }
	// RVA: 0x2583644 VA: 0x7594b9b644
	public String get_SDKUrl() { }
	// RVA: 0x2584860 VA: 0x7594b9c860
	public String get_cachedUsername() { }
	// RVA: 0x25848f0 VA: 0x7594b9c8f0
	protected Void set_cachedUsername(String value) { }
	// RVA: 0x2582cc8 VA: 0x7594b9acc8
	public String get_sdkUid() { }
	// RVA: 0x2582c38 VA: 0x7594b9ac38
	public String get_sdkToken() { }
	// RVA: 0x25849bc VA: 0x7594b9c9bc
	public Boolean get_hasCachedUser() { }
	// RVA: 0x2584a48 VA: 0x7594b9ca48
	public Boolean CheckIfGuest() { }
	// RVA: 0x2584ad4 VA: 0x7594b9cad4
	public Void ProcessPaymentState_PayProcess(Action`1 callback) { }
	// RVA: 0x2584bec VA: 0x7594b9cbec
	public override IExternalPlugin get_externalPlugin() { }
	// RVA: 0x2584d7c VA: 0x7594b9cd7c
	public Void TryInjectSwitchAccount(InjectSwitchAccountOptions options) { }
	// RVA: 0x2584f70 VA: 0x7594b9cf70
	public Void PreventGuestDelete(Action nextStep) { }
	// RVA: 0x25851f0 VA: 0x7594b9d1f0
	private Boolean Torappu.SDK.IMsgHolderInjecter.isPopupAgreement() { }
	// RVA: 0x2585264 VA: 0x7594b9d264
	public Void TryInjectCashShop(InjectShopOptions options) { }
	// RVA: 0x25852ec VA: 0x7594b9d2ec
	public Void TryShowGlobalAgreement(Action onAgree, Action backLogin) { }
	// RVA: 0x258537c VA: 0x7594b9d37c
	public Void TryInjectSettings(InjectSettingOptions options) { }
	// RVA: 0x25855c4 VA: 0x7594b9d5c4
	public Void ConfirmLoginInfo(LoginResult result, Boolean isGuest, Boolean isUpgradingDuringPay) { }
	// RVA: 0x2582edc VA: 0x7594b9aedc
	public Void Login(Action`1 onSuc, Action onFail) { }
	// RVA: 0x25830d8 VA: 0x7594b9b0d8
	public Void Logout(Action onSuc, Action onFail) { }
	// RVA: 0x25832d8 VA: 0x7594b9b2d8
	public Void Pay(Action`1 onSuc, Action onFail) { }
	// RVA: 0x25857d4 VA: 0x7594b9d7d4
	public Void TryFetchCashProductInfo(Action`1 onSuc, Action`1 onFail) { }
	// RVA: 0x2585b0c VA: 0x7594b9db0c
	private Void _QuerySkuDetailsCallBack(JObject querySkuDetailsRet) { }
	// RVA: 0x2585ea0 VA: 0x7594b9dea0
	public Void CallLoginService(String username, String password, Action`1 onSuc, Action onFail) { }
	// RVA: 0x2586144 VA: 0x7594b9e144
	public Void CallAuthService(String token, Action`1 onSuc, Action onFail) { }
	// RVA: 0x25863a8 VA: 0x7594b9e3a8
	public Void CallSendSmsCodeForLogin(String phoneNumber, Action`1 onSuc, Action onFail) { }
	// RVA: 0x25866a8 VA: 0x7594b9e6a8
	public Void CallSendSmsCodeForRegister(String phoneNumber, Action`1 onSuc, Action onFail) { }
	// RVA: 0x2586460 VA: 0x7594b9e460
	private Void _CallSendSmsCode(String phoneNumber, Int32 act, Action`1 onSuc, Action onFail) { }
	// RVA: 0x2586770 VA: 0x7594b9e770
	public Void CallRegisterService(String account, String pwd, String smsCode, Action`1 onSuc, Action onFail) { }
	// RVA: 0x2586a2c VA: 0x7594b9ea2c
	public Void CallSmsCodeLoginService(String phoneNum, String smsCode, Action`1 onSuc, Action onFail) { }
	// RVA: 0x2586cd0 VA: 0x7594b9ecd0
	public Void CallGuestRegisterCaptcha(Action`1 onSuc, Action onFail) { }
	// RVA: 0x2587040 VA: 0x7594b9f040
	public Void CallGuestLoginService(String captcha, Action`1 onSuc, Action onFail) { }
	// RVA: 0x25872e0 VA: 0x7594b9f2e0
	public ResultHandler`1 CallPayCreateOrderAppstore(String orderId) { }
	// RVA: 0x2587454 VA: 0x7594b9f454
	public ResultHandler`1 CallLegacyPayConfirmOrderAppstore(String orderId, String receiptData) { }
	// RVA: 0x25875b0 VA: 0x7594b9f5b0
	public ResultHandler`1 CallPayConfirmOrderAppstore(String curOrderId, List`1 infoList, String receiptData) { }
	// RVA: 0x25877bc VA: 0x7594b9f7bc
	public Void CallIdentityVerifyService(String realName, String cardNum, Action`1 onSuc, Action onFail) { }
	// RVA: 0x2583f5c VA: 0x7594b9bf5c
	public static Void Alert(String content, Action onConfirm) { }
	// RVA: 0x2587a38 VA: 0x7594b9fa38
	public static Void Toast(String content) { }
	// RVA: 0x2587abc VA: 0x7594b9fabc
	public static Void ShowReentrantLoading() { }
	// RVA: 0x2587b28 VA: 0x7594b9fb28
	public static Void HideReentrantLoading() { }
	// RVA: 0x2586f1c VA: 0x7594b9ef1c
	private static String _GenRandomString() { }
	// RVA: 0x VA: 0x0
	private ResultHandler`1 _SendSDKRequest(String serviceCode, RequestType requestContent, Boolean needSign) { }
	// RVA: 0x2587b94 VA: 0x7594b9fb94
	private Void _OnLoginSuc(LoginResult result, Boolean isGuest, Action`1 onSuc) { }
	// RVA: 0x2587c74 VA: 0x7594b9fc74
	private Void _OnAuthOrLoginFail(String alert, Action onFail) { }
	// RVA: 0x2587e00 VA: 0x7594b9fe00
	private Void _OnRegisterFailed(String alert, Action onFail) { }
	// RVA: 0x2587ea8 VA: 0x7594b9fea8
	private Void _OnGuestLoginFailed(Int64 errorCode, Action onFail) { }
	// RVA: 0x2587fb4 VA: 0x7594b9ffb4
	public Void .ctor() { }
	// RVA: 0x2588054 VA: 0x7594ba0054
	private static Void .cctor() { }
}
```