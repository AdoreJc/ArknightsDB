# RoguelikeTopicMonthModeViewWithTask

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `GameObject _pnlAwardReceived`

- `GameObject _pnlAwardNotReceived`

- `RectTransform _itemIconHolder`

- `GameObject _pnlMore`

- `Image _imgIconBp`

- `EasyInstancePool _togglePool`

- `Button _btnLeft`

- `Button _btnRight`

- `Image _rarityImg`

- `Image _professionImg`

- `Text _charName`

- `Text _textDesc`

- `Text _textTeamDescIndex`

- `Text _textTeamName`

- `Text _textTeamSubName`

- `Text _textTeamFlavorDesc`

- `GameObject _panelTask`

- `Text _taskDesc`

- `RectTransform _rectProgress`

- `UIColorGraphic _imgTaskBkg`

- `Vector2 _progressBarLength`

- `Single _rewardItemScale`

- `Color _taskBkgColorIncomplete`

- `Color _taskBkgColorComplete`

- `RectTransform _charIllustHolder`

- `UIAnimationLocation _animSwitch`

- `RoguelikeTopicModeViewModel m_cachedModeViewModel`

- `RoguelikeTopicMonthSquadModel m_cachedMonthSquadModel`

- `RoguelikeTopicMonthSquadTeamChar m_cachedMonthCharModel`

- `String m_cachedTopicId`

- `String m_cachedCurrMonthTeamId`

- `UIItemCard m_itemCard`

- `GameObject m_charIllust`

- `Tween m_tween`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _Render(RoguelikeTopicModeViewModel)`

- `Void _UpdateMonthSquadTaskView()`

- `Void _UpdateMonthSquadView()`

- `Void _RenderToggleGroup(RoguelikeTopicMonthSquadViewModel)`

- `Void _LoadRewardItemIcon(ItemBundle)`

- `Void _LoadCharIllust(CharQuery)`

- `Void EventOnOpenArchive()`

- `Void EventOnOpenRewardDetail()`

- `Void EventOnBtnLeftClicked()`

- `Void EventOnBtnRightClicked()`

- `Void OnBtnCharPortraitClicked()`

- `Void <>xLuaBaseProxy_OnValueChanged(RoguelikeTopicModeViewProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicMonthModeViewWithTask : RoguelikeTopicSubView
{
	private const String TASK_INCOMPLETE_FORMAT; // 0x0
	private GameObject _pnlAwardReceived; // 0x28
	private GameObject _pnlAwardNotReceived; // 0x30
	private RectTransform _itemIconHolder; // 0x38
	private GameObject _pnlMore; // 0x40
	private Image _imgIconBp; // 0x48
	private EasyInstancePool _togglePool; // 0x50
	private Button _btnLeft; // 0x58
	private Button _btnRight; // 0x60
	private Image _rarityImg; // 0x68
	private Image _professionImg; // 0x70
	private Text _charName; // 0x78
	private Text _textDesc; // 0x80
	private Text _textTeamDescIndex; // 0x88
	private Text _textTeamName; // 0x90
	private Text _textTeamSubName; // 0x98
	private Text _textTeamFlavorDesc; // 0xa0
	private GameObject _panelTask; // 0xa8
	private Text _taskDesc; // 0xb0
	private RectTransform _rectProgress; // 0xb8
	private UIColorGraphic _imgTaskBkg; // 0xc0
	private Vector2 _progressBarLength; // 0xc8
	private Single _rewardItemScale; // 0xd0
	private Color _taskBkgColorIncomplete; // 0xd4
	private Color _taskBkgColorComplete; // 0xe4
	private RectTransform _charIllustHolder; // 0xf8
	private UIAnimationLocation _animSwitch; // 0x100
	private RoguelikeTopicModeViewModel m_cachedModeViewModel; // 0x110
	private RoguelikeTopicMonthSquadModel m_cachedMonthSquadModel; // 0x118
	private RoguelikeTopicMonthSquadTeamChar m_cachedMonthCharModel; // 0x120
	private String m_cachedTopicId; // 0x128
	private String m_cachedCurrMonthTeamId; // 0x130
	private UIItemCard m_itemCard; // 0x138
	private GameObject m_charIllust; // 0x140
	private Tween m_tween; // 0x148
	private UIPageFinder m_pageFinder; // 0x150
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__Render; // 0x8
	private static DelegateBridge __Hotfix0__UpdateMonthSquadTaskView; // 0x10
	private static DelegateBridge __Hotfix0__UpdateMonthSquadView; // 0x18
	private static DelegateBridge __Hotfix0__RenderToggleGroup; // 0x20
	private static DelegateBridge __Hotfix0__LoadRewardItemIcon; // 0x28
	private static DelegateBridge __Hotfix0__LoadCharIllust; // 0x30
	private static DelegateBridge __Hotfix0_EventOnOpenArchive; // 0x38
	private static DelegateBridge __Hotfix0_EventOnOpenRewardDetail; // 0x40
	private static DelegateBridge __Hotfix0_EventOnBtnLeftClicked; // 0x48
	private static DelegateBridge __Hotfix0_EventOnBtnRightClicked; // 0x50
	private static DelegateBridge __Hotfix0_OnBtnCharPortraitClicked; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x2653f10 VA: 0x7594c6bf10
	public override Void OnValueChanged(RoguelikeTopicModeViewProperty property) { }
	// RVA: 0x2653fc8 VA: 0x7594c6bfc8
	private Void _Render(RoguelikeTopicModeViewModel modeViewModel) { }
	// RVA: 0x26547ec VA: 0x7594c6c7ec
	private Void _UpdateMonthSquadTaskView() { }
	// RVA: 0x2654338 VA: 0x7594c6c338
	private Void _UpdateMonthSquadView() { }
	// RVA: 0x2654a74 VA: 0x7594c6ca74
	private Void _RenderToggleGroup(RoguelikeTopicMonthSquadViewModel monthSquadGroup) { }
	// RVA: 0x2654c58 VA: 0x7594c6cc58
	private Void _LoadRewardItemIcon(ItemBundle itemData) { }
	// RVA: 0x2654ef4 VA: 0x7594c6cef4
	private Void _LoadCharIllust(CharQuery charQuery) { }
	// RVA: 0x2655164 VA: 0x7594c6d164
	public Void EventOnOpenArchive() { }
	// RVA: 0x2655330 VA: 0x7594c6d330
	public Void EventOnOpenRewardDetail() { }
	// RVA: 0x26553c8 VA: 0x7594c6d3c8
	public Void EventOnBtnLeftClicked() { }
	// RVA: 0x2655464 VA: 0x7594c6d464
	public Void EventOnBtnRightClicked() { }
	// RVA: 0x2655500 VA: 0x7594c6d500
	public Void OnBtnCharPortraitClicked() { }
	// RVA: 0x2655614 VA: 0x7594c6d614
	public Void .ctor() { }
	// RVA: 0x2655690 VA: 0x7594c6d690
	private Void <>xLuaBaseProxy_OnValueChanged(RoguelikeTopicModeViewProperty P0) { }
}
```