# RL02DifficultySelectView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL02`


## Fields

- `UIFadeFloatPanel _fadePanel`

- `UIFullScreenImage _background`

- `GameObject _hardTips`

- `GameObject _extremeHardTips`

- `InertiaScrollViewPager _wheelPager`

- `UIRecycleLayoutGroup _content`

- `Transform _unlockitemsRoot`

- `RL02DifficultyItem _itemPrefab`

- `Text _bpNum`

- `Text _bossNum`

- `GameObject _addRoot`

- `Image _selectBar`

- `Image _selectHardBar`

- `Image _titleImage`

- `Button _nextBtn`

- `Button _preBtn`

- `RL02DifficultyAdditionalDetailView _addDetailView`

- `UIAnimationLocation _dragAnim`

- `PagerAdapter m_pagerAdapter`

- `RoguelikeTopicModeViewModel m_exploreModel`

- `RL02ModeViewExtModel m_extModel`

- `Boolean m_draging`

- `Int32 m_currentShowIdx`


## Methods

- `Void _OnScrollPagerStateChanged(State)`

- `Void _OnPageChangeEnd(Int32)`

- `Void _OnScrollingStateChanged(Boolean)`

- `Void _UpdateSelectDifficulty(Int32)`

- `Void _UpdateWarning(RoguelikeTopicDifficultyWarningType, Color)`

- `Void _CleanRT()`

- `Void Update()`

- `Int32 _ResumeCurrentSelected()`

- `Void OnDisable()`

- `Void EventOnNext()`

- `Void EventOnPre()`

- `Void EventOnConfirm()`

- `Void EventShowAddDetail()`

- `Void _EventOnMoveTo(Int32)`

- `Void _UpdateBtnState()`

- `Void _RebuildLockedItems(RoguelikeTopicModeViewModel, Int32)`

- `Void <>xLuaBaseProxy_SetVisible(Boolean, Boolean)`

- `Void <>xLuaBaseProxy_OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL02
public class RL02DifficultySelectView : RoguelikeTopicDifficultySelectBaseView
{
	private UIFadeFloatPanel _fadePanel; // 0x30
	private UIFullScreenImage _background; // 0x38
	private GameObject _hardTips; // 0x40
	private GameObject _extremeHardTips; // 0x48
	private InertiaScrollViewPager _wheelPager; // 0x50
	private UIRecycleLayoutGroup _content; // 0x58
	private Transform _unlockitemsRoot; // 0x60
	private RL02DifficultyItem _itemPrefab; // 0x68
	private UIFadeFloatPanel[] _hideInDraging; // 0x70
	private Text _bpNum; // 0x78
	private Text _bossNum; // 0x80
	private GameObject _addRoot; // 0x88
	private Image _selectBar; // 0x90
	private Image _selectHardBar; // 0x98
	private Image _titleImage; // 0xa0
	private TitleSprite[] _titles; // 0xa8
	private Button _nextBtn; // 0xb0
	private Button _preBtn; // 0xb8
	private RL02DifficultyAdditionalDetailView _addDetailView; // 0xc0
	private UIAnimationLocation _dragAnim; // 0xc8
	private PagerAdapter m_pagerAdapter; // 0xd8
	private RoguelikeTopicModeViewModel m_exploreModel; // 0xe0
	private RL02ModeViewExtModel m_extModel; // 0xe8
	private Boolean m_draging; // 0xf0
	private Int32 m_currentShowIdx; // 0xf4
	private static DelegateBridge __Hotfix0_OnRefresh; // 0x0
	private static DelegateBridge __Hotfix0__OnScrollPagerStateChanged; // 0x8
	private static DelegateBridge __Hotfix0__OnPageChangeEnd; // 0x10
	private static DelegateBridge __Hotfix0__OnScrollingStateChanged; // 0x18
	private static DelegateBridge __Hotfix0__UpdateSelectDifficulty; // 0x20
	private static DelegateBridge __Hotfix0__UpdateWarning; // 0x28
	private static DelegateBridge __Hotfix0_SetVisible; // 0x30
	private static DelegateBridge __Hotfix0__CleanRT; // 0x38
	private static DelegateBridge __Hotfix0_OnInit; // 0x40
	private static DelegateBridge __Hotfix0_Update; // 0x48
	private static DelegateBridge __Hotfix0__ResumeCurrentSelected; // 0x50
	private static DelegateBridge __Hotfix0_OnDisable; // 0x58
	private static DelegateBridge __Hotfix0_EventOnNext; // 0x60
	private static DelegateBridge __Hotfix0_EventOnPre; // 0x68
	private static DelegateBridge __Hotfix0_EventOnConfirm; // 0x70
	private static DelegateBridge __Hotfix0_EventShowAddDetail; // 0x78
	private static DelegateBridge __Hotfix0__EventOnMoveTo; // 0x80
	private static DelegateBridge __Hotfix0__UpdateBtnState; // 0x88
	private static DelegateBridge __Hotfix0__RebuildLockedItems; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98


	// RVA: 0x26b6c28 VA: 0x7594ccec28
	protected override Void OnRefresh(RoguelikeTopicModeViewProperty property) { }
	// RVA: 0x26b7534 VA: 0x7594ccf534
	private Void _OnScrollPagerStateChanged(State state) { }
	// RVA: 0x26b748c VA: 0x7594ccf48c
	private Void _OnPageChangeEnd(Int32 itemIndex) { }
	// RVA: 0x26b75f0 VA: 0x7594ccf5f0
	private Void _OnScrollingStateChanged(Boolean isDraging) { }
	// RVA: 0x26b7890 VA: 0x7594ccf890
	private Void _UpdateSelectDifficulty(Int32 selectIdx) { }
	// RVA: 0x26b7c38 VA: 0x7594ccfc38
	private Void _UpdateWarning(RoguelikeTopicDifficultyWarningType warningType, Color mainColor) { }
	// RVA: 0x26b7d78 VA: 0x7594ccfd78
	protected override Void SetVisible(Boolean v, Boolean immediately) { }
	// RVA: 0x26b80c8 VA: 0x7594cd00c8
	private Void _CleanRT() { }
	// RVA: 0x26b8220 VA: 0x7594cd0220
	protected override Void OnInit() { }
	// RVA: 0x26b83bc VA: 0x7594cd03bc
	private Void Update() { }
	// RVA: 0x26b7f4c VA: 0x7594ccff4c
	private Int32 _ResumeCurrentSelected() { }
	// RVA: 0x26b852c VA: 0x7594cd052c
	private Void OnDisable() { }
	// RVA: 0x26b8594 VA: 0x7594cd0594
	public Void EventOnNext() { }
	// RVA: 0x26b865c VA: 0x7594cd065c
	public Void EventOnPre() { }
	// RVA: 0x26b8708 VA: 0x7594cd0708
	public Void EventOnConfirm() { }
	// RVA: 0x26b8824 VA: 0x7594cd0824
	public Void EventShowAddDetail() { }
	// RVA: 0x26b8934 VA: 0x7594cd0934
	private Void _EventOnMoveTo(Int32 index) { }
	// RVA: 0x26b7b60 VA: 0x7594ccfb60
	private Void _UpdateBtnState() { }
	// RVA: 0x26b725c VA: 0x7594ccf25c
	private Void _RebuildLockedItems(RoguelikeTopicModeViewModel viewModel, Int32 unlockedCnt) { }
	// RVA: 0x26b89ec VA: 0x7594cd09ec
	public Void .ctor() { }
	// RVA: 0x26b8a64 VA: 0x7594cd0a64
	private Void <>xLuaBaseProxy_SetVisible(Boolean P0, Boolean P1) { }
	// RVA: 0x26b8a74 VA: 0x7594cd0a74
	private Void <>xLuaBaseProxy_OnInit() { }
}
```