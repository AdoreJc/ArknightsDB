# RandomDsaKCalculator

**Namespace:** `Org.BouncyCastle.Crypto.Signers`


## Fields

- `BigInteger q`

- `SecureRandom random`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Signers
public class RandomDsaKCalculator : IDsaKCalculator
{
	private BigInteger q; // 0x10
	private SecureRandom random; // 0x18

	public virtual Boolean IsDeterministic { get; }

	// RVA: 0x65117c8 VA: 0x7598b297c8
	public virtual Boolean get_IsDeterministic() { }
	// RVA: 0x65117d0 VA: 0x7598b297d0
	public virtual Void Init(BigInteger n, SecureRandom random) { }
	// RVA: 0x6511800 VA: 0x7598b29800
	public virtual Void Init(BigInteger n, BigInteger d, Byte[] message) { }
	// RVA: 0x6511850 VA: 0x7598b29850
	public virtual BigInteger NextK() { }
	// RVA: 0x65086d0 VA: 0x7598b206d0
	public Void .ctor() { }
}
```