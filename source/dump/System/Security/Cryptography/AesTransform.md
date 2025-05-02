# AesTransform

**Namespace:** `System.Security.Cryptography`


## Fields

- `Int32 Nk`

- `Int32 Nr`


## Methods

- `UInt32 SubByte(UInt32)`

- `Void Encrypt128(Byte[], Byte[], UInt32[])`

- `Void Decrypt128(Byte[], Byte[], UInt32[])`


## Dump
```C#
// Dll : System.Core.dll
// Namespace : System.Security.Cryptography
internal class AesTransform : SymmetricTransform
{
	private UInt32[] expandedKey; // 0x58
	private Int32 Nk; // 0x60
	private Int32 Nr; // 0x64
	private static readonly UInt32[] Rcon; // 0x0
	private static readonly Byte[] SBox; // 0x8
	private static readonly Byte[] iSBox; // 0x10
	private static readonly UInt32[] T0; // 0x18
	private static readonly UInt32[] T1; // 0x20
	private static readonly UInt32[] T2; // 0x28
	private static readonly UInt32[] T3; // 0x30
	private static readonly UInt32[] iT0; // 0x38
	private static readonly UInt32[] iT1; // 0x40
	private static readonly UInt32[] iT2; // 0x48
	private static readonly UInt32[] iT3; // 0x50


	// RVA: 0x6228974 VA: 0x7598840974
	public Void .ctor(Aes algo, Boolean encryption, Byte[] key, Byte[] iv) { }
	// RVA: 0x6229394 VA: 0x7598841394
	protected override Void ECB(Byte[] input, Byte[] output) { }
	// RVA: 0x62292d0 VA: 0x75988412d0
	private UInt32 SubByte(UInt32 a) { }
	// RVA: 0x62293a8 VA: 0x75988413a8
	private Void Encrypt128(Byte[] indata, Byte[] outdata, UInt32[] ekey) { }
	// RVA: 0x622b1d4 VA: 0x75988431d4
	private Void Decrypt128(Byte[] indata, Byte[] outdata, UInt32[] ekey) { }
	// RVA: 0x622cfc4 VA: 0x7598844fc4
	private static Void .cctor() { }
}
```