# SettingsPropertyValue

**Namespace:** `System.Configuration`


## Properties

- `Boolean Deserialized`

- `Boolean IsDirty`

- `String Name`

- `SettingsProperty Property`

- `Object PropertyValue`

- `Object SerializedValue`

- `Boolean UsingDefaultValue`


## Methods

- `Boolean get_Deserialized()`

- `Void set_Deserialized(Boolean)`

- `Boolean get_IsDirty()`

- `Void set_IsDirty(Boolean)`

- `String get_Name()`

- `SettingsProperty get_Property()`

- `Object get_PropertyValue()`

- `Void set_PropertyValue(Object)`

- `Object get_SerializedValue()`

- `Void set_SerializedValue(Object)`

- `Boolean get_UsingDefaultValue()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Configuration
public class SettingsPropertyValue
{

	public Boolean Deserialized { get; set; }
	public Boolean IsDirty { get; set; }
	public String Name { get; }
	public SettingsProperty Property { get; }
	public Object PropertyValue { get; set; }
	public Object SerializedValue { get; set; }
	public Boolean UsingDefaultValue { get; }

	// RVA: 0x6364fec VA: 0x759897cfec
	public Void .ctor(SettingsProperty property) { }
	// RVA: 0x6365024 VA: 0x759897d024
	public Boolean get_Deserialized() { }
	// RVA: 0x636505c VA: 0x759897d05c
	public Void set_Deserialized(Boolean value) { }
	// RVA: 0x6365094 VA: 0x759897d094
	public Boolean get_IsDirty() { }
	// RVA: 0x63650cc VA: 0x759897d0cc
	public Void set_IsDirty(Boolean value) { }
	// RVA: 0x6365104 VA: 0x759897d104
	public String get_Name() { }
	// RVA: 0x636513c VA: 0x759897d13c
	public SettingsProperty get_Property() { }
	// RVA: 0x6365174 VA: 0x759897d174
	public Object get_PropertyValue() { }
	// RVA: 0x63651ac VA: 0x759897d1ac
	public Void set_PropertyValue(Object value) { }
	// RVA: 0x63651e4 VA: 0x759897d1e4
	public Object get_SerializedValue() { }
	// RVA: 0x636521c VA: 0x759897d21c
	public Void set_SerializedValue(Object value) { }
	// RVA: 0x6365254 VA: 0x759897d254
	public Boolean get_UsingDefaultValue() { }
}
```