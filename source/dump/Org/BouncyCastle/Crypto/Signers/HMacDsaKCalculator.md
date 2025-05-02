# HMacDsaKCalculator

**Namespace:** `Org.BouncyCastle.Crypto.Signers`


## Fields

- `BigInteger n`


## Methods

- `Void Init(BigInteger, BigInteger, Byte[])`

- `BigInteger BitsToInt(Byte[])`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Signers
public class HMacDsaKCalculator : IDsaKCalculator
{
	private readonly HMac hMac; // 0x10
	private readonly Byte[] K; // 0x18
	private readonly Byte[] V; // 0x20
	private BigInteger n; // 0x28

	public virtual Boolean IsDeterministic { get; }

	// RVA: 0x650d354 VA: 0x7598b25354
	public Void .ctor(IDigest digest) { }
	// RVA: 0x650d464 VA: 0x7598b25464
	public virtual Boolean get_IsDeterministic() { }
	// RVA: 0x650d46c VA: 0x7598b2546c
	public virtual Void Init(BigInteger n, SecureRandom random) { }
	// RVA: 0x650d4bc VA: 0x7598b254bc
	public Void Init(BigInteger n, BigInteger d, Byte[] message) { }
	// RVA: 0x650d9c0 VA: 0x7598b259c0
	public virtual BigInteger NextK() { }
	// RVA: 0x650d8f8 VA: 0x7598b258f8
	private BigInteger BitsToInt(Byte[] t) { }
}
```