# SecureRandom

**Namespace:** `Org.BouncyCastle.Security`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Security
public class SecureRandom : Random
{
	private static Int64 counter; // 0x0
	private static readonly SecureRandom master; // 0x8
	protected readonly IRandomGenerator generator; // 0x20
	private static readonly Double DoubleScale; // 0x10

	private static SecureRandom Master { get; }

	// RVA: 0x6703ff0 VA: 0x7598d1bff0
	private static Int64 NextCounterValue() { }
	// RVA: 0x6704048 VA: 0x7598d1c048
	private static SecureRandom get_Master() { }
	// RVA: 0x67040a0 VA: 0x7598d1c0a0
	private static DigestRandomGenerator CreatePrng(String digestName, Boolean autoSeed) { }
	// RVA: 0x6704250 VA: 0x7598d1c250
	public static Byte[] GetNextBytes(SecureRandom secureRandom, Int32 length) { }
	// RVA: 0x67042cc VA: 0x7598d1c2cc
	public static SecureRandom GetInstance(String algorithm) { }
	// RVA: 0x6704324 VA: 0x7598d1c324
	public static SecureRandom GetInstance(String algorithm, Boolean autoSeed) { }
	// RVA: 0x6704520 VA: 0x7598d1c520
	public static Byte[] GetSeed(Int32 length) { }
	// RVA: 0x67045b0 VA: 0x7598d1c5b0
	public Void .ctor() { }
	// RVA: 0x6704628 VA: 0x7598d1c628
	public Void .ctor(Byte[] seed) { }
	// RVA: 0x67044a8 VA: 0x7598d1c4a8
	public Void .ctor(IRandomGenerator generator) { }
	// RVA: 0x67046c0 VA: 0x7598d1c6c0
	public virtual Byte[] GenerateSeed(Int32 length) { }
	// RVA: 0x6704750 VA: 0x7598d1c750
	public virtual Void SetSeed(Byte[] seed) { }
	// RVA: 0x67047f8 VA: 0x7598d1c7f8
	public virtual Void SetSeed(Int64 seed) { }
	// RVA: 0x67048a4 VA: 0x7598d1c8a4
	public override Int32 Next() { }
	// RVA: 0x67048c4 VA: 0x7598d1c8c4
	public override Int32 Next(Int32 maxValue) { }
	// RVA: 0x67049b4 VA: 0x7598d1c9b4
	public override Int32 Next(Int32 minValue, Int32 maxValue) { }
	// RVA: 0x6704a7c VA: 0x7598d1ca7c
	public override Void NextBytes(Byte[] buf) { }
	// RVA: 0x6704b28 VA: 0x7598d1cb28
	public virtual Void NextBytes(Byte[] buf, Int32 off, Int32 len) { }
	// RVA: 0x6704bec VA: 0x7598d1cbec
	public override Double NextDouble() { }
	// RVA: 0x6704ca4 VA: 0x7598d1cca4
	public virtual Int32 NextInt() { }
	// RVA: 0x6704d50 VA: 0x7598d1cd50
	public virtual Int64 NextLong() { }
	// RVA: 0x6704d98 VA: 0x7598d1cd98
	private static Void .cctor() { }
}
```