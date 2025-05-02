# ArraySubsetEnumerator

**Namespace:** `System.ComponentModel`


## Fields

- `Array array`

- `Int32 total`

- `Int32 current`


## Properties

- `Object Current`


## Methods

- `Boolean MoveNext()`

- `Void Reset()`

- `Object get_Current()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
internal class ArraySubsetEnumerator : IEnumerator
{
	private Array array; // 0x10
	private Int32 total; // 0x18
	private Int32 current; // 0x1c

	public Object Current { get; }

	// RVA: 0x63db874 VA: 0x75989f3874
	public Void .ctor(Array array, Int32 count) { }
	// RVA: 0x63db8b4 VA: 0x75989f38b4
	public Boolean MoveNext() { }
	// RVA: 0x63db8dc VA: 0x75989f38dc
	public Void Reset() { }
	// RVA: 0x63db8e8 VA: 0x75989f38e8
	public Object get_Current() { }
}
```