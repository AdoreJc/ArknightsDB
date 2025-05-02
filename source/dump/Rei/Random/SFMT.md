# SFMT

**Namespace:** `Rei.Random`


## Fields

- `Int32 MEXP`

- `Int32 POS1`

- `Int32 SL1`

- `Int32 SL2`

- `Int32 SR1`

- `Int32 SR2`

- `UInt32 MSK1`

- `UInt32 MSK2`

- `UInt32 MSK3`

- `UInt32 MSK4`

- `UInt32 PARITY1`

- `UInt32 PARITY2`

- `UInt32 PARITY3`

- `UInt32 PARITY4`

- `Int32 N`

- `Int32 N32`

- `Int32 SL2_x8`

- `Int32 SR2_x8`

- `Int32 SL2_ix8`

- `Int32 SR2_ix8`

- `Int32 idx`


## Methods

- `Void init_gen_rand(Int32)`

- `Void period_certification()`

- `Void gen_rand_all_19937()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Rei.Random
public class SFMT : RandomBase
{
	protected Int32 MEXP; // 0x10
	protected Int32 POS1; // 0x14
	protected Int32 SL1; // 0x18
	protected Int32 SL2; // 0x1c
	protected Int32 SR1; // 0x20
	protected Int32 SR2; // 0x24
	protected UInt32 MSK1; // 0x28
	protected UInt32 MSK2; // 0x2c
	protected UInt32 MSK3; // 0x30
	protected UInt32 MSK4; // 0x34
	protected UInt32 PARITY1; // 0x38
	protected UInt32 PARITY2; // 0x3c
	protected UInt32 PARITY3; // 0x40
	protected UInt32 PARITY4; // 0x44
	protected Int32 N; // 0x48
	protected Int32 N32; // 0x4c
	protected Int32 SL2_x8; // 0x50
	protected Int32 SR2_x8; // 0x54
	protected Int32 SL2_ix8; // 0x58
	protected Int32 SR2_ix8; // 0x5c
	protected UInt32[] sfmt; // 0x60
	protected Int32 idx; // 0x68


	// RVA: 0x656b8e8 VA: 0x7598b838e8
	public Void .ctor() { }
	// RVA: 0x656bb80 VA: 0x7598b83b80
	public Void .ctor(Int32 seed) { }
	// RVA: 0x656bb88 VA: 0x7598b83b88
	public Void .ctor(Int32 seed, MTPeriodType period) { }
	// RVA: 0x656b90c VA: 0x7598b8390c
	public Void .ctor(Int32 seed, Int32 mexp) { }
	// RVA: 0x656bcc4 VA: 0x7598b83cc4
	public override UInt32 NextUInt32() { }
	// RVA: 0x656bb8c VA: 0x7598b83b8c
	protected Void init_gen_rand(Int32 seed) { }
	// RVA: 0x656bd28 VA: 0x7598b83d28
	protected Void period_certification() { }
	// RVA: 0x656be84 VA: 0x7598b83e84
	protected virtual Void gen_rand_all() { }
	// RVA: 0x656c10c VA: 0x7598b8410c
	private Void gen_rand_all_19937() { }
}
```