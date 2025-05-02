# GZipStream

**Namespace:** `BestHTTP.Decompression.Zlib`


## Fields

- `Int32 _headerByteCount`

- `Boolean _disposed`

- `Boolean _firstReadDone`

- `String _FileName`

- `String _Comment`

- `Int32 _Crc32`


## Properties

- `String Comment`

- `String FileName`

- `Int32 Crc32`

- `Int32 BufferSize`


## Methods

- `String get_Comment()`

- `Void set_Comment(String)`

- `String get_FileName()`

- `Void set_FileName(String)`

- `Int32 get_Crc32()`

- `Int32 get_BufferSize()`

- `Void set_BufferSize(Int32)`

- `Int32 EmitHeader()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : BestHTTP.Decompression.Zlib
internal class GZipStream : Stream
{
	public Nullable`1 LastModified; // 0x28
	private Int32 _headerByteCount; // 0x38
	internal ZlibBaseStream _baseStream; // 0x40
	private Boolean _disposed; // 0x48
	private Boolean _firstReadDone; // 0x49
	private String _FileName; // 0x50
	private String _Comment; // 0x58
	private Int32 _Crc32; // 0x60
	internal static readonly DateTime _unixEpoch; // 0x0
	internal static readonly Encoding iso8859dash1; // 0x8

	public String Comment { get; set; }
	public String FileName { get; set; }
	public Int32 Crc32 { get; }
	public virtual FlushType FlushMode { get; set; }
	public Int32 BufferSize { get; set; }
	public virtual Int64 TotalIn { get; }
	public virtual Int64 TotalOut { get; }
	public override Boolean CanRead { get; }
	public override Boolean CanSeek { get; }
	public override Boolean CanWrite { get; }
	public override Int64 Length { get; }
	public override Int64 Position { get; set; }

	// RVA: 0x6625c90 VA: 0x7598c3dc90
	public String get_Comment() { }
	// RVA: 0x6625c98 VA: 0x7598c3dc98
	public Void set_Comment(String value) { }
	// RVA: 0x6625cfc VA: 0x7598c3dcfc
	public String get_FileName() { }
	// RVA: 0x6625d04 VA: 0x7598c3dd04
	public Void set_FileName(String value) { }
	// RVA: 0x6625ec0 VA: 0x7598c3dec0
	public Int32 get_Crc32() { }
	// RVA: 0x6625ec8 VA: 0x7598c3dec8
	public Void .ctor(Stream stream, CompressionMode mode) { }
	// RVA: 0x6625fa0 VA: 0x7598c3dfa0
	public Void .ctor(Stream stream, CompressionMode mode, CompressionLevel level) { }
	// RVA: 0x6625fa8 VA: 0x7598c3dfa8
	public Void .ctor(Stream stream, CompressionMode mode, Boolean leaveOpen) { }
	// RVA: 0x6625ed4 VA: 0x7598c3ded4
	public Void .ctor(Stream stream, CompressionMode mode, CompressionLevel level, Boolean leaveOpen) { }
	// RVA: 0x6625fb4 VA: 0x7598c3dfb4
	public virtual FlushType get_FlushMode() { }
	// RVA: 0x6625fd0 VA: 0x7598c3dfd0
	public virtual Void set_FlushMode(FlushType value) { }
	// RVA: 0x6626040 VA: 0x7598c3e040
	public Int32 get_BufferSize() { }
	// RVA: 0x662605c VA: 0x7598c3e05c
	public Void set_BufferSize(Int32 value) { }
	// RVA: 0x66261b0 VA: 0x7598c3e1b0
	public virtual Int64 get_TotalIn() { }
	// RVA: 0x66261d4 VA: 0x7598c3e1d4
	public virtual Int64 get_TotalOut() { }
	// RVA: 0x66261f8 VA: 0x7598c3e1f8
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x66262e4 VA: 0x7598c3e2e4
	public override Boolean get_CanRead() { }
	// RVA: 0x6626360 VA: 0x7598c3e360
	public override Boolean get_CanSeek() { }
	// RVA: 0x6626368 VA: 0x7598c3e368
	public override Boolean get_CanWrite() { }
	// RVA: 0x66263e4 VA: 0x7598c3e3e4
	public override Void Flush() { }
	// RVA: 0x662645c VA: 0x7598c3e45c
	public override Int64 get_Length() { }
	// RVA: 0x662649c VA: 0x7598c3e49c
	public override Int64 get_Position() { }
	// RVA: 0x66264fc VA: 0x7598c3e4fc
	public override Void set_Position(Int64 value) { }
	// RVA: 0x662653c VA: 0x7598c3e53c
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x6626604 VA: 0x7598c3e604
	public override Int64 Seek(Int64 offset, SeekOrigin origin) { }
	// RVA: 0x6626644 VA: 0x7598c3e644
	public override Void SetLength(Int64 value) { }
	// RVA: 0x6626668 VA: 0x7598c3e668
	public override Void Write(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x6626768 VA: 0x7598c3e768
	private Int32 EmitHeader() { }
	// RVA: 0x6626b70 VA: 0x7598c3eb70
	public static Byte[] CompressString(String s) { }
	// RVA: 0x6626d64 VA: 0x7598c3ed64
	public static Byte[] CompressBuffer(Byte[] b) { }
	// RVA: 0x6626f58 VA: 0x7598c3ef58
	public static String UncompressString(Byte[] compressed) { }
	// RVA: 0x6627138 VA: 0x7598c3f138
	public static Byte[] UncompressBuffer(Byte[] compressed) { }
	// RVA: 0x6627318 VA: 0x7598c3f318
	private static Void .cctor() { }
}
```