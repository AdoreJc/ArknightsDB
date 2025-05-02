# Enumerator

**Namespace:** ` `


## Fields

- `Int32 _index`

- `T _current`


## Properties

- `T Current`


## Methods

- `T get_Current()`

- `Void Dispose()`

- `Boolean MoveNext()`


## Dump
```C#
// Dll : System.Core.dll
// Namespace : 
private class Enumerator : IEnumerator`1, IDisposable, IEnumerator
{
	private readonly ReadOnlyCollectionBuilder`1 _builder; // 0x0
	private readonly Int32 _version; // 0x0
	private Int32 _index; // 0x0
	private T _current; // 0x0

	public T Current { get; }
	private Object System.Collections.IEnumerator.Current { get; }

	// RVA: 0x VA: 0x0
	internal Void .ctor(ReadOnlyCollectionBuilder`1 builder) { }
	// RVA: 0x VA: 0x0
	public T get_Current() { }
	// RVA: 0x VA: 0x0
	public Void Dispose() { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.IEnumerator.get_Current() { }
	// RVA: 0x VA: 0x0
	public Boolean MoveNext() { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IEnumerator.Reset() { }
}
```