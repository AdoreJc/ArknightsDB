# SchemaDatatypeMap

**Namespace:** ` `


## Fields

- `String name`

- `DatatypeImplementation type`

- `Int32 parentIndex`


## Properties

- `String Name`

- `Int32 ParentIndex`


## Methods

- `String get_Name()`

- `Int32 get_ParentIndex()`

- `Int32 CompareTo(Object)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : 
private class SchemaDatatypeMap : IComparable
{
	private String name; // 0x10
	private DatatypeImplementation type; // 0x18
	private Int32 parentIndex; // 0x20

	public String Name { get; }
	public Int32 ParentIndex { get; }

	// RVA: 0x62dbb00 VA: 0x75988f3b00
	internal Void .ctor(String name, DatatypeImplementation type) { }
	// RVA: 0x62dbb44 VA: 0x75988f3b44
	internal Void .ctor(String name, DatatypeImplementation type, Int32 parentIndex) { }
	// RVA: 0x62dcea4 VA: 0x75988f4ea4
	public static DatatypeImplementation op_Explicit(SchemaDatatypeMap sdm) { }
	// RVA: 0x62dcebc VA: 0x75988f4ebc
	public String get_Name() { }
	// RVA: 0x62dcec4 VA: 0x75988f4ec4
	public Int32 get_ParentIndex() { }
	// RVA: 0x62dcecc VA: 0x75988f4ecc
	public Int32 CompareTo(Object obj) { }
}
```