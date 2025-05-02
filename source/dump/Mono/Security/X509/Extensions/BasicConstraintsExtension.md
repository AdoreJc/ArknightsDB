# BasicConstraintsExtension

**Namespace:** `Mono.Security.X509.Extensions`


## Fields

- `Boolean cA`

- `Int32 pathLenConstraint`


## Properties

- `Boolean CertificateAuthority`


## Methods

- `Boolean get_CertificateAuthority()`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.X509.Extensions
public class BasicConstraintsExtension : X509Extension
{
	private Boolean cA; // 0x28
	private Int32 pathLenConstraint; // 0x2c

	public Boolean CertificateAuthority { get; }

	// RVA: 0x5ee36b8 VA: 0x75984fb6b8
	public Void .ctor(X509Extension extension) { }
	// RVA: 0x5ee541c VA: 0x75984fd41c
	protected override Void Decode() { }
	// RVA: 0x5ee5554 VA: 0x75984fd554
	protected override Void Encode() { }
	// RVA: 0x5ee56bc VA: 0x75984fd6bc
	public Boolean get_CertificateAuthority() { }
	// RVA: 0x5ee56c4 VA: 0x75984fd6c4
	public override String ToString() { }
}
```