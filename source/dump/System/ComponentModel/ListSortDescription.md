# ListSortDescription

**Namespace:** `System.ComponentModel`


## Fields

- `PropertyDescriptor <PropertyDescriptor>k__BackingField`

- `ListSortDirection <SortDirection>k__BackingField`


## Properties

- `PropertyDescriptor PropertyDescriptor`

- `ListSortDirection SortDirection`


## Methods

- `PropertyDescriptor get_PropertyDescriptor()`

- `Void set_PropertyDescriptor(PropertyDescriptor)`

- `ListSortDirection get_SortDirection()`

- `Void set_SortDirection(ListSortDirection)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class ListSortDescription
{
	private PropertyDescriptor <PropertyDescriptor>k__BackingField; // 0x10
	private ListSortDirection <SortDirection>k__BackingField; // 0x18

	public PropertyDescriptor PropertyDescriptor { get; set; }
	public ListSortDirection SortDirection { get; set; }

	// RVA: 0x63c74a0 VA: 0x75989df4a0
	public Void .ctor(PropertyDescriptor property, ListSortDirection direction) { }
	// RVA: 0x63c74dc VA: 0x75989df4dc
	public PropertyDescriptor get_PropertyDescriptor() { }
	// RVA: 0x63c74e4 VA: 0x75989df4e4
	public Void set_PropertyDescriptor(PropertyDescriptor value) { }
	// RVA: 0x63c74ec VA: 0x75989df4ec
	public ListSortDirection get_SortDirection() { }
	// RVA: 0x63c74f4 VA: 0x75989df4f4
	public Void set_SortDirection(ListSortDirection value) { }
}
```