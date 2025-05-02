# EnemyDuelBattleFinishView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Image _imageBkg`

- `Text _title`

- `TwoStateToggle _toggleTag`

- `TwoStateToggle _toggleNumTitle`

- `GameObject _barOperation`

- `GameObject _roundChar`

- `GameObject _panelBest`

- `Text _name`

- `GameObject _comment`

- `Text _commentText`

- `Text _num`

- `Text _rankText`

- `GameObject _panelTopRank`

- `Transform _avatarContainer`

- `Single _avatarScale`

- `LayoutElement _rectAllIn`

- `LayoutElement _rectNormal`

- `LayoutElement _rectSkip`

- `Text _textAllIn`

- `Text _textNormal`

- `Text _textSkip`

- `LoopVerticalScrollRect _scrollRect`

- `EnemyDuelBattleFinishRankAdapter _adapter`

- `UILayoutDimensionListener _listener`

- `GridLayoutGroup _layout`

- `Text _rewardBp`

- `Text _bpDailyMissionComplete`

- `GameObject _dailyPanel`

- `GameObject _dailyCompletePanel`

- `Text _dailyCurrPoint`

- `Text _dailyFullPoint`

- `Slider _sliderDaily`

- `Text _bpLevel`

- `GameObject _bpMax`

- `GameObject _bpNum`

- `Text _bpCurrPoint`

- `Text _bpFullPoint`

- `Slider _sliderBp`

- `GameObject _bpEffect`

- `TwoStateToggle _btnToggle`

- `TwoStateToggle _nextBtnToggle`

- `Text _countDownText`

- `Slider _countDownSlider`

- `UIAnimationLocation _entryAnim`

- `UIAnimationLocation _topRankEntry`

- `UIAnimationLocation _topRankLoop`

- `UIAnimationLocation _dailyComplete`

- `UIAnimationLocation _bpMaxAnim`

- `UIAnimationLocation _bpEffectAnim`

- `Boolean m_hasInited`

- `Boolean m_isTopRank`

- `UIPageFinder m_pageFinder`

- `Tween m_entryTween`

- `PlayerAvatarView m_avatarView`

- `EnemyDuelBattleFinishViewModel m_viewModel`

- `ScaledStopwatch m_stopWatch`

- `Int64 m_countDownTotalTime`

- `Boolean m_isCountingDown`


## Methods

- `Void Start()`

- `Void OnDestroy()`

- `Void UpdateTime(Single)`

- `Void _RenderView(EnemyDuelBattleFinishViewModel)`

- `Void _InitIfNot()`

- `Void _RenderRankList(List`1, Int32)`

- `Void _PlayEntryAnim()`

- `Void _PlayNumberTween(Text, Int32)`

- `Void _OnShowTopRankDance()`

- `Void _RenderOperationRoundBar(ChoiceCntInfo)`

- `Sprite _GetRandomBkgSprite(String, Int32)`

- `Void _RenderDailyMission(EnemyDuelBattleFinishViewModel)`

- `Tween _PlayBpAnim(EnemyDuelBattleFinishViewModel)`

- `Void _RenderBpOnce(MileStoneInfo)`

- `Void _RenderBpOnceWithMaxAnim(MileStoneInfo)`

- `Void _RenderBtns(EnemyDuelBattleFinishViewModel)`

- `Void _UpdateCountdown()`

- `Void _DoFocusAction(Int32)`

- `Void OnBackToEntryBtnClicked()`

- `Void OnNextClicked()`

- `Boolean _CheckIfRoomEnded()`

- `Void _OnBackToEntry()`

- `Void _OnBackToPrepare()`

- `Void <_PlayEntryAnim>b__71_0()`

- `Void <_OnShowTopRankDance>b__73_0()`

- `IEnumerator <>xLuaBaseProxy_ShowEnterEffectCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBattleFinishView : DynBattleFinishView, IHotfixable, ITimeWatcher
{
	private const String NAME_FORMAT; // 0x0
	private const String BKG_ID_FORMAT; // 0x0
	private const Single BASE_LENGTH; // 0x0
	private const Single LENGTH_PER_ROUND; // 0x0
	private Image _imageBkg; // 0x20
	private Text _title; // 0x28
	private TwoStateToggle _toggleTag; // 0x30
	private TwoStateToggle _toggleNumTitle; // 0x38
	private GameObject _barOperation; // 0x40
	private GameObject _roundChar; // 0x48
	private GameObject _panelBest; // 0x50
	private Text _name; // 0x58
	private GameObject _comment; // 0x60
	private Text _commentText; // 0x68
	private Text _num; // 0x70
	private Text _rankText; // 0x78
	private GameObject _panelTopRank; // 0x80
	private Transform _avatarContainer; // 0x88
	private Single _avatarScale; // 0x90
	private LayoutElement _rectAllIn; // 0x98
	private LayoutElement _rectNormal; // 0xa0
	private LayoutElement _rectSkip; // 0xa8
	private Text _textAllIn; // 0xb0
	private Text _textNormal; // 0xb8
	private Text _textSkip; // 0xc0
	private LoopVerticalScrollRect _scrollRect; // 0xc8
	private EnemyDuelBattleFinishRankAdapter _adapter; // 0xd0
	private UILayoutDimensionListener _listener; // 0xd8
	private GridLayoutGroup _layout; // 0xe0
	private Text _rewardBp; // 0xe8
	private Text _bpDailyMissionComplete; // 0xf0
	private GameObject _dailyPanel; // 0xf8
	private GameObject _dailyCompletePanel; // 0x100
	private Text _dailyCurrPoint; // 0x108
	private Text _dailyFullPoint; // 0x110
	private Slider _sliderDaily; // 0x118
	private Text _bpLevel; // 0x120
	private GameObject _bpMax; // 0x128
	private GameObject _bpNum; // 0x130
	private Text _bpCurrPoint; // 0x138
	private Text _bpFullPoint; // 0x140
	private Slider _sliderBp; // 0x148
	private GameObject _bpEffect; // 0x150
	private TwoStateToggle _btnToggle; // 0x158
	private TwoStateToggle _nextBtnToggle; // 0x160
	private Text _countDownText; // 0x168
	private Slider _countDownSlider; // 0x170
	private UIAnimationLocation _entryAnim; // 0x178
	private UIAnimationLocation _topRankEntry; // 0x188
	private UIAnimationLocation _topRankLoop; // 0x198
	private UIAnimationLocation _dailyComplete; // 0x1a8
	private UIAnimationLocation _bpMaxAnim; // 0x1b8
	private UIAnimationLocation _bpEffectAnim; // 0x1c8
	private Boolean m_hasInited; // 0x1d8
	private Boolean m_isTopRank; // 0x1d9
	private UIPageFinder m_pageFinder; // 0x1e0
	private Tween m_entryTween; // 0x1f0
	private PlayerAvatarView m_avatarView; // 0x1f8
	private EnemyDuelBattleFinishViewModel m_viewModel; // 0x200
	private ScaledStopwatch m_stopWatch; // 0x208
	private Int64 m_countDownTotalTime; // 0x218
	private Boolean m_isCountingDown; // 0x220
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_ShowEnterEffectCoroutine; // 0x8
	private static DelegateBridge __Hotfix0_Start; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x20
	private static DelegateBridge __Hotfix0__RenderView; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__RenderRankList; // 0x38
	private static DelegateBridge __Hotfix0__PlayEntryAnim; // 0x40
	private static DelegateBridge __Hotfix0__PlayNumberTween; // 0x48
	private static DelegateBridge __Hotfix0__OnShowTopRankDance; // 0x50
	private static DelegateBridge __Hotfix0__RenderOperationRoundBar; // 0x58
	private static DelegateBridge __Hotfix0__GetRandomBkgSprite; // 0x60
	private static DelegateBridge __Hotfix0__RenderDailyMission; // 0x68
	private static DelegateBridge __Hotfix0__PlayBpAnim; // 0x70
	private static DelegateBridge __Hotfix0__RenderBpOnce; // 0x78
	private static DelegateBridge __Hotfix0__RenderBpOnceWithMaxAnim; // 0x80
	private static DelegateBridge __Hotfix0__RenderBtns; // 0x88
	private static DelegateBridge __Hotfix0__UpdateCountdown; // 0x90
	private static DelegateBridge __Hotfix0__DoFocusAction; // 0x98
	private static DelegateBridge __Hotfix0_OnBackToEntryBtnClicked; // 0xa0
	private static DelegateBridge __Hotfix0_OnNextClicked; // 0xa8
	private static DelegateBridge __Hotfix0__CheckIfRoomEnded; // 0xb0
	private static DelegateBridge __Hotfix0__OnBackToEntry; // 0xb8
	private static DelegateBridge __Hotfix0__OnBackToPrepare; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8


	// RVA: 0x293e064 VA: 0x7594f56064
	protected override Void OnInit() { }
	// RVA: 0x293e1f8 VA: 0x7594f561f8
	public override IEnumerator ShowEnterEffectCoroutine() { }
	// RVA: 0x293e2cc VA: 0x7594f562cc
	private Void Start() { }
	// RVA: 0x293e33c VA: 0x7594f5633c
	private Void OnDestroy() { }
	// RVA: 0x293e3ac VA: 0x7594f563ac
	public Void UpdateTime(Single timeDelta) { }
	// RVA: 0x293e634 VA: 0x7594f56634
	private Void _RenderView(EnemyDuelBattleFinishViewModel model) { }
	// RVA: 0x293e0cc VA: 0x7594f560cc
	private Void _InitIfNot() { }
	// RVA: 0x293ef48 VA: 0x7594f56f48
	private Void _RenderRankList(List`1 rankList, Int32 selfIndex) { }
	// RVA: 0x293fc38 VA: 0x7594f57c38
	private Void _PlayEntryAnim() { }
	// RVA: 0x293ec90 VA: 0x7594f56c90
	private Void _PlayNumberTween(Text roundText, Int32 round) { }
	// RVA: 0x294014c VA: 0x7594f5814c
	private Void _OnShowTopRankDance() { }
	// RVA: 0x293eae4 VA: 0x7594f56ae4
	private Void _RenderOperationRoundBar(ChoiceCntInfo info) { }
	// RVA: 0x293e9bc VA: 0x7594f569bc
	private Sprite _GetRandomBkgSprite(String actId, Int32 picNum) { }
	// RVA: 0x293f1ec VA: 0x7594f571ec
	private Void _RenderDailyMission(EnemyDuelBattleFinishViewModel model) { }
	// RVA: 0x293f714 VA: 0x7594f57714
	private Tween _PlayBpAnim(EnemyDuelBattleFinishViewModel model) { }
	// RVA: 0x293f55c VA: 0x7594f5755c
	private Void _RenderBpOnce(MileStoneInfo info) { }
	// RVA: 0x2940560 VA: 0x7594f58560
	private Void _RenderBpOnceWithMaxAnim(MileStoneInfo info) { }
	// RVA: 0x293f088 VA: 0x7594f57088
	private Void _RenderBtns(EnemyDuelBattleFinishViewModel model) { }
	// RVA: 0x293e428 VA: 0x7594f56428
	private Void _UpdateCountdown() { }
	// RVA: 0x29408e4 VA: 0x7594f588e4
	private Void _DoFocusAction(Int32 index) { }
	// RVA: 0x2940988 VA: 0x7594f58988
	public Void OnBackToEntryBtnClicked() { }
	// RVA: 0x2940754 VA: 0x7594f58754
	public Void OnNextClicked() { }
	// RVA: 0x2940d70 VA: 0x7594f58d70
	private Boolean _CheckIfRoomEnded() { }
	// RVA: 0x2940c30 VA: 0x7594f58c30
	private Void _OnBackToEntry() { }
	// RVA: 0x2940efc VA: 0x7594f58efc
	private Void _OnBackToPrepare() { }
	// RVA: 0x294106c VA: 0x7594f5906c
	public Void .ctor() { }
	// RVA: 0x29411e8 VA: 0x7594f591e8
	private Void <_PlayEntryAnim>b__71_0() { }
	// RVA: 0x29411ec VA: 0x7594f591ec
	private Void <_OnShowTopRankDance>b__73_0() { }
	// RVA: 0x2941288 VA: 0x7594f59288
	private IEnumerator <>xLuaBaseProxy_ShowEnterEffectCoroutine() { }
}
```