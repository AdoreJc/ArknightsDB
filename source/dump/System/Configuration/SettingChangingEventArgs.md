# SettingChangingEventArgs

**Namespace:** `System.Configuration`


## Properties

- `Object NewValue`

- `String SettingClass`

- `String SettingKey`

- `String SettingName`


## Methods

- `Object get_NewValue()`

- `String get_SettingClass()`

- `String get_SettingKey()`

- `String get_SettingName()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Configuration
public class SettingChangingEventArgs : CancelEventArgs
{

	public Object NewValue { get; }
	public String SettingClass { get; }
	public String SettingKey { get; }
	public String SettingName { get; }

	// RVA: 0x636985c VA: 0x759898185c
	public Void .ctor(String settingName, String settingClass, String settingKey, Object newValue, Boolean cancel) { }
	// RVA: 0x6369894 VA: 0x7598981894
	public Object get_NewValue() { }
	// RVA: 0x63698cc VA: 0x75989818cc
	public String get_SettingClass() { }
	// RVA: 0x6369904 VA: 0x7598981904
	public String get_SettingKey() { }
	// RVA: 0x636993c VA: 0x759898193c
	public String get_SettingName() { }
}
```