# ValidationEventArgs

**Namespace:** `System.Xml.Schema`


## Fields

- `XmlSchemaException ex`

- `XmlSeverityType severity`


## Properties

- `XmlSeverityType Severity`

- `XmlSchemaException Exception`


## Methods

- `XmlSeverityType get_Severity()`

- `XmlSchemaException get_Exception()`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
public class ValidationEventArgs : EventArgs
{
	private XmlSchemaException ex; // 0x10
	private XmlSeverityType severity; // 0x18

	public XmlSeverityType Severity { get; }
	public XmlSchemaException Exception { get; }

	// RVA: 0x62ec964 VA: 0x7598904964
	public XmlSeverityType get_Severity() { }
	// RVA: 0x62ec96c VA: 0x759890496c
	public XmlSchemaException get_Exception() { }
}
```