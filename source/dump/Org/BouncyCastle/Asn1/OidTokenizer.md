# OidTokenizer

**Namespace:** `Org.BouncyCastle.Asn1`


## Fields

- `String oid`

- `Int32 index`


## Properties

- `Boolean HasMoreTokens`


## Methods

- `Boolean get_HasMoreTokens()`

- `String NextToken()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class OidTokenizer
{
	private String oid; // 0x10
	private Int32 index; // 0x18

	public Boolean HasMoreTokens { get; }

	// RVA: 0x65a4e40 VA: 0x7598bbce40
	public Void .ctor(String oid) { }
	// RVA: 0x65a4e70 VA: 0x7598bbce70
	public Boolean get_HasMoreTokens() { }
	// RVA: 0x65a4e80 VA: 0x7598bbce80
	public String NextToken() { }
}
```