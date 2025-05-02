# CriFsLoadFileRequest

**Namespace:** `CriWare`


## Fields

- `String <path>k__BackingField`

- `Phase phase`

- `CriFsBinder refBinder`

- `CriFsBinder newBinder`

- `UInt32 bindId`

- `CriFsLoader loader`

- `Int32 readUnitSize`

- `Int64 fileSize`


## Properties

- `String path`


## Methods

- `String get_path()`

- `Void set_path(String)`

- `Void set_bytes(Byte[])`

- `Void UpdateBinder()`

- `Void UpdateLoader()`

- `Void OnError()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriFsLoadFileRequest : CriFsRequest
{
	private String <path>k__BackingField; // 0x40
	private Byte[] <bytes>k__BackingField; // 0x48
	private Phase phase; // 0x50
	private CriFsBinder refBinder; // 0x58
	private CriFsBinder newBinder; // 0x60
	private UInt32 bindId; // 0x68
	private CriFsLoader loader; // 0x70
	private Int32 readUnitSize; // 0x78
	private Int64 fileSize; // 0x80

	public String path { get; set; }
	public Byte[] bytes { get; set; }

	// RVA: 0x413fbac VA: 0x7596757bac
	public String get_path() { }
	// RVA: 0x413fbb4 VA: 0x7596757bb4
	private Void set_path(String value) { }
	// RVA: 0x413fbbc VA: 0x7596757bbc
	public Byte[] get_bytes() { }
	// RVA: 0x413fbc4 VA: 0x7596757bc4
	private Void set_bytes(Byte[] value) { }
	// RVA: 0x413fbcc VA: 0x7596757bcc
	public Void .ctor(CriFsBinder srcBinder, String path, DoneDelegate doneDelegate, Int32 readUnitSize) { }
	// RVA: 0x413fd40 VA: 0x7596757d40
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x413fdf4 VA: 0x7596757df4
	public override Void Stop() { }
	// RVA: 0x413fe10 VA: 0x7596757e10
	public override Void Update() { }
	// RVA: 0x413fe60 VA: 0x7596757e60
	private Void UpdateBinder() { }
	// RVA: 0x413fec4 VA: 0x7596757ec4
	private Void UpdateLoader() { }
	// RVA: 0x414005c VA: 0x759675805c
	private Void OnError() { }
}
```