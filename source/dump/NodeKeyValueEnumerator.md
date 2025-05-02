# NodeKeyValueEnumerator

**Namespace:** ` `


## Fields

- `ListDictionaryInternal list`

- `DictionaryNode current`

- `Int32 version`

- `Boolean isKeys`

- `Boolean start`


## Properties

- `Object Current`


## Methods

- `Object get_Current()`

- `Boolean MoveNext()`

- `Void Reset()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class NodeKeyValueEnumerator : IEnumerator
{
	private ListDictionaryInternal list; // 0x10
	private DictionaryNode current; // 0x18
	private Int32 version; // 0x20
	private Boolean isKeys; // 0x24
	private Boolean start; // 0x25

	public Object Current { get; }

	// RVA: 0x607d2ac VA: 0x75986952ac
	public Void .ctor(ListDictionaryInternal list, Boolean isKeys) { }
	// RVA: 0x607d318 VA: 0x7598695318
	public Object get_Current() { }
	// RVA: 0x607d390 VA: 0x7598695390
	public Boolean MoveNext() { }
	// RVA: 0x607d458 VA: 0x7598695458
	public Void Reset() { }
}
```