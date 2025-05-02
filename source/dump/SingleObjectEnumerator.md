# SingleObjectEnumerator

**Namespace:** ` `


## Fields

- `Object loneValue`

- `Int32 position`


## Properties

- `Object Current`


## Methods

- `Object get_Current()`

- `Boolean MoveNext()`

- `Void Reset()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : 
private class SingleObjectEnumerator : IEnumerator
{
	private Object loneValue; // 0x10
	private Int32 position; // 0x18

	public Object Current { get; }

	// RVA: 0x62b56ac VA: 0x75988cd6ac
	public Void .ctor(Object value) { }
	// RVA: 0x62b56e4 VA: 0x75988cd6e4
	public Object get_Current() { }
	// RVA: 0x62b5738 VA: 0x75988cd738
	public Boolean MoveNext() { }
	// RVA: 0x62b5754 VA: 0x75988cd754
	public Void Reset() { }
}
```