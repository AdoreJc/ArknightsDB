# SipHash

**Namespace:** `Org.BouncyCastle.Crypto.Macs`


## Fields

- `Int64 k0`

- `Int64 k1`

- `Int64 v0`

- `Int64 v1`

- `Int64 v2`

- `Int64 v3`

- `Int64 m`

- `Int32 wordPos`

- `Int32 wordCount`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Macs
public class SipHash : IMac
{
	protected readonly Int32 c; // 0x10
	protected readonly Int32 d; // 0x14
	protected Int64 k0; // 0x18
	protected Int64 k1; // 0x20
	protected Int64 v0; // 0x28
	protected Int64 v1; // 0x30
	protected Int64 v2; // 0x38
	protected Int64 v3; // 0x40
	protected Int64 m; // 0x48
	protected Int32 wordPos; // 0x50
	protected Int32 wordCount; // 0x54

	public virtual String AlgorithmName { get; }

	// RVA: 0x6534f50 VA: 0x7598b4cf50
	public Void .ctor() { }
	// RVA: 0x6534f74 VA: 0x7598b4cf74
	public Void .ctor(Int32 c, Int32 d) { }
	// RVA: 0x6534fa0 VA: 0x7598b4cfa0
	public virtual String get_AlgorithmName() { }
	// RVA: 0x6535044 VA: 0x7598b4d044
	public virtual Int32 GetMacSize() { }
	// RVA: 0x653504c VA: 0x7598b4d04c
	public virtual Void Init(ICipherParameters parameters) { }
	// RVA: 0x65351a0 VA: 0x7598b4d1a0
	public virtual Void Update(Byte input) { }
	// RVA: 0x65351e4 VA: 0x7598b4d1e4
	public virtual Void BlockUpdate(Byte[] input, Int32 offset, Int32 length) { }
	// RVA: 0x6535390 VA: 0x7598b4d390
	public virtual Int64 DoFinal() { }
	// RVA: 0x6535430 VA: 0x7598b4d430
	public virtual Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x6535474 VA: 0x7598b4d474
	public virtual Void Reset() { }
	// RVA: 0x65354d8 VA: 0x7598b4d4d8
	protected virtual Void ProcessMessageWord() { }
	// RVA: 0x6535524 VA: 0x7598b4d524
	protected virtual Void ApplySipRounds(Int32 n) { }
	// RVA: 0x6535570 VA: 0x7598b4d570
	protected static Int64 RotateLeft(Int64 x, Int32 n) { }
}
```