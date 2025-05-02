# X509CertificateCollection

**Namespace:** `Mono.Security.X509`


## Properties

- `X509Certificate Item`


## Methods

- `X509Certificate get_Item(Int32)`

- `Int32 Add(X509Certificate)`

- `Void AddRange(X509CertificateCollection)`

- `Boolean Contains(X509Certificate)`

- `X509CertificateEnumerator GetEnumerator()`

- `Int32 IndexOf(X509Certificate)`

- `Boolean Compare(Byte[], Byte[])`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.X509
public class X509CertificateCollection : CollectionBase, IEnumerable
{

	public X509Certificate Item { get; }

	// RVA: 0x5ed5fb8 VA: 0x75984edfb8
	public Void .ctor() { }
	// RVA: 0x5ee23b0 VA: 0x75984fa3b0
	public X509Certificate get_Item(Int32 index) { }
	// RVA: 0x5ed6154 VA: 0x75984ee154
	public Int32 Add(X509Certificate value) { }
	// RVA: 0x5ee2448 VA: 0x75984fa448
	public Void AddRange(X509CertificateCollection value) { }
	// RVA: 0x5ee251c VA: 0x75984fa51c
	public Boolean Contains(X509Certificate value) { }
	// RVA: 0x5ed9938 VA: 0x75984f1938
	public X509CertificateEnumerator GetEnumerator() { }
	// RVA: 0x5ee273c VA: 0x75984fa73c
	private IEnumerator System.Collections.IEnumerable.GetEnumerator() { }
	// RVA: 0x5ee2760 VA: 0x75984fa760
	public override Int32 GetHashCode() { }
	// RVA: 0x5ee2534 VA: 0x75984fa534
	public Int32 IndexOf(X509Certificate value) { }
	// RVA: 0x5ee2780 VA: 0x75984fa780
	private Boolean Compare(Byte[] array1, Byte[] array2) { }
}
```