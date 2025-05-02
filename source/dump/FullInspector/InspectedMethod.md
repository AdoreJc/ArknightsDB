# InspectedMethod

**Namespace:** `FullInspector`


## Fields

- `MethodInfo <Method>k__BackingField`

- `GUIContent <DisplayLabel>k__BackingField`

- `Boolean <HasArguments>k__BackingField`


## Properties

- `MethodInfo Method`

- `GUIContent DisplayLabel`

- `Boolean HasArguments`


## Methods

- `MethodInfo get_Method()`

- `Void set_Method(MethodInfo)`

- `GUIContent get_DisplayLabel()`

- `Void set_DisplayLabel(GUIContent)`

- `Boolean get_HasArguments()`

- `Void set_HasArguments(Boolean)`

- `Void Invoke(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector
public class InspectedMethod
{
	private MethodInfo <Method>k__BackingField; // 0x10
	private GUIContent <DisplayLabel>k__BackingField; // 0x18
	private Boolean <HasArguments>k__BackingField; // 0x20

	public MethodInfo Method { get; set; }
	public GUIContent DisplayLabel { get; set; }
	public Boolean HasArguments { get; set; }

	// RVA: 0x34ceb40 VA: 0x7595ae6b40
	public Void .ctor(MethodInfo method) { }
	// RVA: 0x34ced78 VA: 0x7595ae6d78
	public MethodInfo get_Method() { }
	// RVA: 0x34ced80 VA: 0x7595ae6d80
	private Void set_Method(MethodInfo value) { }
	// RVA: 0x34ced88 VA: 0x7595ae6d88
	public GUIContent get_DisplayLabel() { }
	// RVA: 0x34ced90 VA: 0x7595ae6d90
	private Void set_DisplayLabel(GUIContent value) { }
	// RVA: 0x34ced98 VA: 0x7595ae6d98
	public Boolean get_HasArguments() { }
	// RVA: 0x34ceda0 VA: 0x7595ae6da0
	private Void set_HasArguments(Boolean value) { }
	// RVA: 0x34cedac VA: 0x7595ae6dac
	public Void Invoke(Object instance) { }
}
```