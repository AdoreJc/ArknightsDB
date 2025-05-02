# ContentValidator

**Namespace:** `System.Xml.Schema`


## Fields

- `XmlSchemaContentType contentType`

- `Boolean isOpen`

- `Boolean isEmptiable`


## Properties

- `XmlSchemaContentType ContentType`

- `Boolean IsOpen`


## Methods

- `XmlSchemaContentType get_ContentType()`

- `Boolean get_IsOpen()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
internal class ContentValidator
{
	private XmlSchemaContentType contentType; // 0x10
	private Boolean isOpen; // 0x14
	private Boolean isEmptiable; // 0x15
	public static readonly ContentValidator Empty; // 0x0
	public static readonly ContentValidator TextOnly; // 0x8
	public static readonly ContentValidator Mixed; // 0x10
	public static readonly ContentValidator Any; // 0x18

	public XmlSchemaContentType ContentType { get; }
	public Boolean IsOpen { get; }

	// RVA: 0x62d5834 VA: 0x75988ed834
	public Void .ctor(XmlSchemaContentType contentType) { }
	// RVA: 0x62d5864 VA: 0x75988ed864
	protected Void .ctor(XmlSchemaContentType contentType, Boolean isOpen, Boolean isEmptiable) { }
	// RVA: 0x62d58a4 VA: 0x75988ed8a4
	public XmlSchemaContentType get_ContentType() { }
	// RVA: 0x62d58ac VA: 0x75988ed8ac
	public Boolean get_IsOpen() { }
	// RVA: 0x62d58d0 VA: 0x75988ed8d0
	private static Void .cctor() { }
}
```