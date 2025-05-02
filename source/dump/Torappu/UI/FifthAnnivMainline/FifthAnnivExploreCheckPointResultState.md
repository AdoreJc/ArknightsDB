# FifthAnnivExploreCheckPointResultState

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `FifthAnnivExploreCheckPointResultView _view`

- `UIBlendRTImage _blurImg`

- `FifthAnnivExploreCheckPointResultViewModel m_viewModel`

- `Boolean m_isInited`

- `FifthAnnivExploreMapController m_mapController`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _InitIfNot()`

- `Void _OnNextBtnClick()`

- `Void _OnConfirmPassTarget()`

- `Void _OnSettleGame()`

- `Void <_OnConfirmPassTarget>b__10_0(ExploreConfirmPassTargetResponse)`

- `Void <_OnSettleGame>b__11_0(ExploreSettleGameResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreCheckPointResultState : PopupFadeState, IHotfixable
{
	private FifthAnnivExploreCheckPointResultView _view; // 0x70
	private UIBlendRTImage _blurImg; // 0x78
	private FifthAnnivExploreCheckPointResultViewModel m_viewModel; // 0x80
	private Boolean m_isInited; // 0x88
	private FifthAnnivExploreMapController m_mapController; // 0x90
	private UIPageFinder m_pageFinder; // 0x98
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0__OnNextBtnClick; // 0x18
	private static DelegateBridge __Hotfix0__OnConfirmPassTarget; // 0x20
	private static DelegateBridge __Hotfix0__OnSettleGame; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x290adbc VA: 0x7594f22dbc
	private Void _InitIfNot() { }
	// RVA: 0x290afb8 VA: 0x7594f22fb8
	protected override Void OnEnter() { }
	// RVA: 0x290b600 VA: 0x7594f23600
	public override IStateBean GetCacheBean() { }
	// RVA: 0x290b664 VA: 0x7594f23664
	private Void _OnNextBtnClick() { }
	// RVA: 0x290ba14 VA: 0x7594f23a14
	private Void _OnConfirmPassTarget() { }
	// RVA: 0x290b80c VA: 0x7594f2380c
	private Void _OnSettleGame() { }
	// RVA: 0x290bc10 VA: 0x7594f23c10
	public Void .ctor() { }
	// RVA: 0x290bcc8 VA: 0x7594f23cc8
	private Void <_OnConfirmPassTarget>b__10_0(ExploreConfirmPassTargetResponse response) { }
	// RVA: 0x290bdd0 VA: 0x7594f23dd0
	private Void <_OnSettleGame>b__11_0(ExploreSettleGameResponse response) { }
	// RVA: 0x290be54 VA: 0x7594f23e54
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```