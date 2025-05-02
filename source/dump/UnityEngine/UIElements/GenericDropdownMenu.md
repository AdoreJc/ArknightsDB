# GenericDropdownMenu

**Namespace:** `UnityEngine.UIElements`


## Fields

- `VisualElement m_MenuContainer`

- `VisualElement m_OuterContainer`

- `ScrollView m_ScrollView`

- `VisualElement m_PanelRootVisualContainer`

- `VisualElement m_TargetElement`

- `Rect m_DesiredRect`

- `KeyboardNavigationManipulator m_NavigationManipulator`

- `Vector2 m_MousePosition`


## Properties

- `VisualElement contentContainer`


## Methods

- `VisualElement get_contentContainer()`

- `Void OnAttachToPanel(AttachToPanelEvent)`

- `Void OnDetachFromPanel(DetachFromPanelEvent)`

- `Void Hide()`

- `Void Apply(KeyboardNavigationOperation, EventBase)`

- `Boolean Apply(KeyboardNavigationOperation)`

- `Void OnPointerDown(PointerDownEvent)`

- `Void OnPointerMove(PointerMoveEvent)`

- `Void OnPointerUp(PointerUpEvent)`

- `Void OnFocusOut(FocusOutEvent)`

- `Void OnParentResized(GeometryChangedEvent)`

- `Void UpdateSelection(VisualElement)`

- `Void ChangeSelectedIndex(Int32, Int32)`

- `Int32 GetSelectedIndex()`

- `Void AddItem(String, Boolean, Action)`

- `Void AddSeparator(String)`

- `MenuItem AddItem(String, Boolean, Boolean, Object)`

- `Void DropDown(Rect, VisualElement, Boolean)`

- `Void OnTargetElementDetachFromPanel(DetachFromPanelEvent)`

- `Void OnContainerGeometryChanged(GeometryChangedEvent)`

- `Void EnsureVisibilityInParent()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class GenericDropdownMenu : IGenericMenu
{
	public static readonly String ussClassName; // 0x0
	public static readonly String itemUssClassName; // 0x8
	public static readonly String labelUssClassName; // 0x10
	public static readonly String containerInnerUssClassName; // 0x18
	public static readonly String containerOuterUssClassName; // 0x20
	public static readonly String checkmarkUssClassName; // 0x28
	public static readonly String separatorUssClassName; // 0x30
	private List`1 m_Items; // 0x10
	private VisualElement m_MenuContainer; // 0x18
	private VisualElement m_OuterContainer; // 0x20
	private ScrollView m_ScrollView; // 0x28
	private VisualElement m_PanelRootVisualContainer; // 0x30
	private VisualElement m_TargetElement; // 0x38
	private Rect m_DesiredRect; // 0x40
	private KeyboardNavigationManipulator m_NavigationManipulator; // 0x50
	private Vector2 m_MousePosition; // 0x58

	public VisualElement contentContainer { get; }

	// RVA: 0x69acf1c VA: 0x7598fc4f1c
	public VisualElement get_contentContainer() { }
	// RVA: 0x69ab6b0 VA: 0x7598fc36b0
	public Void .ctor() { }
	// RVA: 0x69acf40 VA: 0x7598fc4f40
	private Void OnAttachToPanel(AttachToPanelEvent evt) { }
	// RVA: 0x69ad388 VA: 0x7598fc5388
	private Void OnDetachFromPanel(DetachFromPanelEvent evt) { }
	// RVA: 0x69ad72c VA: 0x7598fc572c
	private Void Hide() { }
	// RVA: 0x69ad820 VA: 0x7598fc5820
	private Void Apply(KeyboardNavigationOperation op, EventBase sourceEvent) { }
	// RVA: 0x69ad85c VA: 0x7598fc585c
	private Boolean Apply(KeyboardNavigationOperation op) { }
	// RVA: 0x69adbf0 VA: 0x7598fc5bf0
	private Void OnPointerDown(PointerDownEvent evt) { }
	// RVA: 0x69ade44 VA: 0x7598fc5e44
	private Void OnPointerMove(PointerMoveEvent evt) { }
	// RVA: 0x69adf70 VA: 0x7598fc5f70
	private Void OnPointerUp(PointerUpEvent evt) { }
	// RVA: 0x69ae0ac VA: 0x7598fc60ac
	private Void OnFocusOut(FocusOutEvent evt) { }
	// RVA: 0x69ae1f4 VA: 0x7598fc61f4
	private Void OnParentResized(GeometryChangedEvent evt) { }
	// RVA: 0x69add1c VA: 0x7598fc5d1c
	private Void UpdateSelection(VisualElement target) { }
	// RVA: 0x69ae1f8 VA: 0x7598fc61f8
	private Void ChangeSelectedIndex(Int32 newIndex, Int32 previousIndex) { }
	// RVA: 0x69ad9ec VA: 0x7598fc59ec
	private Int32 GetSelectedIndex() { }
	// RVA: 0x69ae32c VA: 0x7598fc632c
	public Void AddItem(String itemName, Boolean isChecked, Action action) { }
	// RVA: 0x69ae6d4 VA: 0x7598fc66d4
	public Void AddSeparator(String path) { }
	// RVA: 0x69ae360 VA: 0x7598fc6360
	private MenuItem AddItem(String itemName, Boolean isChecked, Boolean isEnabled, Object data) { }
	// RVA: 0x69ae84c VA: 0x7598fc684c
	public Void DropDown(Rect position, VisualElement targetElement, Boolean anchored) { }
	// RVA: 0x69af6c0 VA: 0x7598fc76c0
	private Void OnTargetElementDetachFromPanel(DetachFromPanelEvent evt) { }
	// RVA: 0x69af6c4 VA: 0x7598fc76c4
	private Void OnContainerGeometryChanged(GeometryChangedEvent evt) { }
	// RVA: 0x69aefdc VA: 0x7598fc6fdc
	private Void EnsureVisibilityInParent() { }
	// RVA: 0x69af6c8 VA: 0x7598fc76c8
	private static Void .cctor() { }
	// RVA: 0x69adb34 VA: 0x7598fc5b34
	private Void <Apply>g__UpdateSelectionDown|27_0(Int32 newIndex, ref <>c__DisplayClass27_0 ) { }
	// RVA: 0x69ada8c VA: 0x7598fc5a8c
	private Void <Apply>g__UpdateSelectionUp|27_1(Int32 newIndex, ref <>c__DisplayClass27_0 ) { }
}
```