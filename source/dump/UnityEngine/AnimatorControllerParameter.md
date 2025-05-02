# AnimatorControllerParameter

**Namespace:** `UnityEngine`


## Properties

- `String name`

- `AnimatorControllerParameterType type`


## Methods

- `String get_name()`

- `AnimatorControllerParameterType get_type()`


## Dump
```C#
// Dll : UnityEngine.AnimationModule.dll
// Namespace : UnityEngine
public class AnimatorControllerParameter
{
	internal String m_Name; // 0x10
	internal AnimatorControllerParameterType m_Type; // 0x18
	internal Single m_DefaultFloat; // 0x1c
	internal Int32 m_DefaultInt; // 0x20
	internal Boolean m_DefaultBool; // 0x24

	public String name { get; }
	public AnimatorControllerParameterType type { get; }

	// RVA: 0x6847ddc VA: 0x7598e5fddc
	public String get_name() { }
	// RVA: 0x6847de4 VA: 0x7598e5fde4
	public AnimatorControllerParameterType get_type() { }
	// RVA: 0x6847dec VA: 0x7598e5fdec
	public override Boolean Equals(Object o) { }
	// RVA: 0x6847ec8 VA: 0x7598e5fec8
	public override Int32 GetHashCode() { }
	// RVA: 0x6847ee8 VA: 0x7598e5fee8
	public Void .ctor() { }
}
```