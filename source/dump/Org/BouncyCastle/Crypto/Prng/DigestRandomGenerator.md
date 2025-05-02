# DigestRandomGenerator

**Namespace:** `Org.BouncyCastle.Crypto.Prng`


## Fields

- `Int64 stateCounter`

- `Int64 seedCounter`

- `IDigest digest`


## Methods

- `Void AddSeedMaterial(Byte[])`

- `Void AddSeedMaterial(Int64)`

- `Void NextBytes(Byte[])`

- `Void NextBytes(Byte[], Int32, Int32)`

- `Void CycleSeed()`

- `Void GenerateState()`

- `Void DigestAddCounter(Int64)`

- `Void DigestUpdate(Byte[])`

- `Void DigestDoFinal(Byte[])`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Prng
public class DigestRandomGenerator : IRandomGenerator
{
	private const Int64 CYCLE_COUNT; // 0x0
	private Int64 stateCounter; // 0x10
	private Int64 seedCounter; // 0x18
	private IDigest digest; // 0x20
	private Byte[] state; // 0x28
	private Byte[] seed; // 0x30


	// RVA: 0x6513df0 VA: 0x7598b2bdf0
	public Void .ctor(IDigest digest) { }
	// RVA: 0x6513f80 VA: 0x7598b2bf80
	public Void AddSeedMaterial(Byte[] inSeed) { }
	// RVA: 0x65141cc VA: 0x7598b2c1cc
	public Void AddSeedMaterial(Int64 rSeed) { }
	// RVA: 0x65143a4 VA: 0x7598b2c3a4
	public Void NextBytes(Byte[] bytes) { }
	// RVA: 0x65143c0 VA: 0x7598b2c3c0
	public Void NextBytes(Byte[] bytes, Int32 start, Int32 len) { }
	// RVA: 0x65145ac VA: 0x7598b2c5ac
	private Void CycleSeed() { }
	// RVA: 0x6514538 VA: 0x7598b2c538
	private Void GenerateState() { }
	// RVA: 0x65142ac VA: 0x7598b2c2ac
	private Void DigestAddCounter(Int64 seedVal) { }
	// RVA: 0x6514060 VA: 0x7598b2c060
	private Void DigestUpdate(Byte[] inSeed) { }
	// RVA: 0x651411c VA: 0x7598b2c11c
	private Void DigestDoFinal(Byte[] result) { }
}
```