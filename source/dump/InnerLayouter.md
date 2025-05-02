# InnerLayouter

**Namespace:** ` `


## Fields

- `Act42D0EffectDetailGroupView m_closure`

- `Int32 m_cachedSequenceNum`


## Methods

- `Void _TransitionRemoved(LayoutElement, Boolean)`

- `Void _TransitionNewlyAdded(LayoutElement, LayoutMeta, RectTransform, Boolean)`

- `Void _FocusNewlyAdded(LayoutMeta, RectTransform)`

- `Void _TransitionMove(LayoutMeta, RectTransform, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class InnerLayouter : UICustomSingleOrientationLayouter`2
{
	private Act42D0EffectDetailGroupView m_closure; // 0x68
	private Int32 m_cachedSequenceNum; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_DataComparison; // 0x8
	private static DelegateBridge __Hotfix0_LayoutTransitionImpl; // 0x10
	private static DelegateBridge __Hotfix0_LayoutImmediatelyImpl; // 0x18
	private static DelegateBridge __Hotfix0__TransitionRemoved; // 0x20
	private static DelegateBridge __Hotfix0__TransitionNewlyAdded; // 0x28
	private static DelegateBridge __Hotfix0__FocusNewlyAdded; // 0x30
	private static DelegateBridge __Hotfix0__TransitionMove; // 0x38


	// RVA: 0x320b994 VA: 0x7595823994
	public Void .ctor(Act42D0EffectDetailGroupView closure) { }
	// RVA: 0x320c26c VA: 0x759582426c
	protected override Int32 DataComparison(Act42D0EffectItemViewModel lhs, Act42D0EffectItemViewModel rhs) { }
	// RVA: 0x320c300 VA: 0x7595824300
	protected override Void LayoutTransitionImpl() { }
	// RVA: 0x320cf34 VA: 0x7595824f34
	protected override Void LayoutImmediatelyImpl() { }
	// RVA: 0x320c634 VA: 0x7595824634
	private Void _TransitionRemoved(LayoutElement ele, Boolean needReset) { }
	// RVA: 0x320c884 VA: 0x7595824884
	private Void _TransitionNewlyAdded(LayoutElement ele, LayoutMeta meta, RectTransform rectTrans, Boolean needReset) { }
	// RVA: 0x320d3ac VA: 0x75958253ac
	private Void _FocusNewlyAdded(LayoutMeta meta, RectTransform rectTrans) { }
	// RVA: 0x320cc2c VA: 0x7595824c2c
	private Void _TransitionMove(LayoutMeta meta, RectTransform rectTrans, Boolean needReset) { }
}
```