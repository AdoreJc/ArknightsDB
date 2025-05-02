# XmlSchemaAnyAttribute

**Namespace:** `System.Xml.Schema`


## Fields

- `String ns`

- `XmlSchemaContentProcessing processContents`

- `NamespaceList namespaceList`


## Properties

- `XmlSchemaContentProcessing ProcessContents`


## Methods

- `Void set_ProcessContents(XmlSchemaContentProcessing)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
public class XmlSchemaAnyAttribute : XmlSchemaAnnotated
{
	private String ns; // 0x10
	private XmlSchemaContentProcessing processContents; // 0x18
	private NamespaceList namespaceList; // 0x20

	public XmlSchemaContentProcessing ProcessContents { set; }

	// RVA: 0x62ee0c8 VA: 0x75989060c8
	public Void set_ProcessContents(XmlSchemaContentProcessing value) { }
	// RVA: 0x62ee0d0 VA: 0x75989060d0
	internal Void BuildNamespaceList(String targetNamespace) { }
	// RVA: 0x62ee168 VA: 0x7598906168
	public Void .ctor() { }
}
```