# Sha3Digest

**Namespace:** `Org.BouncyCastle.Crypto.Digests`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Digests
public class Sha3Digest : KeccakDigest
{

	public override String AlgorithmName { get; }

	// RVA: 0x658884c VA: 0x7598ba084c
	private static Int32 CheckBitLength(Int32 bitLength) { }
	// RVA: 0x6588910 VA: 0x7598ba0910
	public Void .ctor() { }
	// RVA: 0x6588918 VA: 0x7598ba0918
	public Void .ctor(Int32 bitLength) { }
	// RVA: 0x6588990 VA: 0x7598ba0990
	public Void .ctor(Sha3Digest source) { }
	// RVA: 0x65889f8 VA: 0x7598ba09f8
	public override String get_AlgorithmName() { }
	// RVA: 0x6588a54 VA: 0x7598ba0a54
	public override Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x6588afc VA: 0x7598ba0afc
	protected override Int32 DoFinal(Byte[] output, Int32 outOff, Byte partialByte, Int32 partialBits) { }
	// RVA: 0x6588c0c VA: 0x7598ba0c0c
	public override IMemoable Copy() { }
}
```