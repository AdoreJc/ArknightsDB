# Gost3410PublicKeyAlgParameters

**Namespace:** `Org.BouncyCastle.Asn1.CryptoPro`


## Fields

- `DerObjectIdentifier publicKeyParamSet`

- `DerObjectIdentifier digestParamSet`

- `DerObjectIdentifier encryptionParamSet`


## Properties

- `DerObjectIdentifier PublicKeyParamSet`

- `DerObjectIdentifier DigestParamSet`

- `DerObjectIdentifier EncryptionParamSet`


## Methods

- `DerObjectIdentifier get_PublicKeyParamSet()`

- `DerObjectIdentifier get_DigestParamSet()`

- `DerObjectIdentifier get_EncryptionParamSet()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.CryptoPro
public class Gost3410PublicKeyAlgParameters : Asn1Encodable
{
	private DerObjectIdentifier publicKeyParamSet; // 0x10
	private DerObjectIdentifier digestParamSet; // 0x18
	private DerObjectIdentifier encryptionParamSet; // 0x20

	public DerObjectIdentifier PublicKeyParamSet { get; }
	public DerObjectIdentifier DigestParamSet { get; }
	public DerObjectIdentifier EncryptionParamSet { get; }

	// RVA: 0x65df704 VA: 0x7598bf7704
	public static Gost3410PublicKeyAlgParameters GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x65df71c VA: 0x7598bf771c
	public static Gost3410PublicKeyAlgParameters GetInstance(Object obj) { }
	// RVA: 0x65dfa9c VA: 0x7598bf7a9c
	public Void .ctor(DerObjectIdentifier publicKeyParamSet, DerObjectIdentifier digestParamSet) { }
	// RVA: 0x65dfaa4 VA: 0x7598bf7aa4
	public Void .ctor(DerObjectIdentifier publicKeyParamSet, DerObjectIdentifier digestParamSet, DerObjectIdentifier encryptionParamSet) { }
	// RVA: 0x65df894 VA: 0x7598bf7894
	public Void .ctor(Asn1Sequence seq) { }
	// RVA: 0x65dfb7c VA: 0x7598bf7b7c
	public DerObjectIdentifier get_PublicKeyParamSet() { }
	// RVA: 0x65dfb84 VA: 0x7598bf7b84
	public DerObjectIdentifier get_DigestParamSet() { }
	// RVA: 0x65dfb8c VA: 0x7598bf7b8c
	public DerObjectIdentifier get_EncryptionParamSet() { }
	// RVA: 0x65dfb94 VA: 0x7598bf7b94
	public override Asn1Object ToAsn1Object() { }
}
```