# NameObjectKeysEnumerator

**Namespace:** ` `


## Fields

- `Int32 _pos`

- `NameObjectCollectionBase _coll`

- `Int32 _version`


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
internal class NameObjectKeysEnumerator : IEnumerator
{
	private Int32 _pos; // 0x10
	private NameObjectCollectionBase _coll; // 0x18
	private Int32 _version; // 0x20

	public Object Current { get; }

	// RVA: 0x640e7c0 VA: 0x7598a267c0
	internal Void .ctor(NameObjectCollectionBase coll) { }
	// RVA: 0x640ec88 VA: 0x7598a26c88
	public Boolean MoveNext() { }
	// RVA: 0x640ed68 VA: 0x7598a26d68
	public Void Reset() { }
	// RVA: 0x640edf8 VA: 0x7598a26df8
	public Object get_Current() { }
}
```