# MD4Managed

**Namespace:** `Mono.Security.Cryptography`


## Methods

- `UInt32 F(UInt32, UInt32, UInt32)`

- `UInt32 G(UInt32, UInt32, UInt32)`

- `UInt32 H(UInt32, UInt32, UInt32)`

- `UInt32 ROL(UInt32, Byte)`

- `Void FF(ref, UInt32, UInt32, UInt32, UInt32, Byte)`

- `Void GG(ref, UInt32, UInt32, UInt32, UInt32, Byte)`

- `Void HH(ref, UInt32, UInt32, UInt32, UInt32, Byte)`

- `Void Encode(Byte[], UInt32[])`

- `Void Decode(UInt32[], Byte[], Int32)`

- `Void MD4Transform(UInt32[], Byte[], Int32)`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.Cryptography
public class MD4Managed : MD4
{
	private UInt32[] state; // 0x28
	private Byte[] buffer; // 0x30
	private UInt32[] count; // 0x38
	private UInt32[] x; // 0x40
	private Byte[] digest; // 0x48


	// RVA: 0x5eeaac0 VA: 0x7598502ac0
	public Void .ctor() { }
	// RVA: 0x5eeabcc VA: 0x7598502bcc
	public override Void Initialize() { }
	// RVA: 0x5eeac80 VA: 0x7598502c80
	protected override Void HashCore(Byte[] array, Int32 ibStart, Int32 cbSize) { }
	// RVA: 0x5eeb41c VA: 0x759850341c
	protected override Byte[] HashFinal() { }
	// RVA: 0x5eeb610 VA: 0x7598503610
	private Byte[] Padding(Int32 nLength) { }
	// RVA: 0x5eeb688 VA: 0x7598503688
	private UInt32 F(UInt32 x, UInt32 y, UInt32 z) { }
	// RVA: 0x5eeb698 VA: 0x7598503698
	private UInt32 G(UInt32 x, UInt32 y, UInt32 z) { }
	// RVA: 0x5eeb6ac VA: 0x75985036ac
	private UInt32 H(UInt32 x, UInt32 y, UInt32 z) { }
	// RVA: 0x5eeb6b8 VA: 0x75985036b8
	private UInt32 ROL(UInt32 x, Byte n) { }
	// RVA: 0x5eeb6c8 VA: 0x75985036c8
	private Void FF(ref UInt32 a, UInt32 b, UInt32 c, UInt32 d, UInt32 x, Byte s) { }
	// RVA: 0x5eeb6f4 VA: 0x75985036f4
	private Void GG(ref UInt32 a, UInt32 b, UInt32 c, UInt32 d, UInt32 x, Byte s) { }
	// RVA: 0x5eeb730 VA: 0x7598503730
	private Void HH(ref UInt32 a, UInt32 b, UInt32 c, UInt32 d, UInt32 x, Byte s) { }
	// RVA: 0x5eeb518 VA: 0x7598503518
	private Void Encode(Byte[] output, UInt32[] input) { }
	// RVA: 0x5eeb764 VA: 0x7598503764
	private Void Decode(UInt32[] output, Byte[] input, Int32 index) { }
	// RVA: 0x5eeada4 VA: 0x7598502da4
	private Void MD4Transform(UInt32[] state, Byte[] block, Int32 index) { }
}
```