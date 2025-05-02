# OutputWindow

**Namespace:** `ICSharpCode.SharpZipLib.Zip.Compression.Streams`


## Fields

- `Int32 windowEnd`

- `Int32 windowFilled`


## Methods

- `Void Write(Int32)`

- `Void SlowRepeat(Int32, Int32, Int32)`

- `Void Repeat(Int32, Int32)`

- `Int32 CopyStored(StreamManipulator, Int32)`

- `Int32 GetFreeSpace()`

- `Int32 GetAvailable()`

- `Int32 CopyOutput(Byte[], Int32, Int32)`

- `Void Reset()`


## Dump
```C#
// Dll : ICSharpCode.SharpZipLib.dll
// Namespace : ICSharpCode.SharpZipLib.Zip.Compression.Streams
public class OutputWindow
{
	private Byte[] window; // 0x10
	private Int32 windowEnd; // 0x18
	private Int32 windowFilled; // 0x1c


	// RVA: 0x5ec6c50 VA: 0x75984dec50
	public Void Write(Int32 value) { }
	// RVA: 0x5ec6cf8 VA: 0x75984decf8
	private Void SlowRepeat(Int32 repStart, Int32 length, Int32 distance) { }
	// RVA: 0x5ec6d6c VA: 0x75984ded6c
	public Void Repeat(Int32 length, Int32 distance) { }
	// RVA: 0x5ec6ea4 VA: 0x75984deea4
	public Int32 CopyStored(StreamManipulator input, Int32 length) { }
	// RVA: 0x5ec715c VA: 0x75984df15c
	public Int32 GetFreeSpace() { }
	// RVA: 0x5ec716c VA: 0x75984df16c
	public Int32 GetAvailable() { }
	// RVA: 0x5ec7174 VA: 0x75984df174
	public Int32 CopyOutput(Byte[] output, Int32 offset, Int32 len) { }
	// RVA: 0x5ec726c VA: 0x75984df26c
	public Void Reset() { }
	// RVA: 0x5ec7274 VA: 0x75984df274
	public Void .ctor() { }
}
```