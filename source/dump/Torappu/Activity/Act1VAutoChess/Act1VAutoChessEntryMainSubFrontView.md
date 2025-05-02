# Act1VAutoChessEntryMainSubFrontView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `GameObject _trackpointDotPrefab`

- `GameObject _trackpointWordPrefab`

- `RectTransform _topMenuContainer`

- `GameObject _tutorialOnly_shopButton`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `Act1VAutoChessEntryMainViewModel m_cachedViewModel`


## Methods

- `Void EventOnClickedStartGameBtn()`

- `Void EventOnClickedQuitGameBtn()`

- `Void EventOnClickedChessPoolBtn()`

- `Void EventOnClickedTeamInfoBtn()`

- `Void EventOnClickedModeChoiceBtn()`

- `Void EventOnClickDailyBtn()`

- `Void EventOnClickRewardRuleBtn()`

- `Void EventOnClickMissionBtn()`

- `Void EventOnClickMilestoneBtn()`

- `Void EventOnClickMedalBtn()`

- `Void EventOnClickChessShopLockHint()`

- `Void _EventOnClickReturnBtn()`

- `Void _InitIfNot()`

- `GameObject _InstantiateTrackPointObj(TrackPointType, Transform)`

- `Void <>xLuaBaseProxy_Render(Act1VAutoChessEntryBaseSubViewModel)`

- `Void <>xLuaBaseProxy_TutorialOnlyRegisterTutorialGo()`

- `Void <>xLuaBaseProxy_EntrySubViewRouted()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryMainSubFrontView : Act1VAutoChessBaseSubView
{
	private List`1 _viewComponents; // 0x18
	private GameObject _trackpointDotPrefab; // 0x20
	private GameObject _trackpointWordPrefab; // 0x28
	private RectTransform _topMenuContainer; // 0x30
	private GameObject _tutorialOnly_shopButton; // 0x38
	private Boolean m_isInited; // 0x40
	private UIPageFinder m_pageFinder; // 0x48
	private Act1VAutoChessEntryMainViewModel m_cachedViewModel; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_TutorialOnlyRegisterTutorialGo; // 0x8
	private static DelegateBridge __Hotfix0_EntrySubViewRouted; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClickedStartGameBtn; // 0x18
	private static DelegateBridge __Hotfix0_EventOnClickedQuitGameBtn; // 0x20
	private static DelegateBridge __Hotfix0_EventOnClickedChessPoolBtn; // 0x28
	private static DelegateBridge __Hotfix0_EventOnClickedTeamInfoBtn; // 0x30
	private static DelegateBridge __Hotfix0_EventOnClickedModeChoiceBtn; // 0x38
	private static DelegateBridge __Hotfix0_EventOnClickDailyBtn; // 0x40
	private static DelegateBridge __Hotfix0_EventOnClickRewardRuleBtn; // 0x48
	private static DelegateBridge __Hotfix0_EventOnClickMissionBtn; // 0x50
	private static DelegateBridge __Hotfix0_EventOnClickMilestoneBtn; // 0x58
	private static DelegateBridge __Hotfix0_EventOnClickMedalBtn; // 0x60
	private static DelegateBridge __Hotfix0_EventOnClickChessShopLockHint; // 0x68
	private static DelegateBridge __Hotfix0__EventOnClickReturnBtn; // 0x70
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x78
	private static DelegateBridge __Hotfix0__InstantiateTrackPointObj; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88


	// RVA: 0x333e500 VA: 0x7595956500
	public override Void Render(Act1VAutoChessEntryBaseSubViewModel subViewModel) { }
	// RVA: 0x333e9bc VA: 0x75959569bc
	public override Void TutorialOnlyRegisterTutorialGo() { }
	// RVA: 0x333eaac VA: 0x7595956aac
	public override Void EntrySubViewRouted() { }
	// RVA: 0x333eb10 VA: 0x7595956b10
	public Void EventOnClickedStartGameBtn() { }
	// RVA: 0x333ebf4 VA: 0x7595956bf4
	public Void EventOnClickedQuitGameBtn() { }
	// RVA: 0x333eca8 VA: 0x7595956ca8
	public Void EventOnClickedChessPoolBtn() { }
	// RVA: 0x333ed5c VA: 0x7595956d5c
	public Void EventOnClickedTeamInfoBtn() { }
	// RVA: 0x333ee10 VA: 0x7595956e10
	public Void EventOnClickedModeChoiceBtn() { }
	// RVA: 0x333eef4 VA: 0x7595956ef4
	public Void EventOnClickDailyBtn() { }
	// RVA: 0x333efa8 VA: 0x7595956fa8
	public Void EventOnClickRewardRuleBtn() { }
	// RVA: 0x333f05c VA: 0x759595705c
	public Void EventOnClickMissionBtn() { }
	// RVA: 0x333f110 VA: 0x7595957110
	public Void EventOnClickMilestoneBtn() { }
	// RVA: 0x333f1c4 VA: 0x75959571c4
	public Void EventOnClickMedalBtn() { }
	// RVA: 0x333f278 VA: 0x7595957278
	public Void EventOnClickChessShopLockHint() { }
	// RVA: 0x333f314 VA: 0x7595957314
	private Void _EventOnClickReturnBtn() { }
	// RVA: 0x333e6f0 VA: 0x75959566f0
	private Void _InitIfNot() { }
	// RVA: 0x333f44c VA: 0x759595744c
	private GameObject _InstantiateTrackPointObj(TrackPointType trackPointType, Transform container) { }
	// RVA: 0x333f598 VA: 0x7595957598
	public Void .ctor() { }
	// RVA: 0x333f604 VA: 0x7595957604
	private Void <>xLuaBaseProxy_Render(Act1VAutoChessEntryBaseSubViewModel P0) { }
	// RVA: 0x333f608 VA: 0x7595957608
	private Void <>xLuaBaseProxy_TutorialOnlyRegisterTutorialGo() { }
	// RVA: 0x333f60c VA: 0x759595760c
	private Void <>xLuaBaseProxy_EntrySubViewRouted() { }
}
```