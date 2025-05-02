# HashtableEnumerator

**Namespace:** ` `


## Fields

- `Hashtable _hashtable`

- `Int32 _bucket`

- `Int32 _version`

- `Boolean _current`

- `Int32 _getObjectRetType`

- `Object _currentKey`

- `Object _currentValue`


## Methods

- `Object Clone()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class HashtableEnumerator : IDictionaryEnumerator, IEnumerator, ICloneable
{
	private Hashtable _hashtable; // 0x10
	private Int32 _bucket; // 0x18
	private Int32 _version; // 0x1c
	private Boolean _current; // 0x20
	private Int32 _getObjectRetType; // 0x24
	private Object _currentKey; // 0x28
	private Object _currentValue; // 0x30

	public virtual Object Key { get; }
	public virtual DictionaryEntry Entry { get; }
	public virtual Object Current { get; }
	public virtual Object Value { get; }

	// RVA: 0x6089354 VA: 0x75986a1354
	internal Void .ctor(Hashtable hashtable, Int32 getObjRetType) { }
	// RVA: 0x608b898 VA: 0x75986a3898
	public Object Clone() { }
	// RVA: 0x608b8a0 VA: 0x75986a38a0
	public virtual Object get_Key() { }
	// RVA: 0x608b904 VA: 0x75986a3904
	public virtual Boolean MoveNext() { }
	// RVA: 0x608ba70 VA: 0x75986a3a70
	public virtual DictionaryEntry get_Entry() { }
	// RVA: 0x608bb0c VA: 0x75986a3b0c
	public virtual Object get_Current() { }
	// RVA: 0x608bc08 VA: 0x75986a3c08
	public virtual Object get_Value() { }
	// RVA: 0x608bc6c VA: 0x75986a3c6c
	public virtual Void Reset() { }
}
```