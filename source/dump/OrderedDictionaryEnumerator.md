# OrderedDictionaryEnumerator

**Namespace:** ` `


## Fields

- `Int32 _objectReturnType`

- `IEnumerator _arrayEnumerator`


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
// Dll : System.dll
// Namespace : 
private class OrderedDictionaryEnumerator : IDictionaryEnumerator, IEnumerator
{
	private Int32 _objectReturnType; // 0x10
	private IEnumerator _arrayEnumerator; // 0x18

	public Object Current { get; }
	public DictionaryEntry Entry { get; }
	public Object Key { get; }
	public Object Value { get; }

	// RVA: 0x640bd14 VA: 0x7598a23d14
	internal Void .ctor(ArrayList array, Int32 objectReturnType) { }
	// RVA: 0x640c3a4 VA: 0x7598a243a4
	public Object get_Current() { }
	// RVA: 0x640c550 VA: 0x7598a24550
	public DictionaryEntry get_Entry() { }
	// RVA: 0x640c6e4 VA: 0x7598a246e4
	public Object get_Key() { }
	// RVA: 0x640c7c8 VA: 0x7598a247c8
	public Object get_Value() { }
	// RVA: 0x640c8ac VA: 0x7598a248ac
	public Boolean MoveNext() { }
	// RVA: 0x640c94c VA: 0x7598a2494c
	public Void Reset() { }
}
```