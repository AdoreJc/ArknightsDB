# XmlSchemaSet

**Namespace:** `System.Xml.Schema`


## Fields

- `XmlNameTable nameTable`

- `SortedList schemas`

- `ValidationEventHandler internalEventHandler`

- `ValidationEventHandler eventHandler`

- `Hashtable schemaLocations`

- `Hashtable chameleonSchemas`

- `Hashtable targetNamespaces`

- `Boolean compileAll`

- `SchemaInfo cachedCompiledInfo`

- `XmlReaderSettings readerSettings`

- `XmlSchemaCompilationSettings compilationSettings`


## Methods

- `Void InternalValidationCallback(Object, ValidationEventArgs)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
public class XmlSchemaSet
{
	private XmlNameTable nameTable; // 0x10
	private SortedList schemas; // 0x18
	private ValidationEventHandler internalEventHandler; // 0x20
	private ValidationEventHandler eventHandler; // 0x28
	private Hashtable schemaLocations; // 0x30
	private Hashtable chameleonSchemas; // 0x38
	private Hashtable targetNamespaces; // 0x40
	private Boolean compileAll; // 0x48
	private SchemaInfo cachedCompiledInfo; // 0x50
	private XmlReaderSettings readerSettings; // 0x58
	private XmlSchemaCompilationSettings compilationSettings; // 0x60


	// RVA: 0x62efdf0 VA: 0x7598907df0
	public Void .ctor() { }
	// RVA: 0x62efe54 VA: 0x7598907e54
	public Void .ctor(XmlNameTable nameTable) { }
	// RVA: 0x62f0168 VA: 0x7598908168
	private Void InternalValidationCallback(Object sender, ValidationEventArgs e) { }
}
```