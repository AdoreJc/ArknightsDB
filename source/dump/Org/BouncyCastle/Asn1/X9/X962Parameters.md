# X962Parameters

**Namespace:** `Org.BouncyCastle.Asn1.X9`


## Properties

- `Boolean IsNamedCurve`

- `Boolean IsImplicitlyCA`

- `Asn1Object Parameters`


## Methods

- `Boolean get_IsNamedCurve()`

- `Boolean get_IsImplicitlyCA()`

- `Asn1Object get_Parameters()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X9
public class X962Parameters : Asn1Encodable, IAsn1Choice
{
	private readonly Asn1Object _params; // 0x10

	public Boolean IsNamedCurve { get; }
	public Boolean IsImplicitlyCA { get; }
	public Asn1Object Parameters { get; }

	// RVA: 0x65ab83c VA: 0x7598bc383c
	public static X962Parameters GetInstance(Object obj) { }
	// RVA: 0x65abb40 VA: 0x7598bc3b40
	public Void .ctor(X9ECParameters ecParameters) { }
	// RVA: 0x65abb88 VA: 0x7598bc3b88
	public Void .ctor(DerObjectIdentifier namedCurve) { }
	// RVA: 0x65abb10 VA: 0x7598bc3b10
	public Void .ctor(Asn1Object obj) { }
	// RVA: 0x65abbb8 VA: 0x7598bc3bb8
	public Boolean get_IsNamedCurve() { }
	// RVA: 0x65abc34 VA: 0x7598bc3c34
	public Boolean get_IsImplicitlyCA() { }
	// RVA: 0x65abcb0 VA: 0x7598bc3cb0
	public Asn1Object get_Parameters() { }
	// RVA: 0x65abcb8 VA: 0x7598bc3cb8
	public override Asn1Object ToAsn1Object() { }
}
```