# PropertyChangingEventArgs

**Namespace:** `System.ComponentModel`


## Fields

- `String <PropertyName>k__BackingField`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : System.ComponentModel
public class PropertyChangingEventArgs : EventArgs
{
	private String <PropertyName>k__BackingField; // 0x10

	public virtual String PropertyName { set; }

	// RVA: 0x613d5d4 VA: 0x75987555d4
	public Void .ctor(String propertyName) { }
	// RVA: 0x613d64c VA: 0x759875564c
	public virtual Void set_PropertyName(String value) { }
}
```