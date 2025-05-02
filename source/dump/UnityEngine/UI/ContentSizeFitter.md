# ContentSizeFitter

**Namespace:** `UnityEngine.UI`


## Fields

- `FitMode m_HorizontalFit`

- `FitMode m_VerticalFit`

- `RectTransform m_Rect`

- `DrivenRectTransformTracker m_Tracker`


## Properties

- `FitMode horizontalFit`

- `FitMode verticalFit`

- `RectTransform rectTransform`


## Methods

- `FitMode get_horizontalFit()`

- `Void set_horizontalFit(FitMode)`

- `FitMode get_verticalFit()`

- `Void set_verticalFit(FitMode)`

- `RectTransform get_rectTransform()`

- `Void HandleSelfFittingAlongAxis(Int32)`

- `Void SetDirty()`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class ContentSizeFitter : UIBehaviour, ILayoutSelfController, ILayoutController
{
	protected FitMode m_HorizontalFit; // 0x18
	protected FitMode m_VerticalFit; // 0x1c
	private RectTransform m_Rect; // 0x20
	private DrivenRectTransformTracker m_Tracker; // 0x28

	public FitMode horizontalFit { get; set; }
	public FitMode verticalFit { get; set; }
	private RectTransform rectTransform { get; }

	// RVA: 0x6a52b28 VA: 0x759906ab28
	public FitMode get_horizontalFit() { }
	// RVA: 0x6a52b30 VA: 0x759906ab30
	public Void set_horizontalFit(FitMode value) { }
	// RVA: 0x6a52c28 VA: 0x759906ac28
	public FitMode get_verticalFit() { }
	// RVA: 0x6a52c30 VA: 0x759906ac30
	public Void set_verticalFit(FitMode value) { }
	// RVA: 0x6a52ca4 VA: 0x759906aca4
	private RectTransform get_rectTransform() { }
	// RVA: 0x6a52d4c VA: 0x759906ad4c
	protected Void .ctor() { }
	// RVA: 0x6a52d54 VA: 0x759906ad54
	protected override Void OnEnable() { }
	// RVA: 0x6a52d70 VA: 0x759906ad70
	protected override Void OnDisable() { }
	// RVA: 0x6a52dec VA: 0x759906adec
	protected override Void OnRectTransformDimensionsChange() { }
	// RVA: 0x6a52df0 VA: 0x759906adf0
	private Void HandleSelfFittingAlongAxis(Int32 axis) { }
	// RVA: 0x6a52eec VA: 0x759906aeec
	public virtual Void SetLayoutHorizontal() { }
	// RVA: 0x6a52f10 VA: 0x759906af10
	public virtual Void SetLayoutVertical() { }
	// RVA: 0x6a52ba4 VA: 0x759906aba4
	protected Void SetDirty() { }
}
```