# LocalFileSettingsProvider

**Namespace:** `System.Configuration`


## Methods

- `SettingsPropertyValue GetPreviousVersion(SettingsContext, SettingsProperty)`

- `Void Reset(SettingsContext)`

- `Void Upgrade(SettingsContext, SettingsPropertyCollection)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Configuration
public class LocalFileSettingsProvider : SettingsProvider, IApplicationSettingsProvider
{

	public override String ApplicationName { get; set; }

	// RVA: 0x636a858 VA: 0x7598982858
	public Void .ctor() { }
	// RVA: 0x636a890 VA: 0x7598982890
	public override String get_ApplicationName() { }
	// RVA: 0x636a8c8 VA: 0x75989828c8
	public override Void set_ApplicationName(String value) { }
	// RVA: 0x636a900 VA: 0x7598982900
	public SettingsPropertyValue GetPreviousVersion(SettingsContext context, SettingsProperty property) { }
	// RVA: 0x636a938 VA: 0x7598982938
	public override SettingsPropertyValueCollection GetPropertyValues(SettingsContext context, SettingsPropertyCollection properties) { }
	// RVA: 0x636a970 VA: 0x7598982970
	public override Void Initialize(String name, NameValueCollection values) { }
	// RVA: 0x636a9a8 VA: 0x75989829a8
	public Void Reset(SettingsContext context) { }
	// RVA: 0x636a9e0 VA: 0x75989829e0
	public override Void SetPropertyValues(SettingsContext context, SettingsPropertyValueCollection values) { }
	// RVA: 0x636aa18 VA: 0x7598982a18
	public Void Upgrade(SettingsContext context, SettingsPropertyCollection properties) { }
}
```