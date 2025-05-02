# X509CertificateEnumerator

**Namespace:** ` `


## Fields

- `IEnumerator enumerator`


## Properties

- `X509Certificate Current`


## Methods

- `X509Certificate get_Current()`

- `Boolean MoveNext()`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : 
public class X509CertificateEnumerator : IEnumerator
{
	private IEnumerator enumerator; // 0x10

	public X509Certificate Current { get; }
	private Object System.Collections.IEnumerator.Current { get; }

	// RVA: 0x5ee2680 VA: 0x75984fa680
	public Void .ctor(X509CertificateCollection mappings) { }
	// RVA: 0x5ed9998 VA: 0x75984f1998
	public X509Certificate get_Current() { }
	// RVA: 0x5ee27fc VA: 0x75984fa7fc
	private Object System.Collections.IEnumerator.get_Current() { }
	// RVA: 0x5ee28a0 VA: 0x75984fa8a0
	private Boolean System.Collections.IEnumerator.MoveNext() { }
	// RVA: 0x5ee2940 VA: 0x75984fa940
	private Void System.Collections.IEnumerator.Reset() { }
	// RVA: 0x5ed9d84 VA: 0x75984f1d84
	public Boolean MoveNext() { }
}
```