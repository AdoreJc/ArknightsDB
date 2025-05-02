# ReusableListViewItem

**Namespace:** `UnityEngine.UIElements`


## Fields

- `VisualElement m_Container`

- `VisualElement m_DragHandle`

- `VisualElement m_ItemContainer`


## Methods

- `Void Init(VisualElement, Boolean)`

- `Void UpdateHierarchy(Boolean)`

- `Void UpdateDragHandle(Boolean)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class ReusableListViewItem : ReusableCollectionItem
{
	private VisualElement m_Container; // 0x40
	private VisualElement m_DragHandle; // 0x48
	private VisualElement m_ItemContainer; // 0x50

	public override VisualElement rootElement { get; }

	// RVA: 0x69a29e4 VA: 0x7598fba9e4
	public override VisualElement get_rootElement() { }
	// RVA: 0x69a29fc VA: 0x7598fba9fc
	public Void Init(VisualElement item, Boolean usesAnimatedDragger) { }
	// RVA: 0x69a2a28 VA: 0x7598fbaa28
	private Void UpdateHierarchy(Boolean usesAnimatedDragger) { }
	// RVA: 0x69a2d00 VA: 0x7598fbad00
	public Void UpdateDragHandle(Boolean needsDragHandle) { }
	// RVA: 0x69a2e3c VA: 0x7598fbae3c
	public override Void PreAttachElement() { }
	// RVA: 0x69a2ec8 VA: 0x7598fbaec8
	public override Void DetachElement() { }
	// RVA: 0x69a2f54 VA: 0x7598fbaf54
	public override Void SetDragGhost(Boolean dragGhost) { }
	// RVA: 0x69a3050 VA: 0x7598fbb050
	public Void .ctor() { }
}
```