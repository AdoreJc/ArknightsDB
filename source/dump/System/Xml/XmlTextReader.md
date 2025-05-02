# XmlTextReader

**Namespace:** `System.Xml`


## Fields

- `XmlTextReaderImpl impl`


## Properties

- `EntityHandling EntityHandling`

- `XmlResolver XmlResolver`


## Methods

- `Void set_EntityHandling(EntityHandling)`

- `Void set_XmlResolver(XmlResolver)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlTextReader : XmlReader, IXmlNamespaceResolver
{
	private XmlTextReaderImpl impl; // 0x10

	public override XmlNodeType NodeType { get; }
	public override String Name { get; }
	public override String LocalName { get; }
	public override String NamespaceURI { get; }
	public override String Prefix { get; }
	public override String Value { get; }
	public override String BaseURI { get; }
	public override Boolean IsEmptyElement { get; }
	public override Boolean IsDefault { get; }
	public override ReadState ReadState { get; }
	public override XmlNameTable NameTable { get; }
	public override Boolean CanResolveEntity { get; }
	public EntityHandling EntityHandling { set; }
	public XmlResolver XmlResolver { set; }
	internal XmlTextReaderImpl Impl { get; }
	internal Boolean XmlValidatingReaderCompatibilityMode { set; }
	internal override IDtdInfo DtdInfo { get; }

	// RVA: 0x6297748 VA: 0x75988af748
	public Void .ctor(TextReader input, XmlNameTable nt) { }
	// RVA: 0x6297814 VA: 0x75988af814
	public override XmlNodeType get_NodeType() { }
	// RVA: 0x6297834 VA: 0x75988af834
	public override String get_Name() { }
	// RVA: 0x6297854 VA: 0x75988af854
	public override String get_LocalName() { }
	// RVA: 0x6297874 VA: 0x75988af874
	public override String get_NamespaceURI() { }
	// RVA: 0x6297894 VA: 0x75988af894
	public override String get_Prefix() { }
	// RVA: 0x62978b4 VA: 0x75988af8b4
	public override String get_Value() { }
	// RVA: 0x62978d4 VA: 0x75988af8d4
	public override String get_BaseURI() { }
	// RVA: 0x62978f4 VA: 0x75988af8f4
	public override Boolean get_IsEmptyElement() { }
	// RVA: 0x6297918 VA: 0x75988af918
	public override Boolean get_IsDefault() { }
	// RVA: 0x629793c VA: 0x75988af93c
	public override Boolean MoveToAttribute(String name) { }
	// RVA: 0x6297960 VA: 0x75988af960
	public override Boolean MoveToFirstAttribute() { }
	// RVA: 0x6297984 VA: 0x75988af984
	public override Boolean MoveToNextAttribute() { }
	// RVA: 0x62979a8 VA: 0x75988af9a8
	public override Boolean MoveToElement() { }
	// RVA: 0x62979cc VA: 0x75988af9cc
	public override Boolean ReadAttributeValue() { }
	// RVA: 0x62979f0 VA: 0x75988af9f0
	public override Boolean Read() { }
	// RVA: 0x6297a14 VA: 0x75988afa14
	public override Void Close() { }
	// RVA: 0x6297a38 VA: 0x75988afa38
	public override ReadState get_ReadState() { }
	// RVA: 0x6297a5c VA: 0x75988afa5c
	public override XmlNameTable get_NameTable() { }
	// RVA: 0x6297a80 VA: 0x75988afa80
	public override String LookupNamespace(String prefix) { }
	// RVA: 0x6297ab8 VA: 0x75988afab8
	public override Boolean get_CanResolveEntity() { }
	// RVA: 0x6297ac0 VA: 0x75988afac0
	public override Void ResolveEntity() { }
	// RVA: 0x6297ae4 VA: 0x75988afae4
	private String System.Xml.IXmlNamespaceResolver.LookupNamespace(String prefix) { }
	// RVA: 0x6297b08 VA: 0x75988afb08
	private String System.Xml.IXmlNamespaceResolver.LookupPrefix(String namespaceName) { }
	// RVA: 0x6297b24 VA: 0x75988afb24
	public Void set_EntityHandling(EntityHandling value) { }
	// RVA: 0x6297b40 VA: 0x75988afb40
	public Void set_XmlResolver(XmlResolver value) { }
	// RVA: 0x6297b5c VA: 0x75988afb5c
	internal XmlTextReaderImpl get_Impl() { }
	// RVA: 0x6297b64 VA: 0x75988afb64
	internal Void set_XmlValidatingReaderCompatibilityMode(Boolean value) { }
	// RVA: 0x6297b84 VA: 0x75988afb84
	internal override IDtdInfo get_DtdInfo() { }
}
```