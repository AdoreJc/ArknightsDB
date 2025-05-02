# BufferOffsetSize

**Namespace:** `Mono.Net.Security`


## Fields

- `Int32 Offset`

- `Int32 Size`

- `Int32 TotalBytes`

- `Boolean Complete`


## Properties

- `Int32 EndOffset`

- `Int32 Remaining`


## Methods

- `Int32 get_EndOffset()`

- `Int32 get_Remaining()`


## Dump
```C#
// Dll : System.dll
// Namespace : Mono.Net.Security
internal class BufferOffsetSize
{
	public Byte[] Buffer; // 0x10
	public Int32 Offset; // 0x18
	public Int32 Size; // 0x1c
	public Int32 TotalBytes; // 0x20
	public Boolean Complete; // 0x24

	public Int32 EndOffset { get; }
	public Int32 Remaining { get; }

	// RVA: 0x6259db4 VA: 0x7598871db4
	public Int32 get_EndOffset() { }
	// RVA: 0x6259dc0 VA: 0x7598871dc0
	public Int32 get_Remaining() { }
	// RVA: 0x6259de8 VA: 0x7598871de8
	public Void .ctor(Byte[] buffer, Int32 offset, Int32 size) { }
	// RVA: 0x6259ef8 VA: 0x7598871ef8
	public override String ToString() { }
}
```