# BinaryWriter

**Namespace:** `System.IO`


## Fields

- `Stream OutStream`

- `Encoding _encoding`

- `Encoder _encoder`

- `Boolean _leaveOpen`

- `Int32 _maxChars`


## Methods

- `Void Dispose()`

- `Void Write7BitEncodedInt(Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.IO
public class BinaryWriter : IDisposable
{
	public static readonly BinaryWriter Null; // 0x0
	protected Stream OutStream; // 0x10
	private Byte[] _buffer; // 0x18
	private Encoding _encoding; // 0x20
	private Encoder _encoder; // 0x28
	private Boolean _leaveOpen; // 0x30
	private Byte[] _largeByteBuffer; // 0x38
	private Int32 _maxChars; // 0x40


	// RVA: 0x6012340 VA: 0x759862a340
	protected Void .ctor() { }
	// RVA: 0x601245c VA: 0x759862a45c
	public Void .ctor(Stream output) { }
	// RVA: 0x6012694 VA: 0x759862a694
	public Void .ctor(Stream output, Encoding encoding) { }
	// RVA: 0x60124dc VA: 0x759862a4dc
	public Void .ctor(Stream output, Encoding encoding, Boolean leaveOpen) { }
	// RVA: 0x601269c VA: 0x759862a69c
	public virtual Void Close() { }
	// RVA: 0x60126ac VA: 0x759862a6ac
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x60126f4 VA: 0x759862a6f4
	public Void Dispose() { }
	// RVA: 0x6012704 VA: 0x759862a704
	public virtual Void Flush() { }
	// RVA: 0x6012728 VA: 0x759862a728
	public virtual Void Write(Boolean value) { }
	// RVA: 0x6012778 VA: 0x759862a778
	public virtual Void Write(Byte value) { }
	// RVA: 0x601279c VA: 0x759862a79c
	public virtual Void Write(SByte value) { }
	// RVA: 0x60127c0 VA: 0x759862a7c0
	public virtual Void Write(Byte[] buffer) { }
	// RVA: 0x601283c VA: 0x759862a83c
	public virtual Void Write(Byte[] buffer, Int32 index, Int32 count) { }
	// RVA: 0x6012860 VA: 0x759862a860
	public virtual Void Write(Char ch) { }
	// RVA: 0x601298c VA: 0x759862a98c
	public virtual Void Write(Char[] chars) { }
	// RVA: 0x6012a34 VA: 0x759862aa34
	public virtual Void Write(Double value) { }
	// RVA: 0x6012a70 VA: 0x759862aa70
	public virtual Void Write(Int16 value) { }
	// RVA: 0x6012ad8 VA: 0x759862aad8
	public virtual Void Write(UInt16 value) { }
	// RVA: 0x6012b40 VA: 0x759862ab40
	public virtual Void Write(Int32 value) { }
	// RVA: 0x6012be0 VA: 0x759862abe0
	public virtual Void Write(UInt32 value) { }
	// RVA: 0x6012c80 VA: 0x759862ac80
	public virtual Void Write(Int64 value) { }
	// RVA: 0x6012d90 VA: 0x759862ad90
	public virtual Void Write(UInt64 value) { }
	// RVA: 0x6012ea0 VA: 0x759862aea0
	public virtual Void Write(Single value) { }
	// RVA: 0x6012edc VA: 0x759862aedc
	public virtual Void Write(String value) { }
	// RVA: 0x60131a0 VA: 0x759862b1a0
	protected Void Write7BitEncodedInt(Int32 value) { }
	// RVA: 0x6013200 VA: 0x759862b200
	private static Void .cctor() { }
}
```