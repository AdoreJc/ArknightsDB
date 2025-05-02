# TeleTrusTNamedCurves

**Namespace:** `Org.BouncyCastle.Asn1.TeleTrust`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.TeleTrust
public class TeleTrusTNamedCurves
{
	private static readonly IDictionary objIds; // 0x0
	private static readonly IDictionary curves; // 0x8
	private static readonly IDictionary names; // 0x10

	public static IEnumerable Names { get; }

	// RVA: 0x65c7b5c VA: 0x7598bdfb5c
	private static ECCurve ConfigureCurve(ECCurve curve) { }
	// RVA: 0x65c7b60 VA: 0x7598bdfb60
	private static Void DefineCurve(String name, DerObjectIdentifier oid, X9ECParametersHolder holder) { }
	// RVA: 0x65c7d70 VA: 0x7598bdfd70
	private static Void .cctor() { }
	// RVA: 0x65c8368 VA: 0x7598be0368
	public static X9ECParameters GetByName(String name) { }
	// RVA: 0x65c853c VA: 0x7598be053c
	public static X9ECParameters GetByOid(DerObjectIdentifier oid) { }
	// RVA: 0x65c83e8 VA: 0x7598be03e8
	public static DerObjectIdentifier GetOid(String name) { }
	// RVA: 0x65c8668 VA: 0x7598be0668
	public static String GetName(DerObjectIdentifier oid) { }
	// RVA: 0x65c8768 VA: 0x7598be0768
	public static IEnumerable get_Names() { }
	// RVA: 0x65c8874 VA: 0x7598be0874
	public static DerObjectIdentifier GetOid(Int16 curvesize, Boolean twisted) { }
	// RVA: 0x65c8970 VA: 0x7598be0970
	public Void .ctor() { }
}
```