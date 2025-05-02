# TreeView

**Namespace:** `UnityEngine.UIElements`


## Properties

- `Int32 itemHeight`

- `Boolean showBorder`

- `SelectionType selectionType`

- `AlternatingRowBackground showAlternatingRowBackgrounds`


## Methods

- `Void set_itemHeight(Int32)`

- `Void set_showBorder(Boolean)`

- `Void set_selectionType(SelectionType)`

- `Void set_showAlternatingRowBackgrounds(AlternatingRowBackground)`

- `Void RefreshItems()`

- `Void Rebuild()`

- `Void OnKeyDown(KeyDownEvent)`

- `Void ListViewRefresh()`

- `Void OnItemsChosen(IEnumerable`1)`

- `Void OnSelectionChange(IEnumerable`1)`

- `Void OnTreeViewMouseUp(MouseUpEvent)`

- `Void OnItemMouseUp(MouseUpEvent)`

- `VisualElement MakeTreeItem()`

- `Void UnbindTreeItem(VisualElement, Int32)`

- `Void BindTreeItem(VisualElement, Int32)`

- `Int32 GetItemId(Int32)`

- `Boolean IsExpandedByIndex(Int32)`

- `Void CollapseItemByIndex(Int32)`

- `Void ExpandItemByIndex(Int32)`

- `Void ToggleExpandedState(ChangeEvent`1)`

- `Void CreateWrappers(IEnumerable`1, Int32, ref)`

- `Void RegenerateWrappers()`

- `Void OnCustomStyleResolved(CustomStyleResolvedEvent)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class TreeView : VisualElement
{
	private static readonly String s_ListViewName; // 0x0
	private static readonly String s_ItemName; // 0x8
	private static readonly String s_ItemToggleName; // 0x10
	private static readonly String s_ItemIndentsContainerName; // 0x18
	private static readonly String s_ItemIndentName; // 0x20
	private static readonly String s_ItemContentContainerName; // 0x28
	private Func`1 m_MakeItem; // 0x3b0
	private Action`1 onItemsChosen; // 0x3b8
	private Action`1 onSelectionChange; // 0x3c0
	private List`1 m_SelectedItems; // 0x3c8
	private Action`2 m_BindItem; // 0x3d0
	private Action`2 <unbindItem>k__BackingField; // 0x3d8
	private IList`1 m_RootItems; // 0x3e0
	private List`1 m_ExpandedItemIds; // 0x3e8
	private List`1 m_ItemWrappers; // 0x3f0
	private readonly ListView m_ListView; // 0x3f8
	private readonly ScrollView m_ScrollView; // 0x400

	public Action`2 unbindItem { get; }
	public Int32 itemHeight { set; }
	public Boolean showBorder { set; }
	public SelectionType selectionType { set; }
	public AlternatingRowBackground showAlternatingRowBackgrounds { set; }

	// RVA: 0x69c8854 VA: 0x7598fe0854
	public Action`2 get_unbindItem() { }
	// RVA: 0x69c885c VA: 0x7598fe085c
	public Void set_itemHeight(Int32 value) { }
	// RVA: 0x69c887c VA: 0x7598fe087c
	public Void set_showBorder(Boolean value) { }
	// RVA: 0x69c889c VA: 0x7598fe089c
	public Void set_selectionType(SelectionType value) { }
	// RVA: 0x69c88b8 VA: 0x7598fe08b8
	public Void set_showAlternatingRowBackgrounds(AlternatingRowBackground value) { }
	// RVA: 0x69c88d4 VA: 0x7598fe08d4
	public Void .ctor() { }
	// RVA: 0x69c8e88 VA: 0x7598fe0e88
	public Void RefreshItems() { }
	// RVA: 0x69c8f50 VA: 0x7598fe0f50
	public Void Rebuild() { }
	// RVA: 0x69c8f74 VA: 0x7598fe0f74
	internal override Void OnViewDataReady() { }
	// RVA: 0x69c8fb0 VA: 0x7598fe0fb0
	public static IEnumerable`1 GetAllItems(IEnumerable`1 rootItems) { }
	// RVA: 0x69c9064 VA: 0x7598fe1064
	public Void OnKeyDown(KeyDownEvent evt) { }
	// RVA: 0x69c8f34 VA: 0x7598fe0f34
	private Void ListViewRefresh() { }
	// RVA: 0x69c9710 VA: 0x7598fe1710
	private Void OnItemsChosen(IEnumerable`1 chosenItems) { }
	// RVA: 0x69c9b34 VA: 0x7598fe1b34
	private Void OnSelectionChange(IEnumerable`1 selectedListItems) { }
	// RVA: 0x69c9fa4 VA: 0x7598fe1fa4
	private Void OnTreeViewMouseUp(MouseUpEvent evt) { }
	// RVA: 0x69c9fdc VA: 0x7598fe1fdc
	private Void OnItemMouseUp(MouseUpEvent evt) { }
	// RVA: 0x69ca7e8 VA: 0x7598fe27e8
	private VisualElement MakeTreeItem() { }
	// RVA: 0x69cacc8 VA: 0x7598fe2cc8
	private Void UnbindTreeItem(VisualElement element, Int32 index) { }
	// RVA: 0x69cade4 VA: 0x7598fe2de4
	private Void BindTreeItem(VisualElement element, Int32 index) { }
	// RVA: 0x69cb140 VA: 0x7598fe3140
	private Int32 GetItemId(Int32 index) { }
	// RVA: 0x69c9120 VA: 0x7598fe1120
	private Boolean IsExpandedByIndex(Int32 index) { }
	// RVA: 0x69c94c4 VA: 0x7598fe14c4
	private Void CollapseItemByIndex(Int32 index) { }
	// RVA: 0x69c91bc VA: 0x7598fe11bc
	private Void ExpandItemByIndex(Int32 index) { }
	// RVA: 0x69cb79c VA: 0x7598fe379c
	private Void ToggleExpandedState(ChangeEvent`1 evt) { }
	// RVA: 0x69cb254 VA: 0x7598fe3254
	private Void CreateWrappers(IEnumerable`1 treeViewItems, Int32 depth, ref List`1 wrappers) { }
	// RVA: 0x69c8eac VA: 0x7598fe0eac
	private Void RegenerateWrappers() { }
	// RVA: 0x69cb920 VA: 0x7598fe3920
	private Void OnCustomStyleResolved(CustomStyleResolvedEvent e) { }
	// RVA: 0x69cba70 VA: 0x7598fe3a70
	private static Void .cctor() { }
}
```