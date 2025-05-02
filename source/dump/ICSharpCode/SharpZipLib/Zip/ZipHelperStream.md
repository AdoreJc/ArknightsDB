# ZipHelperStream

**Namespace:** `ICSharpCode.SharpZipLib.Zip`


## Fields

- `Boolean isOwner_`

- `Stream stream_`


## Methods

- `Void WriteZip64EndOfCentralDirectory(Int64, Int64, Int64)`

- `Void WriteEndOfCentralDirectory(Int64, Int64, Int64, Byte[])`

- `Void WriteLEShort(Int32)`

- `Void WriteLEUshort(UInt16)`

- `Void WriteLEInt(Int32)`

- `Void WriteLEUint(UInt32)`

- `Void WriteLELong(Int64)`


## Dump
```C#
// Dll : ICSharpCode.SharpZipLib.dll
// Namespace : ICSharpCode.SharpZipLib.Zip
internal class ZipHelperStream : Stream
{
	private Boolean isOwner_; // 0x28
	private Stream stream_; // 0x30

	public override Boolean CanRead { get; }
	public override Boolean CanSeek { get; }
	public override Int64 Length { get; }
	public override Int64 Position { get; set; }
	public override Boolean CanWrite { get; }

	// RVA: 0x5ececc0 VA: 0x75984e6cc0
	public Void .ctor(Stream stream) { }
	// RVA: 0x5eced34 VA: 0x75984e6d34
	public override Boolean get_CanRead() { }
	// RVA: 0x5eced54 VA: 0x75984e6d54
	public override Boolean get_CanSeek() { }
	// RVA: 0x5eced74 VA: 0x75984e6d74
	public override Int64 get_Length() { }
	// RVA: 0x5eced94 VA: 0x75984e6d94
	public override Int64 get_Position() { }
	// RVA: 0x5ecedb4 VA: 0x75984e6db4
	public override Void set_Position(Int64 value) { }
	// RVA: 0x5ecedd8 VA: 0x75984e6dd8
	public override Boolean get_CanWrite() { }
	// RVA: 0x5ecedf8 VA: 0x75984e6df8
	public override Void Flush() { }
	// RVA: 0x5ecee1c VA: 0x75984e6e1c
	public override Int64 Seek(Int64 offset, SeekOrigin origin) { }
	// RVA: 0x5ecee40 VA: 0x75984e6e40
	public override Void SetLength(Int64 value) { }
	// RVA: 0x5ecee64 VA: 0x75984e6e64
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x5ecee88 VA: 0x75984e6e88
	public override Void Write(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x5eceeac VA: 0x75984e6eac
	public override Void Close() { }
	// RVA: 0x5ecef08 VA: 0x75984e6f08
	public Void WriteZip64EndOfCentralDirectory(Int64 noOfEntries, Int64 sizeEntries, Int64 centralDirOffset) { }
	// RVA: 0x5ecf0fc VA: 0x75984e70fc
	public Void WriteEndOfCentralDirectory(Int64 noOfEntries, Int64 sizeEntries, Int64 startOfCentralDirectory, Byte[] comment) { }
	// RVA: 0x5ecf0ac VA: 0x75984e70ac
	public Void WriteLEShort(Int32 value) { }
	// RVA: 0x5ecf348 VA: 0x75984e7348
	public Void WriteLEUshort(UInt16 value) { }
	// RVA: 0x5ecf044 VA: 0x75984e7044
	public Void WriteLEInt(Int32 value) { }
	// RVA: 0x5ecf398 VA: 0x75984e7398
	public Void WriteLEUint(UInt32 value) { }
	// RVA: 0x5ecf06c VA: 0x75984e706c
	public Void WriteLELong(Int64 value) { }
}
```