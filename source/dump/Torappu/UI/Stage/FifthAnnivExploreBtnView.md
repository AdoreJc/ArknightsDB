# FifthAnnivExploreBtnView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `UICommonTrackPoint _trackPoint`

- `GameObject _normalPanel`

- `GameObject _lockedPanel`

- `TrackPointViewProperty m_trackProperty`

- `UIPageFinder m_pageFinder`

- `Boolean m_hasInited`

- `Boolean m_cachedOpen`


## Methods

- `Void OnClickEvent()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class FifthAnnivExploreBtnView : StageAdditionalBtnView
{
	private UICommonTrackPoint _trackPoint; // 0x18
	private GameObject _normalPanel; // 0x20
	private GameObject _lockedPanel; // 0x28
	private TrackPointViewProperty m_trackProperty; // 0x30
	private UIPageFinder m_pageFinder; // 0x38
	private Boolean m_hasInited; // 0x48
	private Boolean m_cachedOpen; // 0x49
	private static DelegateBridge __Hotfix0_OnClickEvent; // 0x0
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f8716c VA: 0x759559f16c
	public Void OnClickEvent() { }
	// RVA: 0x2f8724c VA: 0x759559f24c
	public override Boolean OnUpdate(ZoneViewModel model) { }
	// RVA: 0x2f87334 VA: 0x759559f334
	private Void _InitIfNot() { }
	// RVA: 0x2f873dc VA: 0x759559f3dc
	public Void .ctor() { }
}
```