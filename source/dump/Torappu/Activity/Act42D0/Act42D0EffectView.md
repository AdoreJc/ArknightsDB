# Act42D0EffectView

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Act42D0EffectSelectView _selectView`

- `Act42D0EffectDetailGroupView _detailGroupView`

- `Act42D0EffectBottomView _bottomView`

- `CanvasGroup _canvasGroup`

- `GameObject _buffListGraphic`

- `Boolean m_isInited`

- `ShowHideSwitchTween m_switchTween`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _InitIfNot()`

- `Void _RegisterTutorialGo()`

- `Void _NotifyEffectViewShown()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0EffectView : DataBinder`1
{
	private Act42D0EffectSelectView _selectView; // 0x20
	private Act42D0EffectDetailGroupView _detailGroupView; // 0x28
	private Act42D0EffectBottomView _bottomView; // 0x30
	private CanvasGroup _canvasGroup; // 0x38
	private GameObject _buffListGraphic; // 0x40
	private Boolean m_isInited; // 0x48
	private ShowHideSwitchTween m_switchTween; // 0x50
	private UIPageFinder m_pageFinder; // 0x58
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__RegisterTutorialGo; // 0x10
	private static DelegateBridge __Hotfix0__NotifyEffectViewShown; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3210528 VA: 0x7595828528
	public override Void OnValueChanged(Act42D0EffectProperty property) { }
	// RVA: 0x32106b0 VA: 0x75958286b0
	private Void _InitIfNot() { }
	// RVA: 0x3210828 VA: 0x7595828828
	private Void _RegisterTutorialGo() { }
	// RVA: 0x3210988 VA: 0x7595828988
	private Void _NotifyEffectViewShown() { }
	// RVA: 0x3210a2c VA: 0x7595828a2c
	public Void .ctor() { }
}
```