# PropertyTabAttribute

**Namespace:** `System.ComponentModel`


## Methods

- `Void set_TabScopes(PropertyTabScope[])`

- `Boolean Equals(PropertyTabAttribute)`

- `Void InitializeArrays(String[], PropertyTabScope[])`

- `Void InitializeArrays(Type[], PropertyTabScope[])`

- `Void InitializeArrays(String[], Type[], PropertyTabScope[])`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class PropertyTabAttribute : Attribute
{
	private Type[] _tabClasses; // 0x10
	private String[] _tabClassNames; // 0x18
	private PropertyTabScope[] <TabScopes>k__BackingField; // 0x20

	public Type[] TabClasses { get; }
	protected String[] TabClassNames { get; }
	public PropertyTabScope[] TabScopes { get; set; }

	// RVA: 0x63c03cc VA: 0x75989d83cc
	public Void .ctor() { }
	// RVA: 0x63c04c0 VA: 0x75989d84c0
	public Void .ctor(Type tabClass) { }
	// RVA: 0x63c0650 VA: 0x75989d8650
	public Void .ctor(String tabClassName) { }
	// RVA: 0x63c04c8 VA: 0x75989d84c8
	public Void .ctor(Type tabClass, PropertyTabScope tabScope) { }
	// RVA: 0x63c0658 VA: 0x75989d8658
	public Void .ctor(String tabClassName, PropertyTabScope tabScope) { }
	// RVA: 0x63c07e0 VA: 0x75989d87e0
	public Type[] get_TabClasses() { }
	// RVA: 0x63c0b08 VA: 0x75989d8b08
	protected String[] get_TabClassNames() { }
	// RVA: 0x63c0b7c VA: 0x75989d8b7c
	public PropertyTabScope[] get_TabScopes() { }
	// RVA: 0x63c0b84 VA: 0x75989d8b84
	private Void set_TabScopes(PropertyTabScope[] value) { }
	// RVA: 0x63c0b8c VA: 0x75989d8b8c
	public override Boolean Equals(Object other) { }
	// RVA: 0x63c0c18 VA: 0x75989d8c18
	public Boolean Equals(PropertyTabAttribute other) { }
	// RVA: 0x63c0dac VA: 0x75989d8dac
	public override Int32 GetHashCode() { }
	// RVA: 0x63c0db4 VA: 0x75989d8db4
	protected Void InitializeArrays(String[] tabClassNames, PropertyTabScope[] tabScopes) { }
	// RVA: 0x63c10ec VA: 0x75989d90ec
	protected Void InitializeArrays(Type[] tabClasses, PropertyTabScope[] tabScopes) { }
	// RVA: 0x63c0dc0 VA: 0x75989d8dc0
	private Void InitializeArrays(String[] tabClassNames, Type[] tabClasses, PropertyTabScope[] tabScopes) { }
}
```