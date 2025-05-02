# PropertyDescriptorEnumerator

**Namespace:** ` `


## Fields

- `PropertyDescriptorCollection _owner`

- `Int32 _index`


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
private class PropertyDescriptorEnumerator : IDictionaryEnumerator, IEnumerator
{
	private PropertyDescriptorCollection _owner; // 0x10
	private Int32 _index; // 0x18

	public Object Current { get; }
	public DictionaryEntry Entry { get; }
	public Object Key { get; }
	public Object Value { get; }

	// RVA: 0x63d387c VA: 0x75989eb87c
	public Void .ctor(PropertyDescriptorCollection owner) { }
	// RVA: 0x63d4518 VA: 0x75989ec518
	public Object get_Current() { }
	// RVA: 0x63d457c VA: 0x75989ec57c
	public DictionaryEntry get_Entry() { }
	// RVA: 0x63d45e4 VA: 0x75989ec5e4
	public Object get_Key() { }
	// RVA: 0x63d4620 VA: 0x75989ec620
	public Object get_Value() { }
	// RVA: 0x63d465c VA: 0x75989ec65c
	public Boolean MoveNext() { }
	// RVA: 0x63d469c VA: 0x75989ec69c
	public Void Reset() { }
}
```