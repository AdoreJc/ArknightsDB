# QueueEnumerator

**Namespace:** ` `


## Fields

- `Queue _q`

- `Int32 _index`

- `Int32 _version`

- `Object _currentElement`


## Methods

- `Object Clone()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class QueueEnumerator : IEnumerator, ICloneable
{
	private Queue _q; // 0x10
	private Int32 _index; // 0x18
	private Int32 _version; // 0x1c
	private Object _currentElement; // 0x20

	public virtual Object Current { get; }

	// RVA: 0x607f238 VA: 0x7598697238
	internal Void .ctor(Queue q) { }
	// RVA: 0x607f468 VA: 0x7598697468
	public Object Clone() { }
	// RVA: 0x607f470 VA: 0x7598697470
	public virtual Boolean MoveNext() { }
	// RVA: 0x607f554 VA: 0x7598697554
	public virtual Object get_Current() { }
	// RVA: 0x607f5e8 VA: 0x75986975e8
	public virtual Void Reset() { }
}
```