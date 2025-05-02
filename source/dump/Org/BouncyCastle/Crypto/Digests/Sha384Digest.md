# Sha384Digest

**Namespace:** `Org.BouncyCastle.Crypto.Digests`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Digests
public class Sha384Digest : LongDigest
{
	private const Int32 DigestLength; // 0x0

	public override String AlgorithmName { get; }

	// RVA: 0x658855c VA: 0x7598ba055c
	public Void .ctor() { }
	// RVA: 0x65885b4 VA: 0x7598ba05b4
	public Void .ctor(Sha384Digest t) { }
	// RVA: 0x658861c VA: 0x7598ba061c
	public override String get_AlgorithmName() { }
	// RVA: 0x658865c VA: 0x7598ba065c
	public override Int32 GetDigestSize() { }
	// RVA: 0x6588664 VA: 0x7598ba0664
	public override Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x658871c VA: 0x7598ba071c
	public override Void Reset() { }
	// RVA: 0x6588764 VA: 0x7598ba0764
	public override IMemoable Copy() { }
	// RVA: 0x65887c4 VA: 0x7598ba07c4
	public override Void Reset(IMemoable other) { }
}
```