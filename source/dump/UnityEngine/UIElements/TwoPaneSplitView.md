# TwoPaneSplitView

**Namespace:** `UnityEngine.UIElements`


## Fields

- `VisualElement m_LeftPane`

- `VisualElement m_RightPane`

- `VisualElement m_FixedPane`

- `VisualElement m_FlexedPane`

- `Single m_FixedPaneDimension`

- `VisualElement m_DragLine`

- `VisualElement m_DragLineAnchor`

- `Boolean m_CollapseMode`

- `VisualElement m_Content`

- `TwoPaneSplitViewOrientation m_Orientation`

- `Int32 m_FixedPaneIndex`

- `Single m_FixedPaneInitialDimension`


## Properties

- `VisualElement fixedPane`

- `VisualElement flexedPane`

- `Int32 fixedPaneIndex`


## Methods

- `VisualElement get_fixedPane()`

- `VisualElement get_flexedPane()`

- `Int32 get_fixedPaneIndex()`

- `Void OnPostDisplaySetup(GeometryChangedEvent)`

- `Void PostDisplaySetup()`

- `Void OnSizeChange(GeometryChangedEvent)`

- `Void OnSizeChange()`

- `Void SetDragLineOffset(Single)`

- `Void SetFixedPaneDimension(Single)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class TwoPaneSplitView : VisualElement
{
	private static readonly String s_UssClassName; // 0x0
	private static readonly String s_ContentContainerClassName; // 0x8
	private static readonly String s_HandleDragLineClassName; // 0x10
	private static readonly String s_HandleDragLineVerticalClassName; // 0x18
	private static readonly String s_HandleDragLineHorizontalClassName; // 0x20
	private static readonly String s_HandleDragLineAnchorClassName; // 0x28
	private static readonly String s_HandleDragLineAnchorVerticalClassName; // 0x30
	private static readonly String s_HandleDragLineAnchorHorizontalClassName; // 0x38
	private static readonly String s_VerticalClassName; // 0x40
	private static readonly String s_HorizontalClassName; // 0x48
	private VisualElement m_LeftPane; // 0x3b0
	private VisualElement m_RightPane; // 0x3b8
	private VisualElement m_FixedPane; // 0x3c0
	private VisualElement m_FlexedPane; // 0x3c8
	private Single m_FixedPaneDimension; // 0x3d0
	private VisualElement m_DragLine; // 0x3d8
	private VisualElement m_DragLineAnchor; // 0x3e0
	private Boolean m_CollapseMode; // 0x3e8
	private VisualElement m_Content; // 0x3f0
	private TwoPaneSplitViewOrientation m_Orientation; // 0x3f8
	private Int32 m_FixedPaneIndex; // 0x3fc
	private Single m_FixedPaneInitialDimension; // 0x400
	internal TwoPaneSplitViewResizer m_Resizer; // 0x408

	public VisualElement fixedPane { get; }
	public VisualElement flexedPane { get; }
	public Int32 fixedPaneIndex { get; }
	internal Single fixedPaneDimension { get; set; }
	public override VisualElement contentContainer { get; }

	// RVA: 0x69cc6d8 VA: 0x7598fe46d8
	public VisualElement get_fixedPane() { }
	// RVA: 0x69cc6e0 VA: 0x7598fe46e0
	public VisualElement get_flexedPane() { }
	// RVA: 0x69cc6e8 VA: 0x7598fe46e8
	public Int32 get_fixedPaneIndex() { }
	// RVA: 0x69cc6f0 VA: 0x7598fe46f0
	internal Single get_fixedPaneDimension() { }
	// RVA: 0x69cc724 VA: 0x7598fe4724
	internal Void set_fixedPaneDimension(Single value) { }
	// RVA: 0x69cc740 VA: 0x7598fe4740
	public Void .ctor() { }
	// RVA: 0x69cc98c VA: 0x7598fe498c
	internal Void Init(Int32 fixedPaneIndex, Single fixedPaneInitialDimension, TwoPaneSplitViewOrientation orientation) { }
	// RVA: 0x69cdc24 VA: 0x7598fe5c24
	private Void OnPostDisplaySetup(GeometryChangedEvent evt) { }
	// RVA: 0x69ccc78 VA: 0x7598fe4c78
	private Void PostDisplaySetup() { }
	// RVA: 0x69cde18 VA: 0x7598fe5e18
	private Void OnSizeChange(GeometryChangedEvent evt) { }
	// RVA: 0x69cde1c VA: 0x7598fe5e1c
	private Void OnSizeChange() { }
	// RVA: 0x69ce63c VA: 0x7598fe663c
	public override VisualElement get_contentContainer() { }
	// RVA: 0x69ce644 VA: 0x7598fe6644
	internal override Void OnViewDataReady() { }
	// RVA: 0x69ce3ec VA: 0x7598fe63ec
	private Void SetDragLineOffset(Single offset) { }
	// RVA: 0x69ce514 VA: 0x7598fe6514
	private Void SetFixedPaneDimension(Single dimension) { }
	// RVA: 0x69ce680 VA: 0x7598fe6680
	private static Void .cctor() { }
}
```