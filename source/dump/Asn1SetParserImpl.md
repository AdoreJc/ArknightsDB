# Asn1SetParserImpl

**Namespace:** ` `


## Fields

- `Int32 index`


## Methods

- `IAsn1Convertible ReadObject()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
private class Asn1SetParserImpl : Asn1SetParser, IAsn1Convertible
{
	private readonly Asn1Set outer; // 0x10
	private readonly Int32 max; // 0x18
	private Int32 index; // 0x1c


	// RVA: 0x6593f18 VA: 0x7598babf18
	public Void .ctor(Asn1Set outer) { }
	// RVA: 0x6594b60 VA: 0x7598bacb60
	public IAsn1Convertible ReadObject() { }
	// RVA: 0x6594c58 VA: 0x7598bacc58
	public virtual Asn1Object ToAsn1Object() { }
}
```