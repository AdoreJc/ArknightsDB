# StreamManipulator

**Namespace:** `ICSharpCode.SharpZipLib.Zip.Compression.Streams`


## Fields

- `Int32 windowStart_`

- `Int32 windowEnd_`

- `UInt32 buffer_`

- `Int32 bitsInBuffer_`


## Properties

- `Int32 AvailableBits`

- `Int32 AvailableBytes`

- `Boolean IsNeedingInput`


## Methods

- `Int32 PeekBits(Int32)`

- `Void DropBits(Int32)`

- `Int32 get_AvailableBits()`

- `Int32 get_AvailableBytes()`

- `Void SkipToByteBoundary()`

- `Boolean get_IsNeedingInput()`

- `Int32 CopyBytes(Byte[], Int32, Int32)`

- `Void Reset()`

- `Void SetInput(Byte[], Int32, Int32)`


## Dump
```C#
// Dll : ICSharpCode.SharpZipLib.dll
// Namespace : ICSharpCode.SharpZipLib.Zip.Compression.Streams
public class StreamManipulator
{
	private Byte[] window_; // 0x10
	private Int32 windowStart_; // 0x18
	private Int32 windowEnd_; // 0x1c
	private UInt32 buffer_; // 0x20
	private Int32 bitsInBuffer_; // 0x24

	public Int32 AvailableBits { get; }
	public Int32 AvailableBytes { get; }
	public Boolean IsNeedingInput { get; }

	// RVA: 0x5ec72d8 VA: 0x75984df2d8
	public Void .ctor() { }
	// RVA: 0x5ec72e0 VA: 0x75984df2e0
	public Int32 PeekBits(Int32 bitCount) { }
	// RVA: 0x5ec7380 VA: 0x75984df380
	public Void DropBits(Int32 bitCount) { }
	// RVA: 0x5ec7394 VA: 0x75984df394
	public Int32 get_AvailableBits() { }
	// RVA: 0x5ec6fa0 VA: 0x75984defa0
	public Int32 get_AvailableBytes() { }
	// RVA: 0x5ec739c VA: 0x75984df39c
	public Void SkipToByteBoundary() { }
	// RVA: 0x5ec73b4 VA: 0x75984df3b4
	public Boolean get_IsNeedingInput() { }
	// RVA: 0x5ec6fb4 VA: 0x75984defb4
	public Int32 CopyBytes(Byte[] output, Int32 offset, Int32 length) { }
	// RVA: 0x5ec73c4 VA: 0x75984df3c4
	public Void Reset() { }
	// RVA: 0x5ec73cc VA: 0x75984df3cc
	public Void SetInput(Byte[] buffer, Int32 offset, Int32 count) { }
}
```