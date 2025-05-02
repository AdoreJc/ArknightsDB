# StackEnumerator

**Namespace:** ` `


## Fields

- `Stack _stack`

- `Int32 _index`

- `Int32 _version`

- `Object _currentElement`


## Methods

- `Object Clone()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class StackEnumerator : IEnumerator, ICloneable
{
	private Stack _stack; // 0x10
	private Int32 _index; // 0x18
	private Int32 _version; // 0x1c
	private Object _currentElement; // 0x20

	public virtual Object Current { get; }

	// RVA: 0x6083298 VA: 0x759869b298
	internal Void .ctor(Stack stack) { }
	// RVA: 0x6083540 VA: 0x759869b540
	public Object Clone() { }
	// RVA: 0x6083548 VA: 0x759869b548
	public virtual Boolean MoveNext() { }
	// RVA: 0x6083630 VA: 0x759869b630
	public virtual Object get_Current() { }
	// RVA: 0x60836c4 VA: 0x759869b6c4
	public virtual Void Reset() { }
}
```