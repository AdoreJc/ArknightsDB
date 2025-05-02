# BinaryReader

**Namespace:** `System.IO`


## Fields

- `Stream m_stream`

- `Decoder m_decoder`

- `Int32 m_maxCharsSize`

- `Boolean m_2BytesPerChar`

- `Boolean m_isMemoryStream`

- `Boolean m_leaveOpen`


## Methods

- `Void Dispose()`

- `Int32 InternalReadChars(Char[], Int32, Int32)`

- `Int32 InternalReadOneChar()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.IO
public class BinaryReader : IDisposable
{
	private Stream m_stream; // 0x10
	private Byte[] m_buffer; // 0x18
	private Decoder m_decoder; // 0x20
	private Byte[] m_charBytes; // 0x28
	private Char[] m_singleChar; // 0x30
	private Char[] m_charBuffer; // 0x38
	private Int32 m_maxCharsSize; // 0x40
	private Boolean m_2BytesPerChar; // 0x44
	private Boolean m_isMemoryStream; // 0x45
	private Boolean m_leaveOpen; // 0x46

	public virtual Stream BaseStream { get; }

	// RVA: 0x60109d8 VA: 0x75986289d8
	public Void .ctor(Stream input) { }
	// RVA: 0x6010cfc VA: 0x7598628cfc
	public Void .ctor(Stream input, Encoding encoding) { }
	// RVA: 0x6010a50 VA: 0x7598628a50
	public Void .ctor(Stream input, Encoding encoding, Boolean leaveOpen) { }
	// RVA: 0x6010d04 VA: 0x7598628d04
	public virtual Stream get_BaseStream() { }
	// RVA: 0x6010d0c VA: 0x7598628d0c
	public virtual Void Close() { }
	// RVA: 0x6010d1c VA: 0x7598628d1c
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x6010dc8 VA: 0x7598628dc8
	public Void Dispose() { }
	// RVA: 0x6010dd8 VA: 0x7598628dd8
	public virtual Int32 Read() { }
	// RVA: 0x6011084 VA: 0x7598629084
	public virtual Boolean ReadBoolean() { }
	// RVA: 0x60110cc VA: 0x75986290cc
	public virtual Byte ReadByte() { }
	// RVA: 0x6011100 VA: 0x7598629100
	public virtual SByte ReadSByte() { }
	// RVA: 0x6011140 VA: 0x7598629140
	public virtual Char ReadChar() { }
	// RVA: 0x6011164 VA: 0x7598629164
	public virtual Int16 ReadInt16() { }
	// RVA: 0x60111ac VA: 0x75986291ac
	public virtual UInt16 ReadUInt16() { }
	// RVA: 0x60111f4 VA: 0x75986291f4
	public virtual Int32 ReadInt32() { }
	// RVA: 0x60112e4 VA: 0x75986292e4
	public virtual UInt32 ReadUInt32() { }
	// RVA: 0x6011354 VA: 0x7598629354
	public virtual Int64 ReadInt64() { }
	// RVA: 0x6011404 VA: 0x7598629404
	public virtual UInt64 ReadUInt64() { }
	// RVA: 0x60114b4 VA: 0x75986294b4
	public virtual Single ReadSingle() { }
	// RVA: 0x60114e4 VA: 0x75986294e4
	public virtual Double ReadDouble() { }
	// RVA: 0x6011514 VA: 0x7598629514
	public virtual Decimal ReadDecimal() { }
	// RVA: 0x6011724 VA: 0x7598629724
	public virtual String ReadString() { }
	// RVA: 0x6011a90 VA: 0x7598629a90
	private Int32 InternalReadChars(Char[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x6010df0 VA: 0x7598628df0
	private Int32 InternalReadOneChar() { }
	// RVA: 0x6011da8 VA: 0x7598629da8
	public virtual Char[] ReadChars(Int32 count) { }
	// RVA: 0x6011f08 VA: 0x7598629f08
	public virtual Int32 Read(Byte[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x601208c VA: 0x759862a08c
	public virtual Byte[] ReadBytes(Int32 count) { }
	// RVA: 0x601221c VA: 0x759862a21c
	protected virtual Void FillBuffer(Int32 numBytes) { }
	// RVA: 0x60119e8 VA: 0x75986299e8
	protected internal Int32 Read7BitEncodedInt() { }
}
```