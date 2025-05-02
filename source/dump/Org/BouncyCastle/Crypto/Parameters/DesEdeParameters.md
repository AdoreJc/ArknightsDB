# DesEdeParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class DesEdeParameters : DesParameters
{
	public const Int32 DesEdeKeyLength; // 0x0


	// RVA: 0x6514670 VA: 0x7598b2c670
	private static Byte[] FixKey(Byte[] key, Int32 keyOff, Int32 keyLen) { }
	// RVA: 0x6514830 VA: 0x7598b2c830
	public Void .ctor(Byte[] key) { }
	// RVA: 0x6514970 VA: 0x7598b2c970
	public Void .ctor(Byte[] key, Int32 keyOff, Int32 keyLen) { }
	// RVA: 0x65149fc VA: 0x7598b2c9fc
	public static Boolean IsWeakKey(Byte[] key, Int32 offset, Int32 length) { }
	// RVA: 0x6514be0 VA: 0x7598b2cbe0
	public static Boolean IsWeakKey(Byte[] key, Int32 offset) { }
	// RVA: 0x6514814 VA: 0x7598b2c814
	public static Boolean IsWeakKey(Byte[] key) { }
	// RVA: 0x6514bfc VA: 0x7598b2cbfc
	public static Boolean IsRealEdeKey(Byte[] key, Int32 offset) { }
	// RVA: 0x6514ccc VA: 0x7598b2cccc
	public static Boolean IsReal2Key(Byte[] key, Int32 offset) { }
	// RVA: 0x6514c24 VA: 0x7598b2cc24
	public static Boolean IsReal3Key(Byte[] key, Int32 offset) { }
}
```