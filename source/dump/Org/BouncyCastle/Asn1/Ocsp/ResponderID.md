# ResponderID

**Namespace:** `Org.BouncyCastle.Asn1.Ocsp`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.Ocsp
public class ResponderID : Asn1Encodable, IAsn1Choice
{
	private readonly Asn1Encodable id; // 0x10

	public virtual X509Name Name { get; }

	// RVA: 0x65d9560 VA: 0x7598bf1560
	public static ResponderID GetInstance(Object obj) { }
	// RVA: 0x65d974c VA: 0x7598bf174c
	public Void .ctor(Asn1OctetString id) { }
	// RVA: 0x65d97cc VA: 0x7598bf17cc
	public Void .ctor(X509Name id) { }
	// RVA: 0x65d984c VA: 0x7598bf184c
	public static ResponderID GetInstance(Asn1TaggedObject obj, Boolean isExplicit) { }
	// RVA: 0x65d9868 VA: 0x7598bf1868
	public virtual Byte[] GetKeyHash() { }
	// RVA: 0x65d98f0 VA: 0x7598bf18f0
	public virtual X509Name get_Name() { }
	// RVA: 0x65d99a0 VA: 0x7598bf19a0
	public override Asn1Object ToAsn1Object() { }
}
```