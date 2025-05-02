# GameUpdateSDKNode

**Namespace:** ` `


## Fields

- `GameUpdateSDK m_sdk`

- `NetUsagePolicy m_netUsagePolicy`

- `DownloadProgress m_downloadPrg`


## Methods

- `IEnumerator _WorkCoroutine()`

- `Void _OnDownloadStart()`

- `Void _OnDownloadProgress(Int64, Int64)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class GameUpdateSDKNode : Node
{
	private GameUpdateSDK m_sdk; // 0x20
	private NetUsagePolicy m_netUsagePolicy; // 0x28
	private DownloadProgress m_downloadPrg; // 0x30
	private static DelegateBridge __Hotfix0_get_type; // 0x0
	private static DelegateBridge __Hotfix0__WorkCoroutine; // 0x8
	private static DelegateBridge __Hotfix0__OnDownloadStart; // 0x10
	private static DelegateBridge __Hotfix0__OnDownloadProgress; // 0x18
	private static DelegateBridge __Hotfix0_Work; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override ENode type { get; }

	// RVA: 0x27c5234 VA: 0x7594ddd234
	public override ENode get_type() { }
	// RVA: 0x27c529c VA: 0x7594ddd29c
	private IEnumerator _WorkCoroutine() { }
	// RVA: 0x27c5370 VA: 0x7594ddd370
	private Void _OnDownloadStart() { }
	// RVA: 0x27c551c VA: 0x7594ddd51c
	private Void _OnDownloadProgress(Int64 curSize, Int64 totalSize) { }
	// RVA: 0x27c55d8 VA: 0x7594ddd5d8
	public override CustomYieldInstruction Work() { }
	// RVA: 0x27bf894 VA: 0x7594dd7894
	public Void .ctor() { }
}
```