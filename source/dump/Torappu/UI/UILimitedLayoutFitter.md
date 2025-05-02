# UILimitedLayoutFitter

**Namespace:** `Torappu.UI`


## Fields

- `Boolean _horizontal`

- `Boolean _vertical`

- `Single _limitedWidth`

- `Single _limitedHeight`


## Methods

- `Void _GetChildSizeAlongAxis(RectTransform, Int32, Boolean, out, out, out)`

- `Void _SetChildSizeAlongAxis(RectTransform, Int32, Single)`

- `Void _CalcAlongAxis(Int32)`

- `Void _SetChildrenSizeAlongAxis(Int32)`

- `Single <>xLuaBaseProxy_get_minWidth()`

- `Single <>xLuaBaseProxy_get_preferredWidth()`

- `Single <>xLuaBaseProxy_get_flexibleWidth()`

- `Single <>xLuaBaseProxy_get_minHeight()`

- `Single <>xLuaBaseProxy_get_preferredHeight()`

- `Single <>xLuaBaseProxy_get_flexibleHeight()`

- `Void <>xLuaBaseProxy_CalculateLayoutInputHorizontal()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UILimitedLayoutFitter : LayoutGroup, IHotfixable
{
	private Boolean _horizontal; // 0x58
	private Boolean _vertical; // 0x59
	private Single _limitedWidth; // 0x5c
	private Single _limitedHeight; // 0x60
	private static DelegateBridge __Hotfix0_get_minWidth; // 0x0
	private static DelegateBridge __Hotfix0_get_preferredWidth; // 0x8
	private static DelegateBridge __Hotfix0_get_flexibleWidth; // 0x10
	private static DelegateBridge __Hotfix0_get_minHeight; // 0x18
	private static DelegateBridge __Hotfix0_get_preferredHeight; // 0x20
	private static DelegateBridge __Hotfix0_get_flexibleHeight; // 0x28
	private static DelegateBridge __Hotfix0_CalculateLayoutInputHorizontal; // 0x30
	private static DelegateBridge __Hotfix0_CalculateLayoutInputVertical; // 0x38
	private static DelegateBridge __Hotfix0_SetLayoutHorizontal; // 0x40
	private static DelegateBridge __Hotfix0_SetLayoutVertical; // 0x48
	private static DelegateBridge __Hotfix0__GetChildSizeAlongAxis; // 0x50
	private static DelegateBridge __Hotfix0__SetChildSizeAlongAxis; // 0x58
	private static DelegateBridge __Hotfix0__CalcAlongAxis; // 0x60
	private static DelegateBridge __Hotfix0__SetChildrenSizeAlongAxis; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public override Single minWidth { get; }
	public override Single preferredWidth { get; }
	public override Single flexibleWidth { get; }
	public override Single minHeight { get; }
	public override Single preferredHeight { get; }
	public override Single flexibleHeight { get; }

	// RVA: 0x220e8d0 VA: 0x75948268d0
	public override Single get_minWidth() { }
	// RVA: 0x220e980 VA: 0x7594826980
	public override Single get_preferredWidth() { }
	// RVA: 0x220ea30 VA: 0x7594826a30
	public override Single get_flexibleWidth() { }
	// RVA: 0x220eab8 VA: 0x7594826ab8
	public override Single get_minHeight() { }
	// RVA: 0x220eb68 VA: 0x7594826b68
	public override Single get_preferredHeight() { }
	// RVA: 0x220ec18 VA: 0x7594826c18
	public override Single get_flexibleHeight() { }
	// RVA: 0x220eca0 VA: 0x7594826ca0
	public override Void CalculateLayoutInputHorizontal() { }
	// RVA: 0x220ee90 VA: 0x7594826e90
	public override Void CalculateLayoutInputVertical() { }
	// RVA: 0x220eefc VA: 0x7594826efc
	public override Void SetLayoutHorizontal() { }
	// RVA: 0x220f080 VA: 0x7594827080
	public override Void SetLayoutVertical() { }
	// RVA: 0x220f0ec VA: 0x75948270ec
	private Void _GetChildSizeAlongAxis(RectTransform child, Int32 axis, Boolean controlSize, out Single min, out Single preferred, out Single flexible) { }
	// RVA: 0x220f25c VA: 0x759482725c
	private Void _SetChildSizeAlongAxis(RectTransform rect, Int32 axis, Single size) { }
	// RVA: 0x220ed18 VA: 0x7594826d18
	private Void _CalcAlongAxis(Int32 axis) { }
	// RVA: 0x220ef68 VA: 0x7594826f68
	private Void _SetChildrenSizeAlongAxis(Int32 axis) { }
	// RVA: 0x220f378 VA: 0x7594827378
	public Void .ctor() { }
	// RVA: 0x220f3e8 VA: 0x75948273e8
	private Single <>xLuaBaseProxy_get_minWidth() { }
	// RVA: 0x220f3f0 VA: 0x75948273f0
	private Single <>xLuaBaseProxy_get_preferredWidth() { }
	// RVA: 0x220f3f8 VA: 0x75948273f8
	private Single <>xLuaBaseProxy_get_flexibleWidth() { }
	// RVA: 0x220f400 VA: 0x7594827400
	private Single <>xLuaBaseProxy_get_minHeight() { }
	// RVA: 0x220f408 VA: 0x7594827408
	private Single <>xLuaBaseProxy_get_preferredHeight() { }
	// RVA: 0x220f410 VA: 0x7594827410
	private Single <>xLuaBaseProxy_get_flexibleHeight() { }
	// RVA: 0x220f418 VA: 0x7594827418
	private Void <>xLuaBaseProxy_CalculateLayoutInputHorizontal() { }
}
```