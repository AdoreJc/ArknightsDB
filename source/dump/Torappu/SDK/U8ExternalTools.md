# U8ExternalTools

**Namespace:** `Torappu.SDK`


## Methods

- `Void InvokeNextFrame(Action)`

- `Void InvokeDelay(Action, Single)`

- `IEnumerator _NextFrameCoroutine(Action)`

- `IEnumerator _DelayCoroutine(Action, Single)`

- `Boolean OverrideGameVersionUpgrade()`

- `String GenerateDevInfo()`

- `String <>xLuaBaseProxy_GetSignKey()`

- `Void <>xLuaBaseProxy_SwitchAccount()`

- `Void <>xLuaBaseProxy_OnInvalidProduct(Int32)`

- `Void <>xLuaBaseProxy_OnSDKExtraInfo(String)`

- `Void <>xLuaBaseProxy_OnSDKError(SDKError)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.SDK
public class U8ExternalTools : SDKExternalTools, IHotfixable, IDevInfo
{
	private const Int32 RESPONSE_STATE_SUC; // 0x0
	private static Boolean <isSDKInited>k__BackingField; // 0x0
	private static Boolean <isSDKInstReady>k__BackingField; // 0x1
	private static InitExtConfig s_extraConfig; // 0x8
	public static Boolean s_realPayInTest; // 0x20
	private static DelegateBridge __Hotfix0_SendSDKAuthRequest; // 0x28
	private static DelegateBridge __Hotfix0_SendSDKGetCaptchaRequest; // 0x30
	private static DelegateBridge __Hotfix0_SendConfirmOrderRequest; // 0x38
	private static DelegateBridge __Hotfix0__WrappedConfirmOrderCoroutine; // 0x40
	private static DelegateBridge __Hotfix0_SendGetProductListRequest; // 0x48
	private static DelegateBridge __Hotfix0_SendUpgradeGuestRequest; // 0x50
	private static DelegateBridge __Hotfix0_SendSDKVerifyAccountRequest; // 0x58
	private static DelegateBridge __Hotfix0_GetSignKey; // 0x60
	private static DelegateBridge __Hotfix0_Log; // 0x68
	private static DelegateBridge __Hotfix0_LogWarning; // 0x70
	private static DelegateBridge __Hotfix0_LogError; // 0x78
	private static DelegateBridge __Hotfix0_SwitchAccount; // 0x80
	private static DelegateBridge __Hotfix0_OnInvalidProduct; // 0x88
	private static DelegateBridge __Hotfix0_OnSDKExtraInfo; // 0x90
	private static DelegateBridge __Hotfix0_OnSDKError; // 0x98
	private static DelegateBridge __Hotfix0_InvokeNextFrame; // 0xa0
	private static DelegateBridge __Hotfix0_InvokeDelay; // 0xa8
	private static DelegateBridge __Hotfix0__NextFrameCoroutine; // 0xb0
	private static DelegateBridge __Hotfix0__DelayCoroutine; // 0xb8
	private static DelegateBridge __Hotfix0__AuthUrl; // 0xc0
	private static DelegateBridge __Hotfix0__CaptchaUrl; // 0xc8
	private static DelegateBridge __Hotfix0__GetProductListUrl; // 0xd0
	private static DelegateBridge __Hotfix0__CreateOrderUrl; // 0xd8
	private static DelegateBridge __Hotfix0__ConfirmOrderUrl; // 0xe0
	private static DelegateBridge __Hotfix0__UpdateGuestUserUrl; // 0xe8
	private static DelegateBridge __Hotfix0__VerifyAccountUrl; // 0xf0
	private static DelegateBridge __Hotfix0__U8Url; // 0xf8
	private static DelegateBridge __Hotfix0__ConfirmOrderCoroutine; // 0x100
	private static DelegateBridge __Hotfix0__HandleResponseFromU8; // 0x108
	private static DelegateBridge __Hotfix0_get_isSDKInited; // 0x110
	private static DelegateBridge __Hotfix0_set_isSDKInited; // 0x118
	private static DelegateBridge __Hotfix0_get_isSDKInstReady; // 0x120
	private static DelegateBridge __Hotfix0_set_isSDKInstReady; // 0x128
	private static DelegateBridge __Hotfix0_InitSystemsWithExtConfig; // 0x130
	private static DelegateBridge __Hotfix0_InitSDKWhenRemoteConfigReady; // 0x138
	private static DelegateBridge __Hotfix0__HandleInitExtConfigs; // 0x140
	private static DelegateBridge __Hotfix0_IsRealPayOnAndroid; // 0x148
	private static DelegateBridge __Hotfix0_IsRealPayOnIOS; // 0x150
	private static DelegateBridge __Hotfix0_IsRealPayInTest; // 0x158
	private static DelegateBridge __Hotfix0_GetU8DeviceID; // 0x160
	private static DelegateBridge __Hotfix0_GetDeviceIDs; // 0x168
	private static DelegateBridge __Hotfix0_GetPlatformKey; // 0x170
	private static DelegateBridge __Hotfix0_OverrideGameVersionUpgrade; // 0x178
	private static DelegateBridge __Hotfix0_StartSceneToLogout; // 0x180
	private static DelegateBridge __Hotfix0_CreateCaptchaHandler; // 0x188
	private static DelegateBridge __Hotfix0_POSTImplementation; // 0x190
	private static DelegateBridge __Hotfix0_U8RootUrl; // 0x198
	private static DelegateBridge __Hotfix0_GetErrorMessage; // 0x1a0
	private static DelegateBridge __Hotfix0_CreateMockLoginToken; // 0x1a8
	private static DelegateBridge __Hotfix0_GenerateDevInfo; // 0x1b0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x1b8

	public static Boolean isSDKInited { get; set; }
	public static Boolean isSDKInstReady { get; set; }

	// RVA: 0x357ee14 VA: 0x7595b96e14
	protected override SDKPromise`1 SendSDKAuthRequest(String paramStr) { }
	// RVA: 0x357f09c VA: 0x7595b9709c
	protected override SDKPromise`1 SendSDKGetCaptchaRequest(String paramStr) { }
	// RVA: 0x357f324 VA: 0x7595b97324
	protected override SDKPromise`1 SendConfirmOrderRequest(String paramStr) { }
	// RVA: 0x357f448 VA: 0x7595b97448
	private static IEnumerator _WrappedConfirmOrderCoroutine(SDKPromise`1 promise, String paramStr) { }
	// RVA: 0x357f528 VA: 0x7595b97528
	protected override SDKPromise`1 SendGetProductListRequest(String paramStr) { }
	// RVA: 0x357f7a4 VA: 0x7595b977a4
	protected override SDKPromise`1 SendUpgradeGuestRequest(String paramStr) { }
	// RVA: 0x357fa28 VA: 0x7595b97a28
	protected override SDKPromise`1 SendSDKVerifyAccountRequest(String paramStr) { }
	// RVA: 0x357fcac VA: 0x7595b97cac
	protected override String GetSignKey() { }
	// RVA: 0x357fd50 VA: 0x7595b97d50
	protected override Void Log(String content) { }
	// RVA: 0x357fdd8 VA: 0x7595b97dd8
	protected override Void LogWarning(String content) { }
	// RVA: 0x357fe60 VA: 0x7595b97e60
	protected override Void LogError(String content) { }
	// RVA: 0x357ff14 VA: 0x7595b97f14
	public override Void SwitchAccount() { }
	// RVA: 0x357ff88 VA: 0x7595b97f88
	public override Void OnInvalidProduct(Int32 storeId) { }
	// RVA: 0x35800b0 VA: 0x7595b980b0
	public override Void OnSDKExtraInfo(String jsonData) { }
	// RVA: 0x35801ac VA: 0x7595b981ac
	public override Void OnSDKError(SDKError error) { }
	// RVA: 0x3580398 VA: 0x7595b98398
	protected Void InvokeNextFrame(Action action) { }
	// RVA: 0x3580554 VA: 0x7595b98554
	protected Void InvokeDelay(Action action, Single delay) { }
	// RVA: 0x3580484 VA: 0x7595b98484
	private IEnumerator _NextFrameCoroutine(Action action) { }
	// RVA: 0x3580668 VA: 0x7595b98668
	private IEnumerator _DelayCoroutine(Action action, Single delay) { }
	// RVA: 0x357f008 VA: 0x7595b97008
	private static String _AuthUrl() { }
	// RVA: 0x357f290 VA: 0x7595b97290
	private static String _CaptchaUrl() { }
	// RVA: 0x357f710 VA: 0x7595b97710
	private static String _GetProductListUrl() { }
	// RVA: 0x3580874 VA: 0x7595b98874
	private static String _CreateOrderUrl() { }
	// RVA: 0x3580908 VA: 0x7595b98908
	private static String _ConfirmOrderUrl() { }
	// RVA: 0x357f994 VA: 0x7595b97994
	private static String _UpdateGuestUserUrl() { }
	// RVA: 0x357fc18 VA: 0x7595b97c18
	private static String _VerifyAccountUrl() { }
	// RVA: 0x3580750 VA: 0x7595b98750
	private static String _U8Url(String routeUrl) { }
	// RVA: 0x358099c VA: 0x7595b9899c
	private static IEnumerator _ConfirmOrderCoroutine(SDKPromise`1 promise, String paramStr) { }
	// RVA: 0x VA: 0x0
	private static DataType _HandleResponseFromU8(String responseText, out String errorCode) { }
	// RVA: 0x3580a7c VA: 0x7595b98a7c
	public static Boolean get_isSDKInited() { }
	// RVA: 0x3580b04 VA: 0x7595b98b04
	private static Void set_isSDKInited(Boolean value) { }
	// RVA: 0x3580b98 VA: 0x7595b98b98
	public static Boolean get_isSDKInstReady() { }
	// RVA: 0x3580c20 VA: 0x7595b98c20
	private static Void set_isSDKInstReady(Boolean value) { }
	// RVA: 0x3580cb4 VA: 0x7595b98cb4
	public static Void InitSystemsWithExtConfig() { }
	// RVA: 0x35811d0 VA: 0x7595b991d0
	public static IEnumerator InitSDKWhenRemoteConfigReady(RemoteConfig config) { }
	// RVA: 0x3580f7c VA: 0x7595b98f7c
	private static InitExtConfig _HandleInitExtConfigs(String extConfigStr) { }
	// RVA: 0x358128c VA: 0x7595b9928c
	public static Boolean IsRealPayOnAndroid() { }
	// RVA: 0x35812fc VA: 0x7595b992fc
	public static Boolean IsRealPayOnIOS() { }
	// RVA: 0x3581368 VA: 0x7595b99368
	public static Boolean IsRealPayInTest() { }
	// RVA: 0x357e1e4 VA: 0x7595b961e4
	public static String GetU8DeviceID() { }
	// RVA: 0x35813f0 VA: 0x7595b993f0
	public override Dictionary`2 GetDeviceIDs() { }
	// RVA: 0x358162c VA: 0x7595b9962c
	protected override Int32 GetPlatformKey() { }
	// RVA: 0x35816a0 VA: 0x7595b996a0
	public Boolean OverrideGameVersionUpgrade() { }
	// RVA: 0x357ab74 VA: 0x7595b92b74
	public static Void StartSceneToLogout() { }
	// RVA: 0x35818d8 VA: 0x7595b998d8
	protected override SDKCaptchaHandler CreateCaptchaHandler() { }
	// RVA: 0x358194c VA: 0x7595b9994c
	protected override Void POSTImplementation(POSTRequest request, Action`1 callback) { }
	// RVA: 0x3581a70 VA: 0x7595b99a70
	protected override String U8RootUrl() { }
	// RVA: 0x3581b24 VA: 0x7595b99b24
	protected override String GetErrorMessage(ErrMsgMeta meta) { }
	// RVA: 0x3581c3c VA: 0x7595b99c3c
	public static U8MockLogin CreateMockLoginToken(String uid) { }
	// RVA: 0x3581eec VA: 0x7595b99eec
	public String GenerateDevInfo() { }
	// RVA: 0x3582104 VA: 0x7595b9a104
	public Void .ctor() { }
	// RVA: 0x35821a8 VA: 0x7595b9a1a8
	private static Void .cctor() { }
	// RVA: 0x3582254 VA: 0x7595b9a254
	private String <>xLuaBaseProxy_GetSignKey() { }
	// RVA: 0x358225c VA: 0x7595b9a25c
	private Void <>xLuaBaseProxy_SwitchAccount() { }
	// RVA: 0x3582264 VA: 0x7595b9a264
	private Void <>xLuaBaseProxy_OnInvalidProduct(Int32 P0) { }
	// RVA: 0x358226c VA: 0x7595b9a26c
	private Void <>xLuaBaseProxy_OnSDKExtraInfo(String P0) { }
	// RVA: 0x3582274 VA: 0x7595b9a274
	private Void <>xLuaBaseProxy_OnSDKError(SDKError P0) { }
}
```