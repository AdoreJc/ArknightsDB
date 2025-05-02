# PendingBuffer

**Namespace:** `ICSharpCode.SharpZipLib.Zip.Compression`


## Fields

- `Int32 start`

- `Int32 end`

- `UInt32 bits`

- `Int32 bitCount`


## Properties

- `Int32 BitCount`

- `Boolean IsFlushed`


## Methods

- `Void Reset()`

- `Void WriteShort(Int32)`

- `Void WriteBlock(Byte[], Int32, Int32)`

- `Int32 get_BitCount()`

- `Void AlignToByte()`

- `Void WriteBits(Int32, Int32)`

- `Void WriteShortMSB(Int32)`

- `Boolean get_IsFlushed()`

- `Int32 Flush(Byte[], Int32, Int32)`


## Dump
```C#
// Dll : ICSharpCode.SharpZipLib.dll
// Namespace : ICSharpCode.SharpZipLib.Zip.Compression
public class PendingBuffer
{
	private Byte[] buffer_; // 0x10
	private Int32 start; // 0x18
	private Int32 end; // 0x1c
	private UInt32 bits; // 0x20
	private Int32 bitCount; // 0x24

	public Int32 BitCount { get; }
	public Boolean IsFlushed { get; }

	// RVA: 0x5ecb384 VA: 0x75984e3384
	public Void .ctor(Int32 bufferSize) { }
	// RVA: 0x5ec7960 VA: 0x75984df960
	public Void Reset() { }
	// RVA: 0x5eca65c VA: 0x75984e265c
	public Void WriteShort(Int32 value) { }
	// RVA: 0x5eca6c4 VA: 0x75984e26c4
	public Void WriteBlock(Byte[] block, Int32 offset, Int32 length) { }
	// RVA: 0x5ecb3f4 VA: 0x75984e33f4
	public Int32 get_BitCount() { }
	// RVA: 0x5ec8104 VA: 0x75984e0104
	public Void AlignToByte() { }
	// RVA: 0x5ec8068 VA: 0x75984e0068
	public Void WriteBits(Int32 b, Int32 count) { }
	// RVA: 0x5ec7e18 VA: 0x75984dfe18
	public Void WriteShortMSB(Int32 s) { }
	// RVA: 0x5ec7a1c VA: 0x75984dfa1c
	public Boolean get_IsFlushed() { }
	// RVA: 0x5ec7ebc VA: 0x75984dfebc
	public Int32 Flush(Byte[] output, Int32 offset, Int32 length) { }
}
```