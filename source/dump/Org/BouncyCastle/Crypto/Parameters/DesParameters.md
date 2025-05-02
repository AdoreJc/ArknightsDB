# DesParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class DesParameters : KeyParameter
{
	public const Int32 DesKeyLength; // 0x0
	private const Int32 N_DES_WEAK_KEYS; // 0x0
	private static readonly Byte[] DES_weak_keys; // 0x0


	// RVA: 0x65148ac VA: 0x7598b2c8ac
	public Void .ctor(Byte[] key) { }
	// RVA: 0x6514d88 VA: 0x7598b2cd88
	public Void .ctor(Byte[] key, Int32 keyOff, Int32 keyLen) { }
	// RVA: 0x6514a8c VA: 0x7598b2ca8c
	public static Boolean IsWeakKey(Byte[] key, Int32 offset) { }
	// RVA: 0x6514d30 VA: 0x7598b2cd30
	public static Boolean IsWeakKey(Byte[] key) { }
	// RVA: 0x6514e68 VA: 0x7598b2ce68
	public static Byte SetOddParity(Byte b) { }
	// RVA: 0x6514e88 VA: 0x7598b2ce88
	public static Void SetOddParity(Byte[] bytes) { }
	// RVA: 0x6514f44 VA: 0x7598b2cf44
	public static Void SetOddParity(Byte[] bytes, Int32 off, Int32 len) { }
	// RVA: 0x6515024 VA: 0x7598b2d024
	private static Void .cctor() { }
}
```