# Sha512Digest

**Namespace:** `Org.BouncyCastle.Crypto.Digests`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Digests
public class Sha512Digest : LongDigest
{
	private const Int32 DigestLength; // 0x0

	public override String AlgorithmName { get; }

	// RVA: 0x6588c6c VA: 0x7598ba0c6c
	public Void .ctor() { }
	// RVA: 0x6588cc4 VA: 0x7598ba0cc4
	public Void .ctor(Sha512Digest t) { }
	// RVA: 0x6588d2c VA: 0x7598ba0d2c
	public override String get_AlgorithmName() { }
	// RVA: 0x6588d6c VA: 0x7598ba0d6c
	public override Int32 GetDigestSize() { }
	// RVA: 0x6588d74 VA: 0x7598ba0d74
	public override Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x6588e54 VA: 0x7598ba0e54
	public override Void Reset() { }
	// RVA: 0x6588e9c VA: 0x7598ba0e9c
	public override IMemoable Copy() { }
	// RVA: 0x6588efc VA: 0x7598ba0efc
	public override Void Reset(IMemoable other) { }
}
```