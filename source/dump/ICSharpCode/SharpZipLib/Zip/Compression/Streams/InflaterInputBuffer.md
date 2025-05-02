# InflaterInputBuffer

**Namespace:** `ICSharpCode.SharpZipLib.Zip.Compression.Streams`


## Fields

- `Int32 rawLength`

- `Int32 clearTextLength`

- `Int32 available`

- `ICryptoTransform cryptoTransform`

- `Stream inputStream`


## Properties

- `Int32 RawLength`

- `Int32 Available`

- `ICryptoTransform CryptoTransform`


## Methods

- `Int32 get_RawLength()`

- `Int32 get_Available()`

- `Void set_Available(Int32)`

- `Void SetInflaterInput(Inflater)`

- `Void Fill()`

- `Int32 ReadRawBuffer(Byte[])`

- `Int32 ReadRawBuffer(Byte[], Int32, Int32)`

- `Int32 ReadClearTextBuffer(Byte[], Int32, Int32)`

- `Int32 ReadLeByte()`

- `Int32 ReadLeShort()`

- `Int32 ReadLeInt()`

- `Int64 ReadLeLong()`

- `Void set_CryptoTransform(ICryptoTransform)`


## Dump
```C#
// Dll : ICSharpCode.SharpZipLib.dll
// Namespace : ICSharpCode.SharpZipLib.Zip.Compression.Streams
public class InflaterInputBuffer
{
	private Int32 rawLength; // 0x10
	private Byte[] rawData; // 0x18
	private Int32 clearTextLength; // 0x20
	private Byte[] clearText; // 0x28
	private Byte[] internalClearText; // 0x30
	private Int32 available; // 0x38
	private ICryptoTransform cryptoTransform; // 0x40
	private Stream inputStream; // 0x48

	public Int32 RawLength { get; }
	public Int32 Available { get; set; }
	public ICryptoTransform CryptoTransform { set; }

	// RVA: 0x5ec4174 VA: 0x75984dc174
	public Void .ctor(Stream stream, Int32 bufferSize) { }
	// RVA: 0x5ec69f8 VA: 0x75984de9f8
	public Int32 get_RawLength() { }
	// RVA: 0x5ec6a00 VA: 0x75984dea00
	public Int32 get_Available() { }
	// RVA: 0x5ec6a08 VA: 0x75984dea08
	public Void set_Available(Int32 value) { }
	// RVA: 0x5ec46cc VA: 0x75984dc6cc
	public Void SetInflaterInput(Inflater inflater) { }
	// RVA: 0x5ec4590 VA: 0x75984dc590
	public Void Fill() { }
	// RVA: 0x5ec6a48 VA: 0x75984dea48
	public Int32 ReadRawBuffer(Byte[] buffer) { }
	// RVA: 0x5ec6a64 VA: 0x75984dea64
	public Int32 ReadRawBuffer(Byte[] outBuffer, Int32 offset, Int32 length) { }
	// RVA: 0x5ec58c4 VA: 0x75984dd8c4
	public Int32 ReadClearTextBuffer(Byte[] outBuffer, Int32 offset, Int32 length) { }
	// RVA: 0x5ec576c VA: 0x75984dd76c
	public Int32 ReadLeByte() { }
	// RVA: 0x5ec6ba8 VA: 0x75984deba8
	public Int32 ReadLeShort() { }
	// RVA: 0x5ec6bd4 VA: 0x75984debd4
	public Int32 ReadLeInt() { }
	// RVA: 0x5ec6c1c VA: 0x75984dec1c
	public Int64 ReadLeLong() { }
	// RVA: 0x5ec4378 VA: 0x75984dc378
	public Void set_CryptoTransform(ICryptoTransform value) { }
}
```