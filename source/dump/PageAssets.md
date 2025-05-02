# PageAssets

**Namespace:** ` `


## Fields

- `UIPage m_closure`


## Methods

- `UIPageAssetGroup AchieveAsssetGroup(Int32)`

- `T LoadAsset(String)`

- `Void UnloadAsset(Object)`

- `Void ClearAllAssets()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class PageAssets : IAssets, IHotfixable
{
	private UIPage m_closure; // 0x10
	private HashSet`1 m_loadedAssets; // 0x18
	private ListDict`2 m_assetGroups; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_inspectAssets; // 0x8
	private static DelegateBridge __Hotfix0_AchieveAsssetGroup; // 0x10
	private static DelegateBridge __Hotfix0_LoadAsset; // 0x18
	private static DelegateBridge __Hotfix0_UnloadAsset; // 0x20
	private static DelegateBridge __Hotfix0_ClearAllAssets; // 0x28

	public List`1 inspectAssets { get; }

	// RVA: 0x2156d00 VA: 0x759476ed00
	public Void .ctor(UIPage closure) { }
	// RVA: 0x2156de8 VA: 0x759476ede8
	public List`1 get_inspectAssets() { }
	// RVA: 0x2156e4c VA: 0x759476ee4c
	public UIPageAssetGroup AchieveAsssetGroup(Int32 assetGroupId) { }
	// RVA: 0x VA: 0x0
	public T LoadAsset(String path) { }
	// RVA: 0x2157034 VA: 0x759476f034
	public Void UnloadAsset(Object asset) { }
	// RVA: 0x2157168 VA: 0x759476f168
	public Void ClearAllAssets() { }
}
```