# InternalTreeView

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
internal class InternalTreeView : VisualElement
{
	private static readonly String s_ListViewName; // 0x0
	private static readonly String s_ItemToggleName; // 0x8
	private static readonly String s_ItemIndentsContainerName; // 0x10
	private static readonly String s_ItemIndentName; // 0x18
	private static readonly String s_ItemContentContainerName; // 0x20
	public static readonly String itemUssClassName; // 0x28
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
	internal readonly ScrollView m_ScrollView; // 0x400

	public Action`2 unbindItem { get; }
	public Int32 itemHeight { set; }
	public Boolean showBorder { set; }
	public SelectionType selectionType { set; }
	public AlternatingRowBackground showAlternatingRowBackgrounds { set; }

	// RVA: 0x69d0a44 VA: 0x7598fe8a44
	public Action`2 get_unbindItem() { }
	// RVA: 0x69d0a4c VA: 0x7598fe8a4c
	public Void set_itemHeight(Int32 value) { }
	// RVA: 0x69d0a6c VA: 0x7598fe8a6c
	public Void set_showBorder(Boolean value) { }
	// RVA: 0x69d0a8c VA: 0x7598fe8a8c
	public Void set_selectionType(SelectionType value) { }
	// RVA: 0x69d0aa8 VA: 0x7598fe8aa8
	public Void set_showAlternatingRowBackgrounds(AlternatingRowBackground value) { }
	// RVA: 0x69d0ac4 VA: 0x7598fe8ac4
	public Void .ctor() { }
	// RVA: 0x69d1078 VA: 0x7598fe9078
	public Void RefreshItems() { }
	// RVA: 0x69d1140 VA: 0x7598fe9140
	public Void Rebuild() { }
	// RVA: 0x69d1164 VA: 0x7598fe9164
	internal override Void OnViewDataReady() { }
	// RVA: 0x69d11a0 VA: 0x7598fe91a0
	public static IEnumerable`1 GetAllItems(IEnumerable`1 rootItems) { }
	// RVA: 0x69d1254 VA: 0x7598fe9254
	public Void OnKeyDown(KeyDownEvent evt) { }
	// RVA: 0x69d1124 VA: 0x7598fe9124
	private Void ListViewRefresh() { }
	// RVA: 0x69d1908 VA: 0x7598fe9908
	private Void OnItemsChosen(IEnumerable`1 chosenItems) { }
	// RVA: 0x69d1d2c VA: 0x7598fe9d2c
	private Void OnSelectionChange(IEnumerable`1 selectedListItems) { }
	// RVA: 0x69d219c VA: 0x7598fea19c
	private Void OnTreeViewMouseUp(MouseUpEvent evt) { }
	// RVA: 0x69d21d4 VA: 0x7598fea1d4
	private Void OnItemMouseUp(MouseUpEvent evt) { }
	// RVA: 0x69d29c8 VA: 0x7598fea9c8
	private VisualElement MakeTreeItem() { }
	// RVA: 0x69d2ea8 VA: 0x7598feaea8
	private Void UnbindTreeItem(VisualElement element, Int32 index) { }
	// RVA: 0x69d2fe4 VA: 0x7598feafe4
	private Void BindTreeItem(VisualElement element, Int32 index) { }
	// RVA: 0x69d3340 VA: 0x7598feb340
	internal Int32 GetItemId(Int32 index) { }
	// RVA: 0x69d1308 VA: 0x7598fe9308
	private Boolean IsExpandedByIndex(Int32 index) { }
	// RVA: 0x69d16ac VA: 0x7598fe96ac
	private Void CollapseItemByIndex(Int32 index) { }
	// RVA: 0x69d13a4 VA: 0x7598fe93a4
	private Void ExpandItemByIndex(Int32 index) { }
	// RVA: 0x69d399c VA: 0x7598feb99c
	private Void ToggleExpandedState(ChangeEvent`1 evt) { }
	// RVA: 0x69d3454 VA: 0x7598feb454
	private Void CreateWrappers(IEnumerable`1 treeViewItems, Int32 depth, ref List`1 wrappers) { }
	// RVA: 0x69d109c VA: 0x7598fe909c
	private Void RegenerateWrappers() { }
	// RVA: 0x69d3b20 VA: 0x7598febb20
	private Void OnCustomStyleResolved(CustomStyleResolvedEvent e) { }
	// RVA: 0x69d3c70 VA: 0x7598febc70
	private static Void .cctor() { }
}
```