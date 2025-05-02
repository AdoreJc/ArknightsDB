# Act24sideButtonGroupPlugin

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `String m_actId`

- `UICommonTrackPoint _missionTrackPoint`

- `UICommonTrackPoint _battleTrapTrackPoint`

- `GameObject _panelEatBuff`

- `GameObject _panelEatActive`

- `CanvasGroup _panelEatNorm`

- `GameObject _panelEatTimeOut`

- `Button _eatBtn`

- `Image _eatBuffIcon`

- `CanvasGroup _panelBattleTrap`

- `GameObject _panelBattleTrapTimeOut`

- `Button _battleTrapBtn`

- `GameObject _noteTrackPoint`

- `Single _alphaTimeOutBtn`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `TrackPointViewProperty m_trackPointMission`

- `TrackPointViewProperty m_trackPointBattleTrap`


## Methods

- `Void _InitIfNot()`

- `Void OnClickEatBtn()`

- `Void OnClickBattleTrapBtn()`

- `Void OnClickMissionBtn()`

- `Void OnClickGachaBtn()`

- `Void OnClickQuest(String)`

- `Void OnClickNoteBtn()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideButtonGroupPlugin : TemplateActivityCommonPlugin
{
	private String m_actId; // 0x28
	private UICommonTrackPoint _missionTrackPoint; // 0x30
	private UICommonTrackPoint _battleTrapTrackPoint; // 0x38
	private GameObject _panelEatBuff; // 0x40
	private GameObject _panelEatActive; // 0x48
	private CanvasGroup _panelEatNorm; // 0x50
	private GameObject _panelEatTimeOut; // 0x58
	private Button _eatBtn; // 0x60
	private Image _eatBuffIcon; // 0x68
	private CanvasGroup _panelBattleTrap; // 0x70
	private GameObject _panelBattleTrapTimeOut; // 0x78
	private Button _battleTrapBtn; // 0x80
	private GameObject _noteTrackPoint; // 0x88
	private Single _alphaTimeOutBtn; // 0x90
	private Boolean m_isInited; // 0x94
	private UIPageFinder m_pageFinder; // 0x98
	private TrackPointViewProperty m_trackPointMission; // 0xa8
	private TrackPointViewProperty m_trackPointBattleTrap; // 0xb0
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnClickEatBtn; // 0x10
	private static DelegateBridge __Hotfix0_OnClickBattleTrapBtn; // 0x18
	private static DelegateBridge __Hotfix0_OnClickMissionBtn; // 0x20
	private static DelegateBridge __Hotfix0_OnClickGachaBtn; // 0x28
	private static DelegateBridge __Hotfix0_OnClickQuest; // 0x30
	private static DelegateBridge __Hotfix0_OnClickNoteBtn; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x329cf3c VA: 0x75958b4f3c
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x329d2b8 VA: 0x75958b52b8
	private Void _InitIfNot() { }
	// RVA: 0x329d384 VA: 0x75958b5384
	public Void OnClickEatBtn() { }
	// RVA: 0x329d498 VA: 0x75958b5498
	public Void OnClickBattleTrapBtn() { }
	// RVA: 0x329d598 VA: 0x75958b5598
	public Void OnClickMissionBtn() { }
	// RVA: 0x329d6c8 VA: 0x75958b56c8
	public Void OnClickGachaBtn() { }
	// RVA: 0x329d7b0 VA: 0x75958b57b0
	public Void OnClickQuest(String zoneId) { }
	// RVA: 0x329d8dc VA: 0x75958b58dc
	public Void OnClickNoteBtn() { }
	// RVA: 0x329da0c VA: 0x75958b5a0c
	public Void .ctor() { }
}
```