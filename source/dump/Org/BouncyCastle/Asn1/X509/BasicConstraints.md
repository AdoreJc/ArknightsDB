# BasicConstraints

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Properties

- `BigInteger PathLenConstraint`


## Methods

- `Boolean IsCA()`

- `BigInteger get_PathLenConstraint()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class BasicConstraints : Asn1Encodable
{
	private readonly DerBoolean cA; // 0x10
	private readonly DerInteger pathLenConstraint; // 0x18

	public BigInteger PathLenConstraint { get; }

	// RVA: 0x65af798 VA: 0x7598bc7798
	public static BasicConstraints GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65af7b0 VA: 0x7598bc77b0
	public static BasicConstraints GetInstance(Object obj) { }
	// RVA: 0x65af984 VA: 0x7598bc7984
	private Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65afc74 VA: 0x7598bc7c74
	public Void .ctor(Boolean cA) { }
	// RVA: 0x65afcf8 VA: 0x7598bc7cf8
	public Void .ctor(Int32 pathLenConstraint) { }
	// RVA: 0x65afdb8 VA: 0x7598bc7db8
	public Boolean IsCA() { }
	// RVA: 0x65afdcc VA: 0x7598bc7dcc
	public BigInteger get_PathLenConstraint() { }
	// RVA: 0x65afde0 VA: 0x7598bc7de0
	public override Asn1Object ToAsn1Object() { }
	// RVA: 0x65affb4 VA: 0x7598bc7fb4
	public override String ToString() { }
}
```