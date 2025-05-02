# StringFacetsChecker

**Namespace:** `System.Xml.Schema`


## Methods

- `Boolean MatchEnumeration(String, ArrayList, XmlSchemaDatatype)`

- `Exception CheckBuiltInFacets(String, XmlTypeCode, Boolean)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class StringFacetsChecker : FacetsChecker
{
	private static Regex languagePattern; // 0x0

	private static Regex LanguagePattern { get; }

	// RVA: 0x62e9370 VA: 0x7598901370
	private static Regex get_LanguagePattern() { }
	// RVA: 0x62e9428 VA: 0x7598901428
	internal override Exception CheckValueFacets(Object value, XmlSchemaDatatype datatype) { }
	// RVA: 0x62e9488 VA: 0x7598901488
	internal override Exception CheckValueFacets(String value, XmlSchemaDatatype datatype) { }
	// RVA: 0x62e16e8 VA: 0x75988f96e8
	internal Exception CheckValueFacets(String value, XmlSchemaDatatype datatype, Boolean verifyUri) { }
	// RVA: 0x62e987c VA: 0x759890187c
	internal override Boolean MatchEnumeration(Object value, ArrayList enumeration, XmlSchemaDatatype datatype) { }
	// RVA: 0x62e96a8 VA: 0x75989016a8
	private Boolean MatchEnumeration(String value, ArrayList enumeration, XmlSchemaDatatype datatype) { }
	// RVA: 0x62e9490 VA: 0x7598901490
	private Exception CheckBuiltInFacets(String s, XmlTypeCode typeCode, Boolean verifyUri) { }
	// RVA: 0x62e98d8 VA: 0x75989018d8
	public Void .ctor() { }
}
```