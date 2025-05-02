# X509CertificateImplCollection

**Namespace:** `System.Security.Cryptography.X509Certificates`


## Properties

- `Int32 Count`

- `X509CertificateImpl Item`


## Methods

- `Int32 get_Count()`

- `X509CertificateImpl get_Item(Int32)`

- `Void Add(X509CertificateImpl, Boolean)`

- `X509CertificateImplCollection Clone()`

- `Void Dispose()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Security.Cryptography.X509Certificates
internal class X509CertificateImplCollection : IDisposable
{
	private List`1 list; // 0x10

	public Int32 Count { get; }
	public X509CertificateImpl Item { get; }

	// RVA: 0x63a5e10 VA: 0x75989bde10
	public Void .ctor() { }
	// RVA: 0x63a6cc8 VA: 0x75989becc8
	private Void .ctor(X509CertificateImplCollection other) { }
	// RVA: 0x63a6f08 VA: 0x75989bef08
	public Int32 get_Count() { }
	// RVA: 0x63a6f50 VA: 0x75989bef50
	public X509CertificateImpl get_Item(Int32 index) { }
	// RVA: 0x63a5e98 VA: 0x75989bde98
	public Void Add(X509CertificateImpl impl, Boolean takeOwnership) { }
	// RVA: 0x63a4c30 VA: 0x75989bcc30
	public X509CertificateImplCollection Clone() { }
	// RVA: 0x63a6fa8 VA: 0x75989befa8
	public Void Dispose() { }
	// RVA: 0x63a7014 VA: 0x75989bf014
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x63a7234 VA: 0x75989bf234
	protected override Void Finalize() { }
}
```