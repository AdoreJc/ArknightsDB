# Xorshift

**Namespace:** `Rei.Random`


## Fields

- `UInt32 x`

- `UInt32 y`

- `UInt32 z`

- `UInt32 w`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Rei.Random
public class Xorshift : RandomBase
{
	protected UInt32 x; // 0x10
	protected UInt32 y; // 0x14
	protected UInt32 z; // 0x18
	protected UInt32 w; // 0x1c


	// RVA: 0x656c554 VA: 0x7598b84554
	public Void .ctor() { }
	// RVA: 0x656c5a0 VA: 0x7598b845a0
	public Void .ctor(Int32 seed) { }
	// RVA: 0x656c5e0 VA: 0x7598b845e0
	public Void .ctor(UInt32 seed1, UInt32 seed2, UInt32 seed3, UInt32 seed4) { }
	// RVA: 0x656c620 VA: 0x7598b84620
	public override UInt32 NextUInt32() { }
}
```