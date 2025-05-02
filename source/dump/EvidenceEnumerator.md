# EvidenceEnumerator

**Namespace:** ` `


## Fields

- `IEnumerator currentEnum`

- `IEnumerator hostEnum`

- `IEnumerator assemblyEnum`


## Properties

- `Object Current`


## Methods

- `Boolean MoveNext()`

- `Void Reset()`

- `Object get_Current()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class EvidenceEnumerator : IEnumerator
{
	private IEnumerator currentEnum; // 0x10
	private IEnumerator hostEnum; // 0x18
	private IEnumerator assemblyEnum; // 0x20

	public Object Current { get; }

	// RVA: 0x5f45a84 VA: 0x759855da84
	public Void .ctor(IEnumerator hostenum, IEnumerator assemblyenum) { }
	// RVA: 0x5f45ae4 VA: 0x759855dae4
	public Boolean MoveNext() { }
	// RVA: 0x5f45c30 VA: 0x759855dc30
	public Void Reset() { }
	// RVA: 0x5f45d58 VA: 0x759855dd58
	public Object get_Current() { }
}
```