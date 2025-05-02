# CriFsServer

**Namespace:** `CriWare`


## Fields

- `Int32 <installBufferSize>k__BackingField`


## Properties

- `Int32 installBufferSize`


## Methods

- `Int32 get_installBufferSize()`

- `Void set_installBufferSize(Int32)`

- `Void Awake()`

- `Void OnDestroy()`

- `Void AddRequest(CriFsRequest)`

- `CriFsLoadFileRequest LoadFile(CriFsBinder, String, DoneDelegate, Int32)`

- `CriFsLoadAssetBundleRequest LoadAssetBundle(CriFsBinder, String, Int32)`

- `CriFsInstallRequest Install(CriFsBinder, String, String, DoneDelegate)`

- `CriFsInstallRequest WebInstall(String, String, DoneDelegate)`

- `CriFsBindRequest BindCpk(CriFsBinder, CriFsBinder, String)`

- `CriFsBindRequest BindDirectory(CriFsBinder, CriFsBinder, String)`

- `CriFsBindRequest BindFile(CriFsBinder, CriFsBinder, String)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriFsServer : CriMonoBehaviour
{
	private static CriFsServer _instance; // 0x0
	private List`1 requestList; // 0x28
	private Int32 <installBufferSize>k__BackingField; // 0x30

	public static CriFsServer instance { get; }
	public Int32 installBufferSize { get; set; }

	// RVA: 0x4140f88 VA: 0x7596758f88
	public static CriFsServer get_instance() { }
	// RVA: 0x41427e0 VA: 0x759675a7e0
	public Int32 get_installBufferSize() { }
	// RVA: 0x41427e8 VA: 0x759675a7e8
	private Void set_installBufferSize(Int32 value) { }
	// RVA: 0x41426f4 VA: 0x759675a6f4
	public static Void CreateInstance() { }
	// RVA: 0x4142404 VA: 0x759675a404
	public static Void DestroyInstance() { }
	// RVA: 0x4142974 VA: 0x759675a974
	private Void Awake() { }
	// RVA: 0x4142b70 VA: 0x759675ab70
	private Void OnDestroy() { }
	// RVA: 0x4142d3c VA: 0x759675ad3c
	public override Void CriInternalUpdate() { }
	// RVA: 0x4142eb4 VA: 0x759675aeb4
	public override Void CriInternalLateUpdate() { }
	// RVA: 0x4142eb8 VA: 0x759675aeb8
	public Void AddRequest(CriFsRequest request) { }
	// RVA: 0x4140fd4 VA: 0x7596758fd4
	public CriFsLoadFileRequest LoadFile(CriFsBinder binder, String path, DoneDelegate doneDelegate, Int32 readUnitSize) { }
	// RVA: 0x41410f0 VA: 0x75967590f0
	public CriFsLoadAssetBundleRequest LoadAssetBundle(CriFsBinder binder, String path, Int32 readUnitSize) { }
	// RVA: 0x414122c VA: 0x759675922c
	public CriFsInstallRequest Install(CriFsBinder srcBinder, String srcPath, String dstPath, DoneDelegate doneDelegate) { }
	// RVA: 0x4141374 VA: 0x7596759374
	public CriFsInstallRequest WebInstall(String srcPath, String dstPath, DoneDelegate doneDelegate) { }
	// RVA: 0x41414b8 VA: 0x75967594b8
	public CriFsBindRequest BindCpk(CriFsBinder targetBinder, CriFsBinder srcBinder, String path) { }
	// RVA: 0x4141580 VA: 0x7596759580
	public CriFsBindRequest BindDirectory(CriFsBinder targetBinder, CriFsBinder srcBinder, String path) { }
	// RVA: 0x4141680 VA: 0x7596759680
	public CriFsBindRequest BindFile(CriFsBinder targetBinder, CriFsBinder srcBinder, String path) { }
	// RVA: 0x4142f68 VA: 0x759675af68
	public Void .ctor() { }
}
```