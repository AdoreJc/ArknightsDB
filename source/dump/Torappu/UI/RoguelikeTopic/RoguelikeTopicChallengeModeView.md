# RoguelikeTopicChallengeModeView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `UIAtlasImage _imgBkg`

- `GameObject _pnlNormal`

- `GameObject _pnlExploring`

- `RectTransform _transLogoHolder`

- `RectTransform _transCompleteProgressHolder`

- `RectTransform _toggleGroupHolder`

- `LoopPagePicker _picker`

- `RectTransform _challengeGroupHolder`

- `Image _imgExploringChallenge`

- `Text _textExploringChallengeName`

- `Text _textExploringChallengeDesc`

- `UIAtlasImage _imgExploringDeco`

- `UIAtlasImage _imgExploringChallengePrefix`

- `RectTransform _infoHolder`

- `RoguelikeTopicChallengePluginContext m_pluginContext`

- `Coroutine m_pageSwitchCoroutine`

- `RoguelikeTopicModeViewModel m_cachedModel`

- `String m_cachedChallengeId`

- `String m_cachedTopicId`

- `PickerDataSource m_pickerData`

- `RoguelikeTopicChallengeToggleGroup m_toggleGroup`

- `RoguelikeTopicChallengeProgress m_completeProgress`

- `RoguelikeTopicChallengeGroup m_challengeGroup`

- `RoguelikeTopicChallengeModeInfoViewBase m_infoView`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void _Render(RoguelikeTopicModeViewModel)`

- `Void EventOnPreChallenge()`

- `Void EventOnNextChallenge()`

- `Void _EventOnOpenRewardDetail()`

- `Void _EventChanllengeBeginChange(Int32)`

- `Void _EventChallengeGroupSwitch(Single)`

- `IEnumerator _SwitchToPage(Int32, Single)`

- `Void _StopPageSwitchCoroutine()`

- `Void <>xLuaBaseProxy_OnValueChanged(RoguelikeTopicModeViewProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicChallengeModeView : RoguelikeTopicSubView
{
	private UIAtlasImage _imgBkg; // 0x28
	private GameObject _pnlNormal; // 0x30
	private GameObject _pnlExploring; // 0x38
	private RectTransform _transLogoHolder; // 0x40
	private RectTransform _transCompleteProgressHolder; // 0x48
	private RectTransform _toggleGroupHolder; // 0x50
	private LoopPagePicker _picker; // 0x58
	private RectTransform _challengeGroupHolder; // 0x60
	private Image _imgExploringChallenge; // 0x68
	private Text _textExploringChallengeName; // 0x70
	private Text _textExploringChallengeDesc; // 0x78
	private UIAtlasImage _imgExploringDeco; // 0x80
	private UIAtlasImage _imgExploringChallengePrefix; // 0x88
	private RectTransform _infoHolder; // 0x90
	private RoguelikeTopicChallengePluginContext m_pluginContext; // 0x98
	private Coroutine m_pageSwitchCoroutine; // 0xa0
	private RoguelikeTopicModeViewModel m_cachedModel; // 0xa8
	private String m_cachedChallengeId; // 0xb0
	private String m_cachedTopicId; // 0xb8
	private PickerDataSource m_pickerData; // 0xc0
	private RoguelikeTopicChallengeToggleGroup m_toggleGroup; // 0xc8
	private RoguelikeTopicChallengeProgress m_completeProgress; // 0xd0
	private RoguelikeTopicChallengeGroup m_challengeGroup; // 0xd8
	private RoguelikeTopicChallengeModeInfoViewBase m_infoView; // 0xe0
	private Boolean m_hasInited; // 0xe8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__Render; // 0x10
	private static DelegateBridge __Hotfix0__LoadExploringChallengeThumbnail; // 0x18
	private static DelegateBridge __Hotfix0_EventOnPreChallenge; // 0x20
	private static DelegateBridge __Hotfix0_EventOnNextChallenge; // 0x28
	private static DelegateBridge __Hotfix0__EventOnOpenRewardDetail; // 0x30
	private static DelegateBridge __Hotfix0__EventChanllengeBeginChange; // 0x38
	private static DelegateBridge __Hotfix0__EventChallengeGroupSwitch; // 0x40
	private static DelegateBridge __Hotfix0__SwitchToPage; // 0x48
	private static DelegateBridge __Hotfix0__StopPageSwitchCoroutine; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x2649c70 VA: 0x7594c61c70
	private Void _InitIfNot() { }
	// RVA: 0x264a560 VA: 0x7594c62560
	public override Void OnValueChanged(RoguelikeTopicModeViewProperty property) { }
	// RVA: 0x264a6c8 VA: 0x7594c626c8
	private Void _Render(RoguelikeTopicModeViewModel model) { }
	// RVA: 0x264af94 VA: 0x7594c62f94
	private static Sprite _LoadExploringChallengeThumbnail(String topicId, String challengeId) { }
	// RVA: 0x264b03c VA: 0x7594c6303c
	public Void EventOnPreChallenge() { }
	// RVA: 0x264b0b0 VA: 0x7594c630b0
	public Void EventOnNextChallenge() { }
	// RVA: 0x264b124 VA: 0x7594c63124
	private Void _EventOnOpenRewardDetail() { }
	// RVA: 0x264b1bc VA: 0x7594c631bc
	private Void _EventChanllengeBeginChange(Int32 selectIdx) { }
	// RVA: 0x264b324 VA: 0x7594c63324
	private Void _EventChallengeGroupSwitch(Single perPageSwitchDur) { }
	// RVA: 0x264b52c VA: 0x7594c6352c
	private IEnumerator _SwitchToPage(Int32 switchPageCount, Single perPageSwitchDur) { }
	// RVA: 0x264b478 VA: 0x7594c63478
	private Void _StopPageSwitchCoroutine() { }
	// RVA: 0x264b630 VA: 0x7594c63630
	public Void .ctor() { }
	// RVA: 0x264b6a0 VA: 0x7594c636a0
	private Void <>xLuaBaseProxy_OnValueChanged(RoguelikeTopicModeViewProperty P0) { }
}
```