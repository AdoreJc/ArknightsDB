# UIFrameBorder

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform _left`

- `RectTransform _top`

- `RectTransform _right`

- `RectTransform _bottom`

- `RectTransform _center`


## Methods

- `Void UpdateBorders()`

- `Void _UpdateBordersInternal()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIFrameBorder : UIBehaviour
{
	private RectTransform _left; // 0x18
	private RectTransform _top; // 0x20
	private RectTransform _right; // 0x28
	private RectTransform _bottom; // 0x30
	private RectTransform _center; // 0x38


	// RVA: 0x21d52a0 VA: 0x75947ed2a0
	protected override Void Start() { }
	// RVA: 0x21d5704 VA: 0x75947ed704
	protected override Void OnRectTransformDimensionsChange() { }
	// RVA: 0x21d5720 VA: 0x75947ed720
	protected override Void OnTransformParentChanged() { }
	// RVA: 0x21d573c VA: 0x75947ed73c
	public Void UpdateBorders() { }
	// RVA: 0x21d52bc VA: 0x75947ed2bc
	private Void _UpdateBordersInternal() { }
	// RVA: 0x21d5740 VA: 0x75947ed740
	public Void .ctor() { }
}
```