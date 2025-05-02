# StyleProperty

**Namespace:** `UnityEngine.UIElements`


## Fields

- `String m_Name`

- `Int32 m_Line`


## Properties

- `String name`


## Methods

- `String get_name()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class StyleProperty
{
	private String m_Name; // 0x10
	private Int32 m_Line; // 0x18
	private StyleValueHandle[] m_Values; // 0x20
	internal Boolean isCustomProperty; // 0x28
	internal Boolean requireVariableResolve; // 0x29

	public String name { get; }
	public StyleValueHandle[] values { get; }

	// RVA: 0x6a19404 VA: 0x7599031404
	public String get_name() { }
	// RVA: 0x6a1940c VA: 0x759903140c
	public StyleValueHandle[] get_values() { }
	// RVA: 0x6a19414 VA: 0x7599031414
	public Void .ctor() { }
}
```