# TemplateContainer

**Namespace:** `UnityEngine.UIElements`


## Fields

- `String <templateId>k__BackingField`

- `VisualElement m_ContentContainer`

- `VisualTreeAsset m_TemplateSource`


## Properties

- `String templateId`


## Methods

- `String get_templateId()`

- `Void set_templateId(String)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class TemplateContainer : BindableElement
{
	private String <templateId>k__BackingField; // 0x3c0
	private VisualElement m_ContentContainer; // 0x3c8
	private VisualTreeAsset m_TemplateSource; // 0x3d0

	public String templateId { get; set; }
	internal VisualTreeAsset templateSource { set; }
	public override VisualElement contentContainer { get; }

	// RVA: 0x698be84 VA: 0x7598fa3e84
	public String get_templateId() { }
	// RVA: 0x698be8c VA: 0x7598fa3e8c
	private Void set_templateId(String value) { }
	// RVA: 0x698be9c VA: 0x7598fa3e9c
	internal Void set_templateSource(VisualTreeAsset value) { }
	// RVA: 0x698beac VA: 0x7598fa3eac
	public Void .ctor() { }
	// RVA: 0x698beb4 VA: 0x7598fa3eb4
	public Void .ctor(String templateId) { }
	// RVA: 0x698bef4 VA: 0x7598fa3ef4
	public override VisualElement get_contentContainer() { }
	// RVA: 0x698befc VA: 0x7598fa3efc
	internal Void SetContentContainer(VisualElement content) { }
}
```