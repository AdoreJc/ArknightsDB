# TwoPaneSplitViewResizer

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Vector3 m_Start`

- `Boolean m_Active`

- `TwoPaneSplitView m_SplitView`

- `Int32 m_Direction`

- `TwoPaneSplitViewOrientation m_Orientation`


## Properties

- `VisualElement fixedPane`

- `VisualElement flexedPane`

- `Single fixedPaneMinDimension`

- `Single flexedPaneMinDimension`


## Methods

- `VisualElement get_fixedPane()`

- `VisualElement get_flexedPane()`

- `Single get_fixedPaneMinDimension()`

- `Single get_flexedPaneMinDimension()`

- `Void ApplyDelta(Single)`

- `Void OnPointerDown(PointerDownEvent)`

- `Void OnPointerMove(PointerMoveEvent)`

- `Void OnPointerUp(PointerUpEvent)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class TwoPaneSplitViewResizer : PointerManipulator
{
	private Vector3 m_Start; // 0x30
	protected Boolean m_Active; // 0x3c
	private TwoPaneSplitView m_SplitView; // 0x40
	private Int32 m_Direction; // 0x48
	private TwoPaneSplitViewOrientation m_Orientation; // 0x4c

	private VisualElement fixedPane { get; }
	private VisualElement flexedPane { get; }
	private Single fixedPaneMinDimension { get; }
	private Single flexedPaneMinDimension { get; }

	// RVA: 0x69cebf8 VA: 0x7598fe6bf8
	private VisualElement get_fixedPane() { }
	// RVA: 0x69cec14 VA: 0x7598fe6c14
	private VisualElement get_flexedPane() { }
	// RVA: 0x69cec30 VA: 0x7598fe6c30
	private Single get_fixedPaneMinDimension() { }
	// RVA: 0x69ced44 VA: 0x7598fe6d44
	private Single get_flexedPaneMinDimension() { }
	// RVA: 0x69cdd2c VA: 0x7598fe5d2c
	public Void .ctor(TwoPaneSplitView splitView, Int32 dir, TwoPaneSplitViewOrientation orientation) { }
	// RVA: 0x69cee58 VA: 0x7598fe6e58
	protected override Void RegisterCallbacksOnTarget() { }
	// RVA: 0x69cf024 VA: 0x7598fe7024
	protected override Void UnregisterCallbacksFromTarget() { }
	// RVA: 0x69cf1f0 VA: 0x7598fe71f0
	public Void ApplyDelta(Single delta) { }
	// RVA: 0x69cf818 VA: 0x7598fe7818
	protected Void OnPointerDown(PointerDownEvent e) { }
	// RVA: 0x69cf8e0 VA: 0x7598fe78e0
	protected Void OnPointerMove(PointerMoveEvent e) { }
	// RVA: 0x69cf998 VA: 0x7598fe7998
	protected Void OnPointerUp(PointerUpEvent e) { }
}
```