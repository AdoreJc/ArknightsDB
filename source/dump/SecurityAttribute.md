# SecurityAttribute

**Namespace:** ` `


## Fields

- `String _name`

- `String _value`


## Properties

- `String Name`

- `String Value`


## Methods

- `String get_Name()`

- `String get_Value()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
internal class SecurityAttribute
{
	private String _name; // 0x10
	private String _value; // 0x18

	public String Name { get; }
	public String Value { get; }

	// RVA: 0x5f425f8 VA: 0x759855a5f8
	public Void .ctor(String name, String value) { }
	// RVA: 0x5f43770 VA: 0x759855b770
	public String get_Name() { }
	// RVA: 0x5f43778 VA: 0x759855b778
	public String get_Value() { }
}
```