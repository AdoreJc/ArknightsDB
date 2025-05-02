# XmlNumeric2Converter

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class XmlNumeric2Converter : XmlBaseConverter
{


	// RVA: 0x62fa6f4 VA: 0x75989126f4
	protected Void .ctor(XmlSchemaType schemaType) { }
	// RVA: 0x62de54c VA: 0x75988f654c
	public static XmlValueConverter Create(XmlSchemaType schemaType) { }
	// RVA: 0x62fa758 VA: 0x7598912758
	public override Double ToDouble(String value) { }
	// RVA: 0x62fa828 VA: 0x7598912828
	public override Double ToDouble(Object value) { }
	// RVA: 0x62fab68 VA: 0x7598912b68
	public override Single ToSingle(Double value) { }
	// RVA: 0x62fab70 VA: 0x7598912b70
	public override Single ToSingle(String value) { }
	// RVA: 0x62fac40 VA: 0x7598912c40
	public override Single ToSingle(Object value) { }
	// RVA: 0x62faf88 VA: 0x7598912f88
	public override String ToString(Double value) { }
	// RVA: 0x62fb03c VA: 0x759891303c
	public override String ToString(Single value) { }
	// RVA: 0x62fb0c4 VA: 0x75989130c4
	public override String ToString(Object value, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x62fb41c VA: 0x759891341c
	public override Object ChangeType(Double value, Type destinationType) { }
	// RVA: 0x62fb788 VA: 0x7598913788
	public override Object ChangeType(String value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x62fbb34 VA: 0x7598913b34
	public override Object ChangeType(Object value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
}
```