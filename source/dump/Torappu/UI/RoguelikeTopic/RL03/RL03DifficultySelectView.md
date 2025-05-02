# RL03DifficultySelectView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `UIFadeFloatPanel _fadePanel`

- `UIFullScreenImage _background`

- `GameObject _hardTips`

- `InertiaScrollViewPager _wheelPager`

- `UIRecycleLayoutGroup _content`

- `Transform _unlockitemsRoot`

- `RL03DifficultyItem _itemPrefab`

- `Image _selectBar`

- `Image _titleImage`

- `RL03DifficultySelectLeftView _leftView`

- `UIAnimationLocation _dragAnim`

- `RL03DifficultyAdditionalDetailView _addDetailView`

- `RL03DifficultyRulesView _rulesView`

- `TwoStateToggle _viewMode`

- `PagerAdapter m_pagerAdapter`

- `RoguelikeTopicModeViewModel m_exploreModel`

- `RL03ModeViewExtModel m_extModel`

- `Boolean m_draging`

- `Int32 m_currentShowIdx`

- `Coroutine m_hideCo`


## Methods

- `Void _OnScrollPagerStateChanged(State)`

- `Void _OnPageChangeEnd(Int32)`

- `Void _OnScrollingStateChanged(Boolean)`

- `Void _UpdateSelectDifficulty(Int32, Boolean)`

- `IEnumerator _DoHide()`

- `Void _CleanRT()`

- `Void Update()`

- `Int32 _ResumeCurrentSelected()`

- `Void OnDestroy()`

- `Void EventOnConfirm()`

- `Void _EventOnMoveTo(Int32)`

- `Void _EventOpenOuterBuff()`

- `Void _EventOnOpenCollection()`

- `Void _RebuildLockedItems(RoguelikeTopicModeViewModel, Int32)`

- `Sprite _GetBuffIcon(String)`

- `Void <>xLuaBaseProxy_SetVisible(Boolean, Boolean)`

- `Void <>xLuaBaseProxy_OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class RL03DifficultySelectView : RoguelikeTopicDifficultySelectBaseView
{
	private UIFadeFloatPanel _fadePanel; // 0x30
	private UIFullScreenImage _background; // 0x38
	private GameObject _hardTips; // 0x40
	private InertiaScrollViewPager _wheelPager; // 0x48
	private UIRecycleLayoutGroup _content; // 0x50
	private Transform _unlockitemsRoot; // 0x58
	private RL03DifficultyItem _itemPrefab; // 0x60
	private UIFadeFloatPanel[] _hideInDraging; // 0x68
	private Image _selectBar; // 0x70
	private Image _titleImage; // 0x78
	private TitleSprite[] _titles; // 0x80
	private RL03DifficultySelectLeftView _leftView; // 0x88
	private UIAnimationLocation _dragAnim; // 0x90
	private RL03DifficultyAdditionalDetailView _addDetailView; // 0xa0
	private RL03DifficultyRulesView _rulesView; // 0xa8
	private Sprite[] _buffIconSprites; // 0xb0
	private TwoStateToggle _viewMode; // 0xb8
	private PagerAdapter m_pagerAdapter; // 0xc0
	private RoguelikeTopicModeViewModel m_exploreModel; // 0xc8
	private RL03ModeViewExtModel m_extModel; // 0xd0
	private Boolean m_draging; // 0xd8
	private Int32 m_currentShowIdx; // 0xdc
	private Coroutine m_hideCo; // 0xe0
	private static DelegateBridge __Hotfix0_OnRefresh; // 0x0
	private static DelegateBridge __Hotfix0__OnScrollPagerStateChanged; // 0x8
	private static DelegateBridge __Hotfix0__OnPageChangeEnd; // 0x10
	private static DelegateBridge __Hotfix0__OnScrollingStateChanged; // 0x18
	private static DelegateBridge __Hotfix0__UpdateSelectDifficulty; // 0x20
	private static DelegateBridge __Hotfix0_SetVisible; // 0x28
	private static DelegateBridge __Hotfix0__DoHide; // 0x30
	private static DelegateBridge __Hotfix0__CleanRT; // 0x38
	private static DelegateBridge __Hotfix0_OnInit; // 0x40
	private static DelegateBridge __Hotfix0_Update; // 0x48
	private static DelegateBridge __Hotfix0__ResumeCurrentSelected; // 0x50
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x58
	private static DelegateBridge __Hotfix0_EventOnConfirm; // 0x60
	private static DelegateBridge __Hotfix0__EventOnMoveTo; // 0x68
	private static DelegateBridge __Hotfix0__EventOpenOuterBuff; // 0x70
	private static DelegateBridge __Hotfix0__EventOnOpenCollection; // 0x78
	private static DelegateBridge __Hotfix0__RebuildLockedItems; // 0x80
	private static DelegateBridge __Hotfix0__GetBuffIcon; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90


	// RVA: 0x26a3138 VA: 0x7594cbb138
	protected override Void OnRefresh(RoguelikeTopicModeViewProperty property) { }
	// RVA: 0x26a3b18 VA: 0x7594cbbb18
	private Void _OnScrollPagerStateChanged(State state) { }
	// RVA: 0x26a3a74 VA: 0x7594cbba74
	private Void _OnPageChangeEnd(Int32 itemIndex) { }
	// RVA: 0x26a3bd4 VA: 0x7594cbbbd4
	private Void _OnScrollingStateChanged(Boolean isDraging) { }
	// RVA: 0x26a3e78 VA: 0x7594cbbe78
	private Void _UpdateSelectDifficulty(Int32 selectIdx, Boolean immediately) { }
	// RVA: 0x26a40d8 VA: 0x7594cbc0d8
	protected override Void SetVisible(Boolean v, Boolean immediately) { }
	// RVA: 0x26a44e8 VA: 0x7594cbc4e8
	private IEnumerator _DoHide() { }
	// RVA: 0x26a45bc VA: 0x7594cbc5bc
	private Void _CleanRT() { }
	// RVA: 0x26a4714 VA: 0x7594cbc714
	protected override Void OnInit() { }
	// RVA: 0x26a49f4 VA: 0x7594cbc9f4
	private Void Update() { }
	// RVA: 0x26a436c VA: 0x7594cbc36c
	private Int32 _ResumeCurrentSelected() { }
	// RVA: 0x26a4b68 VA: 0x7594cbcb68
	private Void OnDestroy() { }
	// RVA: 0x26a4bd0 VA: 0x7594cbcbd0
	public Void EventOnConfirm() { }
	// RVA: 0x26a4cec VA: 0x7594cbccec
	private Void _EventOnMoveTo(Int32 index) { }
	// RVA: 0x26a4da4 VA: 0x7594cbcda4
	private Void _EventOpenOuterBuff() { }
	// RVA: 0x26a4e3c VA: 0x7594cbce3c
	private Void _EventOnOpenCollection() { }
	// RVA: 0x26a383c VA: 0x7594cbb83c
	private Void _RebuildLockedItems(RoguelikeTopicModeViewModel viewModel, Int32 unlockedCnt) { }
	// RVA: 0x26a4ed8 VA: 0x7594cbced8
	private Sprite _GetBuffIcon(String iconId) { }
	// RVA: 0x26a504c VA: 0x7594cbd04c
	public Void .ctor() { }
	// RVA: 0x26a50c4 VA: 0x7594cbd0c4
	private Void <>xLuaBaseProxy_SetVisible(Boolean P0, Boolean P1) { }
	// RVA: 0x26a50d4 VA: 0x7594cbd0d4
	private Void <>xLuaBaseProxy_OnInit() { }
}
```