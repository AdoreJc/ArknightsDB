# Chunk

**Namespace:** ` `


## Fields

- `Int32 Offset`


## Methods

- `Int32 Read(Byte[], Int32, Int32)`


## Dump
```C#
// Dll : System.dll
// Namespace : 
private class Chunk
{
	public Byte[] Bytes; // 0x10
	public Int32 Offset; // 0x18


	// RVA: 0x632f974 VA: 0x7598947974
	public Void .ctor(Byte[] chunk) { }
	// RVA: 0x632ee6c VA: 0x7598946e6c
	public Int32 Read(Byte[] buffer, Int32 offset, Int32 size) { }
}
```