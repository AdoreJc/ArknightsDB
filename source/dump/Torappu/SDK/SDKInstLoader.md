# SDKInstLoader

**Namespace:** `Torappu.SDK`


## Fields

- `SDKHolder _sdkHolder`

- `GameObject m_sdkGameObj`

- `ISDKBase m_sdkInst`


## Properties

- `ISDKBase sdkInst`


## Methods

- `Void InitSDKInstIfNeeded(RemoteConfig)`

- `ISDKBase get_sdkInst()`

- `Boolean TryHookDeleteAllPlayerPrefs(Action, Action)`

- `Void ShowGlobalAgreement(Action)`

- `Void TryInjectSettings(InjectSettingOptions)`

- `Void TryInjectCashShop(InjectShopOptions)`

- `Boolean TryInjectPopupAgreement()`

- `Void TestOnlyNotifyEnterGame()`

- `Void TryFetchCashProductInfo(Action`1, Action`1)`

- `Void QuerySkuDetailsCallBack(JObject)`

- `Void TryInjectSwitchAccount(InjectSwitchAccountOptions)`

- `Void NotifyU8LoginSucceed()`

- `Void _BackToLogin()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.SDK
public class SDKInstLoader : SingletonMonoBehaviour`1, ISingletonNotAutoCreate, IHotfixable
{
	private SDKHolder _sdkHolder; // 0x18
	private GameObject m_sdkGameObj; // 0x20
	private ISDKBase m_sdkInst; // 0x28
	private static DelegateBridge __Hotfix0_InitSDKInstIfNeeded; // 0x0
	private static DelegateBridge __Hotfix0_get_sdkInst; // 0x8
	private static DelegateBridge __Hotfix0_TryHookDeleteAllPlayerPrefs; // 0x10
	private static DelegateBridge __Hotfix0_ShowGlobalAgreement; // 0x18
	private static DelegateBridge __Hotfix0_TryInjectSettings; // 0x20
	private static DelegateBridge __Hotfix0_TryInjectCashShop; // 0x28
	private static DelegateBridge __Hotfix0_TryInjectPopupAgreement; // 0x30
	private static DelegateBridge __Hotfix0_TestOnlyNotifyEnterGame; // 0x38
	private static DelegateBridge __Hotfix0_TryFetchCashProductInfo; // 0x40
	private static DelegateBridge __Hotfix0_QuerySkuDetailsCallBack; // 0x48
	private static DelegateBridge __Hotfix0_TryInjectSwitchAccount; // 0x50
	private static DelegateBridge __Hotfix0_NotifyU8LoginSucceed; // 0x58
	private static DelegateBridge __Hotfix0__BackToLogin; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public ISDKBase sdkInst { get; }

	// RVA: 0x357c660 VA: 0x7595b94660
	public Void InitSDKInstIfNeeded(RemoteConfig remoteConfig) { }
	// RVA: 0x357c8c4 VA: 0x7595b948c4
	public ISDKBase get_sdkInst() { }
	// RVA: 0x357c978 VA: 0x7595b94978
	public Boolean TryHookDeleteAllPlayerPrefs(Action deleteFunc, Action saveFunc) { }
	// RVA: 0x357caac VA: 0x7595b94aac
	public Void ShowGlobalAgreement(Action onAgree) { }
	// RVA: 0x357cc08 VA: 0x7595b94c08
	public Void TryInjectSettings(InjectSettingOptions options) { }
	// RVA: 0x357cd3c VA: 0x7595b94d3c
	public Void TryInjectCashShop(InjectShopOptions options) { }
	// RVA: 0x357ce48 VA: 0x7595b94e48
	public Boolean TryInjectPopupAgreement() { }
	// RVA: 0x357cf34 VA: 0x7595b94f34
	public Void TestOnlyNotifyEnterGame() { }
	// RVA: 0x357d01c VA: 0x7595b9501c
	public Void TryFetchCashProductInfo(Action`1 onSuc, Action`1 onFail) { }
	// RVA: 0x357a5d0 VA: 0x7595b925d0
	public Void QuerySkuDetailsCallBack(JObject msg) { }
	// RVA: 0x357d28c VA: 0x7595b9528c
	public Void TryInjectSwitchAccount(InjectSwitchAccountOptions options) { }
	// RVA: 0x357d428 VA: 0x7595b95428
	public Void NotifyU8LoginSucceed() { }
	// RVA: 0x357d530 VA: 0x7595b95530
	private Void _BackToLogin() { }
	// RVA: 0x357d5e0 VA: 0x7595b955e0
	public Void .ctor() { }
}
```