# AiriSDKFaker

**Namespace:** `Torappu.AiriSDK.Fake`


## Methods

- `ResultCode Buy(String, BuyServerTag, String)`

- `ResultCode _MockPayWithHG(String, BuyServerTag, String)`

- `Void ClearAccountInfo()`

- `Void ConifrmAgreement()`

- `Void ConfirmUnderAger()`

- `Void DeleteAccount()`

- `String GetAgreement()`

- `Void GetAgreementInfo()`

- `String GetDeviceID()`

- `Void GetSafeArea(out, out, out, out)`

- `Boolean Init(PayStore)`

- `ResultCode LinkSocial(LoginPlatform, String, String)`

- `Void LoginWithDevice()`

- `Void LoginWithFB(Boolean)`

- `Void LoginWithGoogle(Boolean)`

- `Void LoginWithGooglePlay(Boolean)`

- `ResultCode LoginWithMigrationCode(String, String)`

- `ResultCode LoginWithSDK(String, String)`

- `ResultCode _LoginWithHGSDK(String, String)`

- `Void ConfirmLinkGooglePlayGame()`

- `Void ConfirmUnLinkGooglePlayGame()`

- `Void LoginWithTW(Boolean)`

- `Void LoginWithApple(Boolean)`

- `Void MigrationCodeRequest()`

- `Void NewAccountLink()`

- `Void OnPause()`

- `Void OnResume()`

- `Void OpenHelpShift()`

- `Void ShowAiHelpFAQs(String, String, String, String, Int32, String[])`

- `Void OpenHelpShift(String, String, String, String, String, String)`

- `Void QuickLogin()`

- `ResultCode SetBirth(String)`

- `ResultCode UnlinkSocial(LoginPlatform, String, String)`

- `Void UserEventUpload(String, Dictionary`2)`

- `ResultCode VerificationCodeReq(String)`

- `ResultCode SDKToClipboard(String)`

- `String GetSDKRecommendedErrorMsg(Int32, LanguageType)`

- `Void GetShopAgreement(ShopAgreementType)`

- `Void GetUnderAgeAgrement()`

- `Boolean IOSAppleSignInAvailable()`

- `Void RebornAccount()`

- `ResultCode QuerySkuDetails(String[])`

- `String SDKGetUID()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AiriSDK.Fake
public class AiriSDKFaker
{
	private const String YOSTAR_HG_FAKE_TOKEN; // 0x0
	private const String YOSTAR_FAKE_MCODE; // 0x0
	private static Int32 agree; // 0x0
	private static AiriSDKFaker m_inst; // 0x8

	public static AiriSDKFaker Instance { get; }

	// RVA: 0x3ef73b4 VA: 0x759650f3b4
	private static Void _InvokeNextFrame(Action invoke) { }
	// RVA: 0x3ef74c0 VA: 0x759650f4c0
	private static Void _InvokeAfterAWhile(Action invoke) { }
	// RVA: 0x3ef744c VA: 0x759650f44c
	private static IEnumerator _NextFrameCoroutine(Action invoke) { }
	// RVA: 0x3ef7558 VA: 0x759650f558
	private static IEnumerator _AWhileCoroutine(Action invoke) { }
	// RVA: 0x3ef6d10 VA: 0x759650ed10
	public static AiriSDKFaker get_Instance() { }
	// RVA: 0x3ef7624 VA: 0x759650f624
	public ResultCode Buy(String productId, BuyServerTag eServerTag, String extraData) { }
	// RVA: 0x3ef7638 VA: 0x759650f638
	private ResultCode _MockPayWithHG(String productId, BuyServerTag eServerTag, String extraData) { }
	// RVA: 0x3ef7740 VA: 0x759650f740
	public Void ClearAccountInfo() { }
	// RVA: 0x3ef783c VA: 0x759650f83c
	public Void ConifrmAgreement() { }
	// RVA: 0x3ef7888 VA: 0x759650f888
	public Void ConfirmUnderAger() { }
	// RVA: 0x3ef7908 VA: 0x759650f908
	public Void DeleteAccount() { }
	// RVA: 0x3ef7a04 VA: 0x759650fa04
	public String GetAgreement() { }
	// RVA: 0x3ef7a44 VA: 0x759650fa44
	public Void GetAgreementInfo() { }
	// RVA: 0x3ef7b40 VA: 0x759650fb40
	public String GetDeviceID() { }
	// RVA: 0x3ef7b80 VA: 0x759650fb80
	public Void GetSafeArea(out Single x, out Single y, out Single w, out Single h) { }
	// RVA: 0x3ef7bc4 VA: 0x759650fbc4
	public Boolean Init(PayStore pay) { }
	// RVA: 0x3ef7cc8 VA: 0x759650fcc8
	public ResultCode LinkSocial(LoginPlatform platform, String strEmail, String strVerificationCode) { }
	// RVA: 0x3ef7da8 VA: 0x759650fda8
	public Void LoginWithDevice() { }
	// RVA: 0x3ef812c VA: 0x759651012c
	public Void LoginWithFB(Boolean bIsCreateNewAccount) { }
	// RVA: 0x3ef8228 VA: 0x7596510228
	public Void LoginWithGoogle(Boolean bIsCreateNewAccount) { }
	// RVA: 0x3ef8324 VA: 0x7596510324
	public Void LoginWithGooglePlay(Boolean bIsCreateNewAccount) { }
	// RVA: 0x3ef8420 VA: 0x7596510420
	public ResultCode LoginWithMigrationCode(String code, String uid) { }
	// RVA: 0x3ef8524 VA: 0x7596510524
	public ResultCode LoginWithSDK(String account, String password) { }
	// RVA: 0x3ef8538 VA: 0x7596510538
	private ResultCode _LoginWithHGSDK(String account, String password) { }
	// RVA: 0x3ef88d0 VA: 0x75965108d0
	public Void ConfirmLinkGooglePlayGame() { }
	// RVA: 0x3ef8914 VA: 0x7596510914
	public Void ConfirmUnLinkGooglePlayGame() { }
	// RVA: 0x3ef8958 VA: 0x7596510958
	public Void LoginWithTW(Boolean bIsCreateNewAccount) { }
	// RVA: 0x3ef8a54 VA: 0x7596510a54
	public Void LoginWithApple(Boolean bIsCreateNewAccount) { }
	// RVA: 0x3ef8b50 VA: 0x7596510b50
	public Void MigrationCodeRequest() { }
	// RVA: 0x3ef8c4c VA: 0x7596510c4c
	public Void NewAccountLink() { }
	// RVA: 0x3ef8d48 VA: 0x7596510d48
	public Void OnPause() { }
	// RVA: 0x3ef8d4c VA: 0x7596510d4c
	public Void OnResume() { }
	// RVA: 0x3ef8d50 VA: 0x7596510d50
	public Void OpenHelpShift() { }
	// RVA: 0x3ef8d94 VA: 0x7596510d94
	public Void ShowAiHelpFAQs(String roleSever, String roleUid, String roleName, String createTime, Int32 purchase, String[] tags) { }
	// RVA: 0x3ef8f7c VA: 0x7596510f7c
	public Void OpenHelpShift(String roleUid, String roleName, String roleLevel, String roleServer, String rolePurchase, String createTime) { }
	// RVA: 0x3ef9170 VA: 0x7596511170
	public Void QuickLogin() { }
	// RVA: 0x3ef95e0 VA: 0x75965115e0
	public ResultCode SetBirth(String strBirth) { }
	// RVA: 0x3ef6dc4 VA: 0x759650edc4
	public ResultCode UnlinkSocial(LoginPlatform platform, String strEmail, String strVerificationCode) { }
	// RVA: 0x3ef96d4 VA: 0x75965116d4
	public Void UserEventUpload(String strEventName, Dictionary`2 strCallbackParameter) { }
	// RVA: 0x3ef6f04 VA: 0x759650ef04
	public ResultCode VerificationCodeReq(String strEmail) { }
	// RVA: 0x3ef97fc VA: 0x75965117fc
	public ResultCode SDKToClipboard(String cValue) { }
	// RVA: 0x3ef9804 VA: 0x7596511804
	public String GetSDKRecommendedErrorMsg(Int32 code, LanguageType type) { }
	// RVA: 0x3ef7070 VA: 0x759650f070
	public Void GetShopAgreement(ShopAgreementType type) { }
	// RVA: 0x3ef98d8 VA: 0x75965118d8
	public Void GetUnderAgeAgrement() { }
	// RVA: 0x3ef99d4 VA: 0x75965119d4
	public Boolean IOSAppleSignInAvailable() { }
	// RVA: 0x3ef99dc VA: 0x75965119dc
	public Void RebornAccount() { }
	// RVA: 0x3ef71b0 VA: 0x759650f1b0
	public ResultCode QuerySkuDetails(String[] skus) { }
	// RVA: 0x3ef9ae0 VA: 0x7596511ae0
	public String SDKGetUID() { }
	// RVA: 0x3ef761c VA: 0x759650f61c
	public Void .ctor() { }
	// RVA: 0x3ef9b30 VA: 0x7596511b30
	private static Void .cctor() { }
}
```