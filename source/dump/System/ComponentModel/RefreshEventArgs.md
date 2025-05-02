# RefreshEventArgs

**Namespace:** `System.ComponentModel`


## Properties

- `Object ComponentChanged`

- `Type TypeChanged`


## Methods

- `Object get_ComponentChanged()`

- `Type get_TypeChanged()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class RefreshEventArgs : EventArgs
{
	private readonly Object <ComponentChanged>k__BackingField; // 0x10
	private readonly Type <TypeChanged>k__BackingField; // 0x18

	public Object ComponentChanged { get; }
	public Type TypeChanged { get; }

	// RVA: 0x63d7ff0 VA: 0x75989efff0
	public Void .ctor(Object componentChanged) { }
	// RVA: 0x63d8088 VA: 0x75989f0088
	public Void .ctor(Type typeChanged) { }
	// RVA: 0x63d80fc VA: 0x75989f00fc
	public Object get_ComponentChanged() { }
	// RVA: 0x63d8104 VA: 0x75989f0104
	public Type get_TypeChanged() { }
}
```