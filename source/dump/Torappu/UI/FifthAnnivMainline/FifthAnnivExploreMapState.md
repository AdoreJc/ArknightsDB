# FifthAnnivExploreMapState

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `GameObject _mapEntryGo`

- `UIAnimationLocation _animEntrySideBar`

- `FifthAnnivExploreMapEffect _animMapEffect`

- `FifthAnnivExploreCarouselGroup _carouselGroup`

- `UIAnimationLocation _toastAnimationLocation`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _RefreshMap()`

- `Void _DealWithBroadcast()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreMapState : PopupFadeState
{
	private GameObject _mapEntryGo; // 0x70
	private UIAnimationLocation _animEntrySideBar; // 0x78
	private FifthAnnivExploreMapEffect _animMapEffect; // 0x88
	private FifthAnnivExploreCarouselGroup _carouselGroup; // 0x90
	private UIAnimationLocation _toastAnimationLocation; // 0x98
	private UIPageFinder m_pageFinder; // 0xa8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__RefreshMap; // 0x18
	private static DelegateBridge __Hotfix0__DealWithBroadcast; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2920710 VA: 0x7594f38710
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2920774 VA: 0x7594f38774
	protected override Void OnEnter() { }
	// RVA: 0x2920808 VA: 0x7594f38808
	protected override Void OnResume() { }
	// RVA: 0x29208ac VA: 0x7594f388ac
	private Void _RefreshMap() { }
	// RVA: 0x29209a4 VA: 0x7594f389a4
	private Void _DealWithBroadcast() { }
	// RVA: 0x2920b4c VA: 0x7594f38b4c
	public Void .ctor() { }
	// RVA: 0x2920bbc VA: 0x7594f38bbc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2920bc4 VA: 0x7594f38bc4
	private Void <>xLuaBaseProxy_OnResume() { }
}
```