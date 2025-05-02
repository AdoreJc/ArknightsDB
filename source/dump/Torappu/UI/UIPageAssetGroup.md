# UIPageAssetGroup

**Namespace:** `Torappu.UI`


## Fields

- `Int32 m_assetGroupId`

- `Boolean m_isDisposed`


## Methods

- `T LoadAsset(String)`

- `Object LoadAsset(String)`

- `Void UnloadAsset(Object)`

- `Void Dispose()`

- `T _LoadAsset(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIPageAssetGroup : IHotfixable, IDisposable, ILoadAsset
{
	private Int32 m_assetGroupId; // 0x10
	private Boolean m_isDisposed; // 0x14
	private ListSet`1 m_loadedAssets; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_LoadAsset; // 0x8
	private static DelegateBridge __Hotfix1_LoadAsset; // 0x10
	private static DelegateBridge __Hotfix0_UnloadAsset; // 0x18
	private static DelegateBridge __Hotfix0_Dispose; // 0x20
	private static DelegateBridge __Hotfix0__LoadAsset; // 0x28


	// RVA: 0x2156f58 VA: 0x759476ef58
	public Void .ctor(Int32 assetGroupId) { }
	// RVA: 0x VA: 0x0
	public T LoadAsset(String path) { }
	// RVA: 0x21586c4 VA: 0x75947706c4
	public Object LoadAsset(String path) { }
	// RVA: 0x215875c VA: 0x759477075c
	public Void UnloadAsset(Object asset) { }
	// RVA: 0x2157448 VA: 0x759476f448
	public Void Dispose() { }
	// RVA: 0x VA: 0x0
	private T _LoadAsset(String path) { }
}
```