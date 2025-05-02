# XmlParserContext

**Namespace:** `System.Xml`


## Fields

- `XmlNameTable _nt`

- `XmlNamespaceManager _nsMgr`

- `String _docTypeName`

- `String _pubId`

- `String _sysId`

- `String _internalSubset`

- `String _xmlLang`

- `XmlSpace _xmlSpace`

- `String _baseURI`

- `Encoding _encoding`


## Properties

- `XmlNameTable NameTable`

- `XmlNamespaceManager NamespaceManager`

- `String DocTypeName`

- `String PublicId`

- `String SystemId`

- `String BaseURI`

- `String InternalSubset`

- `String XmlLang`

- `XmlSpace XmlSpace`

- `Encoding Encoding`


## Methods

- `XmlNameTable get_NameTable()`

- `XmlNamespaceManager get_NamespaceManager()`

- `String get_DocTypeName()`

- `String get_PublicId()`

- `String get_SystemId()`

- `String get_BaseURI()`

- `String get_InternalSubset()`

- `String get_XmlLang()`

- `XmlSpace get_XmlSpace()`

- `Encoding get_Encoding()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlParserContext
{
	private XmlNameTable _nt; // 0x10
	private XmlNamespaceManager _nsMgr; // 0x18
	private String _docTypeName; // 0x20
	private String _pubId; // 0x28
	private String _sysId; // 0x30
	private String _internalSubset; // 0x38
	private String _xmlLang; // 0x40
	private XmlSpace _xmlSpace; // 0x48
	private String _baseURI; // 0x50
	private Encoding _encoding; // 0x58

	public XmlNameTable NameTable { get; }
	public XmlNamespaceManager NamespaceManager { get; }
	public String DocTypeName { get; }
	public String PublicId { get; }
	public String SystemId { get; }
	public String BaseURI { get; }
	public String InternalSubset { get; }
	public String XmlLang { get; }
	public XmlSpace XmlSpace { get; }
	public Encoding Encoding { get; }
	internal Boolean HasDtdInfo { get; }

	// RVA: 0x627d868 VA: 0x7598895868
	public Void .ctor(XmlNameTable nt, XmlNamespaceManager nsMgr, String docTypeName, String pubId, String sysId, String internalSubset, String baseURI, String xmlLang, XmlSpace xmlSpace) { }
	// RVA: 0x627d894 VA: 0x7598895894
	public Void .ctor(XmlNameTable nt, XmlNamespaceManager nsMgr, String docTypeName, String pubId, String sysId, String internalSubset, String baseURI, String xmlLang, XmlSpace xmlSpace, Encoding enc) { }
	// RVA: 0x627db7c VA: 0x7598895b7c
	public XmlNameTable get_NameTable() { }
	// RVA: 0x627db84 VA: 0x7598895b84
	public XmlNamespaceManager get_NamespaceManager() { }
	// RVA: 0x627db8c VA: 0x7598895b8c
	public String get_DocTypeName() { }
	// RVA: 0x627db94 VA: 0x7598895b94
	public String get_PublicId() { }
	// RVA: 0x627db9c VA: 0x7598895b9c
	public String get_SystemId() { }
	// RVA: 0x627dba4 VA: 0x7598895ba4
	public String get_BaseURI() { }
	// RVA: 0x627dbac VA: 0x7598895bac
	public String get_InternalSubset() { }
	// RVA: 0x627dbb4 VA: 0x7598895bb4
	public String get_XmlLang() { }
	// RVA: 0x627dbbc VA: 0x7598895bbc
	public XmlSpace get_XmlSpace() { }
	// RVA: 0x627dbc4 VA: 0x7598895bc4
	public Encoding get_Encoding() { }
	// RVA: 0x627dbcc VA: 0x7598895bcc
	internal Boolean get_HasDtdInfo() { }
}
```