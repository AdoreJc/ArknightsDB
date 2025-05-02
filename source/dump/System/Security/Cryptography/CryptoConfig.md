# CryptoConfig

**Namespace:** `System.Security.Cryptography`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
public class CryptoConfig
{
	private static readonly Object lockObject; // 0x0
	private static Dictionary`2 algorithms; // 0x8

	public static Boolean AllowOnlyFipsAlgorithms { get; }

	// RVA: 0x5f6af8c VA: 0x7598582f8c
	public static Void AddOID(String oid, String[] names) { }
	// RVA: 0x5f5db9c VA: 0x7598575b9c
	public static Object CreateFromName(String name) { }
	// RVA: 0x5f6afcc VA: 0x7598582fcc
	public static Object CreateFromName(String name, Object[] args) { }
	// RVA: 0x5f6cff0 VA: 0x7598584ff0
	internal static String MapNameToOID(String name, Object arg) { }
	// RVA: 0x5f6d044 VA: 0x7598585044
	public static String MapNameToOID(String name) { }
	// RVA: 0x5f6d7f8 VA: 0x75985857f8
	private static Void Initialize() { }
	// RVA: 0x5f6d8fc VA: 0x75985858fc
	public static Void AddAlgorithm(Type algorithm, String[] names) { }
	// RVA: 0x5f6dc9c VA: 0x7598585c9c
	public static Byte[] EncodeOID(String str) { }
	// RVA: 0x5f6e0a8 VA: 0x75985860a8
	private static Byte[] EncodeLongNumber(Int64 x) { }
	// RVA: 0x5f646ac VA: 0x759857c6ac
	public static Boolean get_AllowOnlyFipsAlgorithms() { }
	// RVA: 0x5f6e238 VA: 0x7598586238
	public Void .ctor() { }
	// RVA: 0x5f6e240 VA: 0x7598586240
	private static Void .cctor() { }
}
```