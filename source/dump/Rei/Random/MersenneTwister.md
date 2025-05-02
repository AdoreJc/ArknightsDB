# MersenneTwister

**Namespace:** `Rei.Random`


## Fields

- `Int32 mti`


## Methods

- `Void gen_rand_all()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Rei.Random
public class MersenneTwister : RandomBase
{
	protected const Int32 N; // 0x0
	protected const Int32 M; // 0x0
	protected const UInt32 MATRIX_A; // 0x0
	protected const UInt32 UPPER_MASK; // 0x0
	protected const UInt32 LOWER_MASK; // 0x0
	protected const UInt32 TEMPER1; // 0x0
	protected const UInt32 TEMPER2; // 0x0
	protected const Int32 TEMPER3; // 0x0
	protected const Int32 TEMPER4; // 0x0
	protected const Int32 TEMPER5; // 0x0
	protected const Int32 TEMPER6; // 0x0
	protected UInt32[] mt; // 0x10
	protected Int32 mti; // 0x18
	private UInt32[] mag01; // 0x20


	// RVA: 0x656b16c VA: 0x7598b8316c
	public Void .ctor() { }
	// RVA: 0x656b18c VA: 0x7598b8318c
	public Void .ctor(Int32 seed) { }
	// RVA: 0x656b2ac VA: 0x7598b832ac
	public override UInt32 NextUInt32() { }
	// RVA: 0x656b328 VA: 0x7598b83328
	protected Void gen_rand_all() { }
}
```