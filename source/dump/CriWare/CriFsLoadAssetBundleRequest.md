# CriFsLoadAssetBundleRequest

**Namespace:** `CriWare`


## Fields

- `String <path>k__BackingField`

- `AssetBundle <assetBundle>k__BackingField`

- `CriFsLoadFileRequest loadFileReq`

- `AssetBundleCreateRequest assetBundleReq`


## Properties

- `String path`

- `AssetBundle assetBundle`


## Methods

- `String get_path()`

- `Void set_path(String)`

- `AssetBundle get_assetBundle()`

- `Void set_assetBundle(AssetBundle)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriFsLoadAssetBundleRequest : CriFsRequest
{
	private String <path>k__BackingField; // 0x40
	private AssetBundle <assetBundle>k__BackingField; // 0x48
	private CriFsLoadFileRequest loadFileReq; // 0x50
	private AssetBundleCreateRequest assetBundleReq; // 0x58

	public String path { get; set; }
	public AssetBundle assetBundle { get; set; }

	// RVA: 0x4140150 VA: 0x7596758150
	public String get_path() { }
	// RVA: 0x4140158 VA: 0x7596758158
	private Void set_path(String value) { }
	// RVA: 0x4140160 VA: 0x7596758160
	public AssetBundle get_assetBundle() { }
	// RVA: 0x4140168 VA: 0x7596758168
	private Void set_assetBundle(AssetBundle value) { }
	// RVA: 0x4140170 VA: 0x7596758170
	public Void .ctor(CriFsBinder binder, String path, Int32 readUnitSize) { }
	// RVA: 0x4140268 VA: 0x7596758268
	public override Void Update() { }
	// RVA: 0x41403c0 VA: 0x75967583c0
	protected override Void Dispose(Boolean disposing) { }
}
```