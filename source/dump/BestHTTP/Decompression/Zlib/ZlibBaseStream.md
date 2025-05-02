# ZlibBaseStream

**Namespace:** `BestHTTP.Decompression.Zlib`


## Fields

- `CRC32 crc`

- `Boolean nomoreinput`


## Properties

- `ZlibCodec z`


## Methods

- `ZlibCodec get_z()`

- `Void finish()`

- `Void end()`

- `String ReadZeroTerminatedString()`

- `Int32 _ReadAndValidateGzipHeader()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : BestHTTP.Decompression.Zlib
internal class ZlibBaseStream : Stream
{
	protected internal ZlibCodec _z; // 0x28
	protected internal StreamMode _streamMode; // 0x30
	protected internal FlushType _flushMode; // 0x34
	protected internal ZlibStreamFlavor _flavor; // 0x38
	protected internal CompressionMode _compressionMode; // 0x3c
	protected internal CompressionLevel _level; // 0x40
	protected internal Boolean _leaveOpen; // 0x44
	protected internal Byte[] _workingBuffer; // 0x48
	protected internal Int32 _bufferSize; // 0x50
	protected internal Int32 windowBitsMax; // 0x54
	protected internal Byte[] _buf1; // 0x58
	protected internal Stream _stream; // 0x60
	protected internal CompressionStrategy Strategy; // 0x68
	private CRC32 crc; // 0x70
	protected internal String _GzipFileName; // 0x78
	protected internal String _GzipComment; // 0x80
	protected internal DateTime _GzipMtime; // 0x88
	protected internal Int32 _gzipHeaderByteCount; // 0x90
	private Boolean nomoreinput; // 0x94

	internal Int32 Crc32 { get; }
	protected internal Boolean _wantCompress { get; }
	private ZlibCodec z { get; }
	private Byte[] workingBuffer { get; }
	public override Boolean CanRead { get; }
	public override Boolean CanSeek { get; }
	public override Boolean CanWrite { get; }
	public override Int64 Length { get; }
	public override Int64 Position { get; set; }

	// RVA: 0x662bfd0 VA: 0x7598c43fd0
	internal Int32 get_Crc32() { }
	// RVA: 0x662bff8 VA: 0x7598c43ff8
	public Void .ctor(Stream stream, CompressionMode compressionMode, CompressionLevel level, ZlibStreamFlavor flavor, Boolean leaveOpen) { }
	// RVA: 0x662c004 VA: 0x7598c44004
	public Void .ctor(Stream stream, CompressionMode compressionMode, CompressionLevel level, ZlibStreamFlavor flavor, Boolean leaveOpen, Int32 windowBits) { }
	// RVA: 0x662c1b4 VA: 0x7598c441b4
	protected internal Boolean get__wantCompress() { }
	// RVA: 0x662c1c4 VA: 0x7598c441c4
	private ZlibCodec get_z() { }
	// RVA: 0x662c3b8 VA: 0x7598c443b8
	private Byte[] get_workingBuffer() { }
	// RVA: 0x662c424 VA: 0x7598c44424
	public override Void Write(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x662c864 VA: 0x7598c44864
	private Void finish() { }
	// RVA: 0x662ce18 VA: 0x7598c44e18
	private Void end() { }
	// RVA: 0x662cf70 VA: 0x7598c44f70
	public override Void Close() { }
	// RVA: 0x662d05c VA: 0x7598c4505c
	public override Void Flush() { }
	// RVA: 0x662d080 VA: 0x7598c45080
	public override Int64 Seek(Int64 offset, SeekOrigin origin) { }
	// RVA: 0x662d0c0 VA: 0x7598c450c0
	public override Void SetLength(Int64 value) { }
	// RVA: 0x662d0f0 VA: 0x7598c450f0
	private String ReadZeroTerminatedString() { }
	// RVA: 0x662d2e4 VA: 0x7598c452e4
	private Int32 _ReadAndValidateGzipHeader() { }
	// RVA: 0x662d638 VA: 0x7598c45638
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x662dac4 VA: 0x7598c45ac4
	public override Boolean get_CanRead() { }
	// RVA: 0x662dae4 VA: 0x7598c45ae4
	public override Boolean get_CanSeek() { }
	// RVA: 0x662db04 VA: 0x7598c45b04
	public override Boolean get_CanWrite() { }
	// RVA: 0x662db24 VA: 0x7598c45b24
	public override Int64 get_Length() { }
	// RVA: 0x662db44 VA: 0x7598c45b44
	public override Int64 get_Position() { }
	// RVA: 0x662db84 VA: 0x7598c45b84
	public override Void set_Position(Int64 value) { }
	// RVA: 0x662dbc4 VA: 0x7598c45bc4
	public static Void CompressString(String s, Stream compressor) { }
	// RVA: 0x662dd74 VA: 0x7598c45d74
	public static Void CompressBuffer(Byte[] b, Stream compressor) { }
	// RVA: 0x662df00 VA: 0x7598c45f00
	public static String UncompressString(Byte[] compressed, Stream decompressor) { }
	// RVA: 0x662e2ac VA: 0x7598c462ac
	public static Byte[] UncompressBuffer(Byte[] compressed, Stream decompressor) { }
}
```