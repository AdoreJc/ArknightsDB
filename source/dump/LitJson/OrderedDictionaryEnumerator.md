# OrderedDictionaryEnumerator

**Namespace:** `LitJson`


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
// Dll : ThirdPartyAssembly.dll
// Namespace : LitJson
internal class OrderedDictionaryEnumerator : IDictionaryEnumerator, IEnumerator
{
	private IEnumerator`1 list_enumerator; // 0x10

	public Object Current { get; }
	public DictionaryEntry Entry { get; }
	public Object Key { get; }
	public Object Value { get; }

	// RVA: 0x65e71c0 VA: 0x7598bff1c0
	public Object get_Current() { }
	// RVA: 0x65e7224 VA: 0x7598bff224
	public DictionaryEntry get_Entry() { }
	// RVA: 0x65e730c VA: 0x7598bff30c
	public Object get_Key() { }
	// RVA: 0x65e73b8 VA: 0x7598bff3b8
	public Object get_Value() { }
	// RVA: 0x65e746c VA: 0x7598bff46c
	public Void .ctor(IEnumerator`1 enumerator) { }
	// RVA: 0x65e749c VA: 0x7598bff49c
	public Boolean MoveNext() { }
	// RVA: 0x65e753c VA: 0x7598bff53c
	public Void Reset() { }
}
```