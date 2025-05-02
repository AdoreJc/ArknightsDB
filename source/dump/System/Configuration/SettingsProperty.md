# SettingsProperty

**Namespace:** `System.Configuration`


## Properties

- `Boolean ThrowOnErrorDeserializing`

- `Boolean ThrowOnErrorSerializing`


## Methods

- `Boolean get_ThrowOnErrorDeserializing()`

- `Void set_ThrowOnErrorDeserializing(Boolean)`

- `Boolean get_ThrowOnErrorSerializing()`

- `Void set_ThrowOnErrorSerializing(Boolean)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Configuration
public class SettingsProperty
{

	public virtual SettingsAttributeDictionary Attributes { get; }
	public virtual Object DefaultValue { get; set; }
	public virtual Boolean IsReadOnly { get; set; }
	public virtual String Name { get; set; }
	public virtual Type PropertyType { get; set; }
	public virtual SettingsProvider Provider { get; set; }
	public virtual SettingsSerializeAs SerializeAs { get; set; }
	public Boolean ThrowOnErrorDeserializing { get; set; }
	public Boolean ThrowOnErrorSerializing { get; set; }

	// RVA: 0x63648b4 VA: 0x759897c8b4
	public Void .ctor(SettingsProperty propertyToCopy) { }
	// RVA: 0x63648ec VA: 0x759897c8ec
	public Void .ctor(String name) { }
	// RVA: 0x6364924 VA: 0x759897c924
	public Void .ctor(String name, Type propertyType, SettingsProvider provider, Boolean isReadOnly, Object defaultValue, SettingsSerializeAs serializeAs, SettingsAttributeDictionary attributes, Boolean throwOnErrorDeserializing, Boolean throwOnErrorSerializing) { }
	// RVA: 0x636495c VA: 0x759897c95c
	public virtual SettingsAttributeDictionary get_Attributes() { }
	// RVA: 0x6364994 VA: 0x759897c994
	public virtual Object get_DefaultValue() { }
	// RVA: 0x63649cc VA: 0x759897c9cc
	public virtual Void set_DefaultValue(Object value) { }
	// RVA: 0x6364a04 VA: 0x759897ca04
	public virtual Boolean get_IsReadOnly() { }
	// RVA: 0x6364a3c VA: 0x759897ca3c
	public virtual Void set_IsReadOnly(Boolean value) { }
	// RVA: 0x6364a74 VA: 0x759897ca74
	public virtual String get_Name() { }
	// RVA: 0x6364aac VA: 0x759897caac
	public virtual Void set_Name(String value) { }
	// RVA: 0x6364ae4 VA: 0x759897cae4
	public virtual Type get_PropertyType() { }
	// RVA: 0x6364b1c VA: 0x759897cb1c
	public virtual Void set_PropertyType(Type value) { }
	// RVA: 0x6364b54 VA: 0x759897cb54
	public virtual SettingsProvider get_Provider() { }
	// RVA: 0x6364b8c VA: 0x759897cb8c
	public virtual Void set_Provider(SettingsProvider value) { }
	// RVA: 0x6364bc4 VA: 0x759897cbc4
	public virtual SettingsSerializeAs get_SerializeAs() { }
	// RVA: 0x6364bfc VA: 0x759897cbfc
	public virtual Void set_SerializeAs(SettingsSerializeAs value) { }
	// RVA: 0x6364c34 VA: 0x759897cc34
	public Boolean get_ThrowOnErrorDeserializing() { }
	// RVA: 0x6364c6c VA: 0x759897cc6c
	public Void set_ThrowOnErrorDeserializing(Boolean value) { }
	// RVA: 0x6364ca4 VA: 0x759897cca4
	public Boolean get_ThrowOnErrorSerializing() { }
	// RVA: 0x6364cdc VA: 0x759897ccdc
	public Void set_ThrowOnErrorSerializing(Boolean value) { }
}
```