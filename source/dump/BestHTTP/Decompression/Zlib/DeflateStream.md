# DeflateStream

**Namespace:** `BestHTTP.Decompression.Zlib`


## Fields

- `Boolean _disposed`


## Properties

- `Int32 BufferSize`

- `CompressionStrategy Strategy`


## Methods

- `Int32 get_BufferSize()`

- `Void set_BufferSize(Int32)`

- `CompressionStrategy get_Strategy()`

- `Void set_Strategy(CompressionStrategy)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : BestHTTP.Decompression.Zlib
internal class DeflateStream : Stream
{
	internal ZlibBaseStream _baseStream; // 0x28
	internal Stream _innerStream; // 0x30
	private Boolean _disposed; // 0x38

	public virtual FlushType FlushMode { get; set; }
	public Int32 BufferSize { get; set; }
	public CompressionStrategy Strategy { get; set; }
	public virtual Int64 TotalIn { get; }
	public virtual Int64 TotalOut { get; }
	public override Boolean CanRead { get; }
	public override Boolean CanSeek { get; }
	public override Boolean CanWrite { get; }
	public override Int64 Length { get; }
	public override Int64 Position { get; set; }

	// RVA: 0x6624bc8 VA: 0x7598c3cbc8
	public Void .ctor(Stream stream, CompressionMode mode) { }
	// RVA: 0x6624cb0 VA: 0x7598c3ccb0
	public Void .ctor(Stream stream, CompressionMode mode, CompressionLevel level) { }
	// RVA: 0x6624cb8 VA: 0x7598c3ccb8
	public Void .ctor(Stream stream, CompressionMode mode, Boolean leaveOpen) { }
	// RVA: 0x6624bd4 VA: 0x7598c3cbd4
	public Void .ctor(Stream stream, CompressionMode mode, CompressionLevel level, Boolean leaveOpen) { }
	// RVA: 0x6624cc4 VA: 0x7598c3ccc4
	public Void .ctor(Stream stream, CompressionMode mode, CompressionLevel level, Boolean leaveOpen, Int32 windowBits) { }
	// RVA: 0x6624db0 VA: 0x7598c3cdb0
	public virtual FlushType get_FlushMode() { }
	// RVA: 0x6624dcc VA: 0x7598c3cdcc
	public virtual Void set_FlushMode(FlushType value) { }
	// RVA: 0x6624e3c VA: 0x7598c3ce3c
	public Int32 get_BufferSize() { }
	// RVA: 0x6624e58 VA: 0x7598c3ce58
	public Void set_BufferSize(Int32 value) { }
	// RVA: 0x6624fac VA: 0x7598c3cfac
	public CompressionStrategy get_Strategy() { }
	// RVA: 0x6624fc8 VA: 0x7598c3cfc8
	public Void set_Strategy(CompressionStrategy value) { }
	// RVA: 0x6625038 VA: 0x7598c3d038
	public virtual Int64 get_TotalIn() { }
	// RVA: 0x662505c VA: 0x7598c3d05c
	public virtual Int64 get_TotalOut() { }
	// RVA: 0x6625080 VA: 0x7598c3d080
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x662514c VA: 0x7598c3d14c
	public override Boolean get_CanRead() { }
	// RVA: 0x66251c8 VA: 0x7598c3d1c8
	public override Boolean get_CanSeek() { }
	// RVA: 0x66251d0 VA: 0x7598c3d1d0
	public override Boolean get_CanWrite() { }
	// RVA: 0x662524c VA: 0x7598c3d24c
	public override Void Flush() { }
	// RVA: 0x66252c4 VA: 0x7598c3d2c4
	public override Int64 get_Length() { }
	// RVA: 0x6625304 VA: 0x7598c3d304
	public override Int64 get_Position() { }
	// RVA: 0x6625354 VA: 0x7598c3d354
	public override Void set_Position(Int64 value) { }
	// RVA: 0x6625394 VA: 0x7598c3d394
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x662540c VA: 0x7598c3d40c
	public override Int64 Seek(Int64 offset, SeekOrigin origin) { }
	// RVA: 0x662544c VA: 0x7598c3d44c
	public override Void SetLength(Int64 value) { }
	// RVA: 0x6625470 VA: 0x7598c3d470
	public override Void Write(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x66254e8 VA: 0x7598c3d4e8
	public static Byte[] CompressString(String s) { }
	// RVA: 0x66256dc VA: 0x7598c3d6dc
	public static Byte[] CompressBuffer(Byte[] b) { }
	// RVA: 0x66258d0 VA: 0x7598c3d8d0
	public static String UncompressString(Byte[] compressed) { }
	// RVA: 0x6625ab0 VA: 0x7598c3dab0
	public static Byte[] UncompressBuffer(Byte[] compressed) { }
}
```