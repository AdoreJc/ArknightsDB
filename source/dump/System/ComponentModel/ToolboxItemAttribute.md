# ToolboxItemAttribute

**Namespace:** `System.ComponentModel`


## Fields

- `Type _toolboxItemType`

- `String _toolboxItemTypeName`


## Properties

- `Type ToolboxItemType`

- `String ToolboxItemTypeName`


## Methods

- `Type get_ToolboxItemType()`

- `String get_ToolboxItemTypeName()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class ToolboxItemAttribute : Attribute
{
	private Type _toolboxItemType; // 0x10
	private String _toolboxItemTypeName; // 0x18
	public static readonly ToolboxItemAttribute Default; // 0x0
	public static readonly ToolboxItemAttribute None; // 0x8

	public Type ToolboxItemType { get; }
	public String ToolboxItemTypeName { get; }

	// RVA: 0x63c10fc VA: 0x75989d90fc
	public override Boolean IsDefaultAttribute() { }
	// RVA: 0x63c1164 VA: 0x75989d9164
	public Void .ctor(Boolean defaultType) { }
	// RVA: 0x63c11d0 VA: 0x75989d91d0
	public Void .ctor(String toolboxItemTypeName) { }
	// RVA: 0x63c1264 VA: 0x75989d9264
	public Void .ctor(Type toolboxItemType) { }
	// RVA: 0x63c12c0 VA: 0x75989d92c0
	public Type get_ToolboxItemType() { }
	// RVA: 0x63c1474 VA: 0x75989d9474
	public String get_ToolboxItemTypeName() { }
	// RVA: 0x63c14c8 VA: 0x75989d94c8
	public override Boolean Equals(Object obj) { }
	// RVA: 0x63c15bc VA: 0x75989d95bc
	public override Int32 GetHashCode() { }
	// RVA: 0x63c15e0 VA: 0x75989d95e0
	private static Void .cctor() { }
}
```