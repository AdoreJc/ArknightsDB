# RL04DifficultySelectView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL04`


## Fields

- `UIFadeFloatPanel _fadePanel`

- `UIFullScreenImage _background`

- `InertiaScrollViewPager _wheelPager`

- `UIRecycleLayoutGroup _content`

- `Transform _unlockitemsRoot`

- `RL04DifficultyItem _itemPrefab`

- `RL04DifficultySelectLeftView _leftView`

- `UIAnimationLocation _dragAnim`

- `RL04DifficultyAdditionalDetailView _addDetailView`

- `RL04DifficultyRulesView _rulesView`

- `GameObject _topicActiveViewObj`

- `GameObject _modeViewGroup`

- `PagerAdapter m_pagerAdapter`

- `RoguelikeTopicModeViewModel m_exploreModel`

- `RL04ModeViewExtModel m_extModel`

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
// Namespace : Torappu.UI.RoguelikeTopic.RL04
public class RL04DifficultySelectView : RoguelikeTopicDifficultySelectBaseView
{
	private const String DIFFICULTY_ICON_FORMAT; // 0x0
	private UIFadeFloatPanel _fadePanel; // 0x30
	private UIFullScreenImage _background; // 0x38
	private InertiaScrollViewPager _wheelPager; // 0x40
	private UIRecycleLayoutGroup _content; // 0x48
	private Transform _unlockitemsRoot; // 0x50
	private RL04DifficultyItem _itemPrefab; // 0x58
	private UIFadeFloatPanel[] _hideInDraging; // 0x60
	private RL04DifficultySelectLeftView _leftView; // 0x68
	private UIAnimationLocation _dragAnim; // 0x70
	private RL04DifficultyAdditionalDetailView _addDetailView; // 0x80
	private RL04DifficultyRulesView _rulesView; // 0x88
	private Sprite[] _buffIconSprites; // 0x90
	private GameObject _topicActiveViewObj; // 0x98
	private GameObject _modeViewGroup; // 0xa0
	private List`1 _modeViewList; // 0xa8
	private PagerAdapter m_pagerAdapter; // 0xb0
	private RoguelikeTopicModeViewModel m_exploreModel; // 0xb8
	private RL04ModeViewExtModel m_extModel; // 0xc0
	private Boolean m_draging; // 0xc8
	private Int32 m_currentShowIdx; // 0xcc
	private Coroutine m_hideCo; // 0xd0
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


	// RVA: 0x26ec378 VA: 0x7594d04378
	protected override Void OnRefresh(RoguelikeTopicModeViewProperty property) { }
	// RVA: 0x26ecd78 VA: 0x7594d04d78
	private Void _OnScrollPagerStateChanged(State state) { }
	// RVA: 0x26eccd4 VA: 0x7594d04cd4
	private Void _OnPageChangeEnd(Int32 itemIndex) { }
	// RVA: 0x26ece34 VA: 0x7594d04e34
	private Void _OnScrollingStateChanged(Boolean isDraging) { }
	// RVA: 0x26ed0f0 VA: 0x7594d050f0
	private Void _UpdateSelectDifficulty(Int32 selectIdx, Boolean immediately) { }
	// RVA: 0x26ed2d4 VA: 0x7594d052d4
	protected override Void SetVisible(Boolean v, Boolean immediately) { }
	// RVA: 0x26ed6f0 VA: 0x7594d056f0
	private IEnumerator _DoHide() { }
	// RVA: 0x26ed7c4 VA: 0x7594d057c4
	private Void _CleanRT() { }
	// RVA: 0x26ed91c VA: 0x7594d0591c
	protected override Void OnInit() { }
	// RVA: 0x26edbfc VA: 0x7594d05bfc
	private Void Update() { }
	// RVA: 0x26ed568 VA: 0x7594d05568
	private Int32 _ResumeCurrentSelected() { }
	// RVA: 0x26edd70 VA: 0x7594d05d70
	private Void OnDestroy() { }
	// RVA: 0x26eddd8 VA: 0x7594d05dd8
	public Void EventOnConfirm() { }
	// RVA: 0x26edefc VA: 0x7594d05efc
	private Void _EventOnMoveTo(Int32 index) { }
	// RVA: 0x26edfb4 VA: 0x7594d05fb4
	private Void _EventOpenOuterBuff() { }
	// RVA: 0x26ee04c VA: 0x7594d0604c
	private Void _EventOnOpenCollection() { }
	// RVA: 0x26ecaa0 VA: 0x7594d04aa0
	private Void _RebuildLockedItems(RoguelikeTopicModeViewModel viewModel, Int32 unlockedCnt) { }
	// RVA: 0x26ee0e8 VA: 0x7594d060e8
	private Sprite _GetBuffIcon(String buffId) { }
	// RVA: 0x26ee298 VA: 0x7594d06298
	public Void .ctor() { }
	// RVA: 0x26ee310 VA: 0x7594d06310
	private Void <>xLuaBaseProxy_SetVisible(Boolean P0, Boolean P1) { }
	// RVA: 0x26ee320 VA: 0x7594d06320
	private Void <>xLuaBaseProxy_OnInit() { }
}
```