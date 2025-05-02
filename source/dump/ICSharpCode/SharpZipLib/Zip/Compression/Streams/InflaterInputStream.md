# InflaterInputStream

**Namespace:** `ICSharpCode.SharpZipLib.Zip.Compression.Streams`


## Fields

- `Inflater inf`

- `InflaterInputBuffer inputBuffer`

- `Stream baseInputStream`

- `Int64 csize`

- `Boolean isClosed`

- `Boolean isStreamOwner`


## Methods

- `Int64 Skip(Int64)`

- `Void StopDecrypting()`

- `Void Fill()`


## Dump
```C#
// Dll : ICSharpCode.SharpZipLib.dll
// Namespace : ICSharpCode.SharpZipLib.Zip.Compression.Streams
public class InflaterInputStream : Stream
{
	protected Inflater inf; // 0x28
	protected InflaterInputBuffer inputBuffer; // 0x30
	private Stream baseInputStream; // 0x38
	protected Int64 csize; // 0x40
	private Boolean isClosed; // 0x48
	private Boolean isStreamOwner; // 0x49

	public override Boolean CanRead { get; }
	public override Boolean CanSeek { get; }
	public override Boolean CanWrite { get; }
	public override Int64 Length { get; }
	public override Int64 Position { get; set; }

	// RVA: 0x5ec3fd4 VA: 0x75984dbfd4
	public Void .ctor(Stream baseInputStream, Inflater inf) { }
	// RVA: 0x5ec3fdc VA: 0x75984dbfdc
	public Void .ctor(Stream baseInputStream, Inflater inflater, Int32 bufferSize) { }
	// RVA: 0x5ec4214 VA: 0x75984dc214
	public Int64 Skip(Int64 count) { }
	// RVA: 0x5ec435c VA: 0x75984dc35c
	protected Void StopDecrypting() { }
	// RVA: 0x5ec4504 VA: 0x75984dc504
	protected Void Fill() { }
	// RVA: 0x5ec470c VA: 0x75984dc70c
	public override Boolean get_CanRead() { }
	// RVA: 0x5ec472c VA: 0x75984dc72c
	public override Boolean get_CanSeek() { }
	// RVA: 0x5ec4734 VA: 0x75984dc734
	public override Boolean get_CanWrite() { }
	// RVA: 0x5ec473c VA: 0x75984dc73c
	public override Int64 get_Length() { }
	// RVA: 0x5ec4758 VA: 0x75984dc758
	public override Int64 get_Position() { }
	// RVA: 0x5ec4778 VA: 0x75984dc778
	public override Void set_Position(Int64 value) { }
	// RVA: 0x5ec47c8 VA: 0x75984dc7c8
	public override Void Flush() { }
	// RVA: 0x5ec47ec VA: 0x75984dc7ec
	public override Int64 Seek(Int64 offset, SeekOrigin origin) { }
	// RVA: 0x5ec483c VA: 0x75984dc83c
	public override Void SetLength(Int64 value) { }
	// RVA: 0x5ec488c VA: 0x75984dc88c
	public override Void Write(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x5ec48dc VA: 0x75984dc8dc
	public override Void WriteByte(Byte value) { }
	// RVA: 0x5ec492c VA: 0x75984dc92c
	public override IAsyncResult BeginWrite(Byte[] buffer, Int32 offset, Int32 count, AsyncCallback callback, Object state) { }
	// RVA: 0x5ec497c VA: 0x75984dc97c
	public override Void Close() { }
	// RVA: 0x5ec49c0 VA: 0x75984dc9c0
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 count) { }
}
```