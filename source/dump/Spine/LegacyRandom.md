# LegacyRandom

**Namespace:** `Spine`


## Fields

- `Int32 inext`

- `Int32 inextp`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class LegacyRandom : Random
{
	private const Int32 MBIG; // 0x0
	private const Int32 MSEED; // 0x0
	private const Int32 MZ; // 0x0
	private Int32 inext; // 0x20
	private Int32 inextp; // 0x24
	private Int32[] SeedArray; // 0x28


	// RVA: 0x61d639c VA: 0x75987ee39c
	public Void .ctor() { }
	// RVA: 0x61d63bc VA: 0x75987ee3bc
	public Void .ctor(Int32 Seed) { }
	// RVA: 0x61d65e8 VA: 0x75987ee5e8
	protected override Double Sample() { }
	// RVA: 0x61d6678 VA: 0x75987ee678
	public override Int32 Next() { }
	// RVA: 0x61d66b4 VA: 0x75987ee6b4
	public override Int32 Next(Int32 maxValue) { }
	// RVA: 0x61d6740 VA: 0x75987ee740
	public override Int32 Next(Int32 minValue, Int32 maxValue) { }
	// RVA: 0x61d67e0 VA: 0x75987ee7e0
	public override Void NextBytes(Byte[] buffer) { }
	// RVA: 0x61d68b0 VA: 0x75987ee8b0
	public override Double NextDouble() { }
}
```