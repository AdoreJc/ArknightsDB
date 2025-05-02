# AiriSDKBridge

**Namespace:** `Torappu.AiriSDK`


## Fields

- `Boolean m_isInited`

- `Boolean m_hasCalledInitFunc`


## Methods

- `Boolean _InitIfNot()`

- `Void _SystemShareEvent(SystemShareRet)`

- `Void _BuyEvent(BuyRet)`

- `Void _BirthSetEvent(BirthSetRet)`

- `Void _VerificationCodeEvent(VerificationCodeRet)`

- `Void _MigrateCodeEvent(MigrationCodeRet)`

- `Void _UnlinkEvent(UnLinkRet)`

- `Void _LinkEvent(LinkRet)`

- `Void _LoginEvent(LoginRet)`

- `Void _InitEvent(InitRet)`

- `Void _ClearAccountInfoEvent(ClearAccountInfoRet)`

- `Void _DeleteAccountEvent(DeleteAccountRet)`

- `Void _GetAgreementEvent(GetAgreementRet)`

- `Void _GetUnderAgeAgrementEvent(GetUnderAgreementRet)`

- `Void _GetShopAgreementEvent(GetShopAgreementRet)`

- `Void _RebornAccountEvent(RebornAccountRet)`

- `Void _QuerySkuDetailsEvent(SkuDetailRet)`

- `ResultCode Buy(String, BuyServerTag, String, Action`1)`

- `Void ClearAccountInfo(Action`1)`

- `Void ConfirmAgreement()`

- `Void ConfirmUnderAgreement()`

- `Void DeleteAccount(Action`1)`

- `String GetAgreement()`

- `String GetDeviceID()`

- `Void GetSafeArea(out, out, out, out)`

- `Boolean Init(Action`1)`

- `ResultCode LinkSocial(LoginPlatform, Action`1)`

- `ResultCode LinkSocial(LoginPlatform, String, String, Action`1)`

- `Void LoginWithDevice(Action`1)`

- `Void LoginWithFB(Action`1)`

- `Void LoginWithGoogle(Action`1)`

- `ResultCode LoginWithMigrationCode(String, String, Action`1)`

- `ResultCode LoginWithSDK(String, String, Action`1)`

- `Void LoginWithTW(Action`1)`

- `Void LoginWithApple(Action`1)`

- `Boolean IOSAppleSignInAvailable()`

- `Void MigrationCodeRequest(Action`1)`

- `Void NewAccountLink(Action`1)`

- `Void OnPause()`

- `Void OnResume()`

- `Void OpenHelpShift()`

- `Void OpenHelpShift(String, String, String, String, String, String)`

- `Void QuickLogin(Action`1)`

- `ResultCode SetBirth(String, Action`1)`

- `ResultCode UnlinkSocial(LoginPlatform, String, String, Action`1)`

- `ResultCode UnlinkSocial(LoginPlatform, Action`1)`

- `Void UserEventUpload(String, Dictionary`2)`

- `ResultCode VerificationCodeReq(String, Action`1)`

- `Void GetAgreementInfo(Action`1)`

- `ResultCode SDKToClipboard(String)`

- `String GetSDKRecommendedErrorMsg(Int32, LanguageType)`

- `Void GetShopAgreement(ShopAgreementType, Action`1)`

- `Void GetUnderAgreement(Action`1)`

- `Void RebornAccount(Action`1)`

- `ResultCode QuerySkuDetails(String[], Action`1)`

- `Void ConfirmLinkGooglePlayGame()`

- `Void ConfirmUnlinkGooglePlayGame()`

- `String SDKGetUID()`

- `Void _SendRequest(Action, Action`1, Boolean)`

- `ResultCode _SendRequest(Func`1, Action`1, Boolean)`

- `ResultType _SendRequest(Func`1, Action`1, Boolean, ResultType)`

- `Void _TriggerCallback(RetType)`

- `Void _BindCallback(Action`1)`

- `Boolean _CheckIfClearOtherRet(Type)`

- `Boolean _ShowLoadingMaskForSocial(LoginPlatform)`

- `Void Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AiriSDK
public class AiriSDKBridge : Singleton`1, IDisposable
{
	private static readonly Type[] CLEAR_OTHER_RET_TYPES; // 0x0
	private Boolean m_isInited; // 0x10
	private Boolean m_hasCalledInitFunc; // 0x11
	private Dictionary`2 m_cbMap; // 0x18
	private List`1 m_cbBuffer; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__SystemShareEvent; // 0x18
	private static DelegateBridge __Hotfix0__BuyEvent; // 0x20
	private static DelegateBridge __Hotfix0__BirthSetEvent; // 0x28
	private static DelegateBridge __Hotfix0__VerificationCodeEvent; // 0x30
	private static DelegateBridge __Hotfix0__MigrateCodeEvent; // 0x38
	private static DelegateBridge __Hotfix0__UnlinkEvent; // 0x40
	private static DelegateBridge __Hotfix0__LinkEvent; // 0x48
	private static DelegateBridge __Hotfix0__LoginEvent; // 0x50
	private static DelegateBridge __Hotfix0__InitEvent; // 0x58
	private static DelegateBridge __Hotfix0__ClearAccountInfoEvent; // 0x60
	private static DelegateBridge __Hotfix0__DeleteAccountEvent; // 0x68
	private static DelegateBridge __Hotfix0__GetAgreementEvent; // 0x70
	private static DelegateBridge __Hotfix0__GetUnderAgeAgrementEvent; // 0x78
	private static DelegateBridge __Hotfix0__GetShopAgreementEvent; // 0x80
	private static DelegateBridge __Hotfix0__RebornAccountEvent; // 0x88
	private static DelegateBridge __Hotfix0__QuerySkuDetailsEvent; // 0x90
	private static DelegateBridge __Hotfix0_Buy; // 0x98
	private static DelegateBridge __Hotfix0_ClearAccountInfo; // 0xa0
	private static DelegateBridge __Hotfix0_ConfirmAgreement; // 0xa8
	private static DelegateBridge __Hotfix0_ConfirmUnderAgreement; // 0xb0
	private static DelegateBridge __Hotfix0_DeleteAccount; // 0xb8
	private static DelegateBridge __Hotfix0_GetAgreement; // 0xc0
	private static DelegateBridge __Hotfix0_GetDeviceID; // 0xc8
	private static DelegateBridge __Hotfix0_GetSafeArea; // 0xd0
	private static DelegateBridge __Hotfix0_Init; // 0xd8
	private static DelegateBridge __Hotfix0_LinkSocial; // 0xe0
	private static DelegateBridge __Hotfix1_LinkSocial; // 0xe8
	private static DelegateBridge __Hotfix0_LoginWithDevice; // 0xf0
	private static DelegateBridge __Hotfix0_LoginWithFB; // 0xf8
	private static DelegateBridge __Hotfix0_LoginWithGoogle; // 0x100
	private static DelegateBridge __Hotfix0_LoginWithMigrationCode; // 0x108
	private static DelegateBridge __Hotfix0_LoginWithSDK; // 0x110
	private static DelegateBridge __Hotfix0_LoginWithTW; // 0x118
	private static DelegateBridge __Hotfix0_LoginWithApple; // 0x120
	private static DelegateBridge __Hotfix0_IOSAppleSignInAvailable; // 0x128
	private static DelegateBridge __Hotfix0_MigrationCodeRequest; // 0x130
	private static DelegateBridge __Hotfix0_NewAccountLink; // 0x138
	private static DelegateBridge __Hotfix0_OnPause; // 0x140
	private static DelegateBridge __Hotfix0_OnResume; // 0x148
	private static DelegateBridge __Hotfix0_OpenHelpShift; // 0x150
	private static DelegateBridge __Hotfix1_OpenHelpShift; // 0x158
	private static DelegateBridge __Hotfix0_QuickLogin; // 0x160
	private static DelegateBridge __Hotfix0_SetBirth; // 0x168
	private static DelegateBridge __Hotfix0_UnlinkSocial; // 0x170
	private static DelegateBridge __Hotfix1_UnlinkSocial; // 0x178
	private static DelegateBridge __Hotfix0_UserEventUpload; // 0x180
	private static DelegateBridge __Hotfix0_VerificationCodeReq; // 0x188
	private static DelegateBridge __Hotfix0_GetAgreementInfo; // 0x190
	private static DelegateBridge __Hotfix0_SDKToClipboard; // 0x198
	private static DelegateBridge __Hotfix0_GetSDKRecommendedErrorMsg; // 0x1a0
	private static DelegateBridge __Hotfix0_GetShopAgreement; // 0x1a8
	private static DelegateBridge __Hotfix0_GetUnderAgreement; // 0x1b0
	private static DelegateBridge __Hotfix0_RebornAccount; // 0x1b8
	private static DelegateBridge __Hotfix0_QuerySkuDetails; // 0x1c0
	private static DelegateBridge __Hotfix0_ConfirmLinkGooglePlayGame; // 0x1c8
	private static DelegateBridge __Hotfix0_ConfirmUnlinkGooglePlayGame; // 0x1d0
	private static DelegateBridge __Hotfix0_SDKGetUID; // 0x1d8
	private static DelegateBridge __Hotfix0__SendRequest; // 0x1e0
	private static DelegateBridge __Hotfix1__SendRequest; // 0x1e8
	private static DelegateBridge __Hotfix2__SendRequest; // 0x1f0
	private static DelegateBridge __Hotfix0__TriggerCallback; // 0x1f8
	private static DelegateBridge __Hotfix0__BindCallback; // 0x200
	private static DelegateBridge __Hotfix0__EnsureCbList; // 0x208
	private static DelegateBridge __Hotfix0__CheckIfClearOtherRet; // 0x210
	private static DelegateBridge __Hotfix0__ShowLoadingMaskForSocial; // 0x218
	private static DelegateBridge __Hotfix0_Dispose; // 0x220


	// RVA: 0x3ef0bdc VA: 0x7596508bdc
	private Void .ctor() { }
	// RVA: 0x3ef0d20 VA: 0x7596508d20
	private Boolean _InitIfNot() { }
	// RVA: 0x3ef18b0 VA: 0x75965098b0
	private Void _SystemShareEvent(SystemShareRet result) { }
	// RVA: 0x3ef1958 VA: 0x7596509958
	private Void _BuyEvent(BuyRet result) { }
	// RVA: 0x3ef1a00 VA: 0x7596509a00
	private Void _BirthSetEvent(BirthSetRet result) { }
	// RVA: 0x3ef1aa8 VA: 0x7596509aa8
	private Void _VerificationCodeEvent(VerificationCodeRet result) { }
	// RVA: 0x3ef1b50 VA: 0x7596509b50
	private Void _MigrateCodeEvent(MigrationCodeRet result) { }
	// RVA: 0x3ef1bf8 VA: 0x7596509bf8
	private Void _UnlinkEvent(UnLinkRet result) { }
	// RVA: 0x3ef1ca0 VA: 0x7596509ca0
	private Void _LinkEvent(LinkRet result) { }
	// RVA: 0x3ef1d48 VA: 0x7596509d48
	private Void _LoginEvent(LoginRet result) { }
	// RVA: 0x3ef1df0 VA: 0x7596509df0
	private Void _InitEvent(InitRet result) { }
	// RVA: 0x3ef1eb0 VA: 0x7596509eb0
	private Void _ClearAccountInfoEvent(ClearAccountInfoRet result) { }
	// RVA: 0x3ef1f58 VA: 0x7596509f58
	private Void _DeleteAccountEvent(DeleteAccountRet result) { }
	// RVA: 0x3ef2000 VA: 0x759650a000
	private Void _GetAgreementEvent(GetAgreementRet result) { }
	// RVA: 0x3ef20a8 VA: 0x759650a0a8
	private Void _GetUnderAgeAgrementEvent(GetUnderAgreementRet result) { }
	// RVA: 0x3ef2150 VA: 0x759650a150
	private Void _GetShopAgreementEvent(GetShopAgreementRet result) { }
	// RVA: 0x3ef21f8 VA: 0x759650a1f8
	private Void _RebornAccountEvent(RebornAccountRet result) { }
	// RVA: 0x3ef22a0 VA: 0x759650a2a0
	private Void _QuerySkuDetailsEvent(SkuDetailRet result) { }
	// RVA: 0x3ef2348 VA: 0x759650a348
	public ResultCode Buy(String strProductId, BuyServerTag eServerTag, String strExtraData, Action`1 callback) { }
	// RVA: 0x3ef24c0 VA: 0x759650a4c0
	public Void ClearAccountInfo(Action`1 callback) { }
	// RVA: 0x3ef2620 VA: 0x759650a620
	public Void ConfirmAgreement() { }
	// RVA: 0x3ef26cc VA: 0x759650a6cc
	public Void ConfirmUnderAgreement() { }
	// RVA: 0x3ef2778 VA: 0x759650a778
	public Void DeleteAccount(Action`1 callback) { }
	// RVA: 0x3ef28d8 VA: 0x759650a8d8
	public String GetAgreement() { }
	// RVA: 0x3ef2984 VA: 0x759650a984
	public String GetDeviceID() { }
	// RVA: 0x3ef2a64 VA: 0x759650aa64
	public Void GetSafeArea(out Single x, out Single y, out Single w, out Single h) { }
	// RVA: 0x3ef2b58 VA: 0x759650ab58
	public Boolean Init(Action`1 callback) { }
	// RVA: 0x3ef2cbc VA: 0x759650acbc
	public ResultCode LinkSocial(LoginPlatform platform, Action`1 callback) { }
	// RVA: 0x3ef2d7c VA: 0x759650ad7c
	public ResultCode LinkSocial(LoginPlatform platform, String strEmail, String strVerificationCode, Action`1 callback) { }
	// RVA: 0x3ef2fcc VA: 0x759650afcc
	public Void LoginWithDevice(Action`1 callback) { }
	// RVA: 0x3ef3148 VA: 0x759650b148
	public Void LoginWithFB(Action`1 callback) { }
	// RVA: 0x3ef32c4 VA: 0x759650b2c4
	public Void LoginWithGoogle(Action`1 callback) { }
	// RVA: 0x3ef3440 VA: 0x759650b440
	public ResultCode LoginWithMigrationCode(String strCode, String strUid, Action`1 callback) { }
	// RVA: 0x3ef35d0 VA: 0x759650b5d0
	public ResultCode LoginWithSDK(String strEmail, String strVerificationCode, Action`1 callback) { }
	// RVA: 0x3ef3760 VA: 0x759650b760
	public Void LoginWithTW(Action`1 callback) { }
	// RVA: 0x3ef38dc VA: 0x759650b8dc
	public Void LoginWithApple(Action`1 callback) { }
	// RVA: 0x3ef3a58 VA: 0x759650ba58
	public Boolean IOSAppleSignInAvailable() { }
	// RVA: 0x3ef3b04 VA: 0x759650bb04
	public Void MigrationCodeRequest(Action`1 callback) { }
	// RVA: 0x3ef3c80 VA: 0x759650bc80
	public Void NewAccountLink(Action`1 callback) { }
	// RVA: 0x3ef3de0 VA: 0x759650bde0
	public Void OnPause() { }
	// RVA: 0x3ef3ea0 VA: 0x759650bea0
	public Void OnResume() { }
	// RVA: 0x3ef3f60 VA: 0x759650bf60
	public Void OpenHelpShift() { }
	// RVA: 0x3ef414c VA: 0x759650c14c
	public Void OpenHelpShift(String roleUid, String roleName, String roleLevel, String roleServer, String rolePurchase, String createTime) { }
	// RVA: 0x3ef4370 VA: 0x759650c370
	public Void QuickLogin(Action`1 callback) { }
	// RVA: 0x3ef44d0 VA: 0x759650c4d0
	public ResultCode SetBirth(String strBirth, Action`1 callback) { }
	// RVA: 0x3ef4618 VA: 0x759650c618
	public ResultCode UnlinkSocial(LoginPlatform platform, String strEmail, String strVerificationCode, Action`1 callback) { }
	// RVA: 0x3ef479c VA: 0x759650c79c
	public ResultCode UnlinkSocial(LoginPlatform platform, Action`1 callback) { }
	// RVA: 0x3ef48dc VA: 0x759650c8dc
	public Void UserEventUpload(String strEventName, Dictionary`2 strCallbackParameter) { }
	// RVA: 0x3ef49ac VA: 0x759650c9ac
	public ResultCode VerificationCodeReq(String strEmail, Action`1 callback) { }
	// RVA: 0x3ef4aec VA: 0x759650caec
	public Void GetAgreementInfo(Action`1 callback) { }
	// RVA: 0x3ef4c4c VA: 0x759650cc4c
	public ResultCode SDKToClipboard(String cValue) { }
	// RVA: 0x3ef4d10 VA: 0x759650cd10
	public String GetSDKRecommendedErrorMsg(Int32 code, LanguageType type) { }
	// RVA: 0x3ef4de0 VA: 0x759650cde0
	public Void GetShopAgreement(ShopAgreementType type, Action`1 callback) { }
	// RVA: 0x3ef4f14 VA: 0x759650cf14
	public Void GetUnderAgreement(Action`1 callback) { }
	// RVA: 0x3ef5074 VA: 0x759650d074
	public Void RebornAccount(Action`1 callback) { }
	// RVA: 0x3ef51d4 VA: 0x759650d1d4
	public ResultCode QuerySkuDetails(String[] skus, Action`1 callback) { }
	// RVA: 0x3ef5314 VA: 0x759650d314
	public Void ConfirmLinkGooglePlayGame() { }
	// RVA: 0x3ef53c0 VA: 0x759650d3c0
	public Void ConfirmUnlinkGooglePlayGame() { }
	// RVA: 0x3ef546c VA: 0x759650d46c
	public String SDKGetUID() { }
	// RVA: 0x VA: 0x0
	private Void _SendRequest(Action invoke, Action`1 callback, Boolean showLoading) { }
	// RVA: 0x VA: 0x0
	private ResultCode _SendRequest(Func`1 invoke, Action`1 callback, Boolean showLoading) { }
	// RVA: 0x VA: 0x0
	private ResultType _SendRequest(Func`1 invoke, Action`1 callback, Boolean showLoading, ResultType defaultVal) { }
	// RVA: 0x VA: 0x0
	private Void _TriggerCallback(RetType result) { }
	// RVA: 0x VA: 0x0
	private Void _BindCallback(Action`1 callback) { }
	// RVA: 0x VA: 0x0
	private List`1 _EnsureCbList() { }
	// RVA: 0x3ef5518 VA: 0x759650d518
	private Boolean _CheckIfClearOtherRet(Type retType) { }
	// RVA: 0x3ef2f24 VA: 0x759650af24
	private Boolean _ShowLoadingMaskForSocial(LoginPlatform platform) { }
	// RVA: 0x3ef5644 VA: 0x759650d644
	public Void Dispose() { }
	// RVA: 0x3ef61e0 VA: 0x759650e1e0
	private static Void .cctor() { }
}
```