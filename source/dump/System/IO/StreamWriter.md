# StreamWriter

**Namespace:** `System.IO`


## Fields

- `Stream _stream`

- `Encoding _encoding`

- `Encoder _encoder`

- `Int32 _charPos`

- `Int32 _charLen`

- `Boolean _autoFlush`

- `Boolean _haveWrittenPreamble`

- `Boolean _closable`

- `Task _asyncWriteTask`


## Methods

- `Void CheckAsyncTaskInProgress()`

- `Void Init(Stream, Encoding, Int32, Boolean)`

- `Void Flush(Boolean, Boolean)`

- `Void WriteSpan(ReadOnlySpan`1, Boolean)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.IO
public class StreamWriter : TextWriter
{
	internal const Int32 DefaultBufferSize; // 0x0
	private const Int32 DefaultFileStreamBufferSize; // 0x0
	private const Int32 MinBufferSize; // 0x0
	private const Int32 DontCopyOnWriteLineThreshold; // 0x0
	public static readonly StreamWriter Null; // 0x0
	private Stream _stream; // 0x30
	private Encoding _encoding; // 0x38
	private Encoder _encoder; // 0x40
	private Byte[] _byteBuffer; // 0x48
	private Char[] _charBuffer; // 0x50
	private Int32 _charPos; // 0x58
	private Int32 _charLen; // 0x5c
	private Boolean _autoFlush; // 0x60
	private Boolean _haveWrittenPreamble; // 0x61
	private Boolean _closable; // 0x62
	private Task _asyncWriteTask; // 0x68

	private static Encoding UTF8NoBOM { get; }
	public virtual Boolean AutoFlush { set; }
	internal Boolean LeaveOpen { get; }
	public override Encoding Encoding { get; }

	// RVA: 0x6002588 VA: 0x759861a588
	private Void CheckAsyncTaskInProgress() { }
	// RVA: 0x60025ec VA: 0x759861a5ec
	private static Void ThrowAsyncIOInProgress() { }
	// RVA: 0x600263c VA: 0x759861a63c
	private static Encoding get_UTF8NoBOM() { }
	// RVA: 0x600268c VA: 0x759861a68c
	internal Void .ctor() { }
	// RVA: 0x60027f4 VA: 0x759861a7f4
	public Void .ctor(Stream stream) { }
	// RVA: 0x6002a88 VA: 0x759861aa88
	public Void .ctor(Stream stream, Encoding encoding) { }
	// RVA: 0x6002868 VA: 0x759861a868
	public Void .ctor(Stream stream, Encoding encoding, Int32 bufferSize, Boolean leaveOpen) { }
	// RVA: 0x6002c14 VA: 0x759861ac14
	public Void .ctor(String path) { }
	// RVA: 0x6002ee0 VA: 0x759861aee0
	public Void .ctor(String path, Boolean append) { }
	// RVA: 0x6002c88 VA: 0x759861ac88
	public Void .ctor(String path, Boolean append, Encoding encoding, Int32 bufferSize) { }
	// RVA: 0x6002a94 VA: 0x759861aa94
	private Void Init(Stream streamArg, Encoding encodingArg, Int32 bufferSize, Boolean shouldLeaveOpen) { }
	// RVA: 0x6002ff0 VA: 0x759861aff0
	public override Void Close() { }
	// RVA: 0x600305c VA: 0x759861b05c
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x6003270 VA: 0x759861b270
	public override Void Flush() { }
	// RVA: 0x60030f0 VA: 0x759861b0f0
	private Void Flush(Boolean flushStream, Boolean flushEncoder) { }
	// RVA: 0x6003290 VA: 0x759861b290
	public virtual Void set_AutoFlush(Boolean value) { }
	// RVA: 0x60032d4 VA: 0x759861b2d4
	internal Boolean get_LeaveOpen() { }
	// RVA: 0x60032e4 VA: 0x759861b2e4
	public override Encoding get_Encoding() { }
	// RVA: 0x60032ec VA: 0x759861b2ec
	public override Void Write(Char value) { }
	// RVA: 0x6003378 VA: 0x759861b378
	public override Void Write(Char[] buffer) { }
	// RVA: 0x60035e0 VA: 0x759861b5e0
	public override Void Write(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x60039b8 VA: 0x759861b9b8
	private Void WriteSpan(ReadOnlySpan`1 buffer, Boolean appendNewLine) { }
	// RVA: 0x6003c80 VA: 0x759861bc80
	public override Void Write(String value) { }
	// RVA: 0x6003eec VA: 0x759861beec
	public override Void WriteLine(String value) { }
	// RVA: 0x60041e8 VA: 0x759861c1e8
	private static Void .cctor() { }
}
```