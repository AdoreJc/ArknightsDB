# Numeric2FacetsChecker

**Namespace:** `System.Xml.Schema`


## Methods

- `Boolean MatchEnumeration(Double, ArrayList, XmlValueConverter)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Numeric2FacetsChecker : FacetsChecker
{


	// RVA: 0x62e83e4 VA: 0x75989003e4
	internal override Exception CheckValueFacets(Object value, XmlSchemaDatatype datatype) { }
	// RVA: 0x62e8444 VA: 0x7598900444
	internal override Exception CheckValueFacets(Double value, XmlSchemaDatatype datatype) { }
	// RVA: 0x62e877c VA: 0x759890077c
	internal override Exception CheckValueFacets(Single value, XmlSchemaDatatype datatype) { }
	// RVA: 0x62e878c VA: 0x759890078c
	internal override Boolean MatchEnumeration(Object value, ArrayList enumeration, XmlSchemaDatatype datatype) { }
	// RVA: 0x62e86c4 VA: 0x75989006c4
	private Boolean MatchEnumeration(Double value, ArrayList enumeration, XmlValueConverter valueConverter) { }
	// RVA: 0x62e8804 VA: 0x7598900804
	public Void .ctor() { }
}
```