# LoopScrollRectWrapper

**Namespace:** ` `


## Fields

- `LoopScrollRect m_inst`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class LoopScrollRectWrapper : Wrapper
{
	private LoopScrollRect m_inst; // 0x10

	public override Boolean vertical { get; set; }
	public override Boolean horizontal { get; set; }
	public override RectTransform content { get; set; }
	public override Vector2 wholeContentSize { get; }
	public override RectTransform viewport { get; set; }
	public override Single verticalNormalizedPosition { get; set; }
	public override Single horizontalNormalizedPosition { get; set; }
	public override Vector2 normalizedPosition { get; set; }

	// RVA: 0x22617e0 VA: 0x75948797e0
	public Void .ctor(IDragHandler iDragHandler) { }
	// RVA: 0x2261ca4 VA: 0x7594879ca4
	public override Boolean get_vertical() { }
	// RVA: 0x2261cc8 VA: 0x7594879cc8
	public override Void set_vertical(Boolean value) { }
	// RVA: 0x2261cf0 VA: 0x7594879cf0
	public override Boolean get_horizontal() { }
	// RVA: 0x2261d14 VA: 0x7594879d14
	public override Void set_horizontal(Boolean value) { }
	// RVA: 0x2261d3c VA: 0x7594879d3c
	public override RectTransform get_content() { }
	// RVA: 0x2261d58 VA: 0x7594879d58
	public override Void set_content(RectTransform value) { }
	// RVA: 0x2261d74 VA: 0x7594879d74
	public override Vector2 get_wholeContentSize() { }
	// RVA: 0x2261d90 VA: 0x7594879d90
	public override RectTransform get_viewport() { }
	// RVA: 0x2261dac VA: 0x7594879dac
	public override Void set_viewport(RectTransform value) { }
	// RVA: 0x2261dc8 VA: 0x7594879dc8
	public override Single get_verticalNormalizedPosition() { }
	// RVA: 0x2261de4 VA: 0x7594879de4
	public override Void set_verticalNormalizedPosition(Single value) { }
	// RVA: 0x2261e00 VA: 0x7594879e00
	public override Single get_horizontalNormalizedPosition() { }
	// RVA: 0x2261e1c VA: 0x7594879e1c
	public override Void set_horizontalNormalizedPosition(Single value) { }
	// RVA: 0x2261e38 VA: 0x7594879e38
	public override Vector2 get_normalizedPosition() { }
	// RVA: 0x2261e54 VA: 0x7594879e54
	public override Void set_normalizedPosition(Vector2 value) { }
	// RVA: 0x2261e70 VA: 0x7594879e70
	public override Void AddOnValueChangedListener(UnityAction`1 callback) { }
	// RVA: 0x2261ed4 VA: 0x7594879ed4
	public override Void AddOnPostLayoutListener(Action onLayoutRebuilt) { }
}
```