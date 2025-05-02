# NetDataWriter

**Namespace:** `FlyingWormConsole3.LiteNetLib.Utils`


## Fields

- `Int32 _position`


## Properties

- `Int32 Capacity`

- `Int32 Length`


## Methods

- `Int32 get_Capacity()`

- `Void ResizeIfNeed(Int32)`

- `Void Reset(Int32)`

- `Void Reset()`

- `Int32 get_Length()`

- `Int32 SetPosition(Int32)`

- `Void Put(Single)`

- `Void Put(Double)`

- `Void Put(Int64)`

- `Void Put(UInt64)`

- `Void Put(Int32)`

- `Void Put(UInt32)`

- `Void Put(Char)`

- `Void Put(UInt16)`

- `Void Put(Int16)`

- `Void Put(SByte)`

- `Void Put(Byte)`

- `Void Put(Byte[], Int32, Int32)`

- `Void Put(Byte[])`

- `Void PutSBytesWithLength(SByte[], Int32, Int32)`

- `Void PutSBytesWithLength(SByte[])`

- `Void PutBytesWithLength(Byte[], Int32, Int32)`

- `Void PutBytesWithLength(Byte[])`

- `Void Put(Boolean)`

- `Void PutArray(Array, Int32)`

- `Void PutArray(Single[])`

- `Void PutArray(Double[])`

- `Void PutArray(Int64[])`

- `Void PutArray(UInt64[])`

- `Void PutArray(Int32[])`

- `Void PutArray(UInt32[])`

- `Void PutArray(UInt16[])`

- `Void PutArray(Int16[])`

- `Void PutArray(Boolean[])`

- `Void PutArray(String[])`

- `Void PutArray(String[], Int32)`

- `Void Put(IPEndPoint)`

- `Void Put(String)`

- `Void Put(String, Int32)`

- `Void Put(T)`


## Dump
```C#
// Dll : ConsolePro.dll
// Namespace : FlyingWormConsole3.LiteNetLib.Utils
public class NetDataWriter
{
	protected Byte[] _data; // 0x10
	protected Int32 _position; // 0x18
	private const Int32 InitialSize; // 0x0
	private readonly Boolean _autoResize; // 0x1c

	public Int32 Capacity { get; }
	public Byte[] Data { get; }
	public Int32 Length { get; }

	// RVA: 0x410967c VA: 0x759672167c
	public Int32 get_Capacity() { }
	// RVA: 0x40f7f0c VA: 0x759670ff0c
	public Void .ctor() { }
	// RVA: 0x4109714 VA: 0x7596721714
	public Void .ctor(Boolean autoResize) { }
	// RVA: 0x4109698 VA: 0x7596721698
	public Void .ctor(Boolean autoResize, Int32 initialSize) { }
	// RVA: 0x4109720 VA: 0x7596721720
	public static NetDataWriter FromBytes(Byte[] bytes, Boolean copy) { }
	// RVA: 0x410984c VA: 0x759672184c
	public static NetDataWriter FromBytes(Byte[] bytes, Int32 offset, Int32 length) { }
	// RVA: 0x4100234 VA: 0x7596718234
	public static NetDataWriter FromString(String value) { }
	// RVA: 0x4109a10 VA: 0x7596721a10
	public Void ResizeIfNeed(Int32 newSize) { }
	// RVA: 0x4109a90 VA: 0x7596721a90
	public Void Reset(Int32 size) { }
	// RVA: 0x4109aa8 VA: 0x7596721aa8
	public Void Reset() { }
	// RVA: 0x4109ab0 VA: 0x7596721ab0
	public Byte[] CopyData() { }
	// RVA: 0x4109b24 VA: 0x7596721b24
	public Byte[] get_Data() { }
	// RVA: 0x4109b2c VA: 0x7596721b2c
	public Int32 get_Length() { }
	// RVA: 0x4109b34 VA: 0x7596721b34
	public Int32 SetPosition(Int32 position) { }
	// RVA: 0x4109b44 VA: 0x7596721b44
	public Void Put(Single value) { }
	// RVA: 0x4109b94 VA: 0x7596721b94
	public Void Put(Double value) { }
	// RVA: 0x4109be4 VA: 0x7596721be4
	public Void Put(Int64 value) { }
	// RVA: 0x4109c34 VA: 0x7596721c34
	public Void Put(UInt64 value) { }
	// RVA: 0x4109c84 VA: 0x7596721c84
	public Void Put(Int32 value) { }
	// RVA: 0x4109cd4 VA: 0x7596721cd4
	public Void Put(UInt32 value) { }
	// RVA: 0x4109d24 VA: 0x7596721d24
	public Void Put(Char value) { }
	// RVA: 0x4109d74 VA: 0x7596721d74
	public Void Put(UInt16 value) { }
	// RVA: 0x4109dc4 VA: 0x7596721dc4
	public Void Put(Int16 value) { }
	// RVA: 0x4109e14 VA: 0x7596721e14
	public Void Put(SByte value) { }
	// RVA: 0x4109e7c VA: 0x7596721e7c
	public Void Put(Byte value) { }
	// RVA: 0x41098d8 VA: 0x75967218d8
	public Void Put(Byte[] data, Int32 offset, Int32 length) { }
	// RVA: 0x41097d8 VA: 0x75967217d8
	public Void Put(Byte[] data) { }
	// RVA: 0x4109ee4 VA: 0x7596721ee4
	public Void PutSBytesWithLength(SByte[] data, Int32 offset, Int32 length) { }
	// RVA: 0x4109f70 VA: 0x7596721f70
	public Void PutSBytesWithLength(SByte[] data) { }
	// RVA: 0x410a000 VA: 0x7596722000
	public Void PutBytesWithLength(Byte[] data, Int32 offset, Int32 length) { }
	// RVA: 0x410a08c VA: 0x759672208c
	public Void PutBytesWithLength(Byte[] data) { }
	// RVA: 0x410a11c VA: 0x759672211c
	public Void Put(Boolean value) { }
	// RVA: 0x410a188 VA: 0x7596722188
	private Void PutArray(Array arr, Int32 sz) { }
	// RVA: 0x410a234 VA: 0x7596722234
	public Void PutArray(Single[] value) { }
	// RVA: 0x410a23c VA: 0x759672223c
	public Void PutArray(Double[] value) { }
	// RVA: 0x410a244 VA: 0x7596722244
	public Void PutArray(Int64[] value) { }
	// RVA: 0x410a24c VA: 0x759672224c
	public Void PutArray(UInt64[] value) { }
	// RVA: 0x410a254 VA: 0x7596722254
	public Void PutArray(Int32[] value) { }
	// RVA: 0x410a25c VA: 0x759672225c
	public Void PutArray(UInt32[] value) { }
	// RVA: 0x410a264 VA: 0x7596722264
	public Void PutArray(UInt16[] value) { }
	// RVA: 0x410a26c VA: 0x759672226c
	public Void PutArray(Int16[] value) { }
	// RVA: 0x410a274 VA: 0x7596722274
	public Void PutArray(Boolean[] value) { }
	// RVA: 0x410a27c VA: 0x759672227c
	public Void PutArray(String[] value) { }
	// RVA: 0x410a304 VA: 0x7596722304
	public Void PutArray(String[] value, Int32 maxLength) { }
	// RVA: 0x410a488 VA: 0x7596722488
	public Void Put(IPEndPoint endPoint) { }
	// RVA: 0x4109944 VA: 0x7596721944
	public Void Put(String value) { }
	// RVA: 0x410a3a0 VA: 0x75967223a0
	public Void Put(String value, Int32 maxLength) { }
	// RVA: 0x VA: 0x0
	public Void Put(T obj) { }
}
```