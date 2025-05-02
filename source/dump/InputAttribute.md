# InputAttribute

**Namespace:** ` `


## Fields

- `ShowBackingValue backingValue`

- `ConnectionType connectionType`

- `Boolean dynamicPortList`

- `TypeConstraint typeConstraint`


## Properties

- `Boolean instancePortList`


## Methods

- `Boolean get_instancePortList()`

- `Void set_instancePortList(Boolean)`


## Dump
```C#
// Dll : XNode.dll
// Namespace : 
public class InputAttribute : Attribute
{
	public ShowBackingValue backingValue; // 0x10
	public ConnectionType connectionType; // 0x14
	public Boolean dynamicPortList; // 0x18
	public TypeConstraint typeConstraint; // 0x1c

	public Boolean instancePortList { get; set; }

	// RVA: 0x6a8c5e0 VA: 0x75990a45e0
	public Boolean get_instancePortList() { }
	// RVA: 0x6a8c5e8 VA: 0x75990a45e8
	public Void set_instancePortList(Boolean value) { }
	// RVA: 0x6a8c5f4 VA: 0x75990a45f4
	public Void .ctor(ShowBackingValue backingValue, ConnectionType connectionType, TypeConstraint typeConstraint, Boolean dynamicPortList) { }
}
```