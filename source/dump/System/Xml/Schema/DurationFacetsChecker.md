# DurationFacetsChecker

**Namespace:** `System.Xml.Schema`


## Methods

- `Boolean MatchEnumeration(TimeSpan, ArrayList)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class DurationFacetsChecker : FacetsChecker
{


	// RVA: 0x62e880c VA: 0x759890080c
	internal override Exception CheckValueFacets(Object value, XmlSchemaDatatype datatype) { }
	// RVA: 0x62e8920 VA: 0x7598900920
	internal override Exception CheckValueFacets(TimeSpan value, XmlSchemaDatatype datatype) { }
	// RVA: 0x62e8d4c VA: 0x7598900d4c
	internal override Boolean MatchEnumeration(Object value, ArrayList enumeration, XmlSchemaDatatype datatype) { }
	// RVA: 0x62e8c40 VA: 0x7598900c40
	private Boolean MatchEnumeration(TimeSpan value, ArrayList enumeration) { }
	// RVA: 0x62e8dc4 VA: 0x7598900dc4
	public Void .ctor() { }
}
```