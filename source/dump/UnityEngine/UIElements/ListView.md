# ListView

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Boolean m_ShowBoundCollectionSize`

- `Boolean m_ShowFoldoutHeader`

- `String m_HeaderTitle`

- `Label m_EmptyListLabel`

- `Foldout m_Foldout`

- `TextField m_ArraySizeField`

- `VisualElement m_Footer`

- `Button m_AddButton`

- `Button m_RemoveButton`

- `Action m_ItemsSourceSizeChangedCallback`

- `ListViewController m_ListViewController`

- `ListViewReorderMode m_ReorderMode`


## Properties

- `Boolean showBoundCollectionSize`

- `Boolean showFoldoutHeader`

- `String headerTitle`

- `Boolean showAddRemoveFooter`

- `ListViewReorderMode reorderMode`


## Methods

- `Boolean get_showBoundCollectionSize()`

- `Void set_showBoundCollectionSize(Boolean)`

- `Boolean get_showFoldoutHeader()`

- `Void set_showFoldoutHeader(Boolean)`

- `Void set_headerTitle(String)`

- `Boolean get_showAddRemoveFooter()`

- `Void set_showAddRemoveFooter(Boolean)`

- `Void EnableFooter(Boolean)`

- `Void AddItems(Int32)`

- `Void OnArraySizeFieldChanged(ChangeEvent`1)`

- `Void UpdateArraySizeField()`

- `Void UpdateEmpty()`

- `Void OnAddClicked()`

- `Void OnRemoveClicked()`

- `Void OnItemAdded(IEnumerable`1)`

- `Void OnItemsRemoved(IEnumerable`1)`

- `Void OnItemsSourceSizeChanged()`

- `ListViewReorderMode get_reorderMode()`

- `Void set_reorderMode(ListViewReorderMode)`

- `Void <OnAddClicked>b__34_0()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class ListView : BaseVerticalCollectionView
{
	private static readonly String k_SizeFieldLabel; // 0x0
	private Boolean m_ShowBoundCollectionSize; // 0x4a4
	private Boolean m_ShowFoldoutHeader; // 0x4a5
	private String m_HeaderTitle; // 0x4a8
	private Action`1 itemsAdded; // 0x4b0
	private Action`1 itemsRemoved; // 0x4b8
	private Label m_EmptyListLabel; // 0x4c0
	private Foldout m_Foldout; // 0x4c8
	private TextField m_ArraySizeField; // 0x4d0
	private VisualElement m_Footer; // 0x4d8
	private Button m_AddButton; // 0x4e0
	private Button m_RemoveButton; // 0x4e8
	private Action`1 m_ItemAddedCallback; // 0x4f0
	private Action`1 m_ItemRemovedCallback; // 0x4f8
	private Action m_ItemsSourceSizeChangedCallback; // 0x500
	private ListViewController m_ListViewController; // 0x508
	private ListViewReorderMode m_ReorderMode; // 0x510
	public static readonly String ussClassName; // 0x8
	public static readonly String itemUssClassName; // 0x10
	public static readonly String emptyLabelUssClassName; // 0x18
	public static readonly String reorderableUssClassName; // 0x20
	public static readonly String reorderableItemUssClassName; // 0x28
	public static readonly String reorderableItemContainerUssClassName; // 0x30
	public static readonly String reorderableItemHandleUssClassName; // 0x38
	public static readonly String reorderableItemHandleBarUssClassName; // 0x40
	public static readonly String footerUssClassName; // 0x48
	public static readonly String foldoutHeaderUssClassName; // 0x50
	public static readonly String arraySizeFieldUssClassName; // 0x58
	public static readonly String arraySizeFieldWithHeaderUssClassName; // 0x60
	public static readonly String arraySizeFieldWithFooterUssClassName; // 0x68
	public static readonly String listViewWithHeaderUssClassName; // 0x70
	public static readonly String listViewWithFooterUssClassName; // 0x78
	public static readonly String scrollViewWithFooterUssClassName; // 0x80
	internal static readonly String footerAddButtonName; // 0x88
	internal static readonly String footerRemoveButtonName; // 0x90

	public Boolean showBoundCollectionSize { get; set; }
	public Boolean showFoldoutHeader { get; set; }
	public String headerTitle { set; }
	public Boolean showAddRemoveFooter { get; set; }
	internal ListViewController viewController { get; }
	public ListViewReorderMode reorderMode { get; set; }

	// RVA: 0x69b3d98 VA: 0x7598fcbd98
	public Boolean get_showBoundCollectionSize() { }
	// RVA: 0x69b3da0 VA: 0x7598fcbda0
	public Void set_showBoundCollectionSize(Boolean value) { }
	// RVA: 0x69b40c0 VA: 0x7598fcc0c0
	public Boolean get_showFoldoutHeader() { }
	// RVA: 0x69b40c8 VA: 0x7598fcc0c8
	public Void set_showFoldoutHeader(Boolean value) { }
	// RVA: 0x69b3dbc VA: 0x7598fcbdbc
	internal Void SetupArraySizeField() { }
	// RVA: 0x69b48c0 VA: 0x7598fcc8c0
	public Void set_headerTitle(String value) { }
	// RVA: 0x69b445c VA: 0x7598fcc45c
	public Boolean get_showAddRemoveFooter() { }
	// RVA: 0x69b4900 VA: 0x7598fcc900
	public Void set_showAddRemoveFooter(Boolean value) { }
	// RVA: 0x69b446c VA: 0x7598fcc46c
	private Void EnableFooter(Boolean enabled) { }
	// RVA: 0x69b4908 VA: 0x7598fcc908
	private Void AddItems(Int32 itemCount) { }
	// RVA: 0x69b492c VA: 0x7598fcc92c
	private Void OnArraySizeFieldChanged(ChangeEvent`1 evt) { }
	// RVA: 0x69b4830 VA: 0x7598fcc830
	private Void UpdateArraySizeField() { }
	// RVA: 0x69b428c VA: 0x7598fcc28c
	private Void UpdateEmpty() { }
	// RVA: 0x69b4a24 VA: 0x7598fcca24
	private Void OnAddClicked() { }
	// RVA: 0x69b4c64 VA: 0x7598fccc64
	private Void OnRemoveClicked() { }
	// RVA: 0x69b4e24 VA: 0x7598fcce24
	internal ListViewController get_viewController() { }
	// RVA: 0x69b4e2c VA: 0x7598fcce2c
	internal override Void CreateVirtualizationController() { }
	// RVA: 0x69b4e74 VA: 0x7598fcce74
	internal override Void CreateViewController() { }
	// RVA: 0x69b4ed8 VA: 0x7598fcced8
	internal Void SetViewController(ListViewController controller) { }
	// RVA: 0x69b50dc VA: 0x7598fcd0dc
	private Void OnItemAdded(IEnumerable`1 indices) { }
	// RVA: 0x69b50f8 VA: 0x7598fcd0f8
	private Void OnItemsRemoved(IEnumerable`1 indices) { }
	// RVA: 0x69b5114 VA: 0x7598fcd114
	private Void OnItemsSourceSizeChanged() { }
	// RVA: 0x69b5118 VA: 0x7598fcd118
	public ListViewReorderMode get_reorderMode() { }
	// RVA: 0x69b5120 VA: 0x7598fcd120
	public Void set_reorderMode(ListViewReorderMode value) { }
	// RVA: 0x69b515c VA: 0x7598fcd15c
	internal override ListViewDragger CreateDragger() { }
	// RVA: 0x69b51fc VA: 0x7598fcd1fc
	internal override ICollectionDragAndDropController CreateDragAndDropController() { }
	// RVA: 0x69b5260 VA: 0x7598fcd260
	public Void .ctor() { }
	// RVA: 0x69b52f8 VA: 0x7598fcd2f8
	internal override Void PostRefresh() { }
	// RVA: 0x69b5318 VA: 0x7598fcd318
	private static Void .cctor() { }
	// RVA: 0x69b582c VA: 0x7598fcd82c
	private Void <OnAddClicked>b__34_0() { }
}
```