# XmlSchemaObjectCollection

**Namespace:** `System.Xml.Schema`


## Fields

- `XmlSchemaObject parent`


## Methods

- `Int32 Add(XmlSchemaObject)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml.Schema
public class XmlSchemaObjectCollection : CollectionBase
{
	private XmlSchemaObject parent; // 0x18


	// RVA: 0x62efc5c VA: 0x7598907c5c
	public Void .ctor() { }
	// RVA: 0x62eeb5c VA: 0x7598906b5c
	public Int32 Add(XmlSchemaObject item) { }
	// RVA: 0x62efc64 VA: 0x7598907c64
	protected override Void OnInsert(Int32 index, Object item) { }
	// RVA: 0x62efc80 VA: 0x7598907c80
	protected override Void OnSet(Int32 index, Object oldValue, Object newValue) { }
	// RVA: 0x62efcdc VA: 0x7598907cdc
	protected override Void OnClear() { }
	// RVA: 0x62efcf8 VA: 0x7598907cf8
	protected override Void OnRemove(Int32 index, Object item) { }
}
```