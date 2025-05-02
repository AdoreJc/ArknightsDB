# Random

**Namespace:** `System`


## Fields

- `Int32 _inext`

- `Int32 _inextp`


## Methods

- `Int32 InternalSample()`

- `Double GetSampleForLargeRange()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
public class Random
{
	private const Int32 MBIG; // 0x0
	private const Int32 MSEED; // 0x0
	private const Int32 MZ; // 0x0
	private Int32 _inext; // 0x10
	private Int32 _inextp; // 0x14
	private Int32[] _seedArray; // 0x18
	private static Random t_threadRandom; // 0xffffffffffffffff
	private static readonly Random s_globalRandom; // 0x0


	// RVA: 0x60c208c VA: 0x75986da08c
	public Void .ctor() { }
	// RVA: 0x60c22b0 VA: 0x75986da2b0
	public Void .ctor(Int32 Seed) { }
	// RVA: 0x60c2470 VA: 0x75986da470
	protected virtual Double Sample() { }
	// RVA: 0x60c2490 VA: 0x75986da490
	private Int32 InternalSample() { }
	// RVA: 0x60c20e8 VA: 0x75986da0e8
	private static Int32 GenerateSeed() { }
	// RVA: 0x60c2520 VA: 0x75986da520
	private static Int32 GenerateGlobalSeed() { }
	// RVA: 0x60c2544 VA: 0x75986da544
	public virtual Int32 Next() { }
	// RVA: 0x60c2548 VA: 0x75986da548
	private Double GetSampleForLargeRange() { }
	// RVA: 0x60c2594 VA: 0x75986da594
	public virtual Int32 Next(Int32 minValue, Int32 maxValue) { }
	// RVA: 0x60c26b0 VA: 0x75986da6b0
	public virtual Int32 Next(Int32 maxValue) { }
	// RVA: 0x60c2778 VA: 0x75986da778
	public virtual Double NextDouble() { }
	// RVA: 0x60c2784 VA: 0x75986da784
	public virtual Void NextBytes(Byte[] buffer) { }
	// RVA: 0x60c2834 VA: 0x75986da834
	private static Void .cctor() { }
}
```