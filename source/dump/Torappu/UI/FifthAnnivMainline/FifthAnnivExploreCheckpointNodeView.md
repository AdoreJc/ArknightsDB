# FifthAnnivExploreCheckpointNodeView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `UIAtlasImage _imgNode`

- `GameObject _panelCircle`

- `UIAnimationLocation _animationLocation`

- `Single _delayShow`

- `Boolean m_isInited`

- `Boolean m_cachedIsCurrent`

- `FifthAnnivExploreMapViewConfig m_mapViewConfig`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _InitIfNot()`

- `Void _PlayEnterAnim()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreCheckpointNodeView : FifthAnnivExploreAbstractNodeView
{
	private UIAtlasImage _imgNode; // 0x18
	private GameObject _panelCircle; // 0x20
	private UIAnimationLocation _animationLocation; // 0x28
	private Single _delayShow; // 0x38
	private Boolean m_isInited; // 0x3c
	private Boolean m_cachedIsCurrent; // 0x3d
	private FifthAnnivExploreMapViewConfig m_mapViewConfig; // 0x40
	private UIPageFinder m_pageFinder; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__PlayEnterAnim; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x29250d8 VA: 0x7594f3d0d8
	public override Void Render(FifthAnnivExploreMapNodeViewModel nodeViewModel, Int32 currentIndexInRoute) { }
	// RVA: 0x2925290 VA: 0x7594f3d290
	private Void _InitIfNot() { }
	// RVA: 0x2925448 VA: 0x7594f3d448
	private Void _PlayEnterAnim() { }
	// RVA: 0x292552c VA: 0x7594f3d52c
	public Void .ctor() { }
}
```