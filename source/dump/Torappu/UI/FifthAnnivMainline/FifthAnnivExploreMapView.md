# FifthAnnivExploreMapView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `RectTransform _nodeShadowContainer`

- `RectTransform _lineShadowContainer`

- `RectTransform _nodeContainer`

- `RectTransform _lineContainer`

- `FifthAnnivExploreNodeGroup _nodeGroupPrefab`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `FifthAnnivExploreMapViewConfig m_mapViewConfig`

- `FifthAnnivExploreMapViewModel m_cachedMapViewModel`

- `NodeViewPool m_nodeViewPool`

- `NodeShadowViewPool m_nodeShadowViewPool`

- `LineViewPool m_lineViewPool`

- `LineShadowViewPool m_lineShadowViewPool`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreMapView : DataBinder`1
{
	private RectTransform _nodeShadowContainer; // 0x20
	private RectTransform _lineShadowContainer; // 0x28
	private RectTransform _nodeContainer; // 0x30
	private RectTransform _lineContainer; // 0x38
	private FifthAnnivExploreNodeGroup _nodeGroupPrefab; // 0x40
	private Boolean m_isInited; // 0x48
	private UIPageFinder m_pageFinder; // 0x50
	private FifthAnnivExploreMapViewConfig m_mapViewConfig; // 0x60
	private FifthAnnivExploreMapViewModel m_cachedMapViewModel; // 0x68
	private ListDict`2 m_cachedNodeViewModelGroup; // 0x70
	private ListDict`2 m_cachedLineViewModelGroup; // 0x78
	private NodeViewPool m_nodeViewPool; // 0x80
	private NodeShadowViewPool m_nodeShadowViewPool; // 0x88
	private LineViewPool m_lineViewPool; // 0x90
	private LineShadowViewPool m_lineShadowViewPool; // 0x98
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2920d30 VA: 0x7594f38d30
	public override Void OnValueChanged(FifthAnnivExploreProperty property) { }
	// RVA: 0x2920f34 VA: 0x7594f38f34
	private Void _InitIfNot() { }
	// RVA: 0x2921344 VA: 0x7594f39344
	public Void .ctor() { }
}
```