# Act1ArcadeStageSelectBottomInfoView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `GameObject _panelRewardSOnly`

- `GameObject _panelRewardSA`

- `Text _textRewardRankSOnly`

- `Text _textRewardRankA`

- `Text _textRewardRankS`

- `Image _imgToken`

- `UICommonTrackPoint _trackPoint`

- `TrackPointViewProperty m_trackPointProperty`

- `UIItemViewModel m_itemViewModel`

- `UIStateFinder m_stateFinder`

- `UIPageFinder m_pageFinder`

- `Boolean m_isInited`

- `UpdateParam m_trackPointParam`


## Methods

- `Void _InitIfNot()`

- `Void EventOnClickBadge()`

- `Void EventOnClickStartBattle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeStageSelectBottomInfoView : DataBinder`1
{
	private GameObject _panelRewardSOnly; // 0x20
	private GameObject _panelRewardSA; // 0x28
	private Text _textRewardRankSOnly; // 0x30
	private Text _textRewardRankA; // 0x38
	private Text _textRewardRankS; // 0x40
	private Image _imgToken; // 0x48
	private List`1 _badgeItemViews; // 0x50
	private UICommonTrackPoint _trackPoint; // 0x58
	private TrackPointViewProperty m_trackPointProperty; // 0x60
	private UIItemViewModel m_itemViewModel; // 0x68
	private UIStateFinder m_stateFinder; // 0x70
	private UIPageFinder m_pageFinder; // 0x80
	private Boolean m_isInited; // 0x90
	private UpdateParam m_trackPointParam; // 0x98
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_EventOnClickBadge; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClickStartBattle; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3414fe0 VA: 0x7595a2cfe0
	private Void _InitIfNot() { }
	// RVA: 0x3415104 VA: 0x7595a2d104
	public override Void OnValueChanged(Act1ArcadeStageSelectProperty property) { }
	// RVA: 0x341566c VA: 0x7595a2d66c
	public Void EventOnClickBadge() { }
	// RVA: 0x3415720 VA: 0x7595a2d720
	public Void EventOnClickStartBattle() { }
	// RVA: 0x34157d4 VA: 0x7595a2d7d4
	public Void .ctor() { }
}
```