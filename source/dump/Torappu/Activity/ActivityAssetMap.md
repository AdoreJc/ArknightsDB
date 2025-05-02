# ActivityAssetMap

**Namespace:** `Torappu.Activity`


## Fields

- `InternalData m_data`

- `Boolean m_isLoaded`


## Methods

- `Boolean _Load()`

- `Void _InitIfNot()`

- `Void ForceReload()`

- `String GetAssetResPath(String, String)`

- `Void LoadAssetResPaths(String, Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivityAssetMap : Singleton`1, IHotfixable
{
	private InternalData m_data; // 0x10
	private Boolean m_isLoaded; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__Load; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_ForceReload; // 0x18
	private static DelegateBridge __Hotfix0_GetAssetResPath; // 0x20
	private static DelegateBridge __Hotfix0_LoadAssetResPaths; // 0x28


	// RVA: 0x30bec10 VA: 0x75956d6c10
	private Void .ctor() { }
	// RVA: 0x30bed6c VA: 0x75956d6d6c
	private Boolean _Load() { }
	// RVA: 0x30bf190 VA: 0x75956d7190
	private Void _InitIfNot() { }
	// RVA: 0x30bf20c VA: 0x75956d720c
	public Void ForceReload() { }
	// RVA: 0x30bf278 VA: 0x75956d7278
	public String GetAssetResPath(String aspect, String assetId) { }
	// RVA: 0x30bf3c0 VA: 0x75956d73c0
	public Void LoadAssetResPaths(String aspect, Dictionary`2 resPaths) { }
}
```