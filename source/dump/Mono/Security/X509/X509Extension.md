# X509Extension

**Namespace:** `Mono.Security.X509`


## Fields

- `String extnOid`

- `Boolean extnCritical`

- `ASN1 extnValue`


## Properties

- `String Oid`

- `Boolean Critical`

- `ASN1 Value`


## Methods

- `String get_Oid()`

- `Boolean get_Critical()`

- `ASN1 get_Value()`

- `Void WriteLine(StringBuilder, Int32, Int32)`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.X509
public class X509Extension
{
	protected String extnOid; // 0x10
	protected Boolean extnCritical; // 0x18
	protected ASN1 extnValue; // 0x20

	public String Oid { get; }
	public Boolean Critical { get; }
	public ASN1 Value { get; }

	// RVA: 0x5ee36bc VA: 0x75984fb6bc
	public Void .ctor(ASN1 asn1) { }
	// RVA: 0x5ee39b0 VA: 0x75984fb9b0
	public Void .ctor(X509Extension extension) { }
	// RVA: 0x5ee3b3c VA: 0x75984fbb3c
	protected virtual Void Decode() { }
	// RVA: 0x5ee3b40 VA: 0x75984fbb40
	protected virtual Void Encode() { }
	// RVA: 0x5ee3b44 VA: 0x75984fbb44
	public String get_Oid() { }
	// RVA: 0x5ee3b4c VA: 0x75984fbb4c
	public Boolean get_Critical() { }
	// RVA: 0x5ee3b10 VA: 0x75984fbb10
	public ASN1 get_Value() { }
	// RVA: 0x5ee3b54 VA: 0x75984fbb54
	public override Boolean Equals(Object obj) { }
	// RVA: 0x5ee3c98 VA: 0x75984fbc98
	public override Int32 GetHashCode() { }
	// RVA: 0x5ee3cb8 VA: 0x75984fbcb8
	private Void WriteLine(StringBuilder sb, Int32 n, Int32 pos) { }
	// RVA: 0x5ee3ee0 VA: 0x75984fbee0
	public override String ToString() { }
}
```