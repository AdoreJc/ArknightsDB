# NetworkRouter

**Namespace:** `Torappu.Network`


## Fields

- `String m_networkConfigVersion`


## Properties

- `String networkConfigVersion`


## Methods

- `String get_networkConfigVersion()`

- `Void ConfirmNetworkConfigVersion(String)`

- `ConfigHandler FetchConfig()`

- `WebHttpResult _SendFetchConfigService(Action`1, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Network
public class NetworkRouter : Singleton`1
{
	private String m_networkConfigVersion; // 0x10
	private static DelegateBridge __Hotfix0_get_networkConfigVersion; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_ConfirmNetworkConfigVersion; // 0x10
	private static DelegateBridge __Hotfix0_FetchConfig; // 0x18
	private static DelegateBridge __Hotfix0__GetCurrentConfig; // 0x20
	private static DelegateBridge __Hotfix0__SendFetchConfigService; // 0x28
	private static DelegateBridge __Hotfix0__DeserializeRouterContent; // 0x30

	public String networkConfigVersion { get; }

	// RVA: 0x3586714 VA: 0x7595b9e714
	public String get_networkConfigVersion() { }
	// RVA: 0x358677c VA: 0x7595b9e77c
	private Void .ctor() { }
	// RVA: 0x3586838 VA: 0x7595b9e838
	public Void ConfirmNetworkConfigVersion(String networkConfigVer) { }
	// RVA: 0x35868bc VA: 0x7595b9e8bc
	public ConfigHandler FetchConfig() { }
	// RVA: 0x3586c28 VA: 0x7595b9ec28
	private static Config _GetCurrentConfig(Content content) { }
	// RVA: 0x3586a68 VA: 0x7595b9ea68
	private WebHttpResult _SendFetchConfigService(Action`1 onSuc, Action`1 onFail) { }
	// RVA: 0x3586fdc VA: 0x7595b9efdc
	private static Content _DeserializeRouterContent(String responseText) { }
}
```