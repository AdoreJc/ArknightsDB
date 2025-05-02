# XmlImplementation

**Namespace:** `System.Xml`


## Fields

- `XmlNameTable nameTable`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlImplementation
{
	private XmlNameTable nameTable; // 0x10

	internal XmlNameTable NameTable { get; }

	// RVA: 0x62afb40 VA: 0x75988c7b40
	public Void .ctor() { }
	// RVA: 0x62afc2c VA: 0x75988c7c2c
	public Void .ctor(XmlNameTable nt) { }
	// RVA: 0x62afc5c VA: 0x75988c7c5c
	public virtual XmlDocument CreateDocument() { }
	// RVA: 0x62afcc0 VA: 0x75988c7cc0
	internal XmlNameTable get_NameTable() { }
}
```