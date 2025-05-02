# StreamReader

**Namespace:** `System.IO`


## Fields

- `Stream _stream`

- `Encoding _encoding`

- `Decoder _decoder`

- `Int32 _charPos`

- `Int32 _charLen`

- `Int32 _byteLen`

- `Int32 _bytePos`

- `Int32 _maxCharsPerBuffer`

- `Boolean _detectEncoding`

- `Boolean _checkPreamble`

- `Boolean _isBlocked`

- `Boolean _closable`

- `Task _asyncReadTask`


## Properties

- `Boolean EndOfStream`


## Methods

- `Void CheckAsyncTaskInProgress()`

- `Void Init(Stream, Encoding, Boolean, Int32, Boolean)`

- `Boolean get_EndOfStream()`

- `Int32 ReadSpan(Span`1)`

- `Void CompressBuffer(Int32)`

- `Void DetectEncoding()`

- `Boolean IsPreamble()`

- `Int32 ReadBuffer(Span`1, out)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.IO
public class StreamReader : TextReader
{
	public static readonly StreamReader Null; // 0x0
	private Stream _stream; // 0x18
	private Encoding _encoding; // 0x20
	private Decoder _decoder; // 0x28
	private Byte[] _byteBuffer; // 0x30
	private Char[] _charBuffer; // 0x38
	private Int32 _charPos; // 0x40
	private Int32 _charLen; // 0x44
	private Int32 _byteLen; // 0x48
	private Int32 _bytePos; // 0x4c
	private Int32 _maxCharsPerBuffer; // 0x50
	private Boolean _detectEncoding; // 0x54
	private Boolean _checkPreamble; // 0x55
	private Boolean _isBlocked; // 0x56
	private Boolean _closable; // 0x57
	private Task _asyncReadTask; // 0x58

	public virtual Encoding CurrentEncoding { get; }
	public virtual Stream BaseStream { get; }
	internal Boolean LeaveOpen { get; }
	public Boolean EndOfStream { get; }

	// RVA: 0x6000750 VA: 0x7598618750
	private Void CheckAsyncTaskInProgress() { }
	// RVA: 0x60007b4 VA: 0x75986187b4
	private static Void ThrowAsyncIOInProgress() { }
	// RVA: 0x6000804 VA: 0x7598618804
	internal Void .ctor() { }
	// RVA: 0x60008d0 VA: 0x75986188d0
	public Void .ctor(Stream stream) { }
	// RVA: 0x600090c VA: 0x759861890c
	public Void .ctor(Stream stream, Boolean detectEncodingFromByteOrderMarks) { }
	// RVA: 0x6000b7c VA: 0x7598618b7c
	public Void .ctor(Stream stream, Encoding encoding) { }
	// RVA: 0x600094c VA: 0x759861894c
	public Void .ctor(Stream stream, Encoding encoding, Boolean detectEncodingFromByteOrderMarks, Int32 bufferSize, Boolean leaveOpen) { }
	// RVA: 0x6000cf4 VA: 0x7598618cf4
	public Void .ctor(String path) { }
	// RVA: 0x6000d2c VA: 0x7598618d2c
	public Void .ctor(String path, Boolean detectEncodingFromByteOrderMarks) { }
	// RVA: 0x6000fbc VA: 0x7598618fbc
	public Void .ctor(String path, Encoding encoding) { }
	// RVA: 0x6000fc8 VA: 0x7598618fc8
	public Void .ctor(String path, Encoding encoding, Boolean detectEncodingFromByteOrderMarks) { }
	// RVA: 0x6000d68 VA: 0x7598618d68
	public Void .ctor(String path, Encoding encoding, Boolean detectEncodingFromByteOrderMarks, Int32 bufferSize) { }
	// RVA: 0x6000b8c VA: 0x7598618b8c
	private Void Init(Stream stream, Encoding encoding, Boolean detectEncodingFromByteOrderMarks, Int32 bufferSize, Boolean leaveOpen) { }
	// RVA: 0x6000fd4 VA: 0x7598618fd4
	internal Void Init(Stream stream) { }
	// RVA: 0x6000ff8 VA: 0x7598618ff8
	public override Void Close() { }
	// RVA: 0x6001008 VA: 0x7598619008
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x60010b0 VA: 0x75986190b0
	public virtual Encoding get_CurrentEncoding() { }
	// RVA: 0x60010b8 VA: 0x75986190b8
	public virtual Stream get_BaseStream() { }
	// RVA: 0x60010a0 VA: 0x75986190a0
	internal Boolean get_LeaveOpen() { }
	// RVA: 0x60010c0 VA: 0x75986190c0
	public Boolean get_EndOfStream() { }
	// RVA: 0x600115c VA: 0x759861915c
	public override Int32 Peek() { }
	// RVA: 0x6001224 VA: 0x7598619224
	public override Int32 Read() { }
	// RVA: 0x60012ec VA: 0x75986192ec
	public override Int32 Read(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x60014ac VA: 0x75986194ac
	private Int32 ReadSpan(Span`1 buffer) { }
	// RVA: 0x6001a24 VA: 0x7598619a24
	public override String ReadToEnd() { }
	// RVA: 0x6001b40 VA: 0x7598619b40
	private Void CompressBuffer(Int32 n) { }
	// RVA: 0x6001b84 VA: 0x7598619b84
	private Void DetectEncoding() { }
	// RVA: 0x6001e8c VA: 0x7598619e8c
	private Boolean IsPreamble() { }
	// RVA: 0x6001fbc VA: 0x7598619fbc
	internal virtual Int32 ReadBuffer() { }
	// RVA: 0x6001714 VA: 0x7598619714
	private Int32 ReadBuffer(Span`1 userBuffer, out Boolean readToUserBuffer) { }
	// RVA: 0x6002128 VA: 0x759861a128
	public override String ReadLine() { }
	// RVA: 0x6002388 VA: 0x759861a388
	internal Boolean DataAvailable() { }
	// RVA: 0x6002398 VA: 0x759861a398
	private static Void .cctor() { }
}
```