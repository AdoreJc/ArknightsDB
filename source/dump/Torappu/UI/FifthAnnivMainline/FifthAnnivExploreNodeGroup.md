# FifthAnnivExploreNodeGroup

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `RectTransform _oriNodeContainer`

- `RectTransform _currentNodeContainer`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `FifthAnnivExploreMapViewConfig m_mapViewConfig`

- `Boolean m_cachedIsCurrent`

- `FifthAnnivNodeType m_cachedNodeType`

- `FifthAnnivExploreAbstractNodeView m_oriNodeView`

- `FifthAnnivExploreAbstractNodeView m_currentNodeView`


## Methods

- `Void Render(FifthAnnivExploreMapNodeViewModel, Int32)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreNodeGroup : MonoBehaviour, IHotfixable
{
	private RectTransform _oriNodeContainer; // 0x18
	private RectTransform _currentNodeContainer; // 0x20
	private Boolean m_isInited; // 0x28
	private UIPageFinder m_pageFinder; // 0x30
	private FifthAnnivExploreMapViewConfig m_mapViewConfig; // 0x40
	private Boolean m_cachedIsCurrent; // 0x48
	private FifthAnnivNodeType m_cachedNodeType; // 0x4c
	private FifthAnnivExploreAbstractNodeView m_oriNodeView; // 0x50
	private FifthAnnivExploreAbstractNodeView m_currentNodeView; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2921970 VA: 0x7594f39970
	public Void Render(FifthAnnivExploreMapNodeViewModel nodeViewModel, Int32 currentIndexInRoute) { }
	// RVA: 0x2925ff0 VA: 0x7594f3dff0
	private Void _InitIfNot() { }
	// RVA: 0x2926110 VA: 0x7594f3e110
	public Void .ctor() { }
}
```