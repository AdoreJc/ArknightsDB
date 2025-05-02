# Numeric10FacetsChecker

**Namespace:** `System.Xml.Schema`


## Fields

- `Decimal maxValue`

- `Decimal minValue`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class Numeric10FacetsChecker : FacetsChecker
{
	private static readonly Char[] signs; // 0x0
	private Decimal maxValue; // 0x10
	private Decimal minValue; // 0x20


	// RVA: 0x62df3c8 VA: 0x75988f73c8
	internal Void .ctor(Decimal minVal, Decimal maxVal) { }
	// RVA: 0x62e78dc VA: 0x75988ff8dc
	internal override Exception CheckValueFacets(Object value, XmlSchemaDatatype datatype) { }
	// RVA: 0x62e794c VA: 0x75988ff94c
	internal override Exception CheckValueFacets(Decimal value, XmlSchemaDatatype datatype) { }
	// RVA: 0x62e811c VA: 0x759890011c
	internal override Exception CheckValueFacets(Int64 value, XmlSchemaDatatype datatype) { }
	// RVA: 0x62e81a8 VA: 0x75989001a8
	internal override Exception CheckValueFacets(Int32 value, XmlSchemaDatatype datatype) { }
	// RVA: 0x62e8234 VA: 0x7598900234
	internal override Exception CheckValueFacets(Int16 value, XmlSchemaDatatype datatype) { }
	// RVA: 0x62e82c0 VA: 0x75989002c0
	internal override Boolean MatchEnumeration(Object value, ArrayList enumeration, XmlSchemaDatatype datatype) { }
	// RVA: 0x62e7ffc VA: 0x75988ffffc
	internal Boolean MatchEnumeration(Decimal value, ArrayList enumeration, XmlValueConverter valueConverter) { }
	// RVA: 0x62e665c VA: 0x75988fe65c
	internal Exception CheckTotalAndFractionDigits(Decimal value, Int32 totalDigits, Int32 fractionDigits, Boolean checkTotal, Boolean checkFraction) { }
	// RVA: 0x62e8344 VA: 0x7598900344
	private static Void .cctor() { }
}
```