# DHParametersHelper

**Namespace:** `Org.BouncyCastle.Crypto.Generators`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Generators
internal class DHParametersHelper
{
	private static readonly BigInteger Six; // 0x0
	private static readonly Int32[][] primeLists; // 0x8
	private static readonly Int32[] primeProducts; // 0x10
	private static readonly BigInteger[] BigPrimeProducts; // 0x18


	// RVA: 0x6536814 VA: 0x7598b4e814
	private static BigInteger[] ConstructBigPrimeProducts(Int32[] primeProducts) { }
	// RVA: 0x6536944 VA: 0x7598b4e944
	internal static BigInteger[] GenerateSafePrimes(Int32 size, Int32 certainty, SecureRandom random) { }
	// RVA: 0x6536e38 VA: 0x7598b4ee38
	internal static BigInteger SelectGenerator(BigInteger p, BigInteger q, SecureRandom random) { }
	// RVA: 0x6536f28 VA: 0x7598b4ef28
	public Void .ctor() { }
	// RVA: 0x6536f30 VA: 0x7598b4ef30
	private static Void .cctor() { }
}
```