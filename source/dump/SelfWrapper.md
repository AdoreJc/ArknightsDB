# SelfWrapper

**Namespace:** ` `


## Fields

- `UIWrappedScrollRect m_inst`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class SelfWrapper : Wrapper
{
	private UIWrappedScrollRect m_inst; // 0x10

	public override Boolean vertical { get; set; }
	public override Boolean horizontal { get; set; }
	public override RectTransform content { get; set; }
	public override Vector2 wholeContentSize { get; }
	public override RectTransform viewport { get; set; }
	public override Single verticalNormalizedPosition { get; set; }
	public override Single horizontalNormalizedPosition { get; set; }
	public override Vector2 normalizedPosition { get; set; }

	// RVA: 0x22618a8 VA: 0x75948798a8
	public Void .ctor(IDragHandler iDragHandler) { }
	// RVA: 0x2261ef0 VA: 0x7594879ef0
	public override Boolean get_vertical() { }
	// RVA: 0x2261f0c VA: 0x7594879f0c
	public override Void set_vertical(Boolean value) { }
	// RVA: 0x2261f2c VA: 0x7594879f2c
	public override Boolean get_horizontal() { }
	// RVA: 0x2261f48 VA: 0x7594879f48
	public override Void set_horizontal(Boolean value) { }
	// RVA: 0x2261f68 VA: 0x7594879f68
	public override RectTransform get_content() { }
	// RVA: 0x2261f84 VA: 0x7594879f84
	public override Void set_content(RectTransform value) { }
	// RVA: 0x2261fa0 VA: 0x7594879fa0
	public override Vector2 get_wholeContentSize() { }
	// RVA: 0x2261fe8 VA: 0x7594879fe8
	public override RectTransform get_viewport() { }
	// RVA: 0x2262004 VA: 0x759487a004
	public override Void set_viewport(RectTransform value) { }
	// RVA: 0x2262020 VA: 0x759487a020
	public override Single get_verticalNormalizedPosition() { }
	// RVA: 0x226203c VA: 0x759487a03c
	public override Void set_verticalNormalizedPosition(Single value) { }
	// RVA: 0x2262058 VA: 0x759487a058
	public override Single get_horizontalNormalizedPosition() { }
	// RVA: 0x2262074 VA: 0x759487a074
	public override Void set_horizontalNormalizedPosition(Single value) { }
	// RVA: 0x2262090 VA: 0x759487a090
	public override Vector2 get_normalizedPosition() { }
	// RVA: 0x22620ac VA: 0x759487a0ac
	public override Void set_normalizedPosition(Vector2 value) { }
	// RVA: 0x22620c8 VA: 0x759487a0c8
	public override Void AddOnValueChangedListener(UnityAction`1 callback) { }
	// RVA: 0x226212c VA: 0x759487a12c
	public override Void AddOnPostLayoutListener(Action onLayoutRebuilt) { }
}
```