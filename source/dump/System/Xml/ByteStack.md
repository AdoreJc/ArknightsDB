# ByteStack

**Namespace:** `System.Xml`


## Fields

- `Int32 growthRate`

- `Int32 top`

- `Int32 size`


## Methods

- `Void Push(Byte)`

- `Byte Pop()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class ByteStack
{
	private Byte[] stack; // 0x10
	private Int32 growthRate; // 0x18
	private Int32 top; // 0x1c
	private Int32 size; // 0x20


	// RVA: 0x62725c0 VA: 0x759888a5c0
	public Void .ctor(Int32 growthRate) { }
	// RVA: 0x627263c VA: 0x759888a63c
	public Void Push(Byte data) { }
	// RVA: 0x627271c VA: 0x759888a71c
	public Byte Pop() { }
}
```