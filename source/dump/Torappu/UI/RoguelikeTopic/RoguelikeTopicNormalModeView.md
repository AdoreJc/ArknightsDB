# RoguelikeTopicNormalModeView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RoguelikeTopicCurrentDifficultyBaseView _currentDiffView`

- `GameObject _bankEntryGo`

- `GameObject _bankNewGo`

- `Text _textBankCurrent`

- `Text _textOuterBuffTokenCurrent`

- `GameObject _pnlOuterBuffPrepared`

- `GameObject _pnlMonthTask`

- `GameObject _pnlMonthTaskRefresh`

- `GameObject _trackpointMonthTask`

- `Text _textMonthTaskRefresh`

- `GameObject _trackpointArchive`

- `RoguelikeTopicOuterBuffDataUtilBase _outerbuffUtil`

- `RoguelikeTopicNormalModeViewPlugin _plugin`

- `Text _textOuterBuffPrepared`

- `RectTransform _rogueActivityEntryCompContent`

- `RoguelikeTopicModeViewProperty m_exploreProp`

- `RoguelikeTopicActivityEntryComp m_activityEntryComp`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _InitProp()`

- `Void _InitActivityEntryComp()`

- `Void _OnDiffDetailShow()`

- `Void _RefreshMonthTaskInfo(RoguelikeTopicModeViewModel, String)`

- `Void _RefreshArchiveInfo(RoguelikeTopicModeViewModel)`

- `Void _OnOpenActivityState()`

- `Void EventOnOpenCollection()`

- `Void EventOnOpenMonthTaskDetail()`

- `Void EventOnOpenOuterBuff()`

- `Void EventOnBank()`

- `Void EventOnMedalClicked()`

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_OnValueChanged(RoguelikeTopicModeViewProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicNormalModeView : RoguelikeTopicSubView
{
	private RoguelikeTopicCurrentDifficultyBaseView _currentDiffView; // 0x28
	private GameObject _bankEntryGo; // 0x30
	private GameObject _bankNewGo; // 0x38
	private Text _textBankCurrent; // 0x40
	private Text _textOuterBuffTokenCurrent; // 0x48
	private GameObject _pnlOuterBuffPrepared; // 0x50
	private GameObject _pnlMonthTask; // 0x58
	private GameObject _pnlMonthTaskRefresh; // 0x60
	private GameObject _trackpointMonthTask; // 0x68
	private Text _textMonthTaskRefresh; // 0x70
	private GameObject _trackpointArchive; // 0x78
	private RoguelikeTopicOuterBuffDataUtilBase _outerbuffUtil; // 0x80
	private RoguelikeTopicNormalModeViewPlugin _plugin; // 0x88
	private Text _textOuterBuffPrepared; // 0x90
	private RectTransform _rogueActivityEntryCompContent; // 0x98
	private RoguelikeTopicModeViewProperty m_exploreProp; // 0xa0
	private RoguelikeTopicActivityEntryComp m_activityEntryComp; // 0xa8
	private UIPageFinder m_pageFinder; // 0xb0
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__InitProp; // 0x10
	private static DelegateBridge __Hotfix0__InitActivityEntryComp; // 0x18
	private static DelegateBridge __Hotfix0__OnDiffDetailShow; // 0x20
	private static DelegateBridge __Hotfix0__RefreshMonthTaskInfo; // 0x28
	private static DelegateBridge __Hotfix0__RefreshArchiveInfo; // 0x30
	private static DelegateBridge __Hotfix0__OnOpenActivityState; // 0x38
	private static DelegateBridge __Hotfix0_EventOnOpenCollection; // 0x40
	private static DelegateBridge __Hotfix0_EventOnOpenMonthTaskDetail; // 0x48
	private static DelegateBridge __Hotfix0_EventOnOpenOuterBuff; // 0x50
	private static DelegateBridge __Hotfix0_EventOnBank; // 0x58
	private static DelegateBridge __Hotfix0_EventOnMedalClicked; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x2651590 VA: 0x7594c69590
	protected override Void OnInit() { }
	// RVA: 0x26519e0 VA: 0x7594c699e0
	public override Void OnValueChanged(RoguelikeTopicModeViewProperty property) { }
	// RVA: 0x2651664 VA: 0x7594c69664
	private Void _InitProp() { }
	// RVA: 0x2651724 VA: 0x7594c69724
	private Void _InitActivityEntryComp() { }
	// RVA: 0x2652088 VA: 0x7594c6a088
	private Void _OnDiffDetailShow() { }
	// RVA: 0x2651cf0 VA: 0x7594c69cf0
	private Void _RefreshMonthTaskInfo(RoguelikeTopicModeViewModel model, String topicId) { }
	// RVA: 0x2651ffc VA: 0x7594c69ffc
	private Void _RefreshArchiveInfo(RoguelikeTopicModeViewModel model) { }
	// RVA: 0x26521ac VA: 0x7594c6a1ac
	private Void _OnOpenActivityState() { }
	// RVA: 0x2652244 VA: 0x7594c6a244
	public Void EventOnOpenCollection() { }
	// RVA: 0x26522dc VA: 0x7594c6a2dc
	public Void EventOnOpenMonthTaskDetail() { }
	// RVA: 0x26523a0 VA: 0x7594c6a3a0
	public Void EventOnOpenOuterBuff() { }
	// RVA: 0x2652438 VA: 0x7594c6a438
	public Void EventOnBank() { }
	// RVA: 0x26524e4 VA: 0x7594c6a4e4
	public Void EventOnMedalClicked() { }
	// RVA: 0x265257c VA: 0x7594c6a57c
	public Void .ctor() { }
	// RVA: 0x26525ec VA: 0x7594c6a5ec
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x26525f4 VA: 0x7594c6a5f4
	private Void <>xLuaBaseProxy_OnValueChanged(RoguelikeTopicModeViewProperty P0) { }
}
```