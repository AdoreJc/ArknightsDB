# X509Extension

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Properties

- `Boolean IsCritical`

- `Asn1OctetString Value`


## Methods

- `Boolean get_IsCritical()`

- `Asn1OctetString get_Value()`

- `Asn1Encodable GetParsedValue()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class X509Extension
{
	internal Boolean critical; // 0x10
	internal Asn1OctetString value; // 0x18

	public Boolean IsCritical { get; }
	public Asn1OctetString Value { get; }

	// RVA: 0x65b87ac VA: 0x7598bd07ac
	public Void .ctor(DerBoolean critical, Asn1OctetString value) { }
	// RVA: 0x65b8844 VA: 0x7598bd0844
	public Void .ctor(Boolean critical, Asn1OctetString value) { }
	// RVA: 0x65b887c VA: 0x7598bd087c
	public Boolean get_IsCritical() { }
	// RVA: 0x65b8884 VA: 0x7598bd0884
	public Asn1OctetString get_Value() { }
	// RVA: 0x65b888c VA: 0x7598bd088c
	public Asn1Encodable GetParsedValue() { }
	// RVA: 0x65b8890 VA: 0x7598bd0890
	public override Int32 GetHashCode() { }
	// RVA: 0x65b88c4 VA: 0x7598bd08c4
	public override Boolean Equals(Object obj) { }
	// RVA: 0x65afb6c VA: 0x7598bc7b6c
	public static Asn1Object ConvertValueToObject(X509Extension ext) { }
}
```