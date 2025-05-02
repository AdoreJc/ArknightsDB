# TemplateAsset

**Namespace:** `UnityEngine.UIElements`


## Fields

- `String m_TemplateAlias`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class TemplateAsset : VisualElementAsset
{
	private String m_TemplateAlias; // 0x68
	private List`1 m_AttributeOverrides; // 0x70
	private List`1 m_SlotUsages; // 0x78

	public List`1 attributeOverrides { get; }
	internal List`1 slotUsages { get; }

	// RVA: 0x6a1f8d4 VA: 0x75990378d4
	public List`1 get_attributeOverrides() { }
	// RVA: 0x6a1f960 VA: 0x7599037960
	internal List`1 get_slotUsages() { }
}
```