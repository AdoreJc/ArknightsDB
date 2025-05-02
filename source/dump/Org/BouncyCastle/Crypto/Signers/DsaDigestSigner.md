# DsaDigestSigner

**Namespace:** `Org.BouncyCastle.Crypto.Signers`


## Fields

- `Boolean forSigning`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Signers
public class DsaDigestSigner : ISigner
{
	private readonly IDigest digest; // 0x10
	private readonly IDsa dsaSigner; // 0x18
	private Boolean forSigning; // 0x20

	public virtual String AlgorithmName { get; }

	// RVA: 0x6507840 VA: 0x7598b1f840
	public Void .ctor(IDsa signer, IDigest digest) { }
	// RVA: 0x6507884 VA: 0x7598b1f884
	public virtual String get_AlgorithmName() { }
	// RVA: 0x65079c4 VA: 0x7598b1f9c4
	public virtual Void Init(Boolean forSigning, ICipherParameters parameters) { }
	// RVA: 0x6507bec VA: 0x7598b1fbec
	public virtual Void Update(Byte input) { }
	// RVA: 0x6507c98 VA: 0x7598b1fc98
	public virtual Void BlockUpdate(Byte[] input, Int32 inOff, Int32 length) { }
	// RVA: 0x6507d5c VA: 0x7598b1fd5c
	public virtual Byte[] GenerateSignature() { }
	// RVA: 0x65080e4 VA: 0x7598b200e4
	public virtual Boolean VerifySignature(Byte[] signature) { }
	// RVA: 0x65085b8 VA: 0x7598b205b8
	public virtual Void Reset() { }
	// RVA: 0x6507f8c VA: 0x7598b1ff8c
	private Byte[] DerEncode(BigInteger r, BigInteger s) { }
	// RVA: 0x65083bc VA: 0x7598b203bc
	private BigInteger[] DerDecode(Byte[] encoding) { }
}
```