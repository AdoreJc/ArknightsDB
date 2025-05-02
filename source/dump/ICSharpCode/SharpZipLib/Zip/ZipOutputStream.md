# ZipOutputStream

**Namespace:** `ICSharpCode.SharpZipLib.Zip`


## Fields

- `ArrayList entries`

- `Crc32 crc`

- `ZipEntry curEntry`

- `Int32 defaultCompressionLevel`

- `CompressionMethod curMethod`

- `Int64 size`

- `Int64 offset`

- `Boolean patchEntryHeader`

- `Int64 crcPatchPos`

- `Int64 sizePatchPos`

- `UseZip64 useZip64_`


## Methods

- `Void WriteLeShort(Int32)`

- `Void WriteLeInt(Int32)`

- `Void WriteLeLong(Int64)`

- `Void PutNextEntry(ZipEntry)`

- `Void CloseEntry()`

- `Void WriteEncryptionHeader(Int64)`

- `Void CopyAndEncrypt(Byte[], Int32, Int32)`


## Dump
```C#
// Dll : ICSharpCode.SharpZipLib.dll
// Namespace : ICSharpCode.SharpZipLib.Zip
public class ZipOutputStream : DeflaterOutputStream
{
	private ArrayList entries; // 0x60
	private Crc32 crc; // 0x68
	private ZipEntry curEntry; // 0x70
	private Int32 defaultCompressionLevel; // 0x78
	private CompressionMethod curMethod; // 0x7c
	private Int64 size; // 0x80
	private Int64 offset; // 0x88
	private Byte[] zipComment; // 0x90
	private Boolean patchEntryHeader; // 0x98
	private Int64 crcPatchPos; // 0xa0
	private Int64 sizePatchPos; // 0xa8
	private UseZip64 useZip64_; // 0xb0


	// RVA: 0x5ed0c90 VA: 0x75984e8c90
	public Void .ctor(Stream baseOutputStream) { }
	// RVA: 0x5ed0dd4 VA: 0x75984e8dd4
	private Void WriteLeShort(Int32 value) { }
	// RVA: 0x5ed0e24 VA: 0x75984e8e24
	private Void WriteLeInt(Int32 value) { }
	// RVA: 0x5ed0e4c VA: 0x75984e8e4c
	private Void WriteLeLong(Int64 value) { }
	// RVA: 0x5ed0e8c VA: 0x75984e8e8c
	public Void PutNextEntry(ZipEntry entry) { }
	// RVA: 0x5ed1614 VA: 0x75984e9614
	public Void CloseEntry() { }
	// RVA: 0x5ed1f04 VA: 0x75984e9f04
	private Void WriteEncryptionHeader(Int64 crcValue) { }
	// RVA: 0x5ed2008 VA: 0x75984ea008
	public override Void Write(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x5ed2234 VA: 0x75984ea234
	private Void CopyAndEncrypt(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x5ed2318 VA: 0x75984ea318
	public override Void Finish() { }
}
```