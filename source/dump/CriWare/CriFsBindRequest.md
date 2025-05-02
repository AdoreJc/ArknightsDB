# CriFsBindRequest

**Namespace:** `CriWare`


## Fields

- `String <path>k__BackingField`

- `UInt32 <bindId>k__BackingField`


## Properties

- `String path`

- `UInt32 bindId`


## Methods

- `String get_path()`

- `Void set_path(String)`

- `UInt32 get_bindId()`

- `Void set_bindId(UInt32)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriFsBindRequest : CriFsRequest
{
	private String <path>k__BackingField; // 0x40
	private UInt32 <bindId>k__BackingField; // 0x48

	public String path { get; set; }
	public UInt32 bindId { get; set; }

	// RVA: 0x4140cec VA: 0x7596758cec
	public String get_path() { }
	// RVA: 0x4140cf4 VA: 0x7596758cf4
	private Void set_path(String value) { }
	// RVA: 0x4140cfc VA: 0x7596758cfc
	public UInt32 get_bindId() { }
	// RVA: 0x4140d04 VA: 0x7596758d04
	private Void set_bindId(UInt32 value) { }
	// RVA: 0x4140d0c VA: 0x7596758d0c
	public Void .ctor(BindType type, CriFsBinder targetBinder, CriFsBinder srcBinder, String path) { }
	// RVA: 0x4140e5c VA: 0x7596758e5c
	public override Void Stop() { }
	// RVA: 0x4140e60 VA: 0x7596758e60
	public override Void Update() { }
	// RVA: 0x4140efc VA: 0x7596758efc
	protected override Void Dispose(Boolean disposing) { }
}
```