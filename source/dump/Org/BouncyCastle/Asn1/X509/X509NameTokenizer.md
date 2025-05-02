# X509NameTokenizer

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Fields

- `String value`

- `Int32 index`

- `Char separator`

- `StringBuilder buffer`


## Methods

- `Boolean HasMoreTokens()`

- `String NextToken()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class X509NameTokenizer
{
	private String value; // 0x10
	private Int32 index; // 0x18
	private Char separator; // 0x1c
	private StringBuilder buffer; // 0x20


	// RVA: 0x65c0660 VA: 0x7598bd8660
	public Void .ctor(String oid) { }
	// RVA: 0x65c0838 VA: 0x7598bd8838
	public Void .ctor(String oid, Char separator) { }
	// RVA: 0x65c08dc VA: 0x7598bd88dc
	public Boolean HasMoreTokens() { }
	// RVA: 0x65c0668 VA: 0x7598bd8668
	public String NextToken() { }
}
```