# EmptyInternalEnumerator

**Namespace:** ` `


## Properties

- `T Current`


## Methods

- `Void Dispose()`

- `Boolean MoveNext()`

- `T get_Current()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
internal class EmptyInternalEnumerator`1 : IEnumerator`1, IDisposable, IEnumerator
{
	public static readonly EmptyInternalEnumerator`1 Value; // 0x0

	public T Current { get; }
	private Object System.Collections.IEnumerator.Current { get; }

	// RVA: 0x VA: 0x0
	public Void Dispose() { }
	// RVA: 0x VA: 0x0
	public Boolean MoveNext() { }
	// RVA: 0x VA: 0x0
	public T get_Current() { }
	// RVA: 0x VA: 0x0
	private Object System.Collections.IEnumerator.get_Current() { }
	// RVA: 0x VA: 0x0
	private Void System.Collections.IEnumerator.Reset() { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	private static Void .cctor() { }
}
```