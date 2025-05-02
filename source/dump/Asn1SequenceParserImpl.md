# Asn1SequenceParserImpl

**Namespace:** ` `


## Fields

- `Int32 index`


## Methods

- `IAsn1Convertible ReadObject()`

- `Asn1Object ToAsn1Object()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
private class Asn1SequenceParserImpl : Asn1SequenceParser, IAsn1Convertible
{
	private readonly Asn1Sequence outer; // 0x10
	private readonly Int32 max; // 0x18
	private Int32 index; // 0x1c


	// RVA: 0x65923d0 VA: 0x7598baa3d0
	public Void .ctor(Asn1Sequence outer) { }
	// RVA: 0x6592cbc VA: 0x7598baacbc
	public IAsn1Convertible ReadObject() { }
	// RVA: 0x6592e14 VA: 0x7598baae14
	public Asn1Object ToAsn1Object() { }
}
```