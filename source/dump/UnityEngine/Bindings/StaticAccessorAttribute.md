# StaticAccessorAttribute

**Namespace:** `UnityEngine.Bindings`


## Fields

- `String <Name>k__BackingField`

- `StaticAccessorType <Type>k__BackingField`


## Properties

- `String Name`

- `StaticAccessorType Type`


## Methods

- `Void set_Name(String)`

- `Void set_Type(StaticAccessorType)`


## Dump
```C#
// Dll : UnityEngine.SharedInternalsModule.dll
// Namespace : UnityEngine.Bindings
internal class StaticAccessorAttribute : Attribute
{
	private String <Name>k__BackingField; // 0x10
	private StaticAccessorType <Type>k__BackingField; // 0x18

	public String Name { set; }
	public StaticAccessorType Type { set; }

	// RVA: 0x68e1a48 VA: 0x7598ef9a48
	public Void set_Name(String value) { }
	// RVA: 0x68e1a50 VA: 0x7598ef9a50
	public Void set_Type(StaticAccessorType value) { }
	// RVA: 0x68e1a58 VA: 0x7598ef9a58
	internal Void .ctor(String name) { }
	// RVA: 0x68e1a88 VA: 0x7598ef9a88
	public Void .ctor(String name, StaticAccessorType type) { }
}
```