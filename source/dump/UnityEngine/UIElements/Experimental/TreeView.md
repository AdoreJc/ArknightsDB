# TreeView

**Namespace:** `UnityEngine.UIElements.Experimental`


## Methods

- `Boolean IsExpanded(Int32)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements.Experimental
internal class TreeView : BaseVerticalCollectionView
{
	public static readonly String ussClassName; // 0x0
	public static readonly String itemUssClassName; // 0x8
	public static readonly String itemToggleUssClassName; // 0x10
	public static readonly String itemIndentsContainerUssClassName; // 0x18
	public static readonly String itemIndentUssClassName; // 0x20
	public static readonly String itemContentContainerUssClassName; // 0x28
	private List`1 m_ExpandedItemIds; // 0x4a8

	internal TreeViewController viewController { get; }
	internal List`1 expandedItemIds { get; }

	// RVA: 0x6988f30 VA: 0x7598fa0f30
	internal TreeViewController get_viewController() { }
	// RVA: 0x6988fac VA: 0x7598fa0fac
	internal override ICollectionDragAndDropController CreateDragAndDropController() { }
	// RVA: 0x6989010 VA: 0x7598fa1010
	internal List`1 get_expandedItemIds() { }
	// RVA: 0x6989018 VA: 0x7598fa1018
	public Boolean IsExpanded(Int32 id) { }
	// RVA: 0x698903c VA: 0x7598fa103c
	private static Void .cctor() { }
}
```