# ZipInputStream

**Namespace:** `ICSharpCode.SharpZipLib.Zip`


## Fields

- `ReadDataHandler internalReader`

- `Crc32 crc`

- `ZipEntry entry`

- `Int64 size`

- `Int32 method`

- `Int32 flags`

- `String password`


## Properties

- `Boolean CanDecompressEntry`


## Methods

- `Boolean get_CanDecompressEntry()`

- `ZipEntry GetNextEntry()`

- `Void ReadDataDescriptor()`

- `Void CompleteCloseEntry(Boolean)`

- `Void CloseEntry()`

- `Int32 ReadingNotAvailable(Byte[], Int32, Int32)`

- `Int32 ReadingNotSupported(Byte[], Int32, Int32)`

- `Int32 InitialRead(Byte[], Int32, Int32)`

- `Int32 BodyRead(Byte[], Int32, Int32)`


## Dump
```C#
// Dll : ICSharpCode.SharpZipLib.dll
// Namespace : ICSharpCode.SharpZipLib.Zip
public class ZipInputStream : InflaterInputStream
{
	private ReadDataHandler internalReader; // 0x50
	private Crc32 crc; // 0x58
	private ZipEntry entry; // 0x60
	private Int64 size; // 0x68
	private Int32 method; // 0x70
	private Int32 flags; // 0x74
	private String password; // 0x78

	public Boolean CanDecompressEntry { get; }
	public override Int64 Length { get; }

	// RVA: 0x5ecf3c0 VA: 0x75984e73c0
	public Void .ctor(Stream baseInputStream) { }
	// RVA: 0x5ecf5b0 VA: 0x75984e75b0
	public Boolean get_CanDecompressEntry() { }
	// RVA: 0x5ecf5c0 VA: 0x75984e75c0
	public ZipEntry GetNextEntry() { }
	// RVA: 0x5ecfdb0 VA: 0x75984e7db0
	private Void ReadDataDescriptor() { }
	// RVA: 0x5ecfef8 VA: 0x75984e7ef8
	private Void CompleteCloseEntry(Boolean testCrc) { }
	// RVA: 0x5ecfbd0 VA: 0x75984e7bd0
	public Void CloseEntry() { }
	// RVA: 0x5ecffd0 VA: 0x75984e7fd0
	public override Int64 get_Length() { }
	// RVA: 0x5ed0074 VA: 0x75984e8074
	public override Int32 ReadByte() { }
	// RVA: 0x5ed010c VA: 0x75984e810c
	private Int32 ReadingNotAvailable(Byte[] destination, Int32 offset, Int32 count) { }
	// RVA: 0x5ed015c VA: 0x75984e815c
	private Int32 ReadingNotSupported(Byte[] destination, Int32 offset, Int32 count) { }
	// RVA: 0x5ed01a8 VA: 0x75984e81a8
	private Int32 InitialRead(Byte[] destination, Int32 offset, Int32 count) { }
	// RVA: 0x5ed0a98 VA: 0x75984e8a98
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x5ed0570 VA: 0x75984e8570
	private Int32 BodyRead(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x5ed0bd4 VA: 0x75984e8bd4
	public override Void Close() { }
}
```