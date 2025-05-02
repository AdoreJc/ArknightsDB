# SkeletonInput

**Namespace:** ` `


## Methods

- `Byte ReadByte()`

- `SByte ReadSByte()`

- `Boolean ReadBoolean()`

- `Single ReadFloat()`

- `Int32 ReadInt()`

- `Int32 ReadInt(Boolean)`

- `String ReadString()`

- `String ReadStringRef()`

- `Void ReadFully(Byte[], Int32, Int32)`

- `String GetVersionString()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : 
internal class SkeletonInput
{
	private Byte[] chars; // 0x10
	private Byte[] bytesBigEndian; // 0x18
	internal ExposedList`1 strings; // 0x20
	internal Stream input; // 0x28


	// RVA: 0x61e2094 VA: 0x75987fa094
	public Void .ctor(Stream input) { }
	// RVA: 0x61e2130 VA: 0x75987fa130
	public Byte ReadByte() { }
	// RVA: 0x61e2158 VA: 0x75987fa158
	public SByte ReadSByte() { }
	// RVA: 0x61e21c4 VA: 0x75987fa1c4
	public Boolean ReadBoolean() { }
	// RVA: 0x61e21f4 VA: 0x75987fa1f4
	public Single ReadFloat() { }
	// RVA: 0x61e2338 VA: 0x75987fa338
	public Int32 ReadInt() { }
	// RVA: 0x61e23bc VA: 0x75987fa3bc
	public Int32 ReadInt(Boolean optimizePositive) { }
	// RVA: 0x61e248c VA: 0x75987fa48c
	public String ReadString() { }
	// RVA: 0x61e2620 VA: 0x75987fa620
	public String ReadStringRef() { }
	// RVA: 0x61e2570 VA: 0x75987fa570
	public Void ReadFully(Byte[] buffer, Int32 offset, Int32 length) { }
	// RVA: 0x61e2674 VA: 0x75987fa674
	public String GetVersionString() { }
}
```