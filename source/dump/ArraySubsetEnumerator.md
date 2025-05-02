# ArraySubsetEnumerator

**Namespace:** ` `


## Fields

- `Int32 _current`


## Properties

- `Object Current`


## Methods

- `Boolean MoveNext()`

- `Void Reset()`

- `Object get_Current()`


## Dump
```C#
// Dll : System.dll
// Namespace : 
private class ArraySubsetEnumerator : IEnumerator
{
	private readonly Array _array; // 0x10
	private readonly Int32 _total; // 0x18
	private Int32 _current; // 0x1c

	public Object Current { get; }

	// RVA: 0x63c2c48 VA: 0x75989dac48
	public Void .ctor(Array array, Int32 count) { }
	// RVA: 0x63c33f4 VA: 0x75989db3f4
	public Boolean MoveNext() { }
	// RVA: 0x63c341c VA: 0x75989db41c
	public Void Reset() { }
	// RVA: 0x63c3428 VA: 0x75989db428
	public Object get_Current() { }
}
```