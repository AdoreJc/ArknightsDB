# TextAsset

**Namespace:** `UnityEngine`


## Properties

- `String text`

- `Int64 dataSize`


## Methods

- `IntPtr GetDataPtr()`

- `Int64 GetDataSize()`

- `String get_text()`

- `Int64 get_dataSize()`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class TextAsset : Object
{

	public Byte[] bytes { get; }
	public String text { get; }
	public Int64 dataSize { get; }

	// RVA: 0x68875e0 VA: 0x7598e9f5e0
	public Byte[] get_bytes() { }
	// RVA: 0x688761c VA: 0x7598e9f61c
	private Byte[] GetPreviewBytes(Int32 maxByteCount) { }
	// RVA: 0x6887660 VA: 0x7598e9f660
	private static Void Internal_CreateInstance(TextAsset self, String text) { }
	// RVA: 0x68876a4 VA: 0x7598e9f6a4
	private IntPtr GetDataPtr() { }
	// RVA: 0x68876e0 VA: 0x7598e9f6e0
	private Int64 GetDataSize() { }
	// RVA: 0x688771c VA: 0x7598e9f71c
	public String get_text() { }
	// RVA: 0x68879e0 VA: 0x7598e9f9e0
	public Int64 get_dataSize() { }
	// RVA: 0x6887a1c VA: 0x7598e9fa1c
	public override String ToString() { }
	// RVA: 0x6887a20 VA: 0x7598e9fa20
	public Void .ctor() { }
	// RVA: 0x6887ad8 VA: 0x7598e9fad8
	public Void .ctor(String text) { }
	// RVA: 0x6887a2c VA: 0x7598e9fa2c
	internal Void .ctor(CreateOptions options, String text) { }
	// RVA: 0x VA: 0x0
	public NativeArray`1 GetData() { }
	// RVA: 0x6887ae4 VA: 0x7598e9fae4
	internal String GetPreview(Int32 maxChars) { }
	// RVA: 0x688775c VA: 0x7598e9f75c
	internal static String DecodeString(Byte[] bytes) { }
}
```