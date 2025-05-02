# NetUsagePolicy

**Namespace:** ` `


## Fields

- `CarrierDownloadCache m_mobileDataCache`

- `NetworkReachability m_lastNetworkState`

- `Boolean m_lastExplictAllowed`

- `Options m_options`


## Methods

- `Void CheckIfAllowDownload(Int64, Action, Action)`

- `Boolean AllowMobileDataInLastCheck()`

- `Boolean ExplictAllowedInLastCheck()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class NetUsagePolicy
{
	private CarrierDownloadCache m_mobileDataCache; // 0x10
	private NetworkReachability m_lastNetworkState; // 0x20
	private Boolean m_lastExplictAllowed; // 0x24
	private Options m_options; // 0x28


	// RVA: 0x373c7fc VA: 0x7595d547fc
	public Void .ctor(Options options) { }
	// RVA: 0x373c888 VA: 0x7595d54888
	public Void CheckIfAllowDownload(Int64 downloadSize, Action onAllowed, Action onRejected) { }
	// RVA: 0x373cae0 VA: 0x7595d54ae0
	public Boolean AllowMobileDataInLastCheck() { }
	// RVA: 0x373cb04 VA: 0x7595d54b04
	public Boolean ExplictAllowedInLastCheck() { }
}
```