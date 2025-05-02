# DictionaryEnumerator

**Namespace:** ` `


## Fields

- `MessageDictionary _methodDictionary`

- `IDictionaryEnumerator _hashtableEnum`

- `Int32 _posMethod`


## Properties

- `Object Current`

- `DictionaryEntry Entry`

- `Object Key`

- `Object Value`


## Methods

- `Object get_Current()`

- `Boolean MoveNext()`

- `Void Reset()`

- `DictionaryEntry get_Entry()`

- `Object get_Key()`

- `Object get_Value()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class DictionaryEnumerator : IDictionaryEnumerator, IEnumerator
{
	private MessageDictionary _methodDictionary; // 0x10
	private IDictionaryEnumerator _hashtableEnum; // 0x18
	private Int32 _posMethod; // 0x20

	public Object Current { get; }
	public DictionaryEntry Entry { get; }
	public Object Key { get; }
	public Object Value { get; }

	// RVA: 0x5fa8f4c VA: 0x75985c0f4c
	public Void .ctor(MessageDictionary methodDictionary) { }
	// RVA: 0x5fa90b0 VA: 0x75985c10b0
	public Object get_Current() { }
	// RVA: 0x5fa9280 VA: 0x75985c1280
	public Boolean MoveNext() { }
	// RVA: 0x5fa9444 VA: 0x75985c1444
	public Void Reset() { }
	// RVA: 0x5fa9114 VA: 0x75985c1114
	public DictionaryEntry get_Entry() { }
	// RVA: 0x5fa94f0 VA: 0x75985c14f0
	public Object get_Key() { }
	// RVA: 0x5fa94f4 VA: 0x75985c14f4
	public Object get_Value() { }
}
```