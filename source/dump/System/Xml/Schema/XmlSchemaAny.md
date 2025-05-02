# XmlSchemaAny

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
public class XmlSchemaAny : XmlSchemaParticle
{
	private String ns; // 0x38
	private XmlSchemaContentProcessing processContents; // 0x40
	private NamespaceList namespaceList; // 0x48

	public XmlSchemaContentProcessing ProcessContents { set; }
	internal NamespaceList NamespaceList { get; }

	// RVA: 0x62edf58 VA: 0x7598905f58
	public Void set_ProcessContents(XmlSchemaContentProcessing value) { }
	// RVA: 0x62edf60 VA: 0x7598905f60
	internal NamespaceList get_NamespaceList() { }
	// RVA: 0x62edf68 VA: 0x7598905f68
	internal Void BuildNamespaceList(String targetNamespace) { }
	// RVA: 0x62ee000 VA: 0x7598906000
	public Void .ctor() { }
}
```