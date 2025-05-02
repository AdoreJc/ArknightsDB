# NativeMethodAttribute

**Namespace:** `UnityEngine.Bindings`


## Fields

- `String <Name>k__BackingField`

- `Boolean <IsThreadSafe>k__BackingField`

- `Boolean <IsFreeFunction>k__BackingField`

- `Boolean <ThrowsException>k__BackingField`

- `Boolean <HasExplicitThis>k__BackingField`


## Properties

- `String Name`

- `Boolean IsThreadSafe`

- `Boolean IsFreeFunction`

- `Boolean ThrowsException`

- `Boolean HasExplicitThis`


## Methods

- `Void set_Name(String)`

- `Void set_IsThreadSafe(Boolean)`

- `Void set_IsFreeFunction(Boolean)`

- `Void set_ThrowsException(Boolean)`

- `Void set_HasExplicitThis(Boolean)`


## Dump
```C#
// Dll : UnityEngine.SharedInternalsModule.dll
// Namespace : UnityEngine.Bindings
internal class NativeMethodAttribute : Attribute
{
	private String <Name>k__BackingField; // 0x10
	private Boolean <IsThreadSafe>k__BackingField; // 0x18
	private Boolean <IsFreeFunction>k__BackingField; // 0x19
	private Boolean <ThrowsException>k__BackingField; // 0x1a
	private Boolean <HasExplicitThis>k__BackingField; // 0x1b

	public String Name { set; }
	public Boolean IsThreadSafe { set; }
	public Boolean IsFreeFunction { set; }
	public Boolean ThrowsException { set; }
	public Boolean HasExplicitThis { set; }

	// RVA: 0x68e15a0 VA: 0x7598ef95a0
	public Void set_Name(String value) { }
	// RVA: 0x68e15a8 VA: 0x7598ef95a8
	public Void set_IsThreadSafe(Boolean value) { }
	// RVA: 0x68e15b4 VA: 0x7598ef95b4
	public Void set_IsFreeFunction(Boolean value) { }
	// RVA: 0x68e15c0 VA: 0x7598ef95c0
	public Void set_ThrowsException(Boolean value) { }
	// RVA: 0x68e15cc VA: 0x7598ef95cc
	public Void set_HasExplicitThis(Boolean value) { }
	// RVA: 0x68e15d8 VA: 0x7598ef95d8
	public Void .ctor() { }
	// RVA: 0x68e15e0 VA: 0x7598ef95e0
	public Void .ctor(String name) { }
	// RVA: 0x68e16ec VA: 0x7598ef96ec
	public Void .ctor(String name, Boolean isFreeFunction) { }
	// RVA: 0x68e1714 VA: 0x7598ef9714
	public Void .ctor(String name, Boolean isFreeFunction, Boolean isThreadSafe) { }
}
```