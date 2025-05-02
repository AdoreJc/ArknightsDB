# Act1ArcadeStageTagItemView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `GameObject _panelNormal`

- `GameObject _panelNoInfo`

- `GameObject _panelLocked`

- `Image _imgRank`

- `UIAnimationLocation _animNormal`

- `UIAnimationLocation _animNoInfo`

- `UICommonTrackPoint _trackPoint`

- `TrackPointViewProperty m_trackPointProperty`

- `UIAnimationTween m_animTween`

- `Builder m_animNormalBuilder`

- `Builder m_animNoInfoBuilder`

- `Act1ArcadeStageSelectViewModel m_stageSelectViewModel`

- `Act1ArcadeSingleStageModel m_stageModel`

- `Boolean m_isPrefSelecting`

- `UIStateFinder m_finder`

- `UIPageFinder m_pageFinder`

- `Boolean m_isInited`

- `UpdateParam m_trackPointParam`


## Properties

- `Boolean m_isSelecting`


## Methods

- `Boolean get_m_isSelecting()`

- `Void _InitIfNot()`

- `Void InitView(Act1ArcadeSingleStageModel, Boolean)`

- `Void _InitAnim(UIAnimationLocation, Boolean)`

- `Void _PlaySelectAnim(Builder, Boolean)`

- `Void EventOnStageTagItemClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeStageTagItemView : DataBinder`1
{
	private GameObject _panelNormal; // 0x20
	private GameObject _panelNoInfo; // 0x28
	private GameObject _panelLocked; // 0x30
	private Image _imgRank; // 0x38
	private UIAnimationLocation _animNormal; // 0x40
	private UIAnimationLocation _animNoInfo; // 0x50
	private UICommonTrackPoint _trackPoint; // 0x60
	private TrackPointViewProperty m_trackPointProperty; // 0x68
	private UIAnimationTween m_animTween; // 0x70
	private Builder m_animNormalBuilder; // 0x78
	private Builder m_animNoInfoBuilder; // 0xa0
	private Act1ArcadeStageSelectViewModel m_stageSelectViewModel; // 0xc8
	private Act1ArcadeSingleStageModel m_stageModel; // 0xd0
	private Boolean m_isPrefSelecting; // 0xd8
	private UIStateFinder m_finder; // 0xe0
	private UIPageFinder m_pageFinder; // 0xf0
	private Boolean m_isInited; // 0x100
	private UpdateParam m_trackPointParam; // 0x108
	private static DelegateBridge __Hotfix0_get_m_isSelecting; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_InitView; // 0x10
	private static DelegateBridge __Hotfix0__InitAnim; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0__PlaySelectAnim; // 0x28
	private static DelegateBridge __Hotfix0_EventOnStageTagItemClicked; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Boolean m_isSelecting { get; }

	// RVA: 0x3415b50 VA: 0x7595a2db50
	private Boolean get_m_isSelecting() { }
	// RVA: 0x3415be8 VA: 0x7595a2dbe8
	private Void _InitIfNot() { }
	// RVA: 0x3410734 VA: 0x7595a28734
	public Void InitView(Act1ArcadeSingleStageModel stageModel, Boolean isDefaultSelect) { }
	// RVA: 0x3415e08 VA: 0x7595a2de08
	private Void _InitAnim(UIAnimationLocation animationLocation, Boolean sampleAtBegin) { }
	// RVA: 0x3415ed4 VA: 0x7595a2ded4
	public override Void OnValueChanged(Act1ArcadeStageSelectProperty property) { }
	// RVA: 0x34161a4 VA: 0x7595a2e1a4
	private Void _PlaySelectAnim(Builder animBuilder, Boolean isSelecting) { }
	// RVA: 0x34162f4 VA: 0x7595a2e2f4
	public Void EventOnStageTagItemClicked() { }
	// RVA: 0x3416418 VA: 0x7595a2e418
	public Void .ctor() { }
}
```