# FastRandom

**Namespace:** `SharpNeatLib.Maths`


## Fields

- `UInt32 x`

- `UInt32 y`

- `UInt32 z`

- `UInt32 w`

- `UInt32 bitBuffer`

- `UInt32 bitMask`


## Methods

- `Void Reinitialise(Int32)`

- `Int32 Next()`

- `Int32 Next(Int32)`

- `Int32 Next(Int32, Int32)`

- `Double NextDouble()`

- `Void NextBytes(Byte[])`

- `UInt32 NextUInt()`

- `Int32 NextInt()`

- `Boolean NextBool()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : SharpNeatLib.Maths
public class FastRandom
{
	private const Double REAL_UNIT_INT; // 0x0
	private const Double REAL_UNIT_UINT; // 0x0
	private const UInt32 Y; // 0x0
	private const UInt32 Z; // 0x0
	private const UInt32 W; // 0x0
	private UInt32 x; // 0x10
	private UInt32 y; // 0x14
	private UInt32 z; // 0x18
	private UInt32 w; // 0x1c
	private UInt32 bitBuffer; // 0x20
	private UInt32 bitMask; // 0x24


	// RVA: 0x656cb6c VA: 0x7598b84b6c
	public Void .ctor() { }
	// RVA: 0x656cbd0 VA: 0x7598b84bd0
	public Void .ctor(Int32 seed) { }
	// RVA: 0x656cbb0 VA: 0x7598b84bb0
	public Void Reinitialise(Int32 seed) { }
	// RVA: 0x656cc18 VA: 0x7598b84c18
	public Int32 Next() { }
	// RVA: 0x656cc5c VA: 0x7598b84c5c
	public Int32 Next(Int32 upperBound) { }
	// RVA: 0x656cd58 VA: 0x7598b84d58
	public Int32 Next(Int32 lowerBound, Int32 upperBound) { }
	// RVA: 0x656ce80 VA: 0x7598b84e80
	public Double NextDouble() { }
	// RVA: 0x656cec0 VA: 0x7598b84ec0
	public Void NextBytes(Byte[] buffer) { }
	// RVA: 0x656d058 VA: 0x7598b85058
	public UInt32 NextUInt() { }
	// RVA: 0x656d084 VA: 0x7598b85084
	public Int32 NextInt() { }
	// RVA: 0x656d0b4 VA: 0x7598b850b4
	public Boolean NextBool() { }
}
```