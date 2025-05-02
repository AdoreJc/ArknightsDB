# BitStack

**Namespace:** `System.Xml`


## Fields

- `Int32 stackPos`

- `UInt32 curr`


## Methods

- `Void PushBit(Boolean)`

- `Boolean PopBit()`

- `Boolean PeekBit()`

- `Void PushCurr()`

- `Void PopCurr()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class BitStack
{
	private UInt32[] bitStack; // 0x10
	private Int32 stackPos; // 0x18
	private UInt32 curr; // 0x1c


	// RVA: 0x6272294 VA: 0x759888a294
	public Void .ctor() { }
	// RVA: 0x62722b4 VA: 0x759888a2b4
	public Void PushBit(Boolean bit) { }
	// RVA: 0x62723e8 VA: 0x759888a3e8
	public Boolean PopBit() { }
	// RVA: 0x6272454 VA: 0x759888a454
	public Boolean PeekBit() { }
	// RVA: 0x62722ec VA: 0x759888a2ec
	private Void PushCurr() { }
	// RVA: 0x6272410 VA: 0x759888a410
	private Void PopCurr() { }
}
```