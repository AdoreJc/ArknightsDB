# ScrollRectWrapper

**Namespace:** ` `


## Fields

- `ScrollRect m_inst`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ScrollRectWrapper : Wrapper
{
	private ScrollRect m_inst; // 0x10

	public override Boolean vertical { get; set; }
	public override Boolean horizontal { get; set; }
	public override RectTransform content { get; set; }
	public override Vector2 wholeContentSize { get; }
	public override RectTransform viewport { get; set; }
	public override Single verticalNormalizedPosition { get; set; }
	public override Single horizontalNormalizedPosition { get; set; }
	public override Vector2 normalizedPosition { get; set; }

	// RVA: 0x2261718 VA: 0x7594879718
	public Void .ctor(IDragHandler iDragHandler) { }
	// RVA: 0x2261978 VA: 0x7594879978
	public override Boolean get_vertical() { }
	// RVA: 0x2261994 VA: 0x7594879994
	public override Void set_vertical(Boolean value) { }
	// RVA: 0x22619b4 VA: 0x75948799b4
	public override Boolean get_horizontal() { }
	// RVA: 0x22619d0 VA: 0x75948799d0
	public override Void set_horizontal(Boolean value) { }
	// RVA: 0x22619f0 VA: 0x75948799f0
	public override RectTransform get_content() { }
	// RVA: 0x2261a0c VA: 0x7594879a0c
	public override Void set_content(RectTransform value) { }
	// RVA: 0x2261a28 VA: 0x7594879a28
	public override Vector2 get_wholeContentSize() { }
	// RVA: 0x2261a70 VA: 0x7594879a70
	public override RectTransform get_viewport() { }
	// RVA: 0x2261a8c VA: 0x7594879a8c
	public override Void set_viewport(RectTransform value) { }
	// RVA: 0x2261aa8 VA: 0x7594879aa8
	public override Single get_verticalNormalizedPosition() { }
	// RVA: 0x2261ac4 VA: 0x7594879ac4
	public override Void set_verticalNormalizedPosition(Single value) { }
	// RVA: 0x2261ae0 VA: 0x7594879ae0
	public override Single get_horizontalNormalizedPosition() { }
	// RVA: 0x2261afc VA: 0x7594879afc
	public override Void set_horizontalNormalizedPosition(Single value) { }
	// RVA: 0x2261b18 VA: 0x7594879b18
	public override Vector2 get_normalizedPosition() { }
	// RVA: 0x2261b34 VA: 0x7594879b34
	public override Void set_normalizedPosition(Vector2 value) { }
	// RVA: 0x2261b50 VA: 0x7594879b50
	public override Void AddOnValueChangedListener(UnityAction`1 callback) { }
	// RVA: 0x2261bb0 VA: 0x7594879bb0
	public override Void AddOnPostLayoutListener(Action onLayoutRebuilt) { }
}
```