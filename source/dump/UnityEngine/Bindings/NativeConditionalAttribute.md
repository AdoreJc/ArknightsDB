# NativeConditionalAttribute

**Namespace:** `UnityEngine.Bindings`


## Fields

- `String <Condition>k__BackingField`

- `String <StubReturnStatement>k__BackingField`

- `Boolean <Enabled>k__BackingField`


## Properties

- `String Condition`

- `String StubReturnStatement`

- `Boolean Enabled`


## Methods

- `Void set_Condition(String)`

- `Void set_StubReturnStatement(String)`

- `Void set_Enabled(Boolean)`


## Dump
```C#
// Dll : UnityEngine.SharedInternalsModule.dll
// Namespace : UnityEngine.Bindings
internal class NativeConditionalAttribute : Attribute
{
	private String <Condition>k__BackingField; // 0x10
	private String <StubReturnStatement>k__BackingField; // 0x18
	private Boolean <Enabled>k__BackingField; // 0x20

	public String Condition { set; }
	public String StubReturnStatement { set; }
	public Boolean Enabled { set; }

	// RVA: 0x68e12a8 VA: 0x7598ef92a8
	public Void set_Condition(String value) { }
	// RVA: 0x68e12b0 VA: 0x7598ef92b0
	public Void set_StubReturnStatement(String value) { }
	// RVA: 0x68e12b8 VA: 0x7598ef92b8
	public Void set_Enabled(Boolean value) { }
	// RVA: 0x68e12c4 VA: 0x7598ef92c4
	public Void .ctor(String condition) { }
	// RVA: 0x68e1300 VA: 0x7598ef9300
	public Void .ctor(String condition, String stubReturnStatement) { }
}
```