# RsassaPssParameters

**Namespace:** `Org.BouncyCastle.Asn1.Pkcs`


## Fields

- `AlgorithmIdentifier hashAlgorithm`

- `AlgorithmIdentifier maskGenAlgorithm`

- `DerInteger saltLength`

- `DerInteger trailerField`


## Properties

- `AlgorithmIdentifier HashAlgorithm`

- `AlgorithmIdentifier MaskGenAlgorithm`

- `DerInteger SaltLength`

- `DerInteger TrailerField`


## Methods

- `AlgorithmIdentifier get_HashAlgorithm()`

- `AlgorithmIdentifier get_MaskGenAlgorithm()`

- `DerInteger get_SaltLength()`

- `DerInteger get_TrailerField()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.Pkcs
public class RsassaPssParameters : Asn1Encodable
{
	private AlgorithmIdentifier hashAlgorithm; // 0x10
	private AlgorithmIdentifier maskGenAlgorithm; // 0x18
	private DerInteger saltLength; // 0x20
	private DerInteger trailerField; // 0x28
	public static readonly AlgorithmIdentifier DefaultHashAlgorithm; // 0x0
	public static readonly AlgorithmIdentifier DefaultMaskGenFunction; // 0x8
	public static readonly DerInteger DefaultSaltLength; // 0x10
	public static readonly DerInteger DefaultTrailerField; // 0x18

	public AlgorithmIdentifier HashAlgorithm { get; }
	public AlgorithmIdentifier MaskGenAlgorithm { get; }
	public DerInteger SaltLength { get; }
	public DerInteger TrailerField { get; }

	// RVA: 0x65d72a0 VA: 0x7598bef2a0
	public static RsassaPssParameters GetInstance(Object obj) { }
	// RVA: 0x65d768c VA: 0x7598bef68c
	public Void .ctor() { }
	// RVA: 0x65d7744 VA: 0x7598bef744
	public Void .ctor(AlgorithmIdentifier hashAlgorithm, AlgorithmIdentifier maskGenAlgorithm, DerInteger saltLength, DerInteger trailerField) { }
	// RVA: 0x65d7428 VA: 0x7598bef428
	public Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65d77b8 VA: 0x7598bef7b8
	public AlgorithmIdentifier get_HashAlgorithm() { }
	// RVA: 0x65d77c0 VA: 0x7598bef7c0
	public AlgorithmIdentifier get_MaskGenAlgorithm() { }
	// RVA: 0x65d77c8 VA: 0x7598bef7c8
	public DerInteger get_SaltLength() { }
	// RVA: 0x65d77d0 VA: 0x7598bef7d0
	public DerInteger get_TrailerField() { }
	// RVA: 0x65d77d8 VA: 0x7598bef7d8
	public override Asn1Object ToAsn1Object() { }
	// RVA: 0x65d7bf4 VA: 0x7598befbf4
	private static Void .cctor() { }
}
```