# StyleVariableContext

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Int32 m_VariableHash`


## Methods

- `Void Add(StyleVariable)`

- `Void AddInitialRange(StyleVariableContext)`

- `Void Clear()`

- `Boolean TryFindVariable(String, out)`

- `Int32 GetVariableHash()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class StyleVariableContext
{
	public static readonly StyleVariableContext none; // 0x0
	private Int32 m_VariableHash; // 0x10
	private List`1 m_Variables; // 0x18
	private List`1 m_SortedHash; // 0x20


	// RVA: 0x6a1b208 VA: 0x7599033208
	public Void Add(StyleVariable sv) { }
	// RVA: 0x6a1b3b4 VA: 0x75990333b4
	public Void AddInitialRange(StyleVariableContext other) { }
	// RVA: 0x6a1b4ac VA: 0x75990334ac
	public Void Clear() { }
	// RVA: 0x6a1b548 VA: 0x7599033548
	public Void .ctor() { }
	// RVA: 0x6a1b630 VA: 0x7599033630
	public Void .ctor(StyleVariableContext other) { }
	// RVA: 0x6a1b734 VA: 0x7599033734
	public Boolean TryFindVariable(String name, out StyleVariable v) { }
	// RVA: 0x6a1b82c VA: 0x759903382c
	public Int32 GetVariableHash() { }
	// RVA: 0x6a1b834 VA: 0x7599033834
	private static Void .cctor() { }
}
```