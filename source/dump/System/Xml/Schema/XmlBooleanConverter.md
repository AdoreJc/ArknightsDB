# XmlBooleanConverter

**Namespace:** `System.Xml.Schema`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class XmlBooleanConverter : XmlBaseConverter
{


	// RVA: 0x62fe1ac VA: 0x75989161ac
	protected Void .ctor(XmlSchemaType schemaType) { }
	// RVA: 0x62de0e4 VA: 0x75988f60e4
	public static XmlValueConverter Create(XmlSchemaType schemaType) { }
	// RVA: 0x62fe210 VA: 0x7598916210
	public override Boolean ToBoolean(String value) { }
	// RVA: 0x62fe2b8 VA: 0x75989162b8
	public override Boolean ToBoolean(Object value) { }
	// RVA: 0x62fe594 VA: 0x7598916594
	public override String ToString(Boolean value) { }
	// RVA: 0x62fe5ec VA: 0x75989165ec
	public override String ToString(Object value, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x62fe8b8 VA: 0x75989168b8
	public override Object ChangeType(Boolean value, Type destinationType) { }
	// RVA: 0x62febe4 VA: 0x7598916be4
	public override Object ChangeType(String value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
	// RVA: 0x62fef24 VA: 0x7598916f24
	public override Object ChangeType(Object value, Type destinationType, IXmlNamespaceResolver nsResolver) { }
}
```