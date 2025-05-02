# DESTransform

**Namespace:** `System.Security.Cryptography`


## Methods

- `UInt32 CipherFunct(UInt32, Int32)`

- `Void ProcessBlock(Byte[], Byte[])`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
internal class DESTransform : SymmetricTransform
{
	internal static readonly Int32 KEY_BIT_SIZE; // 0x0
	internal static readonly Int32 KEY_BYTE_SIZE; // 0x4
	internal static readonly Int32 BLOCK_BIT_SIZE; // 0x8
	internal static readonly Int32 BLOCK_BYTE_SIZE; // 0xc
	private Byte[] keySchedule; // 0x58
	private Byte[] byteBuff; // 0x60
	private UInt32[] dwordBuff; // 0x68
	private static readonly UInt32[] spBoxes; // 0x10
	private static readonly Byte[] PC1; // 0x18
	private static readonly Byte[] leftRotTotal; // 0x20
	private static readonly Byte[] PC2; // 0x28
	internal static readonly UInt32[] ipTab; // 0x30
	internal static readonly UInt32[] fpTab; // 0x38


	// RVA: 0x5f6e3cc VA: 0x75985863cc
	internal Void .ctor(SymmetricAlgorithm symmAlgo, Boolean encryption, Byte[] key, Byte[] iv) { }
	// RVA: 0x5f6ea7c VA: 0x7598586a7c
	private UInt32 CipherFunct(UInt32 r, Int32 n) { }
	// RVA: 0x5f6ecac VA: 0x7598586cac
	internal static Void Permutation(Byte[] input, Byte[] output, UInt32[] permTab, Boolean preSwap) { }
	// RVA: 0x5f6efd0 VA: 0x7598586fd0
	private static Void BSwap(Byte[] byteBuff) { }
	// RVA: 0x5f6e6f0 VA: 0x75985866f0
	internal Void SetKey(Byte[] key) { }
	// RVA: 0x5f6f048 VA: 0x7598587048
	public Void ProcessBlock(Byte[] input, Byte[] output) { }
	// RVA: 0x5f6f3d0 VA: 0x75985873d0
	protected override Void ECB(Byte[] input, Byte[] output) { }
	// RVA: 0x5f6e618 VA: 0x7598586618
	internal static Byte[] GetStrongKey() { }
	// RVA: 0x5f6f474 VA: 0x7598587474
	private static Void .cctor() { }
}
```