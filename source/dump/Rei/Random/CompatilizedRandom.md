# CompatilizedRandom

**Namespace:** `Rei.Random`


## Fields

- `RandomBase original`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Rei.Random
public class CompatilizedRandom : Random
{
	private RandomBase original; // 0x20


	// RVA: 0x656aee4 VA: 0x7598b82ee4
	public Void .ctor(RandomBase rand) { }
	// RVA: 0x656af58 VA: 0x7598b82f58
	public override Int32 Next() { }
	// RVA: 0x656af98 VA: 0x7598b82f98
	public override Int32 Next(Int32 maxValue) { }
	// RVA: 0x656afac VA: 0x7598b82fac
	public override Int32 Next(Int32 minValue, Int32 maxValue) { }
	// RVA: 0x656b054 VA: 0x7598b83054
	protected override Double Sample() { }
	// RVA: 0x656b07c VA: 0x7598b8307c
	public override Void NextBytes(Byte[] buffer) { }
}
```