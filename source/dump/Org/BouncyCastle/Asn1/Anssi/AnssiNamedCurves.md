# AnssiNamedCurves

**Namespace:** `Org.BouncyCastle.Asn1.Anssi`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.Anssi
public class AnssiNamedCurves
{
	private static readonly IDictionary objIds; // 0x0
	private static readonly IDictionary curves; // 0x8
	private static readonly IDictionary names; // 0x10

	public static IEnumerable Names { get; }

	// RVA: 0x65dfd34 VA: 0x7598bf7d34
	private static ECCurve ConfigureCurve(ECCurve curve) { }
	// RVA: 0x65dfd38 VA: 0x7598bf7d38
	private static BigInteger FromHex(String hex) { }
	// RVA: 0x65dfdd8 VA: 0x7598bf7dd8
	private static Void DefineCurve(String name, DerObjectIdentifier oid, X9ECParametersHolder holder) { }
	// RVA: 0x65dffe8 VA: 0x7598bf7fe8
	private static Void .cctor() { }
	// RVA: 0x65e012c VA: 0x7598bf812c
	public static X9ECParameters GetByName(String name) { }
	// RVA: 0x65e0300 VA: 0x7598bf8300
	public static X9ECParameters GetByOid(DerObjectIdentifier oid) { }
	// RVA: 0x65e01ac VA: 0x7598bf81ac
	public static DerObjectIdentifier GetOid(String name) { }
	// RVA: 0x65e042c VA: 0x7598bf842c
	public static String GetName(DerObjectIdentifier oid) { }
	// RVA: 0x65e052c VA: 0x7598bf852c
	public static IEnumerable get_Names() { }
	// RVA: 0x65e0638 VA: 0x7598bf8638
	public Void .ctor() { }
}
```