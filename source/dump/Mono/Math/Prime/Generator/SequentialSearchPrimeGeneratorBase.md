# SequentialSearchPrimeGeneratorBase

**Namespace:** `Mono.Math.Prime.Generator`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Math.Prime.Generator
public class SequentialSearchPrimeGeneratorBase : PrimeGeneratorBase
{


	// RVA: 0x5ef61f8 VA: 0x759850e1f8
	protected virtual BigInteger GenerateSearchBase(Int32 bits, Object context) { }
	// RVA: 0x5ef626c VA: 0x759850e26c
	public override BigInteger GenerateNewPrime(Int32 bits) { }
	// RVA: 0x5ef627c VA: 0x759850e27c
	public virtual BigInteger GenerateNewPrime(Int32 bits, Object context) { }
	// RVA: 0x5ef6560 VA: 0x759850e560
	protected virtual Boolean IsPrimeAcceptable(BigInteger bi, Object context) { }
	// RVA: 0x5ef4eac VA: 0x759850ceac
	public Void .ctor() { }
}
```