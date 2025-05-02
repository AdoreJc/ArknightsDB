# VmpcMac

**Namespace:** `Org.BouncyCastle.Crypto.Macs`


## Fields

- `Byte g`

- `Byte n`

- `Byte s`

- `Byte x1`

- `Byte x2`

- `Byte x3`

- `Byte x4`


## Methods

- `Void initKey(Byte[], Byte[])`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Macs
public class VmpcMac : IMac
{
	private Byte g; // 0x10
	private Byte n; // 0x11
	private Byte[] P; // 0x18
	private Byte s; // 0x20
	private Byte[] T; // 0x28
	private Byte[] workingIV; // 0x30
	private Byte[] workingKey; // 0x38
	private Byte x1; // 0x40
	private Byte x2; // 0x41
	private Byte x3; // 0x42
	private Byte x4; // 0x43

	public virtual String AlgorithmName { get; }

	// RVA: 0x653557c VA: 0x7598b4d57c
	public virtual Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x65359c4 VA: 0x7598b4d9c4
	public virtual String get_AlgorithmName() { }
	// RVA: 0x6535a04 VA: 0x7598b4da04
	public virtual Int32 GetMacSize() { }
	// RVA: 0x6535a0c VA: 0x7598b4da0c
	public virtual Void Init(ICipherParameters parameters) { }
	// RVA: 0x6535bdc VA: 0x7598b4dbdc
	private Void initKey(Byte[] keyBytes, Byte[] ivBytes) { }
	// RVA: 0x6535de0 VA: 0x7598b4dde0
	public virtual Void Reset() { }
	// RVA: 0x6535e84 VA: 0x7598b4de84
	public virtual Void Update(Byte input) { }
	// RVA: 0x65360d0 VA: 0x7598b4e0d0
	public virtual Void BlockUpdate(Byte[] input, Int32 inOff, Int32 len) { }
	// RVA: 0x65361c4 VA: 0x7598b4e1c4
	public Void .ctor() { }
}
```