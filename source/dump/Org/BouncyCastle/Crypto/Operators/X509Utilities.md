# X509Utilities

**Namespace:** `Org.BouncyCastle.Crypto.Operators`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Operators
internal class X509Utilities
{
	private static readonly Asn1Null derNull; // 0x0
	private static readonly IDictionary algorithms; // 0x8
	private static readonly IDictionary exParams; // 0x10
	private static readonly ISet noParams; // 0x18


	// RVA: 0x651c1e8 VA: 0x7598b341e8
	private static Void .cctor() { }
	// RVA: 0x651e7dc VA: 0x7598b367dc
	private static String GetDigestAlgName(DerObjectIdentifier digestAlgOID) { }
	// RVA: 0x651eb74 VA: 0x7598b36b74
	internal static String GetSignatureName(AlgorithmIdentifier sigAlgId) { }
	// RVA: 0x651e6b0 VA: 0x7598b366b0
	private static RsassaPssParameters CreatePssParams(AlgorithmIdentifier hashAlgId, Int32 saltSize) { }
	// RVA: 0x651ee18 VA: 0x7598b36e18
	internal static DerObjectIdentifier GetAlgorithmOid(String algorithmName) { }
	// RVA: 0x651f024 VA: 0x7598b37024
	internal static AlgorithmIdentifier GetSigAlgID(DerObjectIdentifier sigOid, String algorithmName) { }
	// RVA: 0x651f354 VA: 0x7598b37354
	internal static IEnumerable GetAlgNames() { }
	// RVA: 0x651f460 VA: 0x7598b37460
	public Void .ctor() { }
}
```