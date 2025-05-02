# ListChangedEventArgs

**Namespace:** `System.ComponentModel`


## Properties

- `ListChangedType ListChangedType`

- `Int32 NewIndex`

- `Int32 OldIndex`

- `PropertyDescriptor PropertyDescriptor`


## Methods

- `ListChangedType get_ListChangedType()`

- `Int32 get_NewIndex()`

- `Int32 get_OldIndex()`

- `PropertyDescriptor get_PropertyDescriptor()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class ListChangedEventArgs : EventArgs
{
	private readonly ListChangedType <ListChangedType>k__BackingField; // 0x10
	private readonly Int32 <NewIndex>k__BackingField; // 0x14
	private readonly Int32 <OldIndex>k__BackingField; // 0x18
	private readonly PropertyDescriptor <PropertyDescriptor>k__BackingField; // 0x20

	public ListChangedType ListChangedType { get; }
	public Int32 NewIndex { get; }
	public Int32 OldIndex { get; }
	public PropertyDescriptor PropertyDescriptor { get; }

	// RVA: 0x63c71b8 VA: 0x75989df1b8
	public Void .ctor(ListChangedType listChangedType, Int32 newIndex) { }
	// RVA: 0x63c7240 VA: 0x75989df240
	public Void .ctor(ListChangedType listChangedType, Int32 newIndex, PropertyDescriptor propDesc) { }
	// RVA: 0x63c727c VA: 0x75989df27c
	public Void .ctor(ListChangedType listChangedType, PropertyDescriptor propDesc) { }
	// RVA: 0x63c71c0 VA: 0x75989df1c0
	public Void .ctor(ListChangedType listChangedType, Int32 newIndex, Int32 oldIndex) { }
	// RVA: 0x63c72f8 VA: 0x75989df2f8
	public ListChangedType get_ListChangedType() { }
	// RVA: 0x63c7300 VA: 0x75989df300
	public Int32 get_NewIndex() { }
	// RVA: 0x63c7308 VA: 0x75989df308
	public Int32 get_OldIndex() { }
	// RVA: 0x63c7310 VA: 0x75989df310
	public PropertyDescriptor get_PropertyDescriptor() { }
}
```