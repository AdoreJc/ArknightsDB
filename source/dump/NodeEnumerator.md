# NodeEnumerator

**Namespace:** ` `


## Fields

- `ListDictionaryInternal list`

- `DictionaryNode current`

- `Int32 version`

- `Boolean start`


## Properties

- `Object Current`

- `DictionaryEntry Entry`

- `Object Key`

- `Object Value`


## Methods

- `Object get_Current()`

- `DictionaryEntry get_Entry()`

- `Object get_Key()`

- `Object get_Value()`

- `Boolean MoveNext()`

- `Void Reset()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class NodeEnumerator : IDictionaryEnumerator, IEnumerator
{
	private ListDictionaryInternal list; // 0x10
	private DictionaryNode current; // 0x18
	private Int32 version; // 0x20
	private Boolean start; // 0x24

	public Object Current { get; }
	public DictionaryEntry Entry { get; }
	public Object Key { get; }
	public Object Value { get; }

	// RVA: 0x607cb3c VA: 0x7598694b3c
	public Void .ctor(ListDictionaryInternal list) { }
	// RVA: 0x607ccfc VA: 0x7598694cfc
	public Object get_Current() { }
	// RVA: 0x607cd60 VA: 0x7598694d60
	public DictionaryEntry get_Entry() { }
	// RVA: 0x607cdfc VA: 0x7598694dfc
	public Object get_Key() { }
	// RVA: 0x607ce60 VA: 0x7598694e60
	public Object get_Value() { }
	// RVA: 0x607cec4 VA: 0x7598694ec4
	public Boolean MoveNext() { }
	// RVA: 0x607cf8c VA: 0x7598694f8c
	public Void Reset() { }
}
```