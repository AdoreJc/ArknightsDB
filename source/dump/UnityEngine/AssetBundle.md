# AssetBundle

**Namespace:** `UnityEngine`


## Properties

- `Boolean isStreamedSceneAssetBundle`


## Methods

- `Boolean get_isStreamedSceneAssetBundle()`

- `Object LoadAsset(String)`

- `T LoadAsset(String)`

- `Object LoadAsset(String, Type)`

- `Object LoadAsset_Internal(String, Type)`

- `AssetBundleRequest LoadAssetAsync(String)`

- `AssetBundleRequest LoadAssetAsync(String)`

- `AssetBundleRequest LoadAssetAsync(String, Type)`

- `AssetBundleRequest LoadAssetAsync_Internal(String, Type)`

- `Void Unload(Boolean)`


## Dump
```C#
// Dll : UnityEngine.AssetBundleModule.dll
// Namespace : UnityEngine
public class AssetBundle : Object
{

	public Boolean isStreamedSceneAssetBundle { get; }

	// RVA: 0x684c930 VA: 0x7598e64930
	private Void .ctor() { }
	// RVA: 0x684c988 VA: 0x7598e64988
	internal static AssetBundle LoadFromFile_Internal(String path, UInt32 crc, UInt64 offset) { }
	// RVA: 0x684c9dc VA: 0x7598e649dc
	public static AssetBundle LoadFromFile(String path) { }
	// RVA: 0x684ca20 VA: 0x7598e64a20
	internal static AssetBundleCreateRequest LoadFromMemoryAsync_Internal(Byte[] binary, UInt32 crc) { }
	// RVA: 0x684ca64 VA: 0x7598e64a64
	public static AssetBundleCreateRequest LoadFromMemoryAsync(Byte[] binary) { }
	// RVA: 0x684caa4 VA: 0x7598e64aa4
	public Boolean get_isStreamedSceneAssetBundle() { }
	// RVA: 0x684cae0 VA: 0x7598e64ae0
	public Object LoadAsset(String name) { }
	// RVA: 0x VA: 0x0
	public T LoadAsset(String name) { }
	// RVA: 0x684cb6c VA: 0x7598e64b6c
	public Object LoadAsset(String name, Type type) { }
	// RVA: 0x684cc78 VA: 0x7598e64c78
	private Object LoadAsset_Internal(String name, Type type) { }
	// RVA: 0x684cccc VA: 0x7598e64ccc
	public AssetBundleRequest LoadAssetAsync(String name) { }
	// RVA: 0x VA: 0x0
	public AssetBundleRequest LoadAssetAsync(String name) { }
	// RVA: 0x684cd58 VA: 0x7598e64d58
	public AssetBundleRequest LoadAssetAsync(String name, Type type) { }
	// RVA: 0x684ceb8 VA: 0x7598e64eb8
	public Object[] LoadAssetWithSubAssets(String name) { }
	// RVA: 0x VA: 0x0
	internal static T[] ConvertObjects(Object[] rawObjects) { }
	// RVA: 0x VA: 0x0
	public T[] LoadAssetWithSubAssets(String name) { }
	// RVA: 0x684cf44 VA: 0x7598e64f44
	public Object[] LoadAssetWithSubAssets(String name, Type type) { }
	// RVA: 0x684d0a4 VA: 0x7598e650a4
	public Object[] LoadAllAssets() { }
	// RVA: 0x684d128 VA: 0x7598e65128
	public Object[] LoadAllAssets(Type type) { }
	// RVA: 0x684ce64 VA: 0x7598e64e64
	private AssetBundleRequest LoadAssetAsync_Internal(String name, Type type) { }
	// RVA: 0x684d1f4 VA: 0x7598e651f4
	public Void Unload(Boolean unloadAllLoadedObjects) { }
	// RVA: 0x684d238 VA: 0x7598e65238
	public String[] GetAllScenePaths() { }
	// RVA: 0x684d050 VA: 0x7598e65050
	internal Object[] LoadAssetWithSubAssets_Internal(String name, Type type) { }
}
```