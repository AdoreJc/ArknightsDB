# AttributeProviderAttribute

**Namespace:** `System.ComponentModel`


## Properties

- `String TypeName`

- `String PropertyName`


## Methods

- `String get_TypeName()`

- `String get_PropertyName()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class AttributeProviderAttribute : Attribute
{
	private readonly String <TypeName>k__BackingField; // 0x10
	private readonly String <PropertyName>k__BackingField; // 0x18

	public String TypeName { get; }
	public String PropertyName { get; }

	// RVA: 0x63b57e4 VA: 0x75989cd7e4
	public Void .ctor(String typeName) { }
	// RVA: 0x63b5864 VA: 0x75989cd864
	public Void .ctor(String typeName, String propertyName) { }
	// RVA: 0x63b5920 VA: 0x75989cd920
	public Void .ctor(Type type) { }
	// RVA: 0x63b5a10 VA: 0x75989cda10
	public String get_TypeName() { }
	// RVA: 0x63b5a18 VA: 0x75989cda18
	public String get_PropertyName() { }
}
```