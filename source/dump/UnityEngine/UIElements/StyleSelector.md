# StyleSelector

**Namespace:** `UnityEngine.UIElements`


## Fields

- `StyleSelectorRelationship m_PreviousRelationship`


## Properties

- `StyleSelectorRelationship previousRelationship`


## Methods

- `StyleSelectorRelationship get_previousRelationship()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class StyleSelector
{
	private StyleSelectorPart[] m_Parts; // 0x10
	private StyleSelectorRelationship m_PreviousRelationship; // 0x18
	internal Int32 pseudoStateMask; // 0x1c
	internal Int32 negatedPseudoStateMask; // 0x20

	public StyleSelectorPart[] parts { get; set; }
	public StyleSelectorRelationship previousRelationship { get; set; }

	// RVA: 0x6a191d4 VA: 0x75990311d4
	public StyleSelectorPart[] get_parts() { }
	// RVA: 0x6a1942c VA: 0x759903142c
	internal Void set_parts(StyleSelectorPart[] value) { }
	// RVA: 0x6a19434 VA: 0x7599031434
	public StyleSelectorRelationship get_previousRelationship() { }
	// RVA: 0x6a1943c VA: 0x759903143c
	internal Void set_previousRelationship(StyleSelectorRelationship value) { }
	// RVA: 0x6a19444 VA: 0x7599031444
	public override String ToString() { }
	// RVA: 0x6a1958c VA: 0x759903158c
	public Void .ctor() { }
}
```