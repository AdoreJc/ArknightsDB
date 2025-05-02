# XmlDocumentType

**Namespace:** `System.Xml`


## Fields

- `String name`

- `String publicId`

- `String systemId`

- `String internalSubset`

- `Boolean namespaces`

- `XmlNamedNodeMap entities`

- `XmlNamedNodeMap notations`

- `SchemaInfo schemaInfo`


## Properties

- `XmlNamedNodeMap Entities`

- `XmlNamedNodeMap Notations`

- `String PublicId`

- `String SystemId`

- `String InternalSubset`


## Methods

- `XmlNamedNodeMap get_Entities()`

- `XmlNamedNodeMap get_Notations()`

- `String get_PublicId()`

- `String get_SystemId()`

- `String get_InternalSubset()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlDocumentType : XmlLinkedNode
{
	private String name; // 0x20
	private String publicId; // 0x28
	private String systemId; // 0x30
	private String internalSubset; // 0x38
	private Boolean namespaces; // 0x40
	private XmlNamedNodeMap entities; // 0x48
	private XmlNamedNodeMap notations; // 0x50
	private SchemaInfo schemaInfo; // 0x58

	public override String Name { get; }
	public override String LocalName { get; }
	public override XmlNodeType NodeType { get; }
	public override Boolean IsReadOnly { get; }
	public XmlNamedNodeMap Entities { get; }
	public XmlNamedNodeMap Notations { get; }
	public String PublicId { get; }
	public String SystemId { get; }
	public String InternalSubset { get; }
	internal Boolean ParseWithNamespaces { get; }
	internal SchemaInfo DtdSchemaInfo { get; set; }

	// RVA: 0x62ad684 VA: 0x75988c5684
	protected internal Void .ctor(String name, String publicId, String systemId, String internalSubset, XmlDocument doc) { }
	// RVA: 0x62ad814 VA: 0x75988c5814
	public override String get_Name() { }
	// RVA: 0x62ad81c VA: 0x75988c581c
	public override String get_LocalName() { }
	// RVA: 0x62ad824 VA: 0x75988c5824
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x62ad82c VA: 0x75988c582c
	public override XmlNode CloneNode(Boolean deep) { }
	// RVA: 0x62ad868 VA: 0x75988c5868
	public override Boolean get_IsReadOnly() { }
	// RVA: 0x62ad870 VA: 0x75988c5870
	public XmlNamedNodeMap get_Entities() { }
	// RVA: 0x62ad92c VA: 0x75988c592c
	public XmlNamedNodeMap get_Notations() { }
	// RVA: 0x62ad9b8 VA: 0x75988c59b8
	public String get_PublicId() { }
	// RVA: 0x62ad9c0 VA: 0x75988c59c0
	public String get_SystemId() { }
	// RVA: 0x62ad9c8 VA: 0x75988c59c8
	public String get_InternalSubset() { }
	// RVA: 0x62ad9d0 VA: 0x75988c59d0
	internal Boolean get_ParseWithNamespaces() { }
	// RVA: 0x62ad9d8 VA: 0x75988c59d8
	internal SchemaInfo get_DtdSchemaInfo() { }
	// RVA: 0x62ad9e0 VA: 0x75988c59e0
	internal Void set_DtdSchemaInfo(SchemaInfo value) { }
}
```