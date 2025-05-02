# ByteBuffer

**Namespace:** `Google.FlatBuffers`


## Fields

- `ByteBufferAllocator _buffer`

- `Int32 _pos`


## Properties

- `Int32 Position`

- `Int32 Length`


## Methods

- `Int32 get_Position()`

- `Void set_Position(Int32)`

- `Int32 get_Length()`

- `Void Reset()`

- `ByteBuffer Duplicate()`

- `Void GrowFront(Int32)`

- `MemoryStream ToMemoryStream(Int32, Int32)`

- `Void WriteLittleEndian(Int32, Int32, UInt64)`

- `UInt64 ReadLittleEndian(Int32, Int32)`

- `Void AssertOffsetAndLength(Int32, Int32)`

- `Void PutSbyte(Int32, SByte)`

- `Void PutByte(Int32, Byte)`

- `Void PutByte(Int32, Byte, Int32)`

- `Void Put(Int32, Byte)`

- `Void PutStringUTF8(Int32, String)`

- `Void PutShort(Int32, Int16)`

- `Void PutUshort(Int32, UInt16)`

- `Void PutInt(Int32, Int32)`

- `Void PutUint(Int32, UInt32)`

- `Void PutLong(Int32, Int64)`

- `Void PutUlong(Int32, UInt64)`

- `Void PutFloat(Int32, Single)`

- `Void PutDouble(Int32, Double)`

- `SByte GetSbyte(Int32)`

- `Byte Get(Int32)`

- `String GetStringUTF8(Int32, Int32)`

- `Int16 GetShort(Int32)`

- `UInt16 GetUshort(Int32)`

- `Int32 GetInt(Int32)`

- `UInt32 GetUint(Int32)`

- `Int64 GetLong(Int32)`

- `UInt64 GetUlong(Int32)`

- `Single GetFloat(Int32)`

- `Double GetDouble(Int32)`

- `Int32 Put(Int32, T[])`

- `Int32 Put(Int32, ArraySegment`1)`

- `Int32 Put(Int32, IntPtr, Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Google.FlatBuffers
public class ByteBuffer
{
	private ByteBufferAllocator _buffer; // 0x10
	private Int32 _pos; // 0x18
	private static Dictionary`2 genericSizes; // 0x0

	public Int32 Position { get; set; }
	public Int32 Length { get; }

	// RVA: 0x66c677c VA: 0x7598cde77c
	public Void .ctor(ByteBufferAllocator allocator, Int32 position) { }
	// RVA: 0x66c67b8 VA: 0x7598cde7b8
	public Void .ctor(Int32 size) { }
	// RVA: 0x66c681c VA: 0x7598cde81c
	public Void .ctor(Byte[] buffer) { }
	// RVA: 0x66c6824 VA: 0x7598cde824
	public Void .ctor(Byte[] buffer, Int32 pos) { }
	// RVA: 0x66c68b0 VA: 0x7598cde8b0
	public Int32 get_Position() { }
	// RVA: 0x66c68b8 VA: 0x7598cde8b8
	public Void set_Position(Int32 value) { }
	// RVA: 0x66c68c0 VA: 0x7598cde8c0
	public Int32 get_Length() { }
	// RVA: 0x66c68dc VA: 0x7598cde8dc
	public Void Reset() { }
	// RVA: 0x66c68e4 VA: 0x7598cde8e4
	public ByteBuffer Duplicate() { }
	// RVA: 0x66c6968 VA: 0x7598cde968
	public Void GrowFront(Int32 newSize) { }
	// RVA: 0x66c6988 VA: 0x7598cde988
	public Byte[] ToArray(Int32 pos, Int32 len) { }
	// RVA: 0x VA: 0x0
	public static Int32 SizeOf() { }
	// RVA: 0x VA: 0x0
	public static Boolean IsSupportedType() { }
	// RVA: 0x VA: 0x0
	public static Int32 ArraySize(T[] x) { }
	// RVA: 0x VA: 0x0
	public static Int32 ArraySize(ArraySegment`1 x) { }
	// RVA: 0x VA: 0x0
	public T[] ToArray(Int32 pos, Int32 len) { }
	// RVA: 0x66c69e8 VA: 0x7598cde9e8
	public Byte[] ToSizedArray() { }
	// RVA: 0x66c6a48 VA: 0x7598cdea48
	public Byte[] ToFullArray() { }
	// RVA: 0x66c6aa4 VA: 0x7598cdeaa4
	public ArraySegment`1 ToArraySegment(Int32 pos, Int32 len) { }
	// RVA: 0x66c6b28 VA: 0x7598cdeb28
	public MemoryStream ToMemoryStream(Int32 pos, Int32 len) { }
	// RVA: 0x66c6bb0 VA: 0x7598cdebb0
	public static UInt16 ReverseBytes(UInt16 input) { }
	// RVA: 0x66c6bbc VA: 0x7598cdebbc
	public static UInt32 ReverseBytes(UInt32 input) { }
	// RVA: 0x66c6bc4 VA: 0x7598cdebc4
	public static UInt64 ReverseBytes(UInt64 input) { }
	// RVA: 0x66c6bcc VA: 0x7598cdebcc
	protected Void WriteLittleEndian(Int32 offset, Int32 count, UInt64 data) { }
	// RVA: 0x66c6d04 VA: 0x7598cded04
	protected UInt64 ReadLittleEndian(Int32 offset, Int32 count) { }
	// RVA: 0x66c6e58 VA: 0x7598cdee58
	private Void AssertOffsetAndLength(Int32 offset, Int32 length) { }
	// RVA: 0x66c6ec0 VA: 0x7598cdeec0
	public Void PutSbyte(Int32 offset, SByte value) { }
	// RVA: 0x66c6f14 VA: 0x7598cdef14
	public Void PutByte(Int32 offset, Byte value) { }
	// RVA: 0x66c6f68 VA: 0x7598cdef68
	public Void PutByte(Int32 offset, Byte value, Int32 count) { }
	// RVA: 0x66c6ff0 VA: 0x7598cdeff0
	public Void Put(Int32 offset, Byte value) { }
	// RVA: 0x66c6ff4 VA: 0x7598cdeff4
	public Void PutStringUTF8(Int32 offset, String value) { }
	// RVA: 0x66c7058 VA: 0x7598cdf058
	public Void PutShort(Int32 offset, Int16 value) { }
	// RVA: 0x66c7090 VA: 0x7598cdf090
	public Void PutUshort(Int32 offset, UInt16 value) { }
	// RVA: 0x66c70c8 VA: 0x7598cdf0c8
	public Void PutInt(Int32 offset, Int32 value) { }
	// RVA: 0x66c7100 VA: 0x7598cdf100
	public Void PutUint(Int32 offset, UInt32 value) { }
	// RVA: 0x66c7138 VA: 0x7598cdf138
	public Void PutLong(Int32 offset, Int64 value) { }
	// RVA: 0x66c7170 VA: 0x7598cdf170
	public Void PutUlong(Int32 offset, UInt64 value) { }
	// RVA: 0x66c71a8 VA: 0x7598cdf1a8
	public Void PutFloat(Int32 offset, Single value) { }
	// RVA: 0x66c71ec VA: 0x7598cdf1ec
	public Void PutDouble(Int32 offset, Double value) { }
	// RVA: 0x66c7274 VA: 0x7598cdf274
	public SByte GetSbyte(Int32 index) { }
	// RVA: 0x66c72c4 VA: 0x7598cdf2c4
	public Byte Get(Int32 index) { }
	// RVA: 0x66c7314 VA: 0x7598cdf314
	public String GetStringUTF8(Int32 startPos, Int32 len) { }
	// RVA: 0x66c7364 VA: 0x7598cdf364
	public Int16 GetShort(Int32 index) { }
	// RVA: 0x66c7378 VA: 0x7598cdf378
	public UInt16 GetUshort(Int32 index) { }
	// RVA: 0x66c738c VA: 0x7598cdf38c
	public Int32 GetInt(Int32 index) { }
	// RVA: 0x66c73a0 VA: 0x7598cdf3a0
	public UInt32 GetUint(Int32 index) { }
	// RVA: 0x66c73b4 VA: 0x7598cdf3b4
	public Int64 GetLong(Int32 index) { }
	// RVA: 0x66c73bc VA: 0x7598cdf3bc
	public UInt64 GetUlong(Int32 index) { }
	// RVA: 0x66c73c4 VA: 0x7598cdf3c4
	public Single GetFloat(Int32 index) { }
	// RVA: 0x66c73dc VA: 0x7598cdf3dc
	public Double GetDouble(Int32 index) { }
	// RVA: 0x VA: 0x0
	public Int32 Put(Int32 offset, T[] x) { }
	// RVA: 0x VA: 0x0
	public Int32 Put(Int32 offset, ArraySegment`1 x) { }
	// RVA: 0x VA: 0x0
	public Int32 Put(Int32 offset, IntPtr ptr, Int32 sizeInBytes) { }
	// RVA: 0x66c7454 VA: 0x7598cdf454
	private static Void .cctor() { }
}
```