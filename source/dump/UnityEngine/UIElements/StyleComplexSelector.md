# StyleComplexSelector

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Int32 m_Specificity`

- `StyleRule <rule>k__BackingField`


## Properties

- `Int32 specificity`

- `StyleRule rule`


## Methods

- `Int32 get_specificity()`

- `StyleRule get_rule()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class StyleComplexSelector
{
	private Int32 m_Specificity; // 0x10
	private StyleRule <rule>k__BackingField; // 0x18
	private StyleSelector[] m_Selectors; // 0x20
	internal Int32 ruleIndex; // 0x28
	internal StyleComplexSelector nextInTable; // 0x30
	internal Int32 orderInStyleSheet; // 0x38
	private static Dictionary`2 s_PseudoStates; // 0x0

	public Int32 specificity { get; }
	public StyleRule rule { get; set; }
	public StyleSelector[] selectors { get; set; }

	// RVA: 0x6a18cfc VA: 0x7599030cfc
	public Int32 get_specificity() { }
	// RVA: 0x6a18d04 VA: 0x7599030d04
	public StyleRule get_rule() { }
	// RVA: 0x6a18d0c VA: 0x7599030d0c
	internal Void set_rule(StyleRule value) { }
	// RVA: 0x6a18d14 VA: 0x7599030d14
	public StyleSelector[] get_selectors() { }
	// RVA: 0x6a18d1c VA: 0x7599030d1c
	internal Void set_selectors(StyleSelector[] value) { }
	// RVA: 0x6a18d24 VA: 0x7599030d24
	internal Void CachePseudoStateMasks() { }
	// RVA: 0x6a191ec VA: 0x75990311ec
	public override String ToString() { }
	// RVA: 0x6a19364 VA: 0x7599031364
	public Void .ctor() { }
}
```