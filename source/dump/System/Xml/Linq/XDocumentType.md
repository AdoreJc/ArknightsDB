# XDocumentType

**Namespace:** `System.Xml.Linq`


## Fields

- `String _name`

- `String _publicId`

- `String _systemId`

- `String _internalSubset`


## Properties

- `String InternalSubset`

- `String Name`

- `String PublicId`

- `String SystemId`


## Methods

- `String get_InternalSubset()`

- `String get_Name()`

- `String get_PublicId()`

- `String get_SystemId()`


## Dump
```C#
// Dll : System.Xml.Linq.dll
// Namespace : System.Xml.Linq
public class XDocumentType : XNode
{
	private String _name; // 0x28
	private String _publicId; // 0x30
	private String _systemId; // 0x38
	private String _internalSubset; // 0x40

	public String InternalSubset { get; }
	public String Name { get; }
	public override XmlNodeType NodeType { get; }
	public String PublicId { get; }
	public String SystemId { get; }

	// RVA: 0x6282a44 VA: 0x759889aa44
	public Void .ctor(String name, String publicId, String systemId, String internalSubset) { }
	// RVA: 0x6282b08 VA: 0x759889ab08
	public Void .ctor(XDocumentType other) { }
	// RVA: 0x6282bb8 VA: 0x759889abb8
	public String get_InternalSubset() { }
	// RVA: 0x6282bc0 VA: 0x759889abc0
	public String get_Name() { }
	// RVA: 0x6282bc8 VA: 0x759889abc8
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x6282bd0 VA: 0x759889abd0
	public String get_PublicId() { }
	// RVA: 0x6282bd8 VA: 0x759889abd8
	public String get_SystemId() { }
	// RVA: 0x6282be0 VA: 0x759889abe0
	public override Void WriteTo(XmlWriter writer) { }
	// RVA: 0x6282c54 VA: 0x759889ac54
	internal override XNode CloneNode() { }
}
```