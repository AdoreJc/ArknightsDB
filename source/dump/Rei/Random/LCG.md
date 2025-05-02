# LCG

**Namespace:** `Rei.Random`


## Fields

- `UInt32 A`

- `UInt32 C`

- `UInt32 x`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Rei.Random
public class LCG : RandomBase
{
	protected UInt32 A; // 0x10
	protected UInt32 C; // 0x14
	protected UInt32 x; // 0x18


	// RVA: 0x656b09c VA: 0x7598b8309c
	public Void .ctor() { }
	// RVA: 0x656b0dc VA: 0x7598b830dc
	public Void .ctor(Int32 seed) { }
	// RVA: 0x656b110 VA: 0x7598b83110
	public Void .ctor(Int32 seed, UInt32 paramA, UInt32 paramC) { }
	// RVA: 0x656b154 VA: 0x7598b83154
	public override UInt32 NextUInt32() { }
}
```