# FifthAnnivExploreSideInfoView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `FifthAnnivExploreSideInfoExpandSubView _expandSubView`

- `FifthAnnivExploreSideInfoSimpleSubView _simpleSubView`

- `Single _fadeDuration`

- `UIAnimationLocation _switchAnim`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `AnimationSwitchTween m_switchTween`

- `FifthAnnivExploreViewModel m_cachedViewModel`

- `StateEngine m_bindStateEngine`

- `StateTransitionParam m_currTransParam`

- `ViewType m_cachedViewType`


## Methods

- `Void _OnBeforeStateTransition(Object)`

- `Void _OnStateChanged(Object)`

- `Void _SetViewActive()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreSideInfoView : DataBinder`1, IHotfixable
{
	private static readonly Type[] STATES_WITH_SIMPLE_VIEW; // 0x0
	private FifthAnnivExploreSideInfoExpandSubView _expandSubView; // 0x20
	private FifthAnnivExploreSideInfoSimpleSubView _simpleSubView; // 0x28
	private Single _fadeDuration; // 0x30
	private UIAnimationLocation _switchAnim; // 0x38
	private Boolean m_isInited; // 0x48
	private UIPageFinder m_pageFinder; // 0x50
	private AnimationSwitchTween m_switchTween; // 0x60
	private FifthAnnivExploreViewModel m_cachedViewModel; // 0x68
	private StateEngine m_bindStateEngine; // 0x70
	private StateTransitionParam m_currTransParam; // 0x78
	private ViewType m_cachedViewType; // 0x80
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__OnBeforeStateTransition; // 0x10
	private static DelegateBridge __Hotfix0__OnStateChanged; // 0x18
	private static DelegateBridge __Hotfix0__SetViewActive; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x292e968 VA: 0x7594f46968
	public override Void OnValueChanged(FifthAnnivExploreProperty property) { }
	// RVA: 0x292edb8 VA: 0x7594f46db8
	private Void _OnBeforeStateTransition(Object arg) { }
	// RVA: 0x292eeec VA: 0x7594f46eec
	private Void _OnStateChanged(Object arg) { }
	// RVA: 0x292f120 VA: 0x7594f47120
	private Void _SetViewActive() { }
	// RVA: 0x292ea54 VA: 0x7594f46a54
	private Void _InitIfNot() { }
	// RVA: 0x292f1e0 VA: 0x7594f471e0
	public Void .ctor() { }
	// RVA: 0x292f2d0 VA: 0x7594f472d0
	private static Void .cctor() { }
}
```