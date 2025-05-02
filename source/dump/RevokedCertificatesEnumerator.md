# RevokedCertificatesEnumerator

**Namespace:** ` `


## Properties

- `Object Current`


## Methods

- `Boolean MoveNext()`

- `Void Reset()`

- `Object get_Current()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
private class RevokedCertificatesEnumerator : IEnumerator
{
	private readonly IEnumerator e; // 0x10

	public Object Current { get; }

	// RVA: 0x65b75c4 VA: 0x7598bcf5c4
	internal Void .ctor(IEnumerator e) { }
	// RVA: 0x65b75f4 VA: 0x7598bcf5f4
	public Boolean MoveNext() { }
	// RVA: 0x65b7694 VA: 0x7598bcf694
	public Void Reset() { }
	// RVA: 0x65b7738 VA: 0x7598bcf738
	public Object get_Current() { }
}
```