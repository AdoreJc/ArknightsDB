# YostarSDK

**Namespace:** `YostarSDK`


## Fields

- `Options _options`

- `YostarSDKLoginPage _loginPrefab`

- `YostarSDKPayPage _payPrefab`

- `YostarSDKPopupPage _popupPrefab`

- `YostarSDKAgreement _agreementPrefab`

- `YostarSettingViewAccount _settingAccount`

- `YostarSettingViewOthers _settingOthers`

- `SDKPayCashShopPlugin _cashShopPlugin`

- `SDKOptions _sdkOptions`

- `TextAsset _stringMap`

- `StringMap m_strMap`

- `Regex m_mailRegex`

- `AccountInfo currentAccount`

- `Boolean <isPopupAgreement>k__BackingField`

- `Boolean inited`

- `U8Plugin m_plugin`

- `UIManager m_uiManager`


## Properties

- `Boolean isPopupAgreement`

- `SDKOptions sdkOptions`

- `Camera sdkCamera`


## Methods

- `Boolean get_isPopupAgreement()`

- `Void set_isPopupAgreement(Boolean)`

- `SDKOptions get_sdkOptions()`

- `Camera get_sdkCamera()`

- `Void OnApplicationPause(Boolean)`

- `Void Login(Action`1, Action)`

- `Void Pay(U8PayParams, Action`1, Action`1)`

- `String GetString(String)`

- `Boolean CheckIfEmailValid(String)`

- `Void SetAccountByInit(InitRet)`

- `Void SetAccountByLogin(LoginRet)`

- `Void SetAccountByLinkRet(LinkRet)`

- `Void SetAccountByUnlinkRet(UnLinkRet)`

- `Void SetAccountByBirth(BirthSetRet)`

- `Void SetAccountByMigrationCode(MigrationCodeRet)`

- `Void MarkAccountDeleted()`

- `Boolean ShowAgreement(AgreementOptions)`

- `Void TryInjectSettings(InjectSettingOptions)`

- `Void TryInjectCashShop(InjectShopOptions)`

- `Void OpenBindYostarAccountView(Action)`

- `Void OpenUnbindYostarAccountView(Action)`

- `Void OpenAccountWealthView(Action)`

- `Void OpenRequestMigrationCodeView(Action)`

- `Void OpenShopAgreement(ShopAgreementType)`

- `Boolean CheckIfAccountSync()`

- `Boolean CheckIfAccountSyncOrHalt()`

- `Boolean CheckIfTokenValid(ResultCode)`

- `Boolean CheckIfTokenValidOrHalt(ResultCode)`

- `Void TryFetchCashProductInfo(Action`1, Action`1)`

- `IEnumerator _BackToLoginNextFrame()`

- `Void _GetAgreementCallback(AgreementOptions, GetAgreementRet)`

- `Void _OnAgreementRejectedOrFailed()`

- `Void TryShowGlobalAgreement(Action, Action)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK
public class YostarSDK : SDKBase`1, IHotfixable, IMsgHolderInjecter
{
	private Options _options; // 0x18
	private YostarSDKLoginPage _loginPrefab; // 0x48
	private YostarSDKPayPage _payPrefab; // 0x50
	private YostarSDKPopupPage _popupPrefab; // 0x58
	private YostarSDKAgreement _agreementPrefab; // 0x60
	private YostarSettingViewAccount _settingAccount; // 0x68
	private YostarSettingViewOthers _settingOthers; // 0x70
	private SDKPayCashShopPlugin _cashShopPlugin; // 0x78
	private SDKOptions _sdkOptions; // 0x80
	private TextAsset _stringMap; // 0xb0
	private StringMap m_strMap; // 0xb8
	private Regex m_mailRegex; // 0xc0
	public AccountInfo currentAccount; // 0xc8
	private Boolean <isPopupAgreement>k__BackingField; // 0x120
	public Boolean inited; // 0x121
	private U8Plugin m_plugin; // 0x128
	private UIManager m_uiManager; // 0x130
	private static DelegateBridge __Hotfix0_get_isPopupAgreement; // 0x0
	private static DelegateBridge __Hotfix0_set_isPopupAgreement; // 0x8
	private static DelegateBridge __Hotfix0_get_sdkOptions; // 0x10
	private static DelegateBridge __Hotfix0_get_sdkCamera; // 0x18
	private static DelegateBridge __Hotfix0_get_externalPlugin; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0_Start; // 0x30
	private static DelegateBridge __Hotfix0_OnApplicationPause; // 0x38
	private static DelegateBridge __Hotfix0_Login; // 0x40
	private static DelegateBridge __Hotfix0_Pay; // 0x48
	private static DelegateBridge __Hotfix0_Alert; // 0x50
	private static DelegateBridge __Hotfix0_Toast; // 0x58
	private static DelegateBridge __Hotfix0_ShowReentrantLoading; // 0x60
	private static DelegateBridge __Hotfix0_HideReentrantLoading; // 0x68
	private static DelegateBridge __Hotfix0_JudgeDialog; // 0x70
	private static DelegateBridge __Hotfix0_BackToLogin; // 0x78
	private static DelegateBridge __Hotfix0_ExtractAlertByCode; // 0x80
	private static DelegateBridge __Hotfix0_RaiseError; // 0x88
	private static DelegateBridge __Hotfix0_RaiseErrorForLink; // 0x90
	private static DelegateBridge __Hotfix0_GetString; // 0x98
	private static DelegateBridge __Hotfix0_ShotBlurImage; // 0xa0
	private static DelegateBridge __Hotfix0_CheckIfEmailValid; // 0xa8
	private static DelegateBridge __Hotfix0_IsGoogleBannedByApple; // 0xb0
	private static DelegateBridge __Hotfix0_IsThirdPartyBannedByApple; // 0xb8
	private static DelegateBridge __Hotfix0_SetAccountByInit; // 0xc0
	private static DelegateBridge __Hotfix0_SetAccountByLogin; // 0xc8
	private static DelegateBridge __Hotfix0_SetAccountByLinkRet; // 0xd0
	private static DelegateBridge __Hotfix0_SetAccountByUnlinkRet; // 0xd8
	private static DelegateBridge __Hotfix0_SetAccountByBirth; // 0xe0
	private static DelegateBridge __Hotfix0_SetAccountByMigrationCode; // 0xe8
	private static DelegateBridge __Hotfix0_MarkAccountDeleted; // 0xf0
	private static DelegateBridge __Hotfix0_ShowAgreement; // 0xf8
	private static DelegateBridge __Hotfix0_TryInjectSettings; // 0x100
	private static DelegateBridge __Hotfix0_TryInjectCashShop; // 0x108
	private static DelegateBridge __Hotfix0_OpenBindYostarAccountView; // 0x110
	private static DelegateBridge __Hotfix0_OpenUnbindYostarAccountView; // 0x118
	private static DelegateBridge __Hotfix0_OpenAccountWealthView; // 0x120
	private static DelegateBridge __Hotfix0_OpenRequestMigrationCodeView; // 0x128
	private static DelegateBridge __Hotfix0_OpenShopAgreement; // 0x130
	private static DelegateBridge __Hotfix0_TryRebornAccount; // 0x138
	private static DelegateBridge __Hotfix0_CheckIfAccountSync; // 0x140
	private static DelegateBridge __Hotfix0_CheckIfAccountSyncOrHalt; // 0x148
	private static DelegateBridge __Hotfix0_CheckIfTokenValid; // 0x150
	private static DelegateBridge __Hotfix0_CheckIfTokenValidOrHalt; // 0x158
	private static DelegateBridge __Hotfix0_TryFetchCashProductInfo; // 0x160
	private static DelegateBridge __Hotfix0__BackToLoginNextFrame; // 0x168
	private static DelegateBridge __Hotfix0__HookBeforeFetchProductCashInfo; // 0x170
	private static DelegateBridge __Hotfix0__GetCurLangType; // 0x178
	private static DelegateBridge __Hotfix0__GetAgreementCallback; // 0x180
	private static DelegateBridge __Hotfix0__OnAgreementRejectedOrFailed; // 0x188
	private static DelegateBridge __Hotfix0__ConvertTsToDate; // 0x190
	private static DelegateBridge __Hotfix0__CallRebornAccount; // 0x198
	private static DelegateBridge __Hotfix0_Torappu.SDK.IMsgHolderInjecter.isPopupAgreement; // 0x1a0
	private static DelegateBridge __Hotfix0_TryShowGlobalAgreement; // 0x1a8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x1b0

	public Boolean isPopupAgreement { get; set; }
	public SDKOptions sdkOptions { get; }
	protected Camera sdkCamera { get; }
	public override IExternalPlugin externalPlugin { get; }

	// RVA: 0x1b3ee14 VA: 0x7594156e14
	public Boolean get_isPopupAgreement() { }
	// RVA: 0x1b3ee7c VA: 0x7594156e7c
	private Void set_isPopupAgreement(Boolean value) { }
	// RVA: 0x1b3eefc VA: 0x7594156efc
	public SDKOptions get_sdkOptions() { }
	// RVA: 0x1b3ef8c VA: 0x7594156f8c
	protected Camera get_sdkCamera() { }
	// RVA: 0x1b3eff4 VA: 0x7594156ff4
	public override IExternalPlugin get_externalPlugin() { }
	// RVA: 0x1b3f0d8 VA: 0x75941570d8
	protected override Void OnInit() { }
	// RVA: 0x1b3f1d4 VA: 0x75941571d4
	protected virtual Void Start() { }
	// RVA: 0x1b3f248 VA: 0x7594157248
	private Void OnApplicationPause(Boolean pause) { }
	// RVA: 0x1b3b97c VA: 0x759415397c
	public Void Login(Action`1 onSuc, Action onFail) { }
	// RVA: 0x1b3bc50 VA: 0x7594153c50
	public Void Pay(U8PayParams payParams, Action`1 onSuc, Action`1 onFail) { }
	// RVA: 0x1b3f31c VA: 0x759415731c
	public static Void Alert(String content, Action onConfirm) { }
	// RVA: 0x1b3f3a8 VA: 0x75941573a8
	public static Void Toast(String content) { }
	// RVA: 0x1b3f41c VA: 0x759415741c
	public static Void ShowReentrantLoading() { }
	// RVA: 0x1b3f478 VA: 0x7594157478
	public static Void HideReentrantLoading() { }
	// RVA: 0x1b3f4d4 VA: 0x75941574d4
	public static Void JudgeDialog(String msg, Action onPositive, Action onNegative) { }
	// RVA: 0x1b3f650 VA: 0x7594157650
	public static Void BackToLogin() { }
	// RVA: 0x1b3f6f8 VA: 0x75941576f8
	public static String ExtractAlertByCode(ResultCode code) { }
	// RVA: 0x1b3f86c VA: 0x759415786c
	public static Void RaiseError(AlertOptions options) { }
	// RVA: 0x1b3f934 VA: 0x7594157934
	public static Void RaiseErrorForLink(LinkRet ret, Action nextStep) { }
	// RVA: 0x1b3ed2c VA: 0x7594156d2c
	public String GetString(String key) { }
	// RVA: 0x1b3fc28 VA: 0x7594157c28
	public static Void ShotBlurImage(Image image) { }
	// RVA: 0x1b3fc94 VA: 0x7594157c94
	public Boolean CheckIfEmailValid(String emailAddr) { }
	// RVA: 0x1b3fda0 VA: 0x7594157da0
	public static Boolean IsGoogleBannedByApple() { }
	// RVA: 0x1b3fdfc VA: 0x7594157dfc
	public static Boolean IsThirdPartyBannedByApple() { }
	// RVA: 0x1b3fe58 VA: 0x7594157e58
	public Void SetAccountByInit(InitRet ret) { }
	// RVA: 0x1b4002c VA: 0x759415802c
	public Void SetAccountByLogin(LoginRet ret) { }
	// RVA: 0x1b40260 VA: 0x7594158260
	public Void SetAccountByLinkRet(LinkRet ret) { }
	// RVA: 0x1b4040c VA: 0x759415840c
	public Void SetAccountByUnlinkRet(UnLinkRet ret) { }
	// RVA: 0x1b40614 VA: 0x7594158614
	public Void SetAccountByBirth(BirthSetRet ret) { }
	// RVA: 0x1b40748 VA: 0x7594158748
	public Void SetAccountByMigrationCode(MigrationCodeRet ret) { }
	// RVA: 0x1b4087c VA: 0x759415887c
	public Void MarkAccountDeleted() { }
	// RVA: 0x1b40920 VA: 0x7594158920
	public Boolean ShowAgreement(AgreementOptions options) { }
	// RVA: 0x1b40ab8 VA: 0x7594158ab8
	public Void TryInjectSettings(InjectSettingOptions options) { }
	// RVA: 0x1b40d0c VA: 0x7594158d0c
	public Void TryInjectCashShop(InjectShopOptions options) { }
	// RVA: 0x1b41024 VA: 0x7594159024
	public Void OpenBindYostarAccountView(Action onPageClosed) { }
	// RVA: 0x1b4115c VA: 0x759415915c
	public Void OpenUnbindYostarAccountView(Action onPageClosed) { }
	// RVA: 0x1b41294 VA: 0x7594159294
	public Void OpenAccountWealthView(Action onPageClosed) { }
	// RVA: 0x1b413cc VA: 0x75941593cc
	public Void OpenRequestMigrationCodeView(Action onPageClosed) { }
	// RVA: 0x1b41504 VA: 0x7594159504
	public Void OpenShopAgreement(ShopAgreementType type) { }
	// RVA: 0x1b41630 VA: 0x7594159630
	public static Void TryRebornAccount(LoginRet ret, Action nextStep) { }
	// RVA: 0x1b41ce0 VA: 0x7594159ce0
	public Boolean CheckIfAccountSync() { }
	// RVA: 0x1b41dbc VA: 0x7594159dbc
	public Boolean CheckIfAccountSyncOrHalt() { }
	// RVA: 0x1b41f0c VA: 0x7594159f0c
	public Boolean CheckIfTokenValid(ResultCode code) { }
	// RVA: 0x1b41f94 VA: 0x7594159f94
	public Boolean CheckIfTokenValidOrHalt(ResultCode code) { }
	// RVA: 0x1b420dc VA: 0x759415a0dc
	public Void TryFetchCashProductInfo(Action`1 onSuc, Action`1 onFail) { }
	// RVA: 0x1b42040 VA: 0x759415a040
	private IEnumerator _BackToLoginNextFrame() { }
	// RVA: 0x1b4246c VA: 0x759415a46c
	private static Void _HookBeforeFetchProductCashInfo(List`1 productList) { }
	// RVA: 0x1b3f798 VA: 0x7594157798
	private static LanguageType _GetCurLangType() { }
	// RVA: 0x1b425b4 VA: 0x759415a5b4
	private Void _GetAgreementCallback(AgreementOptions options, GetAgreementRet ret) { }
	// RVA: 0x1b427c8 VA: 0x759415a7c8
	private Void _OnAgreementRejectedOrFailed() { }
	// RVA: 0x1b41868 VA: 0x7594159868
	private static String _ConvertTsToDate(String tsStr) { }
	// RVA: 0x1b4282c VA: 0x759415a82c
	private static Void _CallRebornAccount(Action onSuc) { }
	// RVA: 0x1b42960 VA: 0x759415a960
	private Boolean Torappu.SDK.IMsgHolderInjecter.isPopupAgreement() { }
	// RVA: 0x1b429c8 VA: 0x759415a9c8
	public Void TryShowGlobalAgreement(Action onAgree, Action backLogin) { }
	// RVA: 0x1b42b64 VA: 0x759415ab64
	public Void .ctor() { }
}
```