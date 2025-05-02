# AutoUnloadAssets

**Namespace:** `Torappu.UI`


## Fields

- `IHost m_host`

- `ILoadAsset m_assets`


## Methods

- `T LoadAsset(String, out)`

- `Object LoadAsset(String, out)`

- `Void UnloadAsset(Object)`

- `Void UnloadUnusedAssets()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class AutoUnloadAssets
{
	private IHost m_host; // 0x10
	private ILoadAsset m_assets; // 0x18
	private Dictionary`2 m_loadedAssets; // 0x20
	private LocalGenericPool`1 m_infoPool; // 0x28
	private HashSet`1 m_usedAssetsCache; // 0x30


	// RVA: 0x21c5174 VA: 0x75947dd174
	private Void .ctor() { }
	// RVA: 0x21c529c VA: 0x75947dd29c
	public static AutoUnloadAssets Create(ILoadAsset assetGroup, IHost host) { }
	// RVA: 0x VA: 0x0
	public T LoadAsset(String path, out Boolean isNewlyLoaded) { }
	// RVA: 0x21c5324 VA: 0x75947dd324
	public Object LoadAsset(String path, out Boolean isNewlyLoaded) { }
	// RVA: 0x21c5384 VA: 0x75947dd384
	public Void UnloadAsset(Object asset) { }
	// RVA: 0x21c5648 VA: 0x75947dd648
	public Void UnloadUnusedAssets() { }
}
```