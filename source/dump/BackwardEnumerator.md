# BackwardEnumerator

**Namespace:** ` `


## Fields

- `Int32 m_cursor`

- `Boolean m_disposed`


## Properties

- `T Current`


## Methods

- `T get_Current()`

- `Boolean MoveNext()`

- `Void Reset()`

- `Void Reset(IList`1)`

- `Void Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
protected class BackwardEnumerator : IEnumerator`1, IEnumerator, IDisposable
{
	private IList`1 m_items; // 0x0
	private Int32 m_cursor; // 0x0
	private Boolean m_disposed; // 0x0
	private Action`1 m_onDisposed; // 0x0

	public T Current { get; }
	private Object System.Collections.IEnumerator.Current { get; }

	// RVA: 0x VA: 0x0
	public T get_Current() { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.IEnumerator.get_Current() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IList`1 items, Action`1 onDisposed) { }
	// RVA: 0x VA: 0x0
	public Boolean MoveNext() { }
	// RVA: 0x VA: 0x0
	public Void Reset() { }
	// RVA: 0x VA: 0x0
	public Void Reset(IList`1 items) { }
	// RVA: 0x VA: 0x0
	public Void Dispose() { }
}
```