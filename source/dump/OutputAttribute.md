# OutputAttribute

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
public class OutputAttribute : Attribute
{
	public ShowBackingValue backingValue; // 0x10
	public ConnectionType connectionType; // 0x14
	public Boolean dynamicPortList; // 0x18
	public TypeConstraint typeConstraint; // 0x1c

	public Boolean instancePortList { get; set; }

	// RVA: 0x6a8c638 VA: 0x75990a4638
	public Boolean get_instancePortList() { }
	// RVA: 0x6a8c640 VA: 0x75990a4640
	public Void set_instancePortList(Boolean value) { }
	// RVA: 0x6a8c64c VA: 0x75990a464c
	public Void .ctor(ShowBackingValue backingValue, ConnectionType connectionType, TypeConstraint typeConstraint, Boolean dynamicPortList) { }
	// RVA: 0x6a8c690 VA: 0x75990a4690
	public Void .ctor(ShowBackingValue backingValue, ConnectionType connectionType, Boolean dynamicPortList) { }
}
```