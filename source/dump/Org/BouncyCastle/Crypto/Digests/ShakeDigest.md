# ShakeDigest

**Namespace:** `Org.BouncyCastle.Crypto.Digests`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Digests
public class ShakeDigest : KeccakDigest, IXof, IDigest
{

	public override String AlgorithmName { get; }

	// RVA: 0x6589744 VA: 0x7598ba1744
	private static Int32 CheckBitLength(Int32 bitLength) { }
	// RVA: 0x65897ec VA: 0x7598ba17ec
	public Void .ctor() { }
	// RVA: 0x65897f4 VA: 0x7598ba17f4
	public Void .ctor(Int32 bitLength) { }
	// RVA: 0x658986c VA: 0x7598ba186c
	public Void .ctor(ShakeDigest source) { }
	// RVA: 0x65898d4 VA: 0x7598ba18d4
	public override String get_AlgorithmName() { }
	// RVA: 0x6589930 VA: 0x7598ba1930
	public override Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x6589980 VA: 0x7598ba1980
	public virtual Int32 DoFinal(Byte[] output, Int32 outOff, Int32 outLen) { }
	// RVA: 0x65899c4 VA: 0x7598ba19c4
	public virtual Int32 DoOutput(Byte[] output, Int32 outOff, Int32 outLen) { }
	// RVA: 0x6589a8c VA: 0x7598ba1a8c
	protected override Int32 DoFinal(Byte[] output, Int32 outOff, Byte partialByte, Int32 partialBits) { }
	// RVA: 0x6589af4 VA: 0x7598ba1af4
	protected virtual Int32 DoFinal(Byte[] output, Int32 outOff, Int32 outLen, Byte partialByte, Int32 partialBits) { }
	// RVA: 0x6589c74 VA: 0x7598ba1c74
	public override IMemoable Copy() { }
}
```