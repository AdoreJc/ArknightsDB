# LegacyRandom

**Namespace:** `Torappu`


## Fields

- `Int32 inext`

- `Int32 inextp`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Torappu
public class LegacyRandom : Random
{
	private const Int32 MBIG; // 0x0
	private const Int32 MSEED; // 0x0
	private const Int32 MZ; // 0x0
	private Int32 inext; // 0x20
	private Int32 inextp; // 0x24
	private Int32[] SeedArray; // 0x28


	// RVA: 0x656c64c VA: 0x7598b8464c
	public Void .ctor() { }
	// RVA: 0x656c66c VA: 0x7598b8466c
	public Void .ctor(Int32 Seed) { }
	// RVA: 0x656c898 VA: 0x7598b84898
	protected override Double Sample() { }
	// RVA: 0x656c928 VA: 0x7598b84928
	public override Int32 Next() { }
	// RVA: 0x656c964 VA: 0x7598b84964
	public override Int32 Next(Int32 maxValue) { }
	// RVA: 0x656c9f0 VA: 0x7598b849f0
	public override Int32 Next(Int32 minValue, Int32 maxValue) { }
	// RVA: 0x656ca90 VA: 0x7598b84a90
	public override Void NextBytes(Byte[] buffer) { }
	// RVA: 0x656cb60 VA: 0x7598b84b60
	public override Double NextDouble() { }
}
```