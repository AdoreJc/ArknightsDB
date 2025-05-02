# SortedListEnumerator

**Namespace:** ` `


## Fields

- `SortedList _sortedList`

- `Object _key`

- `Object _value`

- `Int32 _index`

- `Int32 _startIndex`

- `Int32 _endIndex`

- `Int32 _version`

- `Boolean _current`

- `Int32 _getObjectRetType`


## Methods

- `Object Clone()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class SortedListEnumerator : IDictionaryEnumerator, IEnumerator, ICloneable
{
	private SortedList _sortedList; // 0x10
	private Object _key; // 0x18
	private Object _value; // 0x20
	private Int32 _index; // 0x28
	private Int32 _startIndex; // 0x2c
	private Int32 _endIndex; // 0x30
	private Int32 _version; // 0x34
	private Boolean _current; // 0x38
	private Int32 _getObjectRetType; // 0x3c

	public virtual Object Key { get; }
	public virtual DictionaryEntry Entry { get; }
	public virtual Object Current { get; }
	public virtual Object Value { get; }

	// RVA: 0x6080598 VA: 0x7598698598
	internal Void .ctor(SortedList sortedList, Int32 index, Int32 count, Int32 getObjRetType) { }
	// RVA: 0x6081eb0 VA: 0x7598699eb0
	public Object Clone() { }
	// RVA: 0x6081eb8 VA: 0x7598699eb8
	public virtual Object get_Key() { }
	// RVA: 0x6081f5c VA: 0x7598699f5c
	public virtual Boolean MoveNext() { }
	// RVA: 0x6082090 VA: 0x759869a090
	public virtual DictionaryEntry get_Entry() { }
	// RVA: 0x608216c VA: 0x759869a16c
	public virtual Object get_Current() { }
	// RVA: 0x6082268 VA: 0x759869a268
	public virtual Object get_Value() { }
	// RVA: 0x608230c VA: 0x759869a30c
	public virtual Void Reset() { }
}
```