# HGSDKV2

**Namespace:** `HGSDK.V2`


## Fields

- `SDKOptions _sdkOptions`

- `HGSDKV2MockLoginDialog _mockLoginDialog`

- `HGSDKV2LoginDialog _loginDialog`

- `HGV2SettingViewAccount _settingAccountPrefab`

- `HGSDKV2GameLicenseDialog _licenseDialog`

- `HGSDKPluginV2 m_plugin`

- `InitRequestController m_initCtrl`

- `String <lastUsedUserName>k__BackingField`


## Properties

- `String lastUsedUserName`


## Methods

- `String get_lastUsedUserName()`

- `Void set_lastUsedUserName(String)`

- `SDKOptions GetSDKOptions()`

- `HGSDKV2MockLoginDialog GetMockLoginDialog()`

- `HGSDKV2LoginDialog GetLoginDialog()`

- `Boolean CheckIfInitedAndUpdate()`

- `Boolean IsHGChannel()`

- `GameRoleInfo GetGameRoleInfo()`

- `Void OpenAgreementSettingView()`

- `Void OpenAccountCenter()`

- `Void NotifyU8LoginSucceed()`

- `Boolean isPopupAgreement()`

- `Void TryInjectCashShop(InjectShopOptions)`

- `Void TryInjectSettings(InjectSettingOptions)`

- `Void TryShowGlobalAgreement(Action, Action)`

- `Void _InjectSettingsHGChannel(InjectSettingOptions)`

- `Void _InjectSettingsOtherChannel(InjectSettingOptions)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.V2
public class HGSDKV2 : SDKBase`1, IMsgHolderInjecter
{
	private SDKOptions _sdkOptions; // 0x18
	private HGSDKV2MockLoginDialog _mockLoginDialog; // 0x40
	private HGSDKV2LoginDialog _loginDialog; // 0x48
	private HGV2SettingViewAccount _settingAccountPrefab; // 0x50
	private HGSDKV2GameLicenseDialog _licenseDialog; // 0x58
	private HGSDKPluginV2 m_plugin; // 0x60
	private InitRequestController m_initCtrl; // 0x68
	private String <lastUsedUserName>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_lastUsedUserName; // 0x0
	private static DelegateBridge __Hotfix0_set_lastUsedUserName; // 0x8
	private static DelegateBridge __Hotfix0_GetSDKOptions; // 0x10
	private static DelegateBridge __Hotfix0_GetMockLoginDialog; // 0x18
	private static DelegateBridge __Hotfix0_GetLoginDialog; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0_CheckIfInitedAndUpdate; // 0x30
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x38
	private static DelegateBridge __Hotfix0_IsHGChannel; // 0x40
	private static DelegateBridge __Hotfix0_get_externalPlugin; // 0x48
	private static DelegateBridge __Hotfix0_GetGameRoleInfo; // 0x50
	private static DelegateBridge __Hotfix0_OpenAgreementSettingView; // 0x58
	private static DelegateBridge __Hotfix0_OpenAccountCenter; // 0x60
	private static DelegateBridge __Hotfix0_TryMigrateHGSDKAccount; // 0x68
	private static DelegateBridge __Hotfix0_NotifyU8LoginSucceed; // 0x70
	private static DelegateBridge __Hotfix0_GetRecentLoginUserFromSDK; // 0x78
	private static DelegateBridge __Hotfix0_isPopupAgreement; // 0x80
	private static DelegateBridge __Hotfix0_TryInjectCashShop; // 0x88
	private static DelegateBridge __Hotfix0_TryInjectSettings; // 0x90
	private static DelegateBridge __Hotfix0_TryShowGlobalAgreement; // 0x98
	private static DelegateBridge __Hotfix0__InjectSettingsHGChannel; // 0xa0
	private static DelegateBridge __Hotfix0__InjectSettingsOtherChannel; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	public String lastUsedUserName { get; set; }
	public override IExternalPlugin externalPlugin { get; }

	// RVA: 0x2f2e070 VA: 0x7595546070
	public String get_lastUsedUserName() { }
	// RVA: 0x2f2e0d8 VA: 0x75955460d8
	public Void set_lastUsedUserName(String value) { }
	// RVA: 0x2f2c9d4 VA: 0x75955449d4
	public SDKOptions GetSDKOptions() { }
	// RVA: 0x2f2d6c8 VA: 0x75955456c8
	public HGSDKV2MockLoginDialog GetMockLoginDialog() { }
	// RVA: 0x2f2e000 VA: 0x7595546000
	public HGSDKV2LoginDialog GetLoginDialog() { }
	// RVA: 0x2f2e524 VA: 0x7595546524
	protected override Void OnInit() { }
	// RVA: 0x2f2cc60 VA: 0x7595544c60
	public Boolean CheckIfInitedAndUpdate() { }
	// RVA: 0x2f2e8f8 VA: 0x75955468f8
	protected override Void OnDestroy() { }
	// RVA: 0x2f2e5cc VA: 0x75955465cc
	public Boolean IsHGChannel() { }
	// RVA: 0x2f2ea7c VA: 0x7595546a7c
	public override IExternalPlugin get_externalPlugin() { }
	// RVA: 0x2f2eb08 VA: 0x7595546b08
	public GameRoleInfo GetGameRoleInfo() { }
	// RVA: 0x2f2ec94 VA: 0x7595546c94
	public Void OpenAgreementSettingView() { }
	// RVA: 0x2f2ed8c VA: 0x7595546d8c
	public Void OpenAccountCenter() { }
	// RVA: 0x2f2dbb0 VA: 0x7595545bb0
	public static Void TryMigrateHGSDKAccount() { }
	// RVA: 0x2f2ee04 VA: 0x7595546e04
	public Void NotifyU8LoginSucceed() { }
	// RVA: 0x2f2dc9c VA: 0x7595545c9c
	public static String GetRecentLoginUserFromSDK() { }
	// RVA: 0x2f2eea4 VA: 0x7595546ea4
	public Boolean isPopupAgreement() { }
	// RVA: 0x2f2ef08 VA: 0x7595546f08
	public Void TryInjectCashShop(InjectShopOptions options) { }
	// RVA: 0x2f2ef80 VA: 0x7595546f80
	public Void TryInjectSettings(InjectSettingOptions options) { }
	// RVA: 0x2f2f4d4 VA: 0x75955474d4
	public Void TryShowGlobalAgreement(Action onAgree, Action backLogin) { }
	// RVA: 0x2f2f050 VA: 0x7595547050
	private Void _InjectSettingsHGChannel(InjectSettingOptions options) { }
	// RVA: 0x2f2f284 VA: 0x7595547284
	private Void _InjectSettingsOtherChannel(InjectSettingOptions options) { }
	// RVA: 0x2f2f554 VA: 0x7595547554
	public Void .ctor() { }
}
```